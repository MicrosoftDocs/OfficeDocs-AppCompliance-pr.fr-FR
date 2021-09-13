---
title: Informations sur l’application pour iGlobe CRM Office 365 pour Microsoft 365 par iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour iGlobe CRM Office 365 pour Microsoft 365, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: dd871a1c4b9e8ef8dd0628ff73a2737e1b94550f
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283270"
---
# <a name="iglobe-crm-office-365-for-microsoft-365"></a>IGlobe CRM Office 365 for Microsoft 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 22, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.iglobecrmoffice365" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par iGlobe à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | IGlobe CRM Office 365 for Microsoft 365 |
| ID | 17859280.iglobecrmoffice365 |
| Nom de la société partenaire | iGlobe |
| URL du site web partenaire | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL de la politique de confidentialité | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL des conditions d’utilisation | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par iGlobe sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Avoir accès aux calendriers des utilisateurs lors de la convivialation d’un rapport de réunion à partir du canlendar dans iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | délégué | Directory.AccessAsUser.All | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Recherchez les autorisations et obtenez les sites et les listes. Créez des dossiers, obtenez des fichiers et enregistrez des fichiers. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, mettre à jour, créer des tâches du panneur, lire les fichiers récents et partagés des utilisateurs, pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers et des données dans SharePoint listes. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, mettre à jour, créer des tâches du panneur, lire les fichiers récents et partagés des utilisateurs, pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers dans SharePoint listes. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, mettre à jour, créer des tâches du panneur, lire les fichiers récents et partagés des utilisateurs, pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers dans SharePoint listes. Intégration à iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Svae the eamil to iGlobe CRM and get informatiopn from iGlobe to a new e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Créer, modifier et supprimer des éléments et des listes dans iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire des éléments dans iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Modifier et supprimer des éléments et des listes dans iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Créer une tâche de planificateur à partir d’iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir des informations sur iGlobe CRM pour l’utilisateur speficic | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | Non |  |  |  |  |
>| Exchange - Mail.Read.All | Non |  |  |  |  |
>| Exchange - Contacts.Read | Non |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | Non |  |  |  |  |
>| Exchange - Tasks.ReadWrite | Non |  |  |  |  |
>| SharePoint - AllSites.Manage | Non |  |  |  |  |
>| SharePoint - AllSites.Read | Non |  |  |  |  |
>| SharePoint -AllSites.Write | Non |  |  |  |  |
>| SharePoint - MyFiles.Write | Non |  |  |  |  |
>| SharePoint - Sites.Manage.All | Non |  |  |  |  |
>| SharePoint - Sites.Read.All | Non |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | Non |  |  |  |  |
>| SharePoint - Sites.Search.All | Non |  |  |  |  |
>| SharePoint - TermStore.Read.All | Non |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>iGlobe collecte des données pour fonctionner efficacement et vous offrir les meilleures expériences avec nos produits et services. Pour la gestion des licences : données collectées pour administrer le compte de licence de votre organisation&#8217;, par exemple lorsque vous déployez un module de licence gratuit, créez un abonnement d’essai ou achetez un abonnement. Les informations suivantes sont collectées. 
- À des fins financières : nom et adresse de la société
- Utilisateurs abonnés : nom d’utilisateur et e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Toutes les données se trouve sur le client. Aucune donnée d’application n’est stockée. Un add-in moderne s’exécute dans un navigateur en bac à sable,&#8220;hors processus&#8221;. Il interagit avec les données des utilisateurs à l’aide services Microsoft. Le module peut uniquement accéder aux données avec lesquelles l’utilisateur travaille.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par iGlobe sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Paramètres de sécurité par défaut et autres stratégies courantes telles que Bloquer l’authentification héritée* Exiger l’authentification multifacteur pour les administrateurs* Exiger l’authentification multifacteur pour la gestion Azure* Exiger l’authentification multifacteur pour tous les utilisateurs* |
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
