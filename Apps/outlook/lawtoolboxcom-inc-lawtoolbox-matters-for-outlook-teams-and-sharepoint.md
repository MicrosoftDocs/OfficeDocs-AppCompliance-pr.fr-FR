---
title: Informations sur les applications pour les affaires LawToolBox Outlook, Teams &amp; SharePoint par LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour LawToolBox Sont importantes pour Outlook, Teams SharePoint, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre &amp; CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 039b83277d1e3a6823b16079ec6a0fa8fbec68d2
ms.sourcegitcommit: 1d47df35430334cfc0c60f7ea0b62392b99b7cbf
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/13/2021
ms.locfileid: "60285987"
---
# <a name="lawtoolbox-matters-for-outlook-teams-amp-sharepoint"></a>Affaires LawToolBox pour Outlook, Teams &amp; SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 24, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003103" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par LawToolBox.com Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Affaires LawToolBox pour Outlook, Teams &amp; SharePoint |
| ID | WA200003103 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou une ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | LawToolBox.com Inc. |
| URL du site web partenaire | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL de la politique de confidentialité | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.lawtoolbox.com/customersupport/2019/LawToolBox_...](https://www.lawtoolbox.com/customersupport/2019/LawToolBox_End_User_License_Agreement_and_SLA_LAWTOOLBOX_2019_APR.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par LawToolBox.com Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | délégué | Cette autorisation est restreinte pour accéder aux contacts de l'&#8217;qu’ils ont déjà accès aux &#8211; nous utilisons cette autorisation pour permettre aux utilisateurs de récupérer leurs propres informations de calendrier | [Facultatif] Lire le calendrier de l’utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite | délégué | Cette autorisation est restreinte pour accéder aux contacts de l’utilisateur&#8217;qu’il a déjà accès aux &#8211; nous utilisons cette autorisation pour permettre aux utilisateurs de récupérer leurs propres informations de calendrier et d’écrire dans des calendriers | Pour créer une invitation de calendrier dans le calendrier de l’utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite.Shared | délégué | Cette autorisation est restreinte pour accéder aux contacts de l'&#8217;qu’ils ont déjà accès aux &#8211; nous utilisons cette autorisation pour permettre aux utilisateurs de récupérer leurs propres informations de calendrier | Pour créer une invitation de calendrier dans un calendrier partagé. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite | délégué | Cette autorisation est restreinte pour accéder aux contacts&#8217;utilisateur à qui ils ont déjà accès.  Nous utilisons cette autorisation pour permettre aux utilisateurs de rechercher leurs contacts O365 et de les ajouter à LawToolBox &#8211; nous n’ajoutons pas automatiquement de contact (cette option peut être révoquée si vous ne souhaitez pas que cette fonctionnalité et les contacts soient ajoutés manuellement) | [Facultatif]- pour lire les contacts des utilisateurs et connecter les utilisateurs d’une liste de contacts à une autre. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite.Shared | délégué | nous utilisons cette autorisation pour permettre aux utilisateurs de rechercher des contacts O365 partagés et de les ajouter à LawToolBox &#8211; nous n’ajoutons aucun contact automatiquement | [Facultatif]- pour lire les contacts partagés des utilisateurs afin de servir la liste des contacts pertinents pour le cas. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.AccessAsUser.All | délégué | nous utilisons le portail d’administration pour récupérer la liste des utilisateurs à partir du client O365 à ajouter à votre compte | [Facultatif] Lire les informations de groupes et d’utilisateurs en tant qu’utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.ReadWrite.All | délégué | nous utilisons le portail d’administration pour récupérer la liste des utilisateurs à partir du client O365 à ajouter à votre compte | [Facultatif] Lire les informations de groupes et d’utilisateurs en tant qu’utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read | délégué | Cela permet au addin de lire et de ré lister les fichiers utilisateur à qui l’utilisateur a déjà accès | [Facultatif] Lire les informations de l’OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read.All | délégué | nous utilisons cette autorisation pour lire et ré lister les fichiers utilisateur à qui l’utilisateur a déjà accès | [Facultatif]-Lire les informations de l’OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite | délégué | nous lisons des fichiers Teams, groupes et OneDrive pour les réunions (si vous le révoquer, notre addin ne répertorie pas les fichiers importants dans nos applications) | [Facultatif]-Lire et modifier des fichiers dans l’OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite.All | délégué | nous lisons des fichiers Teams, groupes et OneDrive pour les réunions (si vous le révoquer, LTB ne répertorie pas les fichiers importants dans nos applications).  L’utilisateur peut uniquement utiliser le addin pour lire et ré lister les fichiers utilisateur à qui l’utilisateur a déjà accès | [Facultatif] Lire/écrire le fichier d’OneDrive associé à la matière. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Group.ReadWrite.All | délégué | GroupID, GroupName, GroupEmail | Nous créons un groupe pour chaque sujet créé dans notre système. Cette aide permet aux utilisateurs de stocker les informations relatives à la matière dans le groupe, qui enregistre à son tour leurs données dans leur propre client. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Read | délégué | nous utilisons cette autorisation pour lire les e-mails PACER dans notre add-in Outlook afin de les ouvrir automatiquement et de lire les contacts à partir de votre courrier électronique à ajouter à notre système de contact.  | [Facultatif] [InProgress] Lire le courrier électronique de l’utilisateur pour les questions. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite | délégué | nous utilisons cette autorisation pour lire les e-mails PACER dans notre add-in Outlook afin de les ouvrir automatiquement et de lire les contacts à partir de votre courrier électronique à ajouter à notre système de contact.  | [Facultatif] [InProgress] Lire/écrire des e-mails pour les utilisateurs. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite.Shared | délégué | nous utilisons cette autorisation pour lire les e-mails PACER dans notre add-in Outlook afin de les ouvrir automatiquement et de lire les contacts à partir de votre courrier électronique à ajouter à notre système de contact.  | [Facultatif] [InProgress] Lire/écrire des e-mails pour les utilisateurs. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Send | délégué | Nous utilisons cet envoi de courriers électroniques en tant qu’utilisateur pour permettre à un utilisateur de s’envoyer des rapports uniquement sur les données à qui il a déjà accès sur notre système. | [Facultatif] [InProgress] Envoyer des échéances sur le courrier électronique en tant qu’utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Tasks.ReadWrite.Shared | délégué | Cette autorisation est restreinte pour accéder aux tâches de l’utilisateur&#8217;qu’il a déjà accès aux &#8211; nous l’utilisons pour permettre aux utilisateurs de récupérer et de mettre à jour leurs propres informations TASK.  | [Facultatif]-[InProgress] Read Write Deadlines as Task for users. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.Read | délégué | permet de suggérer des contacts récents à ajouter à des réunions ou des contacts | Lire les informations de l’utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite | délégué | permet de suggérer des contacts récents à ajouter à des réunions ou des contacts | Lire/écrire les informations de l’utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite.All | délégué | cela est nécessaire pour lire l’API Teams, créer des Teams, créer un événement de calendrier, créer des canaux, Teams partage de fichiers | Lire/écrire les informations de l’utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| email | délégué | Email, Office365 UserID, ObjectID, TenantID. | Lire l’adresse e-mail de l’utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| profil | délégué | Cela est nécessaire pour l’authentification sso - nous utilisons également cette autorisation pour récupérer des images et des noms enregistrés sur le client M365 à afficher afin que l’utilisateur sache qu’il se trouve dans la boîte à outils correcte | Lire les informations de profil utilisateur. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>User Email,UserID, AccessToken, Groups information in our debug log

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous conservons les enregistrements de cas, sauf si nous recevons une demande de suppression des données.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par LawToolBox.com Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Pour un meilleur contrôle, l’administrateur peut implémenter des autorisations d’application |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | ,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/> |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
