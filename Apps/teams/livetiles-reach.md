---
title: Informations d’application pour la portée par LiveTiles
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Reach, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c58462500079df7f7b8b2736eec9289443df4a4c
ms.sourcegitcommit: 9199fd569c5e7c5dd338abd87428c94798a22352
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/23/2022
ms.locfileid: "63753738"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par LiveTiles à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Reach |
| ID | WA200002045 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | LiveTiles |
| URL du site web partenaire | [https://livetilesglobal.com](https://livetilesglobal.com) |
| URL de la Teams d’informations sur l’application | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| URL de la politique de confidentialité | [https://livetilesglobal.com/privacy-policy/](https://livetilesglobal.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://livetilesglobal.com/eula/](https://livetilesglobal.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par LiveTiles sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | application | none | none | [a7c1920d-3ac0-42db-9757-078a2b321fd8 ](../azure/a7c1920d-3ac0-42db-9757-078a2b321fd8.md ) |
>| User.Read | délégué | User DisplayName, User Email Address, UPN. Obligatoire pour permettre aux utilisateurs de se connecter à l’application et d’obtenir des informations de base de l’utilisateur, telles que le nom complet. L’adresse e-mail est utilisée pour envoyer des notifications par courrier électronique.  | User DisplayName, User Email Address, UPN. Obligatoire pour permettre aux utilisateurs de se connecter à l’application et d’obtenir des informations de base de l’utilisateur, telles que le nom complet. L’adresse e-mail est utilisée pour envoyer des notifications par courrier électronique.  | [d492530a-8cff-481c-90da-9c3c3f1be7da](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md) |
>| User.ReadBasic.All | délégué | User DisplayName, User Email Address, UPN, User Department, User Job Title, User Mobile Téléphone Number, User Business Téléphone Number, User Office Location. Obligatoire pour permettre aux utilisateurs de rechercher d’autres utilisateurs dans l’application (Phonebook) et voir le profil de base et les informations de contact des autres utilisateurs.  | none | [d492530a-8cff-481c-90da-9c3c3f1be7da](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md) |
>| Directory.Read.All | application | Appartenance aux groupes, groupes AD dans l’annuaire. L’appartenance à un groupe d’utilisateurs est stockée dans un cache pour minimiser les appels à l’API Microsoft Graph. Obligatoire pour permettre aux utilisateurs de rechercher des groupes Active Directory. En outre, cette autorisation est requise pour que l’application résolve l’appartenance à un groupe AD d’utilisateurs dans les travaux web du serveur arrière. | Appartenance à un groupe d’utilisateurs. L’appartenance à un groupe d’utilisateurs est stockée dans un cache pour minimiser les appels à l’API Microsoft Graph. Obligatoire pour permettre aux utilisateurs de rechercher des groupes Active Directory. En outre, cette autorisation est requise pour que l’application résolve l’appartenance à un groupe AD d’utilisateurs dans les travaux web du serveur arrière.  | [d492530a-8cff-481c-90da-9c3c3f1be7da ](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md ) |
>| User.Read.All | application | Les données récupérées à partir du profil utilisateur dépendent de la configuration de la fonctionnalité de ciblage d’audience spécifiée dans l’application. Obligatoire pour permettre à l’application de lire les profils utilisateur sans utilisateur. La lecture des données de profil est nécessaire pour la fonctionnalité de ciblage d’informations dans l’application, afin que les informations s’affichent pour des utilisateurs spécifiques en fonction d’une valeur de propriété de profil spécifique.  | none | [d492530a-8cff-481c-90da-9c3c3f1be7da ](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md ) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| SendGrid, OneSignal | adresse e-mail, nom complet | Envoyer une notification à l’utilisateur par courrier électronique et notifications Push mobiles |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>adresse de messagerie, UPN. Rétention maximale de 60 jours, après leur suppression

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les administrateurs peuvent contacter le support technique pour toute demande

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par LiveTiles sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Non |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Authentification multifacteur, restriction des emplacements utilisateur et des plages IP |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | -  URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
