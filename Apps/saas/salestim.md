---
title: Informations d’application pour SalesTim par SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour SalesTim, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 98b5d538e9fe73f6c1bf63fe5c53c780adb39548
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413125"
---
# <a name="salestim"></a>SalesTim

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 24, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SalesTim à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | SalesTim |
| ID | salestim.salestim |
| Nom de la société partenaire | SalesTim |
| URL du site web partenaire | [https://salestim.com](https://salestim.com) |
| URL de la politique de confidentialité | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL des conditions d’utilisation | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par SalesTim sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | délégué | NON | Autorisez l’application à installer et à mettre à jour ses propres packages dans le catalogue d’applications d’entreprise. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | délégué | Nous&#8217;stocker uniquement certains ID d’utilisateurs, pas les données de profil. | Permet à un utilisateur de sélectionner d’autres utilisateurs à différents endroits dans l’application, tels que la sélection d’approbations dans un flux de travail. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | délégué | Nous&#8217;stocker uniquement les groupes/ID d’équipes, nous&#8217;stocker aucun contenu de groupes/équipes. | Permet à l’application de créer des groupes, de lire toutes les propriétés et appartenances de groupe pour le compte de l’utilisateur. En outre, elle permet aux propriétaires de groupes de gérer leurs groupes et aux membres de groupes de mettre à jour le contenu des groupes. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Mail.Send | délégué | Nous&#8217;stocker les métadonnées de cette action, telles que la date de notification, le destinataire (ID uniquement), l’ID de demande. | Permet à l’application d’envoyer des courriers électroniques de notification par exemple au cours d’un flux de travail d’approbation. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Sites.ReadWrite.All | délégué | Nous utilisons certains services Azure pour stocker des données, notamment Redis sur Azure et Cosmos DB | Permet à l’application de gérer les lecteurs (fichiers et dossiers) associés à une équipe, au cours d’un processus de mise en service d’équipe. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | délégué | Nous&#8217;stocker uniquement certains ID d’utilisateurs, pas les données de profil. | Permet à l’application de lire l’ensemble complet des propriétés de profil, des rapports et des responsables de n’importe quel utilisateur. Il est utilisé en particulier pendant le processus de ciblage d’audience, pour filtrer certains contenus en fonction du profil utilisateur actuel. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offline_access | délégué | Non | Permet à l’application d’effectuer certaines opérations et actions en arrière-plan en tant qu’utilisateur. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Nous utilisons Intercom comme principale application de support. Intercom peut contenir des informations de profil utilisateur de base, comme décrit ici : https://developers.salestim.com/platform/datamanagement.html#support-data | Nom de la société | Nous utilisons des API GitHub pour générer des problèmes automatiquement à partir de notre environnement de production. Nous stockons également des journaux techniques dans GitHub (comme décrit ici https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) : Ces problèmes et journaux peuvent contenir des informations de profil utilisateur de base. Ces problèmes et journaux sont automatiquement supprimés tous les 15 jours. |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Toutes les données collectées sont décrites ici : Comme décrit, les journaux sont temporairement stockés pendant 15 jours, puis https://developers.salestim.com/platform/datamanagement.html#application-data supprimés automatiquement.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>La plupart des données sont stockées dans Azure Cosmos DB.
L’accès à l’environnement de production est limité à deux personnes, et ces comptes d’administrateur sont appliqués par l’mf.
Ces comptes sont dédiés et différents de nos comptes d’entreprise.
Les données sont chiffrées au repos dans tous les services Azure que nous utilisons.
Les déploiements vers des environnements de production sont automatisés via une branche protégée dédiée dans notre environnement GitHub, où deux personnes seulement peuvent approuver les modifications.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par SalesTim sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | MFA, Conditions d’emplacement |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | ,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/> |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

