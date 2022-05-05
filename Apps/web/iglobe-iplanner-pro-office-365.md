---
title: Informations d’application pour iPlanner Pro Office 365
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour iPlanner Pro Office 365, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c934c8d519163934f27b39a1f52f8c5b343cdb82
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65227986"
---
# <a name="application-information-for-iplanner-pro-office-365"></a>Informations d’application pour iPlanner Pro Office 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur : 22 juin 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.iplannerpro" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par iGlobe à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | iPlanner Pro Office 365 |
| ID | 17859280.iplannerpro |
| Nom de la société partenaire | iGlobe |
| URL du site web du partenaire | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL de la politique de confidentialité | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL des conditions d’utilisation | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par iGlobe sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>| **Permission**  | **Type d’autorisation (délégué/application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-ils stockées ? Justification du stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir la tâche du planificateur et ajouter de nouvelles tâches, mettez à jour le compartiment et la ligne de nage pour l’utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Contacts.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | pour créer un rendez-vous dans le calendrier des utilisateurs à la date d’échéance des tâches | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Directory.AccessAsUser.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Permet à l’application de disposer du même accès aux informations dans l’annuaire que l’utilisateur connecté. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.Read | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour accéder au fichier en tant que pièce jointe et charger des fichiers dans une tâche | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Obtenez l’objet du courrier à partir du courrier sélectionné. Permet à l’application d’obtenir des informations à partir de l’e-mail sélectionné, ce qui permet de copier le champ de description dans la description de la tâche et d’enregistrer les pièces jointes du courrier ou du courrier lui-même dans la tâche. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Group.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | pour obtenir la tâche du planificateur et ajouter de nouvelles tâches mettre à jour le compartiment et la ligne de nage pour l’utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.Read | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir la tâche du planificateur et ajouter de nouvelles tâches, mettez à jour le compartiment et la ligne de nage pour l’utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.ReadBasic.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Vérifier l’autorisation et obtenir la tâche du planificateur et ajouter de nouvelles tâches mettre à jour le compartiment et la ligne de nage pour l’utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| profil | Délégué | Aucune donnée n’est stockée dans les bases de données d’application. | Pour obtenir la tâche du planificateur et ajouter de nouvelles tâches, mettez à jour le compartiment et la ligne de nage pour l’utilisateur spécifique | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et compléments basés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelles (OII). Répertoriez toutes les API Microsoft autres que Microsoft Graph utilisées par cette application.

>| **API** |  **OII est-il collecté ?** |  **Quelle OII est collectée ?** | **Justification de la collecte d’OII ?** | **OII est-il stocké ?** | **Justification du stockage d’OII ?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | Non |  |  |  |  |
>| Exchange - Mail.Read.All | Non |  |  |  |  |
>| SharePoint - AllSites.Manage | Non |  |  |  |  |
>| SharePoint - AllSites.Read | Non |  |  |  |  |
>| SharePoint - AllSites.Write | Non |  |  |  |  |
>| SharePoint - MyFiles.Read | Non |  |  |  |  |
>| SharePoint - MyFiles.Write | Non |  |  |  |  |

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
