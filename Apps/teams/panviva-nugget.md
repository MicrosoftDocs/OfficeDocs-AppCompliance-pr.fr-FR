---
title: Informations sur l’application pour Le Monde par Panviva
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Le Monde, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6108617e72e1996a335b53941989a707a6544337
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283191"
---
# <a name="nugget"></a>Nugget

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 12, 2020</p>

* <a href="https://teams.microsoft.com/l/app/4e85cc82-5187-4059-af36-a49e7db32bee" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001737" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Panviva à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Nugget |
| ID | WA200001737 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Panviva |
| URL du site web partenaire | [https://www.panviva.com](https://www.panviva.com) |
| URL de la politique de confidentialité | [https://www.panviva.com/privacy-policy/](https://www.panviva.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.panviva.com/terms-and-conditions](https://www.panviva.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Panviva sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui.
Teams’ID d’utilisateur est stocké : cela est nécessaire afin que nous pouvons récupérer des informations sur le client dans lequel il se trouve et si l’utilisateur est administrateur ou non.
Teams’organisation : il est stocké afin que nous pouvons récupérer les utilisateurs dans un client et récupérer les détails de l’abonnement pour ce client particulier.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous utilisons Azure CosmosDB pour stocker toutes les données d’application. Pour accéder aux données, vous avez besoin d’un point de terminaison et d’une clé, qui sont tous deux injectés dans le service de configuration utilisé pour accéder aux données. Le service de configuration gère uniquement les demandes avec un jeton du porteur qu’il reçoit dans la demande de notre service d’application de bot. Ce jeton est créé à l’origine par Okta lorsqu’un utilisateur se connecte au bot sur l’interface d’équipe. Ces données sont accessibles par les administrateurs Panviva qui doivent se rendre sur la plateforme Microsoft Azure avec l’utilisation de l’authentification 2 facteurs. Le courrier électronique et le prénom de l’utilisateur sont stockés dans OKTA et sont accessibles uniquement avec une clé privée stockée dans un coffre de clés qui est ensuite accessible par le service de configuration. Seul le service de configuration a accès au coffre de clés via l’utilisation d’identités gérées pour qu’aucune informations d’identification ne soit stockée dans l’application.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

