---
title: Informations d'application pour live chat par intention sociale
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour Live Chat, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 94f0df2b58314e1e87d8301780d7ec08aba0dcc1
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093239"
---
# <a name="live-chat"></a>Conversation en direct

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/a55635a5-8def-48e7-bcff-230cd43d3405" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000440" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par les réseaux sociaux à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Conversation en direct |
| ID | WA200000440 |
| Fonctionnalités | Bot, Onglet |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Intentions sociales |
| URL du site web partenaire | [https://www.socialintents.com](https://www.socialintents.com) |
| URL de la politique de confidentialité | [https://www.socialintents.com/privacy.html](https://www.socialintents.com/privacy.html) |
| URL des conditions d'utilisation | [https://www.socialintents.com/tos.html](https://www.socialintents.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par social intents about how this app collects and stores organizational data and the control that your organization will have over the data the app collects.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n'utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d'identification de l'utilisateur final (EUII) : la liste (prénom, nom, nom d'affichage, adresse e-mail) d'un membre d'une équipe ou d'une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l'accès à EUII ?**  | **L'EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l'EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Lorsqu'un membre de l'équipe clique sur Rejoindre la conversation, nous utilisons le courrier électronique des membres pour identifier le profil d'agent qui a accepté la conversation. | Le courrier électronique et le nom du membre de l'équipe qui a accepté une conversation en direct sont stockés dans une base de données d'historique de conversation. |  |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Le courrier électronique et le nom peuvent s'afficher dans les journaux quotidiens qui sont supprimés/supprimés chaque jour.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Les données sont stockées dans une instance de RDS sécurisée restreinte par ip et 2FA.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35754' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35754" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

