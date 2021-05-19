---
title: Informations d’application pour SurveyMonkey par SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour SurveyMonkey, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57ba8ed84e0d9ea4101ea82ed5d92aef1f634ed1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552725"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SurveyMonkey à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | SurveyMonkey |
| ID | WA104381088 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | SurveyMonkey |
| URL du site web partenaire | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL de la page Teams’informations d’application | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL de la politique de confidentialité | [https://www.surveymonkey.com/privacy](https://www.surveymonkey.com/privacy) |
| URL des conditions d’utilisation | [https://www.surveymonkey.com/mp/policy/terms-of-use/](https://www.surveymonkey.com/mp/policy/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par SurveyMonkey sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Délégué | Non | Fournir une liste de groupes/canaux pour partager un sondage avec |  |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Seul l’id utilisateur MS est stocké dans SurveyMonkey afin d’associer les réponses et les sondages avec l’utilisateur de l’équipe. |  | Pour les équipes, nous utilisons le Microsoft Teams javascript SDK dans le module de travail de création, de prise d’enquête et de résultats d’enquête modal. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nous faisons un appel à v3/conversations/{id}/pagedmembers pour vérifier que l’application est ajoutée à une équipe et obtenir le nombre de membres. Il est pour le suivi interne de l’utilisation, nous ne regardons que la taille de la liste de chat, d’autres informations sont ignorées. | Oui, la taille du chat est stockée (un seul entier) |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>EUII - Un journal de réussite/échec est créé chaque fois qu’une enquête reçoit une réponse, et nous essayons d’envoyer cette réponse à Teams via le connecteur, ce journal inclut user_id, survey_id, integration_id (qui dans la base de données peut être utilisé pour rechercher MS Team ID, MS User ID)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Notre centre de données principal est situé à Las Vegas, NV et notre centre de données secondaire est situé à Santa Clara, CA. SurveyMonkey possède et exploite tous ses serveurs et infrastructures à ces endroits. Nous avons également la résidence de données canadienne disponible pour certains clients surveymonkey Enterprise situés au Canada. Toutes les données sont cryptées au repos à l’aide de TDE avec AES256 et les données en transit sont cryptées à l’aide de TLS 1.2.

SurveyMonkey utilise l’authentification centrale de l’utilisateur pour maintenir l’identité et la gestion de l’accès. Ce système gère toute l’authentification et l’autorisation à toutes les entreprises, et l’infrastructure de production, les systèmes et les services. Des politiques d’accès strictes sont maintenues et revues sur une base trimestrielle. Les avis incluent, mais ne se limitent pas à: listes d’accès des utilisateurs, groupes de stratégies et des examens d’accès tiers. Pour accéder à notre environnement de production (c.-à-d. pour obtenir un compte privilégié), il faut obtenir l’approbation du gestionnaire, compléter un certain nombre de formations requises et obtenir l’approbation de notre équipe de sécurité. À cette époque, un compte VPN supplémentaire est provisionné, ce qui différencie le compte &#8216;normal&#8217; d’un compte &#8216;privilégié&#8217; privilégié.

Seuls les appareils émis par l’entreprise sont autorisés à accéder à notre réseau de production. Tous les défauts des fournisseurs sans fil sont modifiés avant l’installation, y compris, sans s’y limiter, les clés de chiffrement sans fil par défaut, les mots de passe et les chaînes de la communauté SNMP. 2FA et VPN sont tenus de le faire à distance. Nous avons un réseau wifi séparé pour l’accès des clients à nos bureaux d’entreprise.

Tous les services, protocoles et ports autorisés doivent avoir une justification et une approbation commerciales documentées, y compris l’utilisation de caractéristiques de sécurité implémentées pour les protocoles considérés comme non sécurisés. Les routeurs et les pare-feu sont configurés pour limiter la divulgation ip aux parties non autorisées ou non intentionnelles et limiter l’accès internet entrant aux adresses IP dans les ensembles de règles du pare-feu et du routeur DMZ sont examinés au moins tous les six mois.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

