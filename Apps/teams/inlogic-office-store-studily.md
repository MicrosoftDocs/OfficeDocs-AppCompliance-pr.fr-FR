---
title: Informations d’application Studi.ly par inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Studi.ly, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d682e758d9632a2c3ac19296dda7083dc8379689
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525568"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par inLogic-Office Store à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Studi.ly |
| ID | WA200001668 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | inLogic-Office Store |
| URL du site web partenaire | [https://www.inlogic.dk](https://www.inlogic.dk) |
| URL de la politique de confidentialité | [https://studi.ly/Studily_Privacy_Statement.pdf](https://studi.ly/Studily_Privacy_Statement.pdf) |
| URL des conditions d’utilisation | [https://studi.ly/Studily_Terms_Of_Use_v1.pdf](https://studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par inLogic-Office Store sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | délégué | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.Read.All | délégué | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | Écrire un répertoire dans les groupes pour les devoirs et les documents. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.ReadWrite.All | application | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | Écrire un répertoire dans les groupes pour les devoirs et les documents. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.Read.All | application | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | Lisez Les classes d’enseignement, l’établissement scolaire, les membres et les termes.Obtenez toutes les classes et écoles d’un client pour la synchronisation dans la base de données d’application. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadBasic | délégué | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | Lisez Les classes d’enseignement, l’établissement scolaire, les membres et les termes.Obtenez toutes les classes et écoles d’un client pour la synchronisation dans la base de données d’application. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadWrite.All | application | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | Lisez Les classes d’enseignement, l’établissement scolaire, les membres et les termes.Obtenez toutes les classes et écoles d’un client pour la synchronisation dans la base de données d’application. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Files.ReadWrite.All | délégué | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | ReadWrite Files from One Drive | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.Read.All | délégué | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | Cette autorisation a permis à l’application d’obtenir différents événements de calendrier pour les groupes du client.,subject,start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.ReadWrite.All | les deux | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | Cette autorisation a permis à l’application d’obtenir différents événements de calendrier pour les groupes du client.,subject,start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Member.Read.Hidden | application |  |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Sites.ReadWrite.All | les deux | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | ReadWrite Files from One Drive | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.Read | délégué | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | Lecture des informations utilisateur | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.ReadBasic.All | délégué | Nous stockons les classes, les établissements scolaires, les membres et les informations sur les termes de l’api d’enseignement dans notre api, et nous en avons besoin, car si nous les recevons à chaque fois à partir de l’api graphique qui ralentit le travail de notre application. Nous le synchroniseons sur un événement basé sur le temps à partir de l’api d’éducation vers notre base de données. | Lecture des informations utilisateur | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Ces données n’apparaissent pas dans les journaux

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Elle est stockée dans la base de données Azure cosmos et tout chiffrement et stockage disponible par défaut avec la base de données cosmos s’applique à cette application.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

