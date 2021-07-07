---
title: Informations d’application pour SurveyMonkey par SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour SurveyMonkey, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: daf5de5437a08ca8b748157a5e136bbe7b114122
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53280816"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SurveyMonkey à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | SurveyMonkey |
| ID | WA104381088 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | SurveyMonkey |
| URL du site web partenaire | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL de la Teams d’informations sur l’application | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL de la politique de confidentialité | [https://www.surveymonkey.com/mp/legal/privacy-policy/](https://www.surveymonkey.com/mp/legal/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.surveymonkey.com/mp/legal/terms-of-use/](https://www.surveymonkey.com/mp/legal/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par SurveyMonkey sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | délégué | Non | Pour fournir une liste de groupes/canaux avec qui partager une enquête |  |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Seul l’ID d’utilisateur MS est stocké dans SurveyMonkey afin d’associer des réponses et des enquêtes à l’utilisateur de l’équipe. |  | Pour les équipes, nous utilisons Microsoft Teams SDK JavaScript dans le module de tâche créer, prendre des enquêtes et des résultats de l’enquête module modal. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nous appelons v3/conversations/{id}/pagedmembers pour vérifier que l’application est ajoutée à une équipe et obtenir le nombre de membres. Il s’agit d’un suivi interne de l’utilisation, nous regardons uniquement la taille de la liste de conversation, les autres informations sont ignorées. | Oui, la taille de la conversation est stockée (un seul nombre) |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>EUII : un journal de réussite/échec est créé chaque fois qu’une enquête reçoit une réponse et que nous essayons d’envoyer cette réponse à Teams via le connecteur, ce journal inclut user_id, survey_id, integration_id (qui dans la base de données peut être utilisé pour rechercher l’ID d’équipe MS, l’ID utilisateur MS)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Notre centre de données principal se trouve à Las Vegas, NV et notre centre de données secondaire se trouve à Santa Principal, en Californie. SurveyMonkey possède et exploite tous ses serveurs et infrastructure à ces emplacements. Nous avons également la résidence des données au Canada pour certains clients SurveyMonkey Enterprise situés au Canada. Toutes les données sont chiffrées au repos à l’aide de TDE avec AES256 et les données en transit sont chiffrées à l’aide de TLS 1.2.

SurveyMonkey utilise l’authentification utilisateur centrale pour maintenir la gestion des identités et des accès. Ce système gère l’ensemble de l’authentification et de l’autorisation pour tous les systèmes et services d’entreprise et de production. Des stratégies d’accès strictes sont conservées et examinées tous les trimestres. Les révisions incluent, sans s’y limiter, les listes d’accès des utilisateurs, les groupes de stratégies et les révisions d’accès tiers. Pour accéder à notre environnement de production (c’est-à-dire, pour obtenir un compte privilégié), il faut obtenir l’approbation du responsable, effectuer un certain nombre de formations requises et obtenir l’approbation de notre équipe de sécurité. À ce moment-là, un compte VPN supplémentaire est provisioné, ce qui différencie le compte &#8216;&#8217; normal d’un compte &#8216;privilégié&#8217; client.

Seuls les appareils émis par l’entreprise sont autorisés à accéder à notre réseau de production. Toutes les valeurs par défaut du fournisseur sans fil sont modifiées avant l’installation, y compris, mais sans s’y limiter, les clés de chiffrement sans fil par défaut, les mots de passe et les chaînes communautaires SNMP. 2FA et VPN sont requis pour le faire à distance. Nous avons un réseau Wifi distinct pour l’accès invité dans nos bureaux d’entreprise.

Tous les services, protocoles et ports autorisés doivent avoir une justification et une approbation professionnelles documentées, y compris l’utilisation des fonctionnalités de sécurité implémentées pour les protocoles considérés comme non sécurisés. Les routeurs et les pare-feu sont configurés pour limiter la divulgation d’adresses IP aux personnes non autorisées ou involontaires et limiter l’accès Internet entrant aux adresses IP dans le pare-feu DMZ et les jeux de règles de routeur sont examinés au moins tous les six mois.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

