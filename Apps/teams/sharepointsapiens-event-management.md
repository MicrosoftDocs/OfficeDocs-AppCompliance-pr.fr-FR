---
title: Informations sur les applications pour la gestion des événements par SharePoint| Tzéz
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour la gestion des événements, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6c01ea167bc634296e6eb9972192db14f61839a9
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60423094"
---
# <a name="event-management"></a>Gestion des événements

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/2b8b9b59-d595-46b3-ba0a-602024bab0cc" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000714" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SharePoint| Aide-ms à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Gestion des événements |
| ID | WA200000714 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | SharePoint|Sapiens |
| URL du site web partenaire | [https://www.sharepointsapiens.com](https://www.sharepointsapiens.com) |
| URL de la Teams d’informations sur l’application | [https://www.sharepointsapiens.com/event-management-office36...](https://www.sharepointsapiens.com/event-management-office365/documentation/teams/) |
| URL de la politique de confidentialité | [https://www.sharepointsapiens.com/privacy/](https://www.sharepointsapiens.com/privacy/) |
| URL des conditions d’utilisation | [https://addins.sharepointsapiens.com/licensing/services-agr...](https://addins.sharepointsapiens.com/licensing/services-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par SharePoint| Indique comment cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.ReadBasic.All | délégué | Adresse e-mail et nom des salles Exchange ressources pour activer la réservation de salles et de ressources | Aucune donnée ne sera stockée | [9e8e113c-8a08-4606-b08a-de4decc7252f](https://docs.microsoft.com/microsoft-365-app-certification/azure/9e8e113c-8a08-4606-b08a-de4decc7252f) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Office 365 Exchange Online | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailgun.com (facultatif), Stripe.com (facultatif) | Nom de la société et adresse de facturation si Stripe.com est utilisé pour la facturation, les invitations au calendrier et les réponses à l’adresse e-mail des utilisateurs si le mailgun est utilisé comme service de messagerie | Si vous choisissez d’utiliser notre service de messagerie au lieu de votre service de messagerie en ligne Exchange, les services envoient et reçoivent des messages électroniques par le biais de l’API et de l’infrastructure du mailgun. Si vous choisissez d’utiliser votre propre boîte aux Exchange, aucune donnée n’est traitée par mailgun. Si vous choisissez d’utiliser une carte de crédit pour payer les frais d’abonnement, les données collectées seront contrôlées et traitées par stripe.com. Si vous choisissez d’acheter par le biais d’un po et d’une facture au lieu d’une carte de crédit, aucune donnée n’est traitée stripe.com. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun EUII ne sera stocké. TenantID et SharePoint domaine seront stockés dans la télémétrie de l’application. Les journaux et les données de télémétrie seront stockés pendant 90 jours.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Toutes les données sont stockées sur le site web SharePoint client. Nous ne stockons pas les données client ailleurs, à l’exception des paramètres de l’application, des informations de licence et d’utilisation.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36018' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36018" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par SharePoint| Informations sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/><br/> |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
