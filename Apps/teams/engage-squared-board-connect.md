---
title: Informations sur l’application pour les Connecter par Engage Squared
ms.author: elmalova
author: elenamalova
ms.date: 02/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour les Connecter du comité, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6b314c6cc51515efced101ba986555d859dc4182
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553185"
---
# <a name="board-connect"></a>Connexion de tableau

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e8f06a4e-cefe-4b1e-a24b-c97bea471130" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001955" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Engage Squared à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Connexion de tableau |
| ID | WA200001955 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Engage Squared |
| URL du site web partenaire | [https://boardconnect.app](https://boardconnect.app) |
| URL de la Teams d’informations sur l’application | [https://boardconnect.app](https://boardconnect.app) |
| URL de la politique de confidentialité | [https://boardconnect.app/privacy](https://boardconnect.app/privacy) |
| URL des conditions d’utilisation | [https://boardconnect.app/terms](https://boardconnect.app/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Engage Squared sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | délégué | Pour permettre à l’application de mettre à jour les calendriers des utilisateurs afin qu’ils reflètent les réponses de participation aux réunions du conseil envoyées via l’application. | Aucune donnée n’est stockée dans notre stockage de table Azure | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| Group.ReadWrite.All | délégué | Pour permettre à l’application de créer, mettre à jour et supprimer des événements de calendrier de groupe. | Nous stockons l’ID du groupe, ainsi que l’ID de client : il est stocké et utilisé du point de vue de la gestion des licences afin de pouvoir vérifier que l’organisation est titulaire d’une licence pour le Connecter. Nous l’utilisons également pour suivre le nombre d’installations des applications au sein du client, car cela est en ligne avec notre modèle de gestion des licences. | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| Sites.Manage.All | délégué | Pour permettre à l’application de créer des listes et des bibliothèques, gérez les éléments de liste et gérez les documents sur une collection de sites d’équipe. | Aucun | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.Read | délégué | Pour autoriser les utilisateurs à se connecter à l’application et permettre à l’application de lire le profil de l’utilisateur actuellement connecté. | Aucune donnée de ce point de terminaison n’est stockée dans notre stockage de table Azure | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.ReadBasic.All | délégué | Permet à l’application de lire un ensemble de base de propriétés de profil d’autres utilisateurs au nom de l’utilisateur inscrit, afin de l’afficher dans l’application. Cela inclut le nom d’affichage, le prénom et le nom, l’adresse e-mail et la photo. | Aucun, les données ne sont pas stockées dans notre stockage de table Azure | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| offline_access | délégué | Pour permettre à l’application d’obtenir un jeton d’actualisation, qu’elle peut utiliser pour obtenir un nouveau jeton d’accès à l’expiration de l’actuel. | Aucun, les données ne sont pas stockées dans notre stockage de table Azure | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |


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

>2FA pour tous les administrateurs, seuls deux utilisateurs au carré d’engagement peuvent accéder

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Engage Squared sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

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
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/> |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
