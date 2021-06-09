---
title: Informations sur l’application pour déplacer le travail vers l’avant avec Jira par déplacer le travail vers l’avant
ms.author: elmalova
author: elenamalova
ms.date: 05/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Move Work Forward avec Jira, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a5ca2ec25650abba3f68a2ec543434c56d3c3d27
ms.sourcegitcommit: bb013192ff1a6db66c2ffe05cc83afc1d4140e76
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/09/2021
ms.locfileid: "52852055"
---
# <a name="move-work-forward-with-jira"></a>Avancer avec Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/79ca2e8f-dd2c-40d5-897e-1b22d41038fe" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002855" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Move Work Forward à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Avancer avec Jira |
| ID | WA200002855 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Déplacer le travail vers l’avant |
| URL du site web partenaire | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| URL de la Teams d’informations sur l’application | [https://www.moveworkforward.com/product/microsoft-teams-jir...](https://www.moveworkforward.com/product/microsoft-teams-jira-connector) |
| URL de la politique de confidentialité | [https://www.moveworkforward.com/privacy-policy](https://www.moveworkforward.com/privacy-policy) |
| URL des conditions d’utilisation | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Move Work Forward sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.Create | délégué | Utilisé pour créer un canal de discussion sur les problèmes. | L’URL web du canal nouvellement créé est stockée pour s’afficher dans Jira pour un accès rapide au canal Microsoft Teams discussion. | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| Channel.ReadBasic.All | délégué | Le nom et l’ID du canal sont utilisés pour envoyer des notifications de Jira Microsoft Teams. | L’ID de canal et le nom sont stockés pour configurer les notifications de Jira vers Microsoft Teams. | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| Team.ReadBasic.All | délégué | L’autorisation permet à l’utilisateur de sélectionner l’une de ces équipes jointes dans Jira. | ID d’équipe et nom à afficher dans l’écran Configuration de Jira. | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| TeamsAppInstallation.ReadForTeam | délégué | Lire les applications Teams installées dans Teams. Lors de la configuration de la remise Microsoft Teams l’application peut envoyer à Teams avec le bot installé. | Aucun | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| User.Read | délégué | Permet à l’utilisateur de créer un canal de discussion avec des collègues et de @mentionner dans un message de canal | Aucun | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| email | délégué | Le courrier électronique est utilisé pour faire correspondre atlassian et utilisateurs Microsoft | Le courrier électronique n’est pas stocké. Utilisé uniquement pendant le processus de correspondance. | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Accueillir les utilisateurs par leur nom lors de l’installation de l’application. Correspond aux utilisateurs Microsoft Teams et atlassien. | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous logons l’URL du client, qui est stockée dans les journaux pendant 5 jours au plus.

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

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Move Work Forward sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/><br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
