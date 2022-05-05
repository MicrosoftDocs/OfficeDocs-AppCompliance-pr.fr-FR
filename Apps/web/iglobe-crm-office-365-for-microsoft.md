---
title: Informations sur l’application pour iGlobe CRM Office 365 pour Microsoft 365
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour iGlobe CRM Office 365 pour Microsoft 365, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 020e2ce913d50c72c401b4d08bc7810173faaa28
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225011"
---
# <a name="application-information-for-iglobe-crm-office-365-for-microsoft-365"></a>Informations d’application pour iGlobe CRM Office 365 pour Microsoft 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur : 22 juin 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.iglobecrmoffice365" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par iGlobe à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | iGlobe CRM Office 365 pour Microsoft 365 |
| ID | 17859280.iglobecrmoffice365 |
| Nom de la société partenaire | iGlobe |
| URL du site web du partenaire | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL de la politique de confidentialité | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL des conditions d’utilisation | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par iGlobe sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>| **Permission**  | **Type d’autorisation (délégué/application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-ils stockées ? Justification du stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Avoir accès aux calendriers utilisateur lors de l’dreating d’un rapport de réunion du canlendar vers iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | Délégué | Directory.AccessAsUser.All | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Recherchez l’autorisation et obtenez les sites et les listes. Créez des dossiers, obtenez des fichiers et enregistrez des fichiers. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, mettre à jour, créer des tâches Panner, Lire les fichiers récents et partagés des utilisateurs, Pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers et des données dans SharePoint listes. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, mettre à jour, créer des tâches Panner, Lire les fichiers récents et partagés des utilisateurs, Pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers dans SharePoint listes. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, mettre à jour, créer des tâches Panner, Lire les fichiers récents et partagés des utilisateurs, Pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers dans SharePoint listes. Intégration à iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Svae l’eamil à iGlobe CRM et obtenir informatiopn d’iGlobe à un nouveau e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Créer, modifier et supprimer des éléments et des listes dans iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire des éléments dans iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Modifier et supprimer des éléments et des listes dans iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Créer une tâche de planificateur à partir d’iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir des informations sur iGlobe CRM pour l’utilisateur speficic | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et compléments basés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelles (OII). Répertoriez toutes les API Microsoft autres que Microsoft Graph utilisées par cette application.

>| **API** |  **OII est-il collecté ?** |  **Quelle OII est collectée ?** | **Justification de la collecte d’OII ?** | **OII est-il stocké ?** | **Justification du stockage d’OII ?** |
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

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>Les non-services Microsoft ne sont pas utilisées.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>iGlobe collecte des données pour fonctionner efficacement et vous offrir les meilleures expériences avec nos produits et services. Pour les licences : données collectées pour administrer votre organisation&#8217;compte de licence, par exemple lorsque vous déployez des compléments gratuits, créez un abonnement d’évaluation ou achetez un abonnement. Les informations suivantes sont collectées. 
- À des fins financières : nom et adresse de la société
- Utilisateurs abonnés : nom d’utilisateur et e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>Toutes les données se trouve sur le propre locataire du client. Aucune donnée d’application n’est stockée. Un complément moderne s’exécute dans un navigateur en bac à sable ( sandbox), &#8220;hors processus&#8221;. Il interagit avec les données des utilisateurs à l’aide de services Microsoft. Le complément peut accéder uniquement aux données avec lesquelles l’utilisateur travaille.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans l’examen ou l’analyse des données d’information d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par iGlobe sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Intégrez-vous à La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle d’intégration Plateforme d'identités Microsoft ?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Répertorier les types de stratégies prises en charge | Paramètres de sécurité par défaut et autres stratégies courantes telles que Bloquer l’authentification héritée* Exiger l’authentification multifacteur pour les administrateurs* Exiger l’authentification multifacteur pour la gestion Azure* Exiger l’authentification multifacteur pour tous les utilisateurs* |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations inscrites statiquement de votre application reflètent-elles précisément les autorisations demandées par votre application de manière dynamique et incrémentielle ? | Oui |
| Votre application prend-elle en charge la mutualisation ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de l’URI (Identificateur de ressource unifié) de redirection inscrit pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle des API de préversion ? | Non |
| Votre application utilise-t-elle des API déconseillées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
