---
title: Informations sur l’application du tableau des tâches agile pour SharePoint Online par Agile-IS
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour le tableau des tâches Agile pour SharePoint Online, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 26b19e5ce6563f49a5e76bf40e5422e43c5f804b
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251683"
---
# <a name="agile-task-board-for-sharepoint-online"></a>Tableau des tâches agile pour SharePoint Online

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002087" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Agile-IS à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Tableau des tâches agile pour SharePoint Online |
| ID | WA200002087 |
| Office 365 clients pris en charge | SharePoint 2016 ou ultérieure |
| Nom de la société partenaire | Agile-IS |
| URL du site web partenaire | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| URL de la politique de confidentialité | [https://www.agile-is.de/en/telemetry](https://www.agile-is.de/en/telemetry) |
| URL des conditions d’utilisation | [https://go.microsoft.com/fwlink/?linkid=2041178](https://go.microsoft.com/fwlink/?linkid=2041178) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Agile-IS sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="add-in-data-access"></a>Accès aux données du add-in

List the permissions this app requires for accessing your organization’s data, the justification and purpose for this permission (what does the app use this information for?) and whether the app stores any of this information in its databases.

>| **Autorisation**  | **Description** |
>|:----------------|:----------------|
>| Par défaut | Ne&#8217;pas lire ou apporter des modifications à votre document |
>| Envoyer des données | Peut envoyer des données sur Internet |

#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous collectons le nom de domaine et l’ID d’utilisateur hachage dans les données de télémétrie d’informations sur l’application. Dans chaque instance d’application, la transmission des données de télémétrie peut être contrôlée et désactivée. Une suppression ultérieure des données doit être demandée de notre part.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>L’application stocke toutes les données dans SharePoint listes et bibliothèques de documents en ligne sur le même site que l’instance respective de l’application. Le contrôle d’accès à ces données dépend de la configuration du client client. 

Pour le contrôle de licence, le domaine et l’UPN sont transférés vers un service hébergé dans Azure. Ces informations sont sécurisées par l’authentification Azure AD.


#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36140' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36140" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

