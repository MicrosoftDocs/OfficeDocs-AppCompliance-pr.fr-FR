---
title: Informations d’application pour Office2SharePoint pour Office par iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour Office2SharePoint pour Office, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1d1fccbab2aab91eacbc5a43ef79462dd536ff6e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548844"
---
# <a name="office2sharepoint-for-office"></a>Office2SharePoint pour Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur le: Novembre 17, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381787" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par iGlobe à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Office2SharePoint pour Office |
| ID | WA104381787 |
| Office 365 clients soutenus | Excel 2016 ou plus tard sur Mac, Excel 2016 ou plus tard sur Windows, Excel sur le Web, Word 2016 ou plus tard sur Mac, Word sur le web, Word 2016 ou plus tard sur Windows, PowerPoint 2016 ou plus tard sur Mac, PowerPoint sur le web, PowerPoint 2016 ou plus tard sur Windows |
| Nom de l’entreprise partenaire | iGlobe |
| URL du site web partenaire | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL de la politique de confidentialité | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL des conditions d’utilisation | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par iGlobe sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Vérifiez l’autorisation et pour obtenir les sites et les listes. Créez des dossiers, obtenez des fichiers et enregistrez des fichiers. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Vérifiez l’autorisation et pour obtenir les sites et les listes. Créez des dossiers, obtenez des fichiers et enregistrez des fichiers. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour obtenir les sites du Groupe des utilisateurs. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour accéder aux mail/s sélectionnés et obtenir les pièces jointes. Du courrier ou ajouter à partir SharePoint site ou groupes au courrier. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Mail.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour accéder aux mail/s sélectionnés et obtenir les pièces jointes. Du courrier ou ajouter à partir SharePoint site ou groupes au courrier. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Permet à l’application de créer ou de supprimer des bibliothèques de documents et des listes dans toutes les collections de sites pour le compte de l’utilisateur connecté. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour obtenir les utilisateurs SharePoint site. Obtenez des fichiers et enregistrez les pièces jointes à partir du courrier sélectionné. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers sur SharePoint listes. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour obtenir les utilisateurs sur SharePoint site, OneDrive et les sites du Groupe. | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les modules complémentaires intégrés à Microsoft 365 peuvent utiliser d’autres API Microsoft que Microsoft Graph pour recueillir ou traiter des informations organisationnelles identifiables (OII). Énumérez toutes les API Microsoft autres que Microsoft Graph utilisations de cette application.

>| **API** |  **L’ŒIL est-il recueilli?** |  **Quel OII est recueilli?** | **Justification de la collecte de l’ŒII?** | **OII est-il stocké ?** | **Justification pour stocker OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | Non |  |  |  |  |
>| Exchange - Mail.ReadWrite | Non |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | Non |  |  |  |  |
>| SharePoint- AllSites.Manage | Non |  |  |  |  |
>| SharePoint - AllSites.Write | Non |  |  |  |  |
>| SharePoint - MyFiles.Write | Non |  |  |  |  |
>| SharePoint - User.Read.All | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>iGlobe recueille des données pour fonctionner efficacement et vous fournir les meilleures expériences avec nos produits et services. Pour l’octroi de licences : Données collectées pour administrer le compte de licence de votre organisation&#8217;, par exemple lorsque vous déployez un add-in gratuit, créez un abonnement d’essai ou achetez un abonnement. Les informations suivantes sont recueillies. À des fins financières : Nom et adresse de l’entreprise Utilisateurs abonnés : nom d’utilisateur et courriel


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Toutes les données d’application sont sur le propre locataire du client et elles sont contrôlées par l’administrateur locataire comme tous les autres services Office 365. Aucune donnée d’application n’est stockée dans l’add-in. Un module d’ajout moderne s’exécute dans un navigateur bac à sable, &#8220;hors processus&#8221;. L’add-in ne peut accéder qu’aux données avec lesquelles l’utilisateur travaille. Il interagit avec les données des utilisateurs en utilisant services Microsoft.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par iGlobe sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Énumérer les types de politiques prises en charge | Les défauts de sécurité et toute autre des stratégies courantes telles que l’authentification héritée de Bloc* Nécessitent un AMF pour les administrateurs* Exiger un AMF pour la gestion Azure* Exiger un AMF pour tous les utilisateurs* |
| Votre application demande-t-elle le moins d’autorisations de privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles fidèlement les autorisations que votre application demandera de manière dynamique et progressive ? | Oui |
| Votre application prend-elle en charge la multi-location ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Possédez-vous l’ensemble de l’identifiant de ressources unifié (URI) redirigé enregistré pour votre application ? | Oui |
| Votre application expose-t-elle des API Web ? | Non |
| Votre application utilise-t-elle des API de prévisualisation ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
