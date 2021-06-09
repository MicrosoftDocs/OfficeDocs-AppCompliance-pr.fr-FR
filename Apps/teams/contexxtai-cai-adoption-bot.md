---
title: Informations sur l’application C.AI bot d’adoption par contexxt.ai
ms.author: elmalova
author: elenamalova
ms.date: 05/06/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour C.AI Adoption Bot, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d5e1ad704a7b72a8d3717b7aa1b3d60b23099998
ms.sourcegitcommit: bb013192ff1a6db66c2ffe05cc83afc1d4140e76
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/09/2021
ms.locfileid: "52851594"
---
# <a name="cai-adoption-bot"></a>Bot C.AI d’adoption

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 6, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f5323aab-3063-46cb-b632-ee01d95de494" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002633" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par contexxt.ai à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Bot C.AI d’adoption |
| ID | WA200002633 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | contexxt.ai |
| URL du site web partenaire | [https://contexxt.ai](https://contexxt.ai) |
| URL de la Teams d’informations sur l’application | [https://contexxt.ai/cai-adoption-bot/](https://contexxt.ai/cai-adoption-bot/) |
| URL de la politique de confidentialité | [https://contexxt.ai/privacy-policy](https://contexxt.ai/privacy-policy) |
| URL des conditions d’utilisation | [https://contexxt.ai/terms-of-use](https://contexxt.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par contexxt.ai sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | application | Disponibilité de l’utilisateur en mesure d’envoyer des conseils au bon moment et non pendant les heures de travail au travail, par exemple | Disponibilité de l’utilisateur anonymisé en mesure d’envoyer des conseils au bon moment et non pendant les heures de travail, par exemple | abe28a0d-6acc-47d8-9169-cfcc2553bc13 |
>| ChannelMessage.Read.All | application | Microsoft Teams métadonnées de canal, telles que privées ou non, ou la quantité de conversations par canal pour analyser l’utilisation des Teams | Les métadonnées Microsoft Teams canal de données anonymes, telles que privés ou non, ou la quantité de conversations par canal pour analyser l’utilisation des Teams | abe28a0d-6acc-47d8-9169-cfcc2553bc13 |
>| Chat.Read.All | application | Microsoft Teams métadonnées de conversation, comme si un message a été aimé ou combien de groupes et de conversations 1:1 existent pour analyser l’utilisation des Teams | Les métadonnées Microsoft Teams conversation anonymes, comme si un message a été aimé ou combien de groupes et de conversations 1:1 existent pour analyser l’utilisation des Teams | abe28a0d-6acc-47d8-9169-cfcc2553bc13 |
>| Directory.Read.All | application | ID d’objet utilisateur pour pouvoir envoyer des conseils à l’utilisateur ultérieurement. | Hashed (anonymized) Object-ID of the user for being able sending tips to specifi user later. | abe28a0d-6acc-47d8-9169-cfcc2553bc13 |
>| Group.Read.All | application | Microsoft Teams métadonnées, telles que la quantité de Teams et de canaux pour analyser l’utilisation des Teams | Microsoft Teams métadonnées, telles que la quantité de Teams et de canaux pour analyser l’utilisation des Teams | abe28a0d-6acc-47d8-9169-cfcc2553bc13 |
>| Mail.Read | application | Microsoft Exchange métadonnées, telles que la quantité d’e-mails et de groupes par rapport aux e-mails 1:1 pour analyser l’utilisation des Exchange (par rapport à Teams) | Métadonnées microsoft Exchange anonymes, telles que la quantité d’e-mails et de groupes par rapport aux e-mails 1:1 pour analyser l’utilisation des Exchange (par rapport à Teams) | abe28a0d-6acc-47d8-9169-cfcc2553bc13 |
>| User.Read.All | application | Microsoft Teams de conversation et de conversation, comme si un utilisateur était mentionné pour analyser l’utilisation des Teams | Les métadonnées Microsoft Teams conversation et conversation anonymes, comme si un utilisateur était mentionné pour analyser l’utilisation des Teams | abe28a0d-6acc-47d8-9169-cfcc2553bc13 |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Dans Bot Framework, l’ID d’utilisateur est transmis automatiquement pour pouvoir communiquer avec l’utilisateur. Les données d’utilisation supplémentaires de C.AI Adoption Analytics sont utilisées pour individualiser l’expérience d’apprentissage pour l’utilisateur, et donc envoyer uniquement des conseils appropriés et utiles aux utilisateurs, qui ne connaissent peut-être pas ces conseils. | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les organizsations peuvent gérer (attribuer/supprimer) des licences pour leurs utilisateurs. Les organisations peuvent attribuer différents rôles pour gérer leurs licences. Les administrateurs peuvent toujours demander la suppression de leurs données.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par des contexxt.ai sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
