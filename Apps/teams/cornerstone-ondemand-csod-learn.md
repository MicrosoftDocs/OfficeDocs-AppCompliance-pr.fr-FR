---
title: Informations sur l’application pour CSOD Learn parOnDemand
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour CSOD Learn, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 76046422709a8472b17d1b4b6c51f672f043eed8
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414710"
---
# <a name="csod-learn"></a>CSOD Learn

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/81726ee9-4d27-47ad-8b22-08147c6f8613" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003020" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par l’élément OnDemand à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | CSOD Learn |
| ID | WA200003020 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Cornerstone OnDemand |
| URL du site web partenaire | [https://www.cornerstoneondemand.com](https://www.cornerstoneondemand.com) |
| URL de la politique de confidentialité | [https://www.cornerstoneondemand.com/client-privacy-policy/](https://www.cornerstoneondemand.com/client-privacy-policy/) |
| URL des conditions d’utilisation | [https://www.microsoft.com/en-us/microsoft-teams/group-chat-...](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par La base de données OnDemand sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Les données organisationnelles sont partagées entre les services CSOD et Microsoft. Pour plus d’informations, reportez-vous aux conditions d’accord avec CSOD | Les données organisationnelles sont partagées entre les services CSOD et Microsoft. Pour plus d’informations, reportez-vous aux conditions d’accord avec CSOD | Le service CSOD n’utilise pas Graph API. Nous utilisons microsoft frameworks botbuilder^4.9.2 pour les performances du service. Les données OII sont utilisées par le service pour identifier le consommateur de service CSOD. Pour plus d’informations, reportez-vous aux conditions d’accord avec CSOD |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Veuillez consulter les conditions d’accord avec CSOD pour plus d’informations à cet égard. | Mappage aadObjectId de l’utilisateur final sur L’ID interne de l’utilisateur CSOD | Veuillez consulter les conditions d’accord avec CSOD pour plus d’informations à cet égard. |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Le service CSOD stocke les journaux des applications qui contiennent l’interaction de l’utilisateur avec l’application pendant une période limitée pour résoudre les bogues et les problèmes signalés par l’utilisateur. Les instructions de journal individuel sont composées de l’ID d’utilisateur lm interne de l’utilisateur final, du nom de l’organisation configuré dans le service CSOD et de l’action appropriée effectuée. v

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>L’accès au service CSOD est contrôlé par les administrateurs de l’organisation de l’utilisateur final. Pour plus d’informations, reportez-vous aux conditions d’accord avec CSOD

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par LasOnDemand sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

