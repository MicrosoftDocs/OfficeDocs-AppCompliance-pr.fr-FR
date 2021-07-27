---
title: Informations sur les applications pour l’ecBooking par les systèmes experts IVR (Asie) Co.Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 12/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour ecBooking, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f36edd400f35d7e4ccbfef5edd0225855f73ab69
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521727"
---
# <a name="ecbooking"></a>ecBooking

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/fe9627db-f23e-42b1-b454-d4d1ca5af33e" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002096" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par la réponse vocale vocale (IVR) des systèmes experts (Asie) Co.Ltd. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | ecBooking |
| ID | WA200002096 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Expert Systems IVR(Asia) Co.Ltd. |
| URL du site web partenaire | [https://www.esi-asia.com](https://www.esi-asia.com) |
| URL de la Teams d’informations sur l’application | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/) |
| URL de la politique de confidentialité | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1510822239639-efecac03-d43200b0-aa88) |
| URL des conditions d’utilisation | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1598241760681-29d114e0-5c2b) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par expert Systems IVR(Asia) Co.Ltd. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | application | Les données telles que la messagerie de l’utilisateur, les événements utilisateur sont stockées. Les événements utilisateur sont collectés pour vérifier la disponibilité des salles et créer des événements. | L’ID de l’événement Users, le nom de l’emplacement et les détails des autres événements sont stockés. Les données sont collectées pour vérifier la disponibilité des salles et créer des événements. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| Mail.Send | application | Données telles que la messagerie de l’utilisateur. Les messages électroniques de l’utilisateur sont collectés pour l’envoi d’un e-mail de rappel de réservation de salle. | Données telles que la messagerie de l’utilisateur. Les messages électroniques de l’utilisateur sont collectés pour l’envoi d’un e-mail de rappel de réservation de salle. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read | délégué | Données telles que l’ID d’utilisateur, le nom et le courrier électronique. Les données utilisateur sont collectées pour la signature de l’utilisateur dans l’application. | Données telles que l’ID d’utilisateur, le nom et le courrier électronique. Les données utilisateur sont collectées pour la signature de l’utilisateur dans l’application. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read.All | application | Données telles que l’ID d’utilisateur, le nom et le courrier électronique. Les données utilisateur sont collectées pour la signature de l’utilisateur dans l’application. | Données telles que l’ID d’utilisateur, le nom et le courrier électronique. Les données utilisateur sont collectées pour la signature de l’utilisateur dans l’application. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| email | délégué | Données telles que la messagerie de l’utilisateur. Les messages électroniques de l’utilisateur sont collectés pour vérifier la disponibilité de l’utilisateur et créer des événements. | Données telles que la messagerie de l’utilisateur. Les messages électroniques de l’utilisateur sont collectés pour vérifier la disponibilité de l’utilisateur et créer des événements. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| openid | délégué | L’ordre d’ouverture de l’utilisateur pour que l’utilisateur se connecte à l’application. | L’ordre d’ouverture de l’utilisateur pour que l’utilisateur se connecte à l’application. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Les données telles que la messagerie de l’utilisateur, les événements utilisateur sont stockées. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Données stockées dans la base de données.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par expert Systems IVR(Asia) Co.Ltd. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/><br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
