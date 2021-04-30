---
title: Informations sur l'application pour iPlanner Office 365 du planificateur pour Outlook par iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour le module complémentaire planificateur iPlanner Office 365 pour Outlook, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a62f773ba3b172035429af8dc612131a1d777ee3
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094069"
---
# <a name="iplanner-office-365-planner-add-in-for-outlook"></a>IPlanner Office 365 Planner pour Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: November 17, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380147" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par iGlobe à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | IPlanner Office 365 Planner pour Outlook |
| ID | WA104380147 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook sur le web |
| Nom de la société partenaire | iGlobe |
| URL du site web partenaire | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL de la politique de confidentialité | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL des conditions d'utilisation | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par iGlobe sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d'autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d'application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | délégué | Aucune donnée n'est stockée dans les bases de données d'application. | Pour obtenir la tâche du planificateur et ajouter de nouvelles tâches, mettez à jour le compartiment et la ligne de compartiment pour l'utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Contacts.ReadWrite | délégué | Aucune donnée n'est stockée dans les bases de données d'application. | pour créer un rendez-vous dans le calendrier des utilisateurs à la date d'échéance des tâches | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Directory.AccessAsUser.All | délégué | Aucune donnée n'est stockée dans les bases de données d'application. | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.Read | délégué | Aucune donnée n'est stockée dans les bases de données d'application. | Pour accéder à un fichier en tant que pièce jointe et télécharger des fichiers vers une tâche | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.ReadWrite.All | délégué | Aucune donnée n'est stockée dans les bases de données d'application. | Obtenir l'objet du courrier à partir du courrier sélectionné. Permet à l'application d'obtenir des informations à partir de l'e-mail sélectionné, ce qui permet de copier le champ de description dans la description de la tâche et d'enregistrer des pièces jointes à partir du courrier électronique ou du courrier lui-même dans la tâche. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Group.Read.All | délégué | Aucune donnée n'est stockée dans les bases de données d'application. |  pour obtenir la tâche du planificateur et ajouter de nouvelles tâches, mettez à jour le compartiment et la ligne de compartiment pour l'utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.Read | délégué | Aucune donnée n'est stockée dans les bases de données d'application. | Pour obtenir la tâche du planificateur et ajouter de nouvelles tâches, mettez à jour le compartiment et la ligne de compartiment pour l'utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.ReadBasic.All | délégué | Aucune donnée n'est stockée dans les bases de données d'application. |  Vérifier l'autorisation et obtenir la tâche du planificateur et ajouter de nouvelles tâches mettre à jour le compartiment et la ligne de compartiment pour l'utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| profil | délégué | Aucune donnée n'est stockée dans les bases de données d'application. | Pour obtenir la tâche du planificateur et ajouter de nouvelles tâches, mettez à jour le compartiment et la ligne de compartiment pour l'utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l'aide d'autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d'identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu'est-ce qu'OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | Non |  |  |  |  |
>| Exchange - Mail.Read.All | Non |  |  |  |  |
>| SharePoint - AllSites.Manage | Non |  |  |  |  |
>| SharePoint - AllSites.Read | Non |  |  |  |  |
>| SharePoint - AllSites.Write | Non |  |  |  |  |
>| SharePoint - MyFiles.Read | Non |  |  |  |  |
>| SharePoint - MyFiles.Write | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="add-in-data-access"></a>Accès aux données du add-in

List the permissions this app requires for accessing your organization's data, the justification and purpose for this permission (what does the app use this information for?) and whether the app stores any of this information in its databases.

>| **Autorisation**  | **Description** |
>|:----------------|:----------------|
>| ReadWrite Mailbox | Ce module peut lire ou modifier le contenu de n'importe quel élément de votre boîte aux lettres et créer des éléments. Il peut accéder à des informations personnelles, telles que le corps, l'objet, l'expéditeur, les destinataires ou les pièces jointes, dans n'importe quel élément de message ou de calendrier. Il peut envoyer ces données à un service tiers. |
>| Envoyer des données | Peut envoyer des données sur Internet |

#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>iGlobe collecte des données pour fonctionner efficacement et vous offrir les meilleures expériences avec nos produits et services. Pour la gestion des licences : données collectées pour administrer le compte de licence de votre organisation&#8217;, par exemple lorsque vous déployez un module de licence gratuit, créez un abonnement d'essai ou achetez un abonnement. Les informations suivantes sont collectées. 
- À des fins financières : nom et adresse de la société
- Utilisateurs abonnés : nom d'utilisateur et e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Toutes les données se trouve sur le client. Aucune donnée d'application n'est stockée. Un add-in moderne s'exécute dans un navigateur en bac à sable,&#8220;hors processus&#8221;. Il interagit avec les données des utilisateurs à l'aide services Microsoft. Le module peut uniquement accéder aux données avec lesquelles l'utilisateur travaille.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d'identité

Ces informations ont été fournies par iGlobe sur la façon dont cette application gère l'authentification, l'autorisation, les meilleures pratiques d'inscription des applications et d'autres critères d'identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d'identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft'intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d'authentification Microsoft) pour l'authentification ? | Non |
| Votre application prend-elle en charge les stratégies d'accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Paramètres de sécurité par défaut et autres stratégies courantes telles que Bloquer l'authentification héritée* Exiger l'authentification multifacteur pour les administrateurs* Exiger l'authentification multifacteur pour la gestion Azure* Exiger l'authentification multifacteur pour tous les utilisateurs* |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l'location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d'aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
