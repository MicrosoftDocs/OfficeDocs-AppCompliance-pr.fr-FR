---
title: Informations sur l’application pour l’agent virtuel désormais par ServiceNow
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour l’agent virtuel maintenant, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bbd2b42fe7ad81e2ba0ba8157a34da67878e09c8
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551664"
---
# <a name="now-virtual-agent"></a>Agent désormais virtuel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/49471a10-fdbc-4ffb-b0b8-944f3df985d9" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381816" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ServiceNow à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Agent désormais virtuel |
| ID | WA104381816 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | ServiceNow |
| URL du site web partenaire | [https://www.servicenow.com/](https://www.servicenow.com/) |
| URL de la Teams d’informations sur l’application | [https://docs.servicenow.com/bundle/london-servicenow-platfo...](https://docs.servicenow.com/bundle/london-servicenow-platform/page/administer/virtual-agent/task/install-va-integrations.html#install-va-integrations) |
| URL de la politique de confidentialité | [https://www.servicenow.com/service-privacy.html](https://www.servicenow.com/service-privacy.html) |
| URL des conditions d’utilisation | [https://www.servicenow.com/terms-of-use.html](https://www.servicenow.com/terms-of-use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par ServiceNow sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | délégué | Le domaine est stocké dans notre centre de données à des fins de routage des messages futures. | Lorsque l’administrateur ServiceNow installe l’intégration avec MS Teams, l’administrateur doit se connecter à son compte Teams MS. Nous lisons le domaine à partir de l’adresse e-mail (pas l’adresse de messagerie complète). |  |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Non out of box by ServiceNow. Les clients peuvent tirer parti de l’infrastructure de l’agent virtuel pour créer des fonctionnalités supplémentaires pouvant potentiellement accéder aux informations de l’organisation ou de l’utilisateur final. Les utilisateurs peuvent taper des informations d’identification personnelle pendant l’interaction avec le bot et les envoyer à ServiceNow.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Pour plus d’informations, [reportez-vous](/microsoft-365-app-certification/teams/servicenow-now-virtual-agent?pivots=csa) à la section Cloud Security Alliance.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

