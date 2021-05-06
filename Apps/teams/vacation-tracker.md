---
title: Informations sur l’application pour le suivi des vacances par le suivi des vacances
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour le suivi des vacances, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f4f6c515c09b33bc5ffbb9c4cb3c702362b9059c
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252244"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par le suivi des vacances à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Vacation Tracker |
| ID | WA200002167 |
| Fonctionnalités | Bot, Onglet |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Vacation Tracker |
| URL du site web partenaire | [https://vacationtracker.io](https://vacationtracker.io) |
| URL de la Teams d’informations sur l’application | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL de la politique de confidentialité | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL des conditions d’utilisation | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par le suivi des vacances sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | délégué | Nous lisons les ID et les noms des canaux publics lorsque les utilisateurs définissent leurs notifications hebdomadaires ou quotidiennes. | Les utilisateurs peuvent sélectionner un canal dans lequel ils souhaitent recevoir des notifications quotidiennes ou hebdomadaires à partir du suivi des vacances. Lorsqu’un utilisateur choisit son canal préféré, nous stockons l’ID de canal. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Team.ReadBasic.All | délégué | Nous listons les utilisateurs Microsoft Teams teams joints lors de l’inscription pour permettre aux utilisateurs de sélectionner une équipe qu’ils souhaitent inscrire au suivi des vacances. Ils peuvent également s’inscrire à l’ensemble de leur organisation. | Nous stockons l’ID Microsoft Teams d’équipe d’une équipe sélectionnée uniquement si l’utilisateur s’adeinsse au suivi des vacances en tant qu’équipe unique (et non en tant qu’organisation entière). Nous utilisons les ID d’équipe pour connecter un utilisateur connecté à un compte existant dans le suivi des vacances. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | délégué | Nous collectons les informations de base de l’utilisateur, notamment son nom, son ID et son ID de client. Nous utilisons ces données pour connecter les utilisateurs connectés à leur organisation dans le suivi des vacances. | Nous stockons le nom, l’ID et l’ID client de l’utilisateur. Nous utilisons ces données pour connecter les utilisateurs connectés à leur organisation dans le suivi des vacances. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | délégué | Nos utilisateurs peuvent importer tous les utilisateurs de leur Microsoft 365 organisation ou Microsoft Teams équipe. Nous utilisons cette autorisation pour importer uniquement les utilisateurs sous licence pour une équipe Microsoft Teams ou une organisation. | Nous stockons des informations de base sur les utilisateurs importés, notamment leur nom, leur adresse e-mail et leur ID d’utilisateur. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | délégué | Nous permettons aux utilisateurs d’importer les autres utilisateurs de leur organisation ou de leur Microsoft Teams équipe. Nous utilisons cette autorisation pour lister les utilisateurs disponibles et leurs adresses de messagerie dans la fenêtre d’importation. | Lorsque les utilisateurs sélectionnent leurs collègues à importer dans le suivi des vacances, nous stockons des informations de base sur ces utilisateurs importés, notamment leur nom, leur adresse e-mail et leur ID d’utilisateur. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| email | délégué | Lorsque l’utilisateur se connecte à l’aide de Microsoft AAD, nous stockons son adresse de messagerie en tant qu’identificateur unique. | Nous stockons le courrier électronique de l’utilisateur en tant qu’identificateur unique. Nous n’utilisons pas ce courrier électronique pour la communication, les utilisateurs entrent leur adresse de messagerie professionnelle que nous utilisons pour la communication pendant l’inscription. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | délégué | Nous ne collectons aucune donnée avec cette autorisation. Il est utilisé pour maintenir l’accès aux données que nous avons l’autorisation d’accéder. | Nous ne stockons pas de données avec cette autorisation. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| openid | délégué | Nous utilisons cette autorisation pour vous inscrire ou vous inscrire aux suivis de vacances. Nous ne collectons pas de données spécifiques avec cette autorisation. | Nous utilisons cette autorisation pour vous inscrire ou vous inscrire aux suivis de vacances. Nous ne stockons pas de données spécifiques avec cette autorisation. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| profil | délégué | Nous collectons les informations de base de l’utilisateur, notamment son nom, son ID et son ID de client. Nous utilisons ces données pour connecter les utilisateurs connectés à leur organisation dans le suivi des vacances. | Nous stockons le nom, l’ID et l’ID client de l’utilisateur. Nous utilisons ces données pour connecter les utilisateurs connectés à leur organisation dans le suivi des vacances. | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | Nom de la société (tel qu’entré par l’utilisateur) | Lorsqu’un utilisateur s’inscrivez, il entre son nom d’entreprise et nous l’utilisons comme nom d’organisation à l’intérieur du produit. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Le bot peut voir les informations de base sur l’utilisateur qui communique avec le bot. Toutefois, nous ne stockons pas et n’utilisons pas ces informations. Nous utilisons uniquement l’ID de l’utilisateur, l’ID de conversation et un message envoyé à notre bot. | Nous stockons l’adresse e-mail de l’utilisateur, son nom (tel que défini dans Microsoft AAD) et la photo de profil de l’utilisateur (à partir de Microsoft AAD) | Nous utilisons une adresse de messagerie comme identificateur unique pour nos utilisateurs, ainsi que le nom et la photo de profil de l’utilisateur pour permettre aux administrateurs et aux approuveurs de la même société de reconnaître leurs employés dans notre tableau de bord.  |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nom de la société et conservé et supprimé conformément à notre stratégie de rétention standard d’un an pour ce type de données

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Pour commencer, nous collectons la quantité minimale de données requises des utilisateurs. Ensuite, nous partageons le minimum possible avec nos partenaires et nous avons enfin des stratégies de rétention des données afin que toutes les données sont supprimées dans un délai d’un an, le cas échéant.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par le suivi des vacances sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
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
