---
title: Informations d’application pour Timeneye par DM Digital SRL
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Timeneye, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c98a1fbd0db2d02caf71e16000d8b57bb8df06da
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429942"
---
# <a name="timeneye"></a>Timeneye

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 31, 2021</p>

* <a href="https://teams.microsoft.com/l/app/015bf4ec-bc37-4931-9862-ef8686da652b" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001950" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par DM Digital SRL à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Timeneye |
| ID | WA200001950 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | DM Digital SRL |
| URL du site web partenaire | [https://www.dmdigital.it](https://www.dmdigital.it) |
| URL de la politique de confidentialité | [https://www.timeneye.com/privacy-policy](https://www.timeneye.com/privacy-policy) |
| URL des conditions d’utilisation | [https://www.timeneye.com/terms-and-conditions](https://www.timeneye.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par DM Digital SRL sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | délégué | Date/fin de l’événement DateTime, objet de l’événement, ID d’événement, URI web de l’événement. Générer des suggestions basées sur des événements de calendrier. | Date/fin de l’événement DateTime, objet de l’événement, ID d’événement, URI web de l’événement. Possibilité de lier une suggestion générée à l’événement de calendrier approprié. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Calendars.Read.Shared | délégué | Date/fin de l’événement DateTime, objet de l’événement, ID d’événement, URI web de l’événement. Nous utilisons ces informations pour générer des suggestions basées sur des événements de calendrier. | Date/fin de l’événement DateTime, objet de l’événement, ID d’événement, URI web de l’événement. Nous utilisons ces informations pour lier une suggestion générée à l’événement de calendrier approprié. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Directory.Read.All | délégué | ID de groupes d’utilisateurs. Nous utilisons ces informations pour vérifier les groupes dont l’utilisateur est membre afin de synchroniser les planificateurs de ses groupes. | ID de groupes d’utilisateurs. Nous utilisons ces informations pour vérifier les groupes dont l’utilisateur est membre afin de synchroniser les planificateurs de ses groupes. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Group.Read.All | délégué | Nom du groupe, ID de groupe. Nous utilisons ces informations lors de la synchronisation des projets du planificateur. | Nom du groupe, ID de groupe.  | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Tasks.Read | délégué | nom de liste de tâches, ID de liste de tâches. Nous utilisons ces informations lors de la synchronisation des projets du planificateur. | nom de liste de tâches, ID de liste de tâches. Nous utilisons ces informations lors de la synchronisation des projets du planificateur. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.Read | délégué | e-mail, nom. Nous utilisons ces informations pour nous connecter à l’utilisateur/créer le compte d’utilisateur | e-mail, nom. Nous utilisons ces informations pour nous connecter à l’utilisateur/créer le compte d’utilisateur | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.ReadBasic.All | délégué | nom d’utilisateur, e-mail. Nous utilisons ces informations pour que l’utilisateur puisse importer d’autres utilisateurs du Planificateur/Microsoft vers notre service. | nom d’utilisateur, e-mail. Informations de base requises pour créer un utilisateur dans notre service. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| email | délégué | Messagerie. Nous utilisons ces informations pour nous connecter à l’utilisateur/créer le compte d’utilisateur | Messagerie. Nous utilisons ces informations pour nous connecter à l’utilisateur/créer le compte d’utilisateur | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| offline_access | délégué | Autorisation requise pour synchroniser le planificateur/le calendrier alors que l’utilisateur n’est pas en ligne. | Autorisation requise pour synchroniser le planificateur/le calendrier alors que l’utilisateur n’est pas en ligne. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| openid | délégué | id_token. Connexion à l’utilisateur via l' sso Microsoft | id_token. Connexion à l’utilisateur via l' sso Microsoft. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| profil | délégué | e-mail, nom. Nous utilisons ces informations pour nous connecter à l’utilisateur/créer le compte d’utilisateur | e-mail, nom. Nous utilisons ces informations pour nous connecter à l’utilisateur/créer le compte d’utilisateur | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook API de calendrier | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nom d’utilisateur et courrier électronique, détails de facturation de l’entreprise. Lorsque le compte/l’utilisateur est supprimé, les informations sont supprimées.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous ne passons pas d’informations sensibles à nos systèmes partenaires à l’exception du courrier électronique de l’utilisateur à des fins de support, de gestion des tickets et de facturation. Les informations sont supprimées lors de la suppression du compte sur notre système.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par DM Digital SRL sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

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
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Oui |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
