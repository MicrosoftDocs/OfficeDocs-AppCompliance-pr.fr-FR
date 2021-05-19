---
title: Informations d’application pour Q par ModuleQ
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Q, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3424ac372f46be0fc9834611fb1a0d57c69831a4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551904"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Mars 17, 2020</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ModuleQ à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Q |
| ID | WA104381433 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | ModuleQ |
| URL du site web partenaire | [https://moduleq.com](https://moduleq.com) |
| URL de la politique de confidentialité | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://moduleq.com/terms-of-service/](https://moduleq.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par ModuleQ sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | application | stocke les données de réunion, à l’exception du corps du message et de toute pièce jointe | Permet à l’application de lire les événements du calendrier d’un utilisateur afin de comprendre intelligemment les priorités métier de l’utilisateur. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | Délégué | Aucune | Permet à l’application d’interagir au au cours d’une équipe pour le partage de contenu. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | application | stocke les données de messagerie, à l’exception du corps du message et de toute pièce jointe | Permet à l’application de lire le courrier d’un utilisateur afin de comprendre intelligemment les priorités commerciales de l’utilisateur | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | Délégué | jetons d’email et d’authentification de l’utilisateur | Permet à l’utilisateur de se connecter et de lier Office 365 compte avec son compte ModuleQ | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | Délégué | Aucune | Permettez à l’application d’obtenir la liste Teams que l’utilisateur fait partie de. Uniquement utilisé pour le partage  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Nous connectons un utilisateur interne GUID et les noms et domaines organisationnels. Il n’y a pas de contrôle d’archivage ou de suppression pour le moment.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données sont stockées dans Microsoft Azure Cloud sur plusieurs microservices en fonction de leur fonction. Toutes les données identifiables par l’utilisateur sont cryptées côté client avec le cryptage AES-256 avant d’être transmises pour le stockage. Les données peuvent être consultées par les ingénieurs à des fins de débogage avec l’approbation de notre haute direction. L’accès aux données est contrôlé par VPN interne.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

