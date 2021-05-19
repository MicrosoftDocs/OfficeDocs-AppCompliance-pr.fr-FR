---
title: Informations d’application pour Prezi Video par Prezi
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Prezi Video, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8b689869b4c8799d396a61ccbecd0d1b4a4e5c51
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552835"
---
# <a name="prezi-video"></a>Vidéo Prezi

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Juin 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Prezi à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Vidéo Prezi |
| ID | WA200001577 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Prezi |
| URL du site web partenaire | [https://prezi.com](https://prezi.com) |
| URL de la politique de confidentialité | [https://prezi.com/privacy-policy/201910_NL/](https://prezi.com/privacy-policy/201910_NL/) |
| URL des conditions d’utilisation | [https://prezi.com/terms-of-use/201910_NL/](https://prezi.com/terms-of-use/201910_NL/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Prezi sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>Cette application n’utilise pas microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Pour plus de détails s’il vous plaît visitez https://prezi.com/privacy-policy/ |  | Les API/SDK suivantes sont utilisées pour l’intégration avec le 1. Botbuilder-SDK (python) : À l’aide de ce SDK, nous stockons l’iD d’objet Azure Active Directory (désigné par l’API comme aad_object_id). Nous avons besoin de ces informations pour cartographier Microsoft Teams utilisateur à tout contenu lié à Prezi Video créé prezi.com.  2. Botbuilder-js (javascript): Aucune donnée Microsoft Teams spécifiques n’est recueillie à l’aide de ce SDK. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Le bot n’accède pas aux informations mentionnées sur la liste. | Le bot n’accède pas aux informations mentionnées sur la liste. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Aucun EUII ou OII n’apparaît dans les journaux de l’application.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Nous stockons les informations suivantes dans une base de données RDS :

1. Azure Active Directory’iD d’objet (référé par l’API sous le nom aad_object_id) est stocké pour aller chercher un Microsoft Teams utilisateur&#8217;vidéos de l’utilisateur. Le aad_object_id récupéré en toute sécurité à l’aide du sdk botbuilder officiel de Microsoft&#8217;sur nos serveurs.

2. Liens vidéo créés sur prezi.com. Le contenu créé prezi.com est stocké selon la section 14 dans l’URL suivante : https://prezi.com/privacy-policy/ 

Les droits d’accès aux systèmes externes à haut risque (comme AWS) sont gérés par l’intermédiaire d’une plate-forme de gestion unifiée de l’identité et de l’accès (OneLogin).

La stratégie de mot de passe et l’authentification multifaction sont appliquées pour le personnel de la plate-forme unifiée de gestion de l’identité et de l’accès. Au cas par cas, l’authentification multifaction n’est pas requise à partir des adresses IP du bureau.

Les services et bases de données hébergés par AWS, par défaut, ne sont accessibles de nulle part; les règles entrantes explicites doivent être ajoutées manuellement.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

