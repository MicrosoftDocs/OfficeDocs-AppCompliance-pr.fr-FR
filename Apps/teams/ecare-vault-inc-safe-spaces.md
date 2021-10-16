---
title: Informations sur l’application Coffre espaces de travail par eCare Vault Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour les espaces Coffre, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 39ca1a0a99e62bbedb14d0248cb751bf4089a70f
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414690"
---
# <a name="safe-spaces"></a>Safe Spaces

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 14, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ec321cf7-ae3e-4ed4-a707-ff5c18e77313" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002691" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par eCare Vault Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Safe Spaces |
| ID | WA200002691 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | eCare Vault Inc. |
| URL du site web partenaire | [https://ecarevault.com](https://ecarevault.com) |
| URL de la Teams d’informations sur l’application | [https://ecarevault.com/ecare-vault-for-teams](https://ecarevault.com/ecare-vault-for-teams) |
| URL de la politique de confidentialité | [https://ecarevault.com/ecare-vault-privacy-policy](https://ecarevault.com/ecare-vault-privacy-policy) |
| URL des conditions d’utilisation | [https://downloads.ecarevault.com/downloads/eCare+Vault+-+Te...](https://downloads.ecarevault.com/downloads/eCare+Vault+-+Terms+of+Service.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par eCare Vault Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| EduRoster.Read | délégué | Le nom et la date de naissance sont utilisés pour pré-prérupler les champs d’entrée | Aucun : toutes les données stockées sont envoyées par l’utilisateur (données pré-prérupuplées dans des champs, puis envoyées par l’utilisateur) | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| Group.Read.All | délégué | Utilisé pour obtenir des informations sur les canaux disponibles à afficher dans l’application | Aucun de cette autorisation | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| GroupMember.Read.All | délégué | AAD ID des membres du groupe utilisés pour générer une liste d’équipe eCare Vault | AAD L’ID utilisateur est stocké pour être associé à un compte d’utilisateur eCare Vault pour chaque membre | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read | délégué | adresse e-mail et ID AAD utilisé pour inscrire les utilisateurs et les associer à des comptes d’utilisateur &amp; eCare Vault | adresse e-mail et ID AAD pour les comptes d’utilisateur et envoi de notification à l’utilisateur via Bot Framework | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read.All | délégué | Nom et ID AAD, et adresse de messagerie, uniquement pour les utilisateurs membres d’un canal sur lequel des espaces Coffre sont installés | Nom, ID AAD et adresse e-mail stockés sur des comptes d’utilisateur eCare Vault | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| email | délégué | Adresse de messagerie uniquement | Aucun : un utilisateur décide d’envoyer un formulaire qui  | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| openid | délégué | adresse e-mail et ID AAD utilisé pour inscrire les utilisateurs et les associer à des comptes d’utilisateur &amp; eCare Vault | adresse e-mail et ID AAD pour les comptes d’utilisateur et envoi de notification à l’utilisateur via Bot Framework | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| profil | délégué | Le nom de l’utilisateur est utilisé pour remplir l’écran d’inscription de l’utilisateur. | Aucun directement : l’utilisateur choisit d’envoyer son nom au système lors de son inscription | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| MSAL (points de terminaison d’authentification Microsoft) | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| eCare Vault | Informations sur le client/la société, le nom de domaine de connexion de l’utilisateur, les informations de connexion utilisateur, Microsoft Teams &amp; les identificateurs de canal d’équipe. | Coffre Les espaces sont une application complémentaire de la plateforme eCare Vault. L’OII est nécessaire pour lier les utilisateurs de Microsoft Teams aux utilisateurs eCare Vault pour la société. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Toutes les données qui sont transmises aux systèmes partenaires (n’incluent pas d’OII, piI ou PHI) sont transférées dans le cadre d’un baa pour garantir la conformité HIPAA.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par eCare Vault Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/><br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

