---
title: Informations sur l’application pour Smart Connecter Jira par yasoon
ms.author: elmalova
author: elenamalova
ms.date: 07/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Smart Connecter pour Jira, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a4a5a1ad980bba5214811bea5d981a1705ec4f1f
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528027"
---
# <a name="smart-connect-for-jira"></a>Smart Connect pour Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par yasoon ContrôleH à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Smart Connect pour Jira |
| ID | WA200002055 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | yasoon GmbH |
| URL du site web partenaire | [https://www.yasoon.com](https://www.yasoon.com) |
| URL de la Teams d’informations sur l’application | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| URL de la politique de confidentialité | [https://yasoon.com/privacy-policy-services/](https://yasoon.com/privacy-policy-services/) |
| URL des conditions d’utilisation | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474846970/Product_42949680957/Asset_3f25ec80-eacb-454f-8cc2-eeee583b65c6/170825EULAOfficeaddinEN.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par yasoon Contrôleh sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | délégué | L’autorisation permet à l’utilisateur de sélectionner l’un de ces canaux joints dans Jira. | ID de canal, à des fins de mise en cache | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Read.Group | application | Permet à l’application d’afficher des messages de canal lié dans Jira. | ID de message pour lier des messages à des problèmes de Jira | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Send | délégué | Aucune donnée n’est utilisée, cette API est utilisée pour permettre à l’utilisateur de répondre aux messages de canal à partir de Jira. | Aucun | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelSettings.Read.Group | application | Utilisé pour rechercher des informations détaillées sur un canal. | Aucun | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Chat.ReadWrite | délégué | Permet à l’utilisateur d’ajouter de nouvelles réponses aux conversations et d’afficher les messages de conversation à partir de Jira. | Aucun | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Member.Read.Group | application | Utilisé pour les vérifications d’autorisation, permet à l’application de valider l’appartenance des utilisateurs à l’équipe. | Aucun | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Team.ReadBasic.All | délégué | L’autorisation permet à l’utilisateur de sélectionner l’une de ces équipes jointes dans Jira. | ID d’équipe à des fins de mise en cache | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| TeamSettings.Read.Group | application | Permet à l’application de lire les paramètres d’équipe pour respecter certaines valeurs par défaut. | Aucun | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| User.ReadBasic.All | délégué | Permet à l’utilisateur de sélectionner des collègues à @mentionner dans un message de canal | Aucun | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Atlassian Jira et éventuellement l’un de nos sous-traitants, sont visibles ici : https://go.yasoon.com/contractors | Métadonnées de message (ID, timestamps), métadonnées utilisateur et organisationnelles (ID d’utilisateur, ID d’organisation) et adresses de messagerie de l’utilisateur | Prise en charge des fonctionnalités de l’application (par exemple, mise en correspondance de comptes Atlassian avec des comptes Office) et activation de notre prise en charge pour résoudre les problèmes plus rapidement. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Correspondance des utilisateurs Teams compte d’utilisateurs Atlassian Jira | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Métadonnées utilisateur (id)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous travaillons uniquement avec des services qui offrent des garanties strictes de confidentialité des données. 

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par yasoon ContrôleH sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
