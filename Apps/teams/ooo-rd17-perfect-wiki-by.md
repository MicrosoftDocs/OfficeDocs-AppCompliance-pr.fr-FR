---
title: Informations d’application pour le Wiki parfait par RD17 par OOO RD17
ms.author: elmalova
author: elenamalova
ms.date: 08/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Le Wiki parfait par RD17, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: deacceb8c77fd935e6ff7dd03fe8195042b8e259
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282735"
---
# <a name="perfect-wiki-by-rd17"></a>Perfect Wiki by RD17

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/40906836-4323-4bbe-875e-3cbb134c40a2" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001679" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par OOO RD17 à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Perfect Wiki by RD17 |
| ID | WA200001679 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | OOO RD17 |
| URL du site web partenaire | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| URL de la Teams d’informations sur l’application | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| URL de la politique de confidentialité | [https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NK...](https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NKFVucpN44PO30SFZHDfxWhu-u5wlZI56UW7v3bT-WCM4zH4ZaWGzQR7lnoUpVyU1S/pub) |
| URL des conditions d’utilisation | [https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9...](https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9tNvhDe8Sb2AF8A9v8jfG3gJ503cXzIq1nr_Zbq5aShN0mU49fvADgKZ8a58Oha-C/pub) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par OOO RD17 sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | délégué | ChannelId et channelName, nous recevons les informations pour afficher l’utilisateur dans l’application | Nous stockons channelId et channelName pour l’afficher ultérieurement pour l’utilisateur | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| Team.ReadBasic.All | délégué | Nous allons obtenir teamId de l’utilisateur et obtenir le nom de l’équipe | teamId et teamName, nous l’utilisons pour comprendre à quel utilisateur d’équipe appartient | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| User.Read | délégué | userId, utilisé pour comprendre quel utilisateur est connecté | hashed userId, to login user and get associated data from DB | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous utilisons le contrôle d’accès basé sur les rôles pour toute opération avec le système du partenaire

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par OOO RD17 sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
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
