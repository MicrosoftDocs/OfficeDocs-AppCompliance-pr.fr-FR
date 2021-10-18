---
title: Informations sur l’application pour le lanceur de liens par les produits Commun communicateur
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour le lanceur de liens, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 37a82564e1dc0a716d31eeb6bd7f7a8b2de510fb
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444692"
---
# <a name="link-spotter"></a>Link Spotter

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/9e486bb8-9633-48ba-8416-71da1d30cd08" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003092" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Commun communicate products à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Link Spotter |
| ID | WA200003092 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Communardo Products |
| URL du site web partenaire | [https://www.communardo.com](https://www.communardo.com) |
| URL de la Teams d’informations sur l’application | [https://communardo.atlassian.net/wiki/spaces/LINK/overview](https://communardo.atlassian.net/wiki/spaces/LINK/overview) |
| URL de la politique de confidentialité | [https://www.communardo.com/privacy-statement/](https://www.communardo.com/privacy-statement/) |
| URL des conditions d’utilisation | [https://www.communardo.com/customer-agreement/](https://www.communardo.com/customer-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Les produits Communités sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | délégué | Vérification de l’appartenance au canal de l’utilisateur actuel | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| ChannelMessage.Read.All | application | URL à l’intérieur des messages, messageid, ID de réponse au message, ID de canal, ID d’auteur... Ces informations sont requises, Graph ne fournit pas un moyen performant de récupérer tous les liens publiés dans des messages sur un canal. Par conséquent, les messages doivent être analysés activement afin de fournir la fonctionnalité de lien dans notre Teams onglet. | URL à l’intérieur des messages, messageid, ID de réponse au message, ID de canal, ID d’auteur | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.Read | délégué | Activer la connexion et lire le profil utilisateur | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.Read.All | application | Déterminez le nombre d’utilisateurs qui ont une licence Teams licence. Permet de mettre à jour la taille du siège de l’abonnement source de l’application payante pour le client. | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.ReadBasic.All | délégué | affichage de l’image de profil et du nom de l’auteur du message à l’intérieur de l’application | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| email | délégué | OpenID Connect | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| offline_access | délégué | OpenID Connect | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| openid | délégué | OpenID Connect | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| profil | délégué | OpenID Connect | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API Marketplace (API d’enrichissement SaaS) | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>ID client, ID de canal, les utilisateurs peuvent supprimer les données directement, données supprimées automatiquement après 90 jours

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>suppression, stratégie de l’utilisateur final

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Les produits Communités sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
