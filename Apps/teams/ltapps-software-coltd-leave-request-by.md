---
title: Informations sur l'application pour la demande de congé par LTAPPs par LTAPPs SOFTWARE CO.,LTD
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour la demande d'autorisation par LTAPPs, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cabfdc7cfc73ad75cedd7846adb82f8aba1e6a6d
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093359"
---
# <a name="leave-request-by-ltapps"></a>Demande de congé par LTAPPs

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/782cf385-ea23-41ce-828b-832781eec530" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001928" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par LTAPPs SOFTWARE CO.,LTD à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Demande de congé par LTAPPs |
| ID | WA200001928 |
| Fonctionnalités | Tab |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | LTAPPs SOFTWARE CO.,LTD |
| URL du site web partenaire | [https://ltaddins.com](https://ltaddins.com) |
| URL de la politique de confidentialité | [https://ltaddins.com/TermsCondition/privacypolicy.html](https://ltaddins.com/TermsCondition/privacypolicy.html) |
| URL des conditions d'utilisation | [https://ltaddins.com/TermsCondition/terms.html](https://ltaddins.com/TermsCondition/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par LTAPPs SOFTWARE CO.,LTD sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n'utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d'identification de l'utilisateur final (EUII) : la liste (prénom, nom, nom d'affichage, adresse e-mail) d'un membre d'une équipe ou d'une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n'est accessible.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Le module complémentaire ne stocke aucune information de l'utilisateur final. Il stocke uniquement 2 informations de configuration sous les magasins &amp; dans Cosmos db Azure
- GUID client du client
- URL de l'application de demande de congé du client 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>L'application ne stocke pas les données du client. Toutes les données des magasins clients dans le site client (site Sharepoint).
Il n'obtienne/définisse les données sur le site client que via SharePoint API Rest a utilisé l'inscription d'application &amp; Azure pour l'th.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36147' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36147" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

