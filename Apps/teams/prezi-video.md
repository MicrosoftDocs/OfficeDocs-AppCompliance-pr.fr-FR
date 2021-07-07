---
title: Informations sur l’application pour Prezi Video by Prezi
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Prezi Video, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8bd0c290442e01f6f7a07f39bc38f2f7ece2123b
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283138"
---
# <a name="prezi-video"></a>Vidéo Prezi

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Prezi à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Vidéo Prezi |
| ID | WA200001577 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Prezi |
| URL du site web partenaire | [https://prezi.com](https://prezi.com) |
| URL de la politique de confidentialité | [https://prezi.com/privacy-policy/](https://prezi.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://prezi.com/terms-of-use/](https://prezi.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Prezi sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Pour plus d’informations, visitez https://prezi.com/privacy-policy/ |  | Les API/SDK suivantes sont utilisées pour l’intégration avec la 1. Botbuilder-SDK (python) : à l’aide de ce SDK, nous stockons l’ID d’objet Azure Active Directory (appelé aad_object_id). Nous avons besoin de ces informations pour ma Microsoft Teams utilisateur à tout contenu lié à Prezi Video créé sur prezi.com.  2. Botbuilder-js (javascript) : aucune Microsoft Teams données spécifiques n’est collectée à l’aide de ce SDK. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Le bot n’accède pas aux informations de liste mentionnées. | Le bot n’accède pas aux informations de liste mentionnées. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun EUII ou OII n’apparaît dans les journaux de l’application.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous stockons les informations suivantes dans une base de données RDS :

1. Azure Active Directory’ID d’objet (appelé aad_object_id api) est stocké pour récupérer les vidéos d Microsoft Teams'&#8217;'utilisateur. Le aad_object_id est récupéré en toute sécurité à l’aide du sdk botbuilder officiel de Microsoft&#8217;sur nos serveurs.

2. Liens vidéo créés sur prezi.com. Le contenu créé sur prezi.com est stocké comme dans la section 14 dans l’URL suivante : https://prezi.com/privacy-policy/ 

Les droits d’accès aux systèmes externes à haut risque (comme AWS) sont gérés via une plateforme de gestion des identités et des accès unifiée tierce (OneLogin).

La stratégie de mot de passe et l’authentification multifacteur sont appliquées pour le personnel dans la plateforme de gestion des identités et des accès unifiées. Au cas par cas, l’authentification multifacteur n’est pas requise auprès des adresses IP du bureau.

Les services et les bases de données hébergés par AWS, par défaut, ne sont pas accessibles depuis n’importe où ; les règles de trafic entrant explicite doivent être ajoutées manuellement.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

