---
title: Informations d’application pour Vacation Tracker par Vacation Tracker
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Vacation Tracker, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 89ed0cc27e26acdeae13cc787fc180cc9f93b8ae
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550994"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Février 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Vacation Tracker à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Vacation Tracker |
| ID | WA200002167 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Vacation Tracker |
| URL du site web partenaire | [https://vacationtracker.io](https://vacationtracker.io) |
| URL de la page Teams’informations d’application | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL de la politique de confidentialité | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL des conditions d’utilisation | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Vacation Tracker sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | Délégué | Nous lisons les iD et les noms des chaînes publiques lorsque les utilisateurs fixent leurs notifications hebdomadaires ou quotidiennes. | Les utilisateurs peuvent sélectionner un canal où ils souhaitent recevoir des notifications quotidiennes ou hebdomadaires de Vacation Tracker. Lorsqu’un utilisateur choisit son canal préféré, nous stockons l’iD du canal. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Team.ReadBasic.All | Délégué | Nous énumérons les Microsoft Teams utilisateurs des équipes sélectionnées lors de l’inscription pour permettre aux utilisateurs de sélectionner une équipe qu’ils souhaitent s’inscrire à Vacation Tracker. Ils peuvent alternativement s’inscrire auprès de toute leur organisation. | Nous stockons l’Microsoft Teams’identification d’équipe pour une équipe sélectionnée uniquement si l’utilisateur s’insindrie à Vacation Tracker en tant qu’équipe unique (et non en tant qu’organisation entière). Nous utilisons des iD d’équipe pour connecter un utilisateur connecté à un compte existant dans Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | Délégué | Nous recueillons les informations de base de l’utilisateur, y compris son nom, son identité et son identifiant de locataire. Nous utilisons ces données pour connecter les utilisateurs connectés à leur organisation dans Vacation Tracker. | Nous stockons le nom de l’utilisateur, l’identité et l’identité du locataire. Nous utilisons ces données pour connecter les utilisateurs connectés à leur organisation dans Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | Délégué | Nos utilisateurs peuvent importer tous les utilisateurs de leur organisation Microsoft 365'organisation ou Microsoft Teams équipe. Nous utilisons cette autorisation pour importer uniquement des utilisateurs titulaires d’une licence pour une équipe Microsoft Teams’une organisation sélectionnée. | Nous stockons des informations de base sur les utilisateurs importés, y compris leur nom, adresse e-mail et identifiant d’utilisateur. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | Délégué | Nous permettons aux utilisateurs d’importer les autres utilisateurs de leur organisation ou de leur Microsoft Teams équipe. Nous utilisons cette autorisation pour énumérer les utilisateurs disponibles et leurs adresses e-mail dans le popup d’importation. | Lorsque les utilisateurs choisissent leurs collègues à importer sur Vacation Tracker, nous stockons des informations de base sur ces utilisateurs importés, y compris leur nom, adresse e-mail et identifiant d’utilisateur. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| email | Délégué | Lorsque l’utilisateur se connecte à l’aide de Microsoft AAD, nous stockons leur adresse e-mail comme un identifiant unique. | Nous stockons l’e-mail de l’utilisateur comme un identificateur unique. Nous n’utilisons pas cet e-mail pour la communication, les utilisateurs saisnt leur adresse e-mail d’entreprise que nous utilisons pour la communication pendant l’inscription. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | Délégué | Nous ne recueillons aucune donnée avec cette permission. Il est utilisé pour maintenir l’accès aux données que nous permission d’accéder. | Nous ne stockons aucune donnée avec cette permission. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| openid | Délégué | Nous utilisons cette autorisation pour vous connecter ou inscrire des utilisateurs à Vacation Tracker. Nous ne recueillons pas de données spécifiques avec cette autorisation. | Nous utilisons cette autorisation pour vous connecter ou inscrire des utilisateurs à Vacation Tracker. Nous ne stockons pas de données spécifiques avec cette autorisation. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| profil | Délégué | Nous recueillons les informations de base de l’utilisateur, y compris son nom, son identité et son identifiant de locataire. Nous utilisons ces données pour connecter les utilisateurs connectés à leur organisation dans Vacation Tracker. | Nous stockons le nom de l’utilisateur, l’identité et l’identité du locataire. Nous utilisons ces données pour connecter les utilisateurs connectés à leur organisation dans Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | Nom de l’entreprise (tel qu’il est entré par l’utilisateur) | Lorsqu’un utilisateur s’insr signe, il entre le nom de son entreprise et nous utilisons ce nom comme nom d’organisation à l’intérieur du produit. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Le bot peut voir les informations de base sur l’utilisateur communiquant avec le bot. Toutefois, nous ne stockons ni n’utilisons ces informations. Nous n’utilisons que l’iD de l’utilisateur, l’identifiant de conversation et un message envoyé à notre bot. | Nous stockons l’adresse e-mail de l’utilisateur, le nom de l’utilisateur (tel que défini dans l’AAD Microsoft) et la photo de profil de l’utilisateur (à partir de Microsoft AAD) | Nous utilisons une adresse e-mail comme identifiant unique pour nos utilisateurs et le nom et la photo de profil de l’utilisateur pour permettre aux administrateurs et aux approbateurs de la même entreprise de reconnaître leurs employés dans notre tableau de bord.  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Nom de l’entreprise et il est conservé et supprimer conformément à notre politique standard de conservation d’un an pour ce type de données

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Pour commencer, nous recueillons le minimum de données requises auprès des utilisateurs. Ensuite, nous partageons le minimum possible avec nos partenaires et finalement nous avons des politiques de conservation des données afin que toutes les données soient supprimées dans un délai d’un an, le cas échéant.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Vacation Tracker sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle le moins d’autorisations de privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles fidèlement les autorisations que votre application demandera de manière dynamique et progressive ? | Oui |
| Votre application prend-elle en charge la multi-location ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Possédez-vous l’ensemble de l’identifiant de ressources unifié (URI) redirigé enregistré pour votre application ? | Oui |
| Pour votre application, qu’évitez-vous d’utiliser ? | - Wildcard rediriger les URL,<br/>- OAuth2 Implicite Flow, sauf si nécessaire pour un SPA<br/>- Flux d’identification de mot de passe propriétaire de ressources (ROPC) |
| Votre application expose-t-elle des API Web ? | Oui |
| Votre modèle d’autorisation ne permet-il aux appels de réussir que si l’application client reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de prévisualisation ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
