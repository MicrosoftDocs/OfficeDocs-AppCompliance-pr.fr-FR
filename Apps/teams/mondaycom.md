---
title: Informations d’application monday.com par monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour monday.com, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 64fc8e948618b760a3f82ee9c1ac67a32de9afb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552925"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Septembre 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par monday.com à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | monday.com |
| ID | WA200001798 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | monday.com |
| URL du site web partenaire | [https://monday.com](https://monday.com) |
| URL de la politique de confidentialité | [https://monday.com/privacy](https://monday.com/privacy) |
| URL des conditions d’utilisation | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par monday.com sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>Cette application n’utilise pas microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com utilise les sous-processeurs suivants pour les performances de son service: &#160;https://monday.com/terms/subprocessors |  | monday.com n’utilise pas d’API. Nous utilisons les frameworks Microsoft suivants pour les performances de notre service (comme détaillé dans notre réponse ci-dessus): &#8216;botbuilder&#8217; &#8216;botframework-connecteur&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>monday.com stocke les journaux d’applications qui contiennent du contenu généré par les utilisateurs pendant une période limitée afin de permettre à notre personnel de R &amp; D de dépanner les bogues et les problèmes signalés par l’utilisateur. Les journaux de sécurité qui contiennent des adresses IP sont conservés pendant une période plus longue, selon notre politique de conservation des données.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>monday.com service est hébergé sur l’infrastructure AWS dans le nord de la Virginie à travers plusieurs zones de disponibilité, avec un site DR établi dans une autre région. Certaines données de sauvegarde sont stockées sur GCP (US, multi-region). L’accès monday.com service est contrôlé par les administrateurs de l’organisation utilisateur et est réalisé en utilisant les fonctionnalités suivantes :
- Types d'utilisateur
- Autorisations au niveau du compte
- Workspaces
- Types de planches
- Autorisations au niveau du conseil
- Les autorisations au niveau de la colonne monday.com prend en charge les méthodes d’authentification suivantes :
- Identifiants
- Google SSO (pour Pro plan)
- Okta, OneLogin et SAML 2.0 personnalisé (pour le plan Enterprise) 2FA via SMS ou via une application authentification peuvent être activés en option par les administrateurs de compte via le panneau d’administration de la plate-forme.
Toutes les données au repos sont cryptées à l’aide d’AES-256. Toutes les données en transit sur les réseaux ouverts sont cryptées à l’aide de TLS 1.3 (TLS 1.2 au minimum).

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

