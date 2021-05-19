---
title: Informations sur les demandes d’ezTeam par EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour ezTeam, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: da54d5a540fd43c2bdc25a6f4e31ba88520ecbc3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553175"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Février 24, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par EnterprizID Inc à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | ezTeam |
| ID | WA200002546 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | EnterprizID Inc |
| URL du site web partenaire | [https://enterprizid.com](https://enterprizid.com) |
| URL de la page Teams’informations d’application | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL de la politique de confidentialité | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par EnterprizID Inc sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.Read.All | Délégué | Liste des applications disponibles à Teams afin que nous puissions le montrer sur le processus Teams de création de demande | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Application.Read.All | Délégué | Permet à l'application de lire les applications et les principes de service pour le compte de l'utilisateur connecté. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | Délégué | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | Délégué | Permet à l’application de lire les données dans l’annuaire de votre organisation, comme les utilisateurs, les groupes et les applications. | Teams Informations sur la propriété et l’adhésion  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | application | Permet à l’application de lire les données dans l’annuaire de votre organisation, comme les utilisateurs, les groupes et les applications, sans utilisateur connecté. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | Délégué | Permet à l’application de lire et d’écrire des données dans l’annuaire de votre organisation, tels que les utilisateurs et les groupes | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | application | Permet à l’application de lire et d’écrire des données dans l’annuaire de votre organisation, telles que les utilisateurs et les groupes, sans utilisateur connecté. N’autorise pas la suppression d’un utilisateur ou d’un groupe. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | application | Permet à l’application de lire tous les fichiers dans toutes les collections de sites sans utilisateur connecté. | Quantité de données sous gouvernance utilisateur final en Gb | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Create | application | Permet à l’application de créer des groupes sans utilisateur connecté. | Nouveaux détails sur les propriétés du groupe. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | Délégué | Permet à l’application de répertorier les groupes et de lire leurs propriétés et toutes les appartenances au groupe, au nom de l’utilisateur connecté. Utilisé pour déterminer Mon Teams  | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | application | Permet à l’application de lire les propriétés et les adhésions du groupe, et de lire le calendrier et les conversations pour tous les groupes, sans utilisateur connecté. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | Délégué | Permet à l’application de créer des groupes et de lire toutes les propriétés et les appartenances du groupe, au nom de l’utilisateur connecté.  | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | application | Permet à l’application de créer des groupes, de lire toutes les propriétés et adhésions de groupe, de mettre à jour les propriétés et les adhésions du groupe et de supprimer des groupes. Permet également à l’application de lire et d’écrire le calendrier de groupe et les conversations.  | Dernière activité de l’Équipe. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.Read.All | application | Permet à l’application de consulter les abonnements et les propriétés de base de chaque groupe sans connexion d’utilisateur. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.ReadWrite.All | application | Permet à l’application de répertorier des groupes, consulter leurs propriétés de base et mettre à jour l’abonnement des groupes auxquels l’application a accès sans connexion d’utilisateur. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| People.Read.All | application | Permet à l’application de lire la liste des personnes concernées notées par l’utilisateur, sans utilisateur connecté. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | Délégué | Permet à l’application de lire tous les rapports d’utilisation du service pour le compte de l’utilisateur connecté. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | application | Permet à l’application de lire tous les rapports d’utilisation du service sans utilisateur connecté. | Dernière activité utilisateur par groupe | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | application | Permet à l’application de créer, de lire, de mettre à jour et de supprimer des documents et des éléments de liste dans toutes les collections de sites sans utilisateur connecté. | Top 10 des sites par taille pour chaque utilisateur | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | Délégué | Permet aux utilisateurs de se connecter à l’application et permet à l’application de lire le profil des utilisateurs connectés. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | application | Permet à l’application de lire les profils des utilisateurs sans un utilisateur connecté. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | Délégué | Permet à l’application de voir et de mettre à jour les données à qui vous lui avez donné accès, même lorsque les utilisateurs n’utilisent pas actuellement l’application.  | Notifications bot | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| openid | Délégué | Permet aux utilisateurs de se connecter à l’application avec leurs comptes professionnels ou scolaires et permet à l’application d’afficher les informations de profil utilisateur de base. | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| profil | Délégué | Permet à l’application de voir le profil de base de vos utilisateurs (nom, image, nom d’utilisateur) | N/A | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Message de bienvenue, approbation et processus d’attestation notifications | Nous stockons le nom d’affichage des identités  | Notre outil permet aux utilisateurs finaux de créer une demande pour différents éléments de service et nous stockons le nom d’affichage du demandeur. Une demande suivrait un workflow d’approbation et nous avons besoin du nom d’affichage de l’approbateur afin de montrer dans les détails de la demande. De plus, dans le cadre d’un processus de certification d’équipe, nous énumérons le nom d’affichage des membres. |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>EndUser et Organisation Nom complet. Les politiques de conservation et de suppression peuvent être trouvées https://enterprizid.com/privacy-policy à la section Conservation de vos données &quot; &quot; personnelles

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Nous avons permis à Privileged Access Management (PMA) au sein d’Azure et aux identités avec privilège de se connecter aux ressources utilise 2FA pour augmenter la sécurité. Nous utilisons Azure comme fournisseur de partenaires cloud et nous sommes soumis à la confidentialité et aux conditions d’utilisation d’Azure

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par EnterprizID Inc sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle le moins d’autorisations de privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles fidèlement les autorisations que votre application demandera de manière dynamique et progressive ? | Oui |
| Votre application prend-elle en charge la multi-location ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Possédez-vous l’ensemble de l’identifiant de ressources unifié (URI) redirigé enregistré pour votre application ? | Oui |
| Pour votre application, qu’évitez-vous d’utiliser ? | - Wildcard rediriger les URL,<br/>- OAuth2 Implicite Flow, sauf si nécessaire pour un SPA<br/>- Flux d’identification de mot de passe propriétaire de ressources (ROPC) |
| Votre application expose-t-elle des API Web ? | Oui |
| Votre modèle d’autorisation ne permet-il aux appels de réussir que si l’application client reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de prévisualisation ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
