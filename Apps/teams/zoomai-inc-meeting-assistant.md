---
title: Application Information for Zoom.ai Meeting Assistant by Zoom.ai Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour l'Assistant réunion Zoom.ai, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c5928d1ba26624bbae26fdf0dab09fbb4ddcded6
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094206"
---
# <a name="zoomai-meeting-assistant"></a>Assistant réunion Zoom.ai

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 17, 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Zoom.ai Inc à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Assistant réunion Zoom.ai |
| ID | WA200000150 |
| Fonctionnalités | Bot, Onglet, Connecteur |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Zoom.ai Inc |
| URL du site web partenaire | [https://zoom.ai](https://zoom.ai) |
| URL de la Teams d'informations sur l'application | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL de la politique de confidentialité | [https://zoom.ai/privacy](https://zoom.ai/privacy) |
| URL des conditions d'utilisation | [https://zoom.ai/terms-of-use](https://zoom.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par Zoom.ai Inc sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d'autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d'application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | les deux | Les réunions sont mises en cache dans notre mongoDB sur Azure, mais les descriptions sont chiffrées. | Accès aux événements de calendrier de l'utilisateur. |  |
>| Contacts.ReadWrite | les deux | Nom et adresse e-mail des contacts. | Lisez les contacts de l'utilisateur (afin de pouvoir les inviter à une réunion). |  |
>| Group.Read.All | les deux | Nom et membres du groupe. | (Facultatif) lire les groupes d'utilisateurs d'entreprise (pour la planification avec des groupes). |  |
>| Mail.Read | les deux | Adresse de messagerie/nom du contact, fréquence/recency des interactions. | (Facultatif) est utilisé pour lire les métadon données de courrier électronique en dessous de qui sont les contacts les plus importants de l'utilisateur (via Machine Learning). |  |
>| MailboxSettings.ReadWrite | les deux | Fuseau horaire de l'utilisateur. | Fuseau horaire de l'utilisateur. |  |
>| User.Read.All | les deux | E-mail de nom &amp; d'utilisateur (stocké en tant que contact). | (Facultatif) lire les utilisateurs d'entreprise (pour la planification avec des collègues) |  |
>| offline_access | application | Non | Nous devons lire et écrire dans notre back-end à tout moment, sans que l'utilisateur soit présent. |  |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d'identification de l'utilisateur final (EUII) : la liste (prénom, nom, nom d'affichage, adresse e-mail) d'un membre d'une équipe ou d'une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l'accès à EUII ?**  | **L'EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l'EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| importer les noms/e-mails de collègues afin que notre bot assistant de réunion puisse planifier des réunions avec eux | &amp;e-mail de nom. les deux sont stockées dans notre base de données pour la recherche rapide et pour la recherche partielle de noms (par exemple, rencontrer Joe P) |  |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>L'adresse e-mail d'un utilisateur et/ou d'un contact est utilisée pour consigner des événements dans LogDNA, notre fournisseur de journalisation.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Toutes les données sont stockées dans le centre de données cloud MS Azure situé à City, Canada. Plusieurs champs sont chiffrés avec AES256. L'accès à la base de données est disponible uniquement pour les ingénieurs et nos serveurs back-end par le biais d'informations d'identification de niveau utilisateur/service.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

