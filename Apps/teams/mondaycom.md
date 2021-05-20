---
title: Informations sur l’application monday.com par monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour monday.com, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
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
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par monday.com à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | monday.com |
| ID | WA200001798 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | monday.com |
| URL du site web partenaire | [https://monday.com](https://monday.com) |
| URL de la politique de confidentialité | [https://monday.com/privacy](https://monday.com/privacy) |
| URL des conditions d’utilisation | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par monday.com sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com utilise les sous-processeurs suivants pour les performances de son service :&#160;https://monday.com/terms/subprocessors |  | monday.com n’utilise pas d’API. Nous utilisons les infrastructure Microsoft suivantes pour les performances de notre service (comme détaillé dans notre réponse ci-dessus) : &#8216;botbuilder&#8217; &#8216;botframework-connector&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>monday.com stocke les journaux des applications qui contiennent du contenu généré par les utilisateurs pendant une période limitée afin de permettre à notre personnel de R D de résoudre les bogues et les problèmes signalés par &amp; l’utilisateur. Les journaux de sécurité qui contiennent des adresses IP sont conservés pendant une période plus longue, selon notre stratégie de rétention des données.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>monday.com service est hébergé sur l’infrastructure AWS du Nord dans plusieurs zones de disponibilité, avec un site de dr établi dans une autre région. Certaines données de sauvegarde sont stockées sur GCP (États-Unis, multi-région). L’accès au service monday.com est contrôlé par les administrateurs de l’organisation utilisateur et est obtenu à l’aide des fonctionnalités suivantes :
- Types d'utilisateur
- Autorisations au niveau du compte
- Workspaces
- Types de tableaux
- Autorisations au niveau du tableau
- Les autorisations au niveau des colonnes monday.com les méthodes d’authentification suivantes :
- Identifiants
- SSO Google (pour Pro plan)
- Okta, OneLogin et SAML 2.0 personnalisé (pour le plan Enterprise) 2FA via SMS ou via une application d’authentification peuvent être activés par les administrateurs de compte via le panneau d’administration de la plateforme.
Toutes les données au repos sont chiffrées à l’aide d’AES-256. Toutes les données en transit sur des réseaux ouverts sont chiffrées à l’aide de TLS 1.3 (TLS 1.2 au minimum).

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

