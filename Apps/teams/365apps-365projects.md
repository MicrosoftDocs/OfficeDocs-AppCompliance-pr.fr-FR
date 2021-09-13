---
title: Informations d’application pour 365Projects par 365Apps
ms.author: elmalova
author: elenamalova
ms.date: 03/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour 365Projects, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: aad8e35ad1e02212c23ef2a892412ba3c0ce1312
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59280018"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par 365Apps à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | 365Projects |
| ID | WA200002160 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | 365Apps |
| URL du site web partenaire | [https://365apps.com.au](https://365apps.com.au) |
| URL de la Teams d’informations sur l’application | [https://365projects.app](https://365projects.app) |
| URL de la politique de confidentialité | [https://365projects.app/privacy](https://365projects.app/privacy) |
| URL des conditions d’utilisation | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par 365Apps sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | délégué | canaux au sein de l’équipe pour lier le projet au canal | canaux au sein de l’équipe pour lier le projet au canal | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.Read.All | délégué | obtenir des tâches de planificateur d’équipe/planificateur, il est préférable qu’une autre étendue des privilèges minimum autorise l’application à obtenir des plans et des tâches de plans utilisateur, mais qu’il n’existe malheureusement aucune étendue qui autorise cette possibilité | pas de magasin dans la DB | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.ReadWrite.All | application | Créer Teams  | non stocké dans la DB | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| People.Read | délégué | nom d’utilisateur, pour les ajouter en tant que membres de l’équipe ou leur affecter des tâches | Guid d’utilisateur stocké dans l’affectation de tâche | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Team.ReadBasic.All | délégué | Noms d’équipe joints, pour lier le projet Teams canal | Le Guid d’équipe est stocké dans les métadonnées du projet pour établir le lien | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read | délégué | obtention des informations utilisateur pour les afficher dans l’en-tête  | l’e-mail de l’utilisateur est stocké en tant que propriétaire lors de la première mise en service du client | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read.All | délégué | lire les utilisateurs pour mettre à jour l’affectation de tâche | seul le Guid de l’utilisateur est stocké, aucune information d’identification personnelle n’est stockée dans la base de données | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>L’application ne stocke pas les données utilisateur en dehors du Guid de l’administrateur de l’application (le premier utilisateur utilise l’application au sein du client) 

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par 365Apps sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | ,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/> |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
