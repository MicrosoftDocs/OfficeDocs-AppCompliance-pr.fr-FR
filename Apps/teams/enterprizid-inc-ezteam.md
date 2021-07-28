---
title: Informations d’application pour ezTeam par EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour ezTeam, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6c4ad813b21963005857c69a05727ca261a73f9c
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525658"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 24, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par EnterprizID Inc à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | ezTeam |
| ID | WA200002546 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | EnterprizID Inc |
| URL du site web partenaire | [https://enterprizid.com](https://enterprizid.com) |
| URL de la Teams d’informations sur l’application | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL de la politique de confidentialité | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par EnterprizID Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | délégué | Liste des applications disponibles sur Teams de sorte que nous pouvons l’afficher Teams processus de création de demande | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Application.Read.All | délégué | Permet à l'application de lire les applications et les principes de service pour le compte de l'utilisateur connecté. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.AccessAsUser.All | délégué | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | délégué | Permet à l’application de lire les données dans l’annuaire de votre organisation, comme les utilisateurs, les groupes et les applications. | Teams Informations sur la propriété et l’appartenance  | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | application | Permet à l’application de lire les données dans l’annuaire de votre organisation, comme les utilisateurs, les groupes et les applications, sans utilisateur connecté. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | délégué | Permet à l’application de lire et d’écrire des données dans l’annuaire de votre organisation, telles que les utilisateurs et les groupes | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | application | Permet à l’application de lire et d’écrire des données dans l’annuaire de votre organisation, telles que les utilisateurs et les groupes, sans utilisateur connecté. N’autorise pas la suppression d’un utilisateur ou d’un groupe. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Files.Read.All | application | Permet à l’application de lire tous les fichiers dans toutes les collections de sites sans utilisateur connecté. | Quantité de données sous gouvernance de l’utilisateur final en Go | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Create | application | Permet à l’application de créer des groupes sans utilisateur. | Détails des nouvelles propriétés de groupe. | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | délégué | Permet à l’application de répertorier les groupes et de lire leurs propriétés et toutes les appartenances au groupe, au nom de l’utilisateur connecté. Utilisé pour déterminer Mon Teams  | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | application | Permet à l’application de lire les propriétés de groupe et les appartenances, et de lire le calendrier et les conversations de tous les groupes, sans utilisateurs. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | délégué | Permet à l’application de créer des groupes et de lire toutes les propriétés et les appartenances du groupe, au nom de l’utilisateur connecté.  | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | application | Permet à l’application de créer des groupes, de lire toutes les propriétés et appartenances de groupe, de mettre à jour les propriétés et appartenances des groupes et de supprimer des groupes. Permet également à l’application de lire et d’écrire le calendrier de groupe et les conversations.  | Dernière activité de l’équipe. | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.Read.All | application | Permet à l’application de consulter les abonnements et les propriétés de base de chaque groupe sans connexion d’utilisateur. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.ReadWrite.All | application | Permet à l’application de répertorier des groupes, consulter leurs propriétés de base et mettre à jour l’abonnement des groupes auxquels l’application a accès sans connexion d’utilisateur. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| People.Read.All | application | Permet à l’application de lire la liste des contacts pertinents de n’importe quel utilisateur, sans utilisateur. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | délégué | Permet à l’application de lire tous les rapports d’utilisation du service pour le compte de l’utilisateur connecté. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | application | Permet à l’application de lire tous les rapports d’utilisation du service sans utilisateur connecté. | Dernière activité utilisateur par groupe | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Sites.ReadWrite.All | application | Permet à l’application de créer, de lire, de mettre à jour et de supprimer des documents et des éléments de liste dans toutes les collections de sites sans utilisateur connecté. | 10 premiers sites par taille pour chaque utilisateur | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read | délégué | Permet aux utilisateurs de se connecter à l’application et permet à l’application de lire le profil des utilisateurs connectés. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read.All | application | Permet à l’application de lire les profils utilisateur sans utilisateur. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| offline_access | délégué | Permet à l’application de voir et de mettre à jour les données à qui vous lui avez donné accès, même lorsque les utilisateurs n’utilisent pas l’application.  | Notifications de bot | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| openid | délégué | Permet aux utilisateurs de se connecter à l’application avec leurs comptes professionnels ou scolaires et permet à l’application d’afficher les informations de profil utilisateur de base. | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| profil | délégué | Permet à l’application de voir le profil de base de vos utilisateurs (nom, image, nom d’utilisateur) | N/A | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Notifications de message de bienvenue, d’approbation et d’attestation | Nous stockons le nom complet des identités  | Notre outil permet aux utilisateurs finaux de créer une demande pour différents éléments de service et nous stockons le nom complet du demandeur. Une demande doit suivre un flux de travail d’approbation et nous avons besoin du nom complet de l’approuveur pour s’afficher dans les détails de la demande. En outre, dans les membres d’un processus de certification d’équipe, nous listons le nom complet des membres. |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>EndUser et nom complet de l’organisation. Les stratégies de rétention et de suppression se trouvent dans https://enterprizid.com/privacy-policy la section Rétention de vos données &quot; &quot; personnelles.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous avons activé Privileged Access Management (PMA) au sein d’Azure et les identités avec privilège pour se connecter aux ressources utilisent l'2FA pour renforcer la sécurité. Nous utilisons Azure comme fournisseur de partenaires cloud et nous sommes soumis à la confidentialité et aux conditions d’utilisation d’Azure

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par EnterprizID Inc sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
