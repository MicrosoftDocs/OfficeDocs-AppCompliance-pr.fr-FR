---
title: Informations d’application pour Office2SharePoint Office par iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour Office2SharePoint pour Office, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 85198f216bb99ab5d172886d7852878d0cf61be1
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281556"
---
# <a name="office2sharepoint-for-office"></a>Office2SharePoint pour Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: November 17, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381787" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par iGlobe à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Office2SharePoint pour Office |
| ID | WA104381787 |
| Office 365 clients pris en charge | Excel 2016 ou une ultérieure sur Mac, Excel 2016 ou une ultérieure sur Windows, Excel sur le Web, Word 2016 ou ultérieur sur Mac, Word sur le web, Word 2016 ou ultérieur sur Windows, PowerPoint 2016 ou ultérieur sur Mac, PowerPoint sur le web, PowerPoint 2016 ou une Windows |
| Nom de la société partenaire | iGlobe |
| URL du site web partenaire | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL de la politique de confidentialité | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL des conditions d’utilisation | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par iGlobe sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Recherchez les autorisations et obtenez les sites et les listes. Créez des dossiers, obtenez des fichiers et enregistrez des fichiers. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Recherchez les autorisations et obtenez les sites et les listes. Créez des dossiers, obtenez des fichiers et enregistrez des fichiers. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir les sites de groupe utilisateurs. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour accéder aux e-mails sélectionnés et obtenir les pièces jointes. À partir du courrier électronique ou de l’SharePoint site de groupes au courrier électronique. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Mail.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour accéder aux e-mails sélectionnés et obtenir les pièces jointes. À partir du courrier électronique ou de l’SharePoint site de groupes au courrier électronique. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Permet à l’application de créer ou de supprimer des bibliothèques de documents et des listes dans toutes les collections de sites pour le compte de l’utilisateur. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir les utilisateurs SharePoint site. Obtenez des fichiers et enregistrez les pièces jointes à partir du courrier sélectionné. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers dans SharePoint listes. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir les utilisateurs SharePoint site, OneDrive sites et sites de groupe. | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | Non |  |  |  |  |
>| Exchange - Mail.ReadWrite | Non |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | Non |  |  |  |  |
>| SharePoint- AllSites.Manage | Non |  |  |  |  |
>| SharePoint - AllSites.Write | Non |  |  |  |  |
>| SharePoint - MyFiles.Write | Non |  |  |  |  |
>| SharePoint - User.Read.All | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>iGlobe collecte des données pour fonctionner efficacement et vous offrir les meilleures expériences avec nos produits et services. Pour la gestion des licences : données collectées pour administrer le compte de licence de votre organisation&#8217;, par exemple lorsque vous déployez un module de licence gratuit, créez un abonnement d’essai ou achetez un abonnement. Les informations suivantes sont collectées. À des fins financières : Nom de la société et adresse des utilisateurs abonnés : nom d’utilisateur et e-mail


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Toutes les données d’application se trouve sur le client et sont contrôlées par l’administrateur client comme tous les autres services Office 365. Aucune donnée d’application n’est stockée dans le add-in. Un add-in moderne s’exécute dans un navigateur en bac à sable,&#8220;hors processus&#8221;. Le module peut uniquement accéder aux données avec lesquelles l’utilisateur travaille. Il interagit avec les données des utilisateurs à l’aide services Microsoft.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par iGlobe sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
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
