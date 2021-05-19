---
title: Informations d’application pour iGlobe CRM Office 365 pour Microsoft Office 365 par iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour iGlobe CRM Office 365 for Microsoft Office 365, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b52fcc6ec5d5f5f36c11379c736e098048e58b6b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553505"
---
# <a name="iglobe-crm-office-365-for-microsoft-office-365"></a>iGlobe CRM Office 365 pour Microsoft Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur le: Novembre 17, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379222" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par iGlobe à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | iGlobe CRM Office 365 pour Microsoft Office 365 |
| ID | WA104379222 |
| Office 365 clients soutenus | SharePoint 2013 ou plus tard |
| Nom de l’entreprise partenaire | iGlobe |
| URL du site web partenaire | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL de la politique de confidentialité | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL des conditions d’utilisation | [https://www.iglobecrm.com/content/iglobe-crm-office-365-end...](https://www.iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par iGlobe sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Avoir accès aux calendriers des utilisateurs lors de l’arrosage d’un rapport de réunion du canlendar à iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | Délégué |  Directory.AccessAsUser.All | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Vérifiez l’autorisation et pour obtenir les sites et les listes. Créez des dossiers, obtenez des fichiers et enregistrez des fichiers. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Lire, mettre à jour, créer des tâches Panner, Lire les fichiers récents et partagés des utilisateurs, Pour obtenir SharePoint liste, les bibliothèques et les fichiers. Pour enregistrer des fichiers et des données à SharePoint listes. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Lire, mettre à jour, créer des tâches Panner, Lire les fichiers récents et partagés des utilisateurs, Pour obtenir SharePoint liste, les bibliothèques et les fichiers. Pour enregistrer des fichiers sur SharePoint listes. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Lire, mettre à jour, créer des tâches Panner, Lire les fichiers récents et partagés des utilisateurs, Pour obtenir SharePoint liste, les bibliothèques et les fichiers. Pour enregistrer des fichiers sur SharePoint listes. Intégration à iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Svae l’eamil à iGlobe CRM et obtenir informatiopn d’iGlobe à un nouveau e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Créez, modifiez et supprimez des éléments et des listes dans iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Lire les articles dans iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. |  Modifier et supprimer des éléments et des listes dans iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Créer une tâche de planificateur à partir d’iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour obtenir des informations sur le CRM iGlobe pour l’utilisateur speficic | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les modules complémentaires intégrés à Microsoft 365 peuvent utiliser d’autres API Microsoft que Microsoft Graph pour recueillir ou traiter des informations organisationnelles identifiables (OII). Énumérez toutes les API Microsoft autres que Microsoft Graph utilisations de cette application.

>| **API** |  **L’ŒIL est-il recueilli?** |  **Quel OII est recueilli?** | **Justification de la collecte de l’ŒII?** | **OII est-il stocké ?** | **Justification pour stocker OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | Non |  |  |  |  |
>| Exchange - Mail.Read.All | Non |  |  |  |  |
>| Exchange - Contacts.Read | Non |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | Non |  |  |  |  |
>| Exchange - Tasks.ReadWrite | Non |  |  |  |  |
>| SharePoint - AllSites.Manage | Non |  |  |  |  |
>| SharePoint - AllSites.Read | Non |  |  |  |  |
>|  SharePoint -AllSites.Write | Non |  |  |  |  |
>| SharePoint - MyFiles.Write | Non |  |  |  |  |
>| SharePoint - Sites.Manage.All | Non |  |  |  |  |
>| SharePoint - Sites.Read.All | Non |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | Non |  |  |  |  |
>| SharePoint - Sites.Search.All | Non |  |  |  |  |
>|  SharePoint - TermStore.Read.All | Non |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>iGlobe recueille des données pour fonctionner efficacement et vous fournir les meilleures expériences avec nos produits et services. Pour l’octroi de licences : Données collectées pour administrer le compte de licence de votre organisation&#8217;, par exemple lorsque vous déployez un add-in gratuit, créez un abonnement d’essai ou achetez un abonnement. Les informations suivantes sont recueillies. 
- À des fins financières : Nom et adresse de l’entreprise
- Utilisateurs abonnés : nom d’utilisateur et e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Toutes les données sont sur le propre locataire du client. Aucune donnée d’application n’est stockée. Un module d’ajout moderne s’exécute dans un navigateur bac à sable, &#8220;hors processus&#8221;. Il interagit avec les données des utilisateurs en utilisant services Microsoft. L’add-in ne peut accéder qu’aux données avec lesquelles l’utilisateur travaille.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Afficher dans un nouvel onglet</a>

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
