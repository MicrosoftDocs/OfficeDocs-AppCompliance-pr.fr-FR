---
title: Informations sur l’application pour SalesTim
ms.author: elmalova
manager: tonybal
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Passez en revue toutes les informations de sécurité et de conformité disponibles pour SalesTim, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9bf1f4057ad73ba33a8ae3ba0ff02c74851cdecf
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/26/2022
ms.locfileid: "65688119"
---
# <a name="application-information-for-salestim-by-salestim"></a>Informations d’application pour SalesTim by SalesTim

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur : 24 juin 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SalesTim à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | SalesTim |
| ID | salestim.salestim |
| Nom de la société partenaire | SalesTim |
| URL du site web du partenaire | [https://nbold.co/](https://nbold.co/) |
| URL de la politique de confidentialité | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL des conditions d’utilisation | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par SalesTim sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>| **Permission**  | **Type d’autorisation (délégué/application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-ils stockées ? Justification du stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Délégué | NON | Autoriser l’application à installer et mettre à jour ses propres packages dans le catalogue d’applications d’entreprise. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Délégué | Nous&#8217;stocker certains ID d’utilisateur uniquement, et non les données de profil. | Permet à un utilisateur de sélectionner d’autres utilisateurs à différents endroits de l’application, tels que la sélection d’approbateurs dans un flux de travail. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Délégué | Nous&#8217;stocker des ID de groupes/équipes uniquement, nous&#8217;ne stockons aucun contenu de groupes/équipes. | Permet à l’application de créer des groupes, de lire toutes les propriétés et appartenances de groupe pour le compte de l’utilisateur connecté. En outre, elle permet aux propriétaires de groupes de gérer leurs groupes et aux membres de groupes de mettre à jour le contenu des groupes. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Délégué | Nous&#8217;stocker à nouveau les métadonnées de cette action, telles que la date de notification, le destinataire (ID uniquement), l’ID de demande. | Permet à l’application d’envoyer des e-mails de notification par exemple pendant un flux de travail d’approbation. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Délégué | Nous utilisons certains services Azure pour stocker des données, en particulier Redis sur Azure et Cosmos base de données | Permet à l’application de gérer les lecteurs (fichiers et dossiers) associés à une équipe pendant un processus d’approvisionnement d’équipe. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Délégué | Nous&#8217;stocker certains ID d’utilisateur uniquement, et non les données de profil. | Permet à l’application de lire l’ensemble complet des propriétés de profil, des rapports et des gestionnaires de n’importe quel utilisateur. Il est utilisé en particulier pendant le processus de ciblage d’audience, pour filtrer certains contenus en fonction du profil utilisateur actuel. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | Délégué | Non | Permet à l’application d’effectuer certaines opérations et actions en arrière-plan en tant qu’utilisateur. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quel OII est transféré ?** | **Justification du transfert d’OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Nous utilisons Intercom comme principale application de support. Intercom peut contenir des informations de profil utilisateur de base, comme décrit ici : https://developers.salestim.com/platform/datamanagement.html#support-data | Nom de la société | Nous utilisons GitHub API pour générer automatiquement des problèmes à partir de notre environnement de production. Nous stockons également des journaux techniques dans GitHub (comme décrit ici : https://developers.salestim.com/platform/datamanagement.html#error-reporting-data). Ces problèmes et journaux d’activité peuvent contenir des informations de profil utilisateur de base. Ces problèmes et journaux d’activité sont automatiquement supprimés tous les 15 jours. |



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Toutes les données collectées sont décrites ici : https://developers.salestim.com/platform/datamanagement.html#application-data comme décrit, les journaux sont temporairement stockés pendant 15 jours, puis supprimés automatiquement.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>La plupart des données sont stockées dans Azure Cosmos base de données.
L’accès à l’environnement de production est limité à deux personnes, et ces comptes d’administrateur sont appliqués par l’authentification multifacteur.
Ces comptes sont dédiés et différents de nos comptes d’entreprise.
Les données sont chiffrées au repos dans tous les services Azure que nous utilisons.
Les déploiements dans des environnements de production sont automatisés via une branche protégée dédiée dans notre environnement GitHub, où seules deux personnes peuvent approuver les modifications.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans l’examen ou l’analyse des données d’information d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par SalesTim sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Vous intégrez-vous à Microsoft Identify Platform (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle d’intégration Plateforme d'identités Microsoft ?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Répertorier les types de stratégies prises en charge | MFA, Conditions d’emplacement |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations inscrites statiquement de votre application reflètent-elles précisément les autorisations demandées par votre application de manière dynamique et incrémentielle ? | Oui |
| Votre application prend-elle en charge la mutualisation ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de l’URI (Identificateur de ressource unifié) de redirection inscrit pour votre application ? | Oui |
| Pour votre application, que pouvez-vous éviter d’utiliser ? | ,<br/>- Flow implicite OAuth2, sauf si nécessaire pour une spa<br/> |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement la réussite des appels si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de préversion ? | Non |
| Votre application utilise-t-elle des API déconseillées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
