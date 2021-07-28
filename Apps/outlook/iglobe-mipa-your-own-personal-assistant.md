---
title: Informations sur l’application pour MIPA - Votre propre Assistant personnel par iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/05/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: 'Toutes les informations de sécurité et de conformité disponibles pour MIPA : votre Propre Assistant personnel, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.'
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7db3c4f2e43ab80a84cc1421bff8489b2e467732
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527020"
---
# <a name="mipa---your-own-personal-assistant"></a>MIPA - Votre propre Assistant personnel

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: November 5, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000062" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par iGlobe à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | MIPA - Votre propre Assistant personnel |
| ID | WA200000062 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou une ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | iGlobe |
| URL du site web partenaire | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL de la politique de confidentialité | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL des conditions d’utilisation | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par iGlobe sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour des ensembles de calendriers | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Contacts.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour des ensembles de calendriers | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Directory.AccessAsUser.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, Mettre à jour, Créer des tâches du panneur. Pour vérifier que l’utilisateur a le consentement et a accès pour utiliser l’API. | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Directory.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir la tâche du planificateur, Outlook To Do courriers électroniques marqués et les mettre à jour. Pour créer une tâche du planificateur. | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Files.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, mettre à jour, créer des tâches du panneur, lire les fichiers récents et partagés des utilisateurs, pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers dans SharePoint listes. | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Group.Read.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, mettre à jour, créer des tâches du panneur, lire les fichiers récents et partagés des utilisateurs, pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers dans SharePoint listes. | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Group.ReadWrite.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire, mettre à jour, créer des tâches du panneur, lire les fichiers récents et partagés des utilisateurs, pour obtenir SharePoint liste, bibliothèques et fichiers. Pour enregistrer des fichiers dans SharePoint listes. Intégration à iGlobe CRM Office 365 | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Mail.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour le courrier marqué | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| MailboxSettings.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour des ensembles de calendriers, lire et mettre à jour le courrier marqué, lire et mettre à jour Outlook To Do entiers | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Tasks.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour des ensembles de calendriers, lire et mettre à jour Outlook à faire entreies | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| User.Read | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour des ensembles de calendriers, lire et mettre à jour Outlook à faire entreies | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| User.Read.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour des ensembles de calendriers, lire et mettre Outlook à faire entreies, lire, mettre à jour, créer des tâches de panneur | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| User.ReadBasic.All | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour des ensembles de calendriers, lire et mettre Outlook à faire entreies, lire, mettre à jour, créer des tâches de panneur | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| User.ReadWrite | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour des ensembles de calendriers, lire et mettre à jour Outlook à faire entreies | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| email | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Permet à l’application de lire l’adresse e-mail principale de vos utilisateurs (pour l' cesso). | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| offline_access | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Permet à l’application de voir et de mettre à jour les données à qui vous lui avez donné accès, même lorsque les utilisateurs n’utilisent pas l’application. Cela ne donne pas à l’application d’autorisations supplémentaires (pour l' sso). | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| openid | délégué | Aucune donnée n’est stockée dans la base de données d’application | Permet aux utilisateurs de se connecter à l’application avec leurs comptes professionnels ou scolaires et permet à l’application d’voir les informations de profil utilisateur de base ( pour l' cesso). | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| profil | délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Lire et mettre à jour des ensembles de calendriers, lire et mettre à jour Outlook faire des entrées, lire, mettre à jour, créer des tâches de panneur | [e854ea05-68ab-4204-fb-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Quels OII sont collectés ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - Calendars.ReadWrite.All | Non |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | Non |  |  |  |  |
>| Exchange - Mail.Read | Non |  |  |  |  |
>| Exchange - Mail.ReadWrite.All | Non |  |  |  |  |
>| Exchange - MailboxSettings.Read | Non |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | Non |  |  |  |  |
>| Exchange - Tasks.ReadWrite | Non |  |  |  |  |
>| SharePoint - MyFiles.Read | Non |  |  |  |  |
>| SharePoint - MyFiles.Write | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>iGlobe collecte des données pour fonctionner efficacement et vous offrir les meilleures expériences avec nos produits et services. Pour la gestion des licences : données collectées pour administrer le compte de licence de votre organisation&#8217;, par exemple lorsque vous déployez un module de licence gratuit, créez un abonnement d’essai ou achetez un abonnement. Les informations suivantes sont collectées. - À des fins financières : nom et adresse de la société : utilisateurs abonnés : nom d’utilisateur et e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Toutes les données se trouve sur le client. Aucune donnée d’application n’est stockée. Un add-in moderne s’exécute dans un navigateur en bac à sable,&#8220;hors processus&#8221;. Il interagit avec les données des utilisateurs à l’aide services Microsoft. Le module peut uniquement accéder aux données avec lesquelles l’utilisateur travaille.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par iGlobe sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Paramètres de sécurité par défaut et autres stratégies courantes telles que Bloquer l’authentification héritée* Exiger l’authentification multifacteur pour les administrateurs* Exiger l’authentification multifacteur pour la gestion Azure* Exiger l’authentification multifacteur pour tous les utilisateurs* |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Non |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
