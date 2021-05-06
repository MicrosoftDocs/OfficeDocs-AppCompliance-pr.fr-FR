---
title: Informations sur l’application pour Tryane Analytics par Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Tryane Analytics, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: db14e8aa547589ef6e2f9a886e68da41bbbfbdb3
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251013"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Tryane à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Tryane Analytics |
| ID | WA200001827 |
| Fonctionnalités | Tab |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Tryane |
| URL du site web partenaire | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| URL de la politique de confidentialité | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| URL des conditions d’utilisation | [https://tryane.com/tryane-analytics/terms_of_use.html](https://tryane.com/tryane-analytics/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Tryane sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ActivityFeed.Read | application |  | Lire toutes les activités des utilisateurs dans teams | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Channel.ReadBasic.All | application |  | Lister tous les canaux avec des noms, des descriptions | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| ChannelMessage.Read.All | application |  | Liste de tous les messages de canaux&#8217; métadonnées | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Directory.Read.All | application |  | Identifier les utilisateurs avec une licence d’équipe dans le client | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Member.Read.Hidden | application |  | Obtenir la liste de toutes les équipes,&#8217;membres de l’équipe et les appartenances masquées | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Reports.Read.All | application |  | Lire toutes les activités des utilisateurs dans teams | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Team.ReadBasic.All | application |  | Liste de toutes les propriétés de canaux et d’équipes | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| User.Read | délégué | ID d’utilisateur, nom, adresse e-mail, date de création. Nous stockons ces données afin de fournir une analyse de l’utilisation sur Teams | Identifier l’utilisateur actuel pendant l’abonnement | 9b03f15d-1219-4b2f-9699-640be54e1319 |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>La règle organisationnelle décrite dans notre stratégie de sécurité informatique et nos normes de codage nous empêchent d’avoir eu l’EUII et L’OII apparaissent dans les journaux

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Où/Comment : La base de données Azure/Azure pour les serveurs PostgreSQL Qui y accéder : notre application et le contrôle d’autorisation des administrateurs de base de données : 
 - Contrôle d’autorisation individuel : RBAC
 - Contrôle d’autorisation du système : points de terminaison privés dans les réseaux virtuels Azure

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

