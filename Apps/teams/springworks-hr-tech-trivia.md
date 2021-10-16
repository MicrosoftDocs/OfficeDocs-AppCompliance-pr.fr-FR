---
title: Informations sur l’application pour Trivia par Springworks HR Tech
ms.author: elmalova
author: elenamalova
ms.date: 01/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Trivia, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f2e79a1843977a1c8c1ea0f62259cfa4bde8f076
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410848"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Springworks HR Tech à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Trivia |
| ID | WA200001956 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Springworks HR Tech |
| URL du site web partenaire | [https://www.springworks.in](https://www.springworks.in) |
| URL de la Teams d’informations sur l’application | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| URL de la politique de confidentialité | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| URL des conditions d’utilisation | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Springworks HR Tech sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | délégué | Non | Pour obtenir la liste des Teams dont l’utilisateur fait partie | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| Team.ReadBasic.All | délégué | Oui, stockage de la liste des équipes dans lesquelles le bot a été ajouté | Pour collecter des informations de base sur toutes les équipes présentes dans un espace de travail | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| User.Read.All | délégué | Oui, pour stocker l’aadObjectId unique d’un utilisateur. Divers détails de l’utilisateur tels que le nom d’utilisateur, le courrier électronique, etc., et l’afficher dans le tableau de bord Trivia | Pour obtenir les détails de tous les utilisateurs présents dans un espace de travail | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| openid | délégué | Oui, pour stocker les utilisateurs qui se connectent à l’application. |  Pour permettre à l’utilisateur d’utiliser l’application avec son compte et l’application d’utiliser les données de l’utilisateur | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| profil | délégué | Oui, pour stocker les ID d’utilisateur et les noms des hôtes de questionnaires et d’autres fonctionnalités, et les identifier de manière unique | Pour lire les informations de profil de base de l’utilisateur telles que le nom d’utilisateur, courrier électronique | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS, Mailchimp, Stripe.  | Nom du client, e-mail, adresse IP, informations de paiement | Nous utilisons ces tiers pour offrir la meilleure expérience client à nos clients |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Ces données sont utilisées pour afficher et stocker la liste des participants dans un questionnaire et d’autres fonctionnalités de ce type | Nom, Courrier électronique | Oui, stockage des données de l’hôte et des participants des questionnaires et autres fonctionnalités pour l’analyse et la communication avec l’hôte en cas d’erreurs |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>OII : nom de l’organisation, ID de client apparaissent dans les journaux ; EUII : ID d’objet aad, nom complet, courrier électronique s’affichent dans les journaux. Nous avons une période de rétention de 30 jours après laquelle les journaux sont automatiquement supprimés. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Données stockées dans RDS, AWS. il est chiffré. L’accès est uniquement à un ingénieur DevOps, chef d’ingénierie et fondateur

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Springworks HR Tech sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

