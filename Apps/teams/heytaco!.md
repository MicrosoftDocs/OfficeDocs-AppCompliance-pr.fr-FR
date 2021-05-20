---
title: Informations sur l’application pour HeyTaco! par HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour HeyTaco!, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 66739977ba4aa3eef7456d4ec60530f94065a2b9
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553125"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par HeyTaco! à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | HeyTaco! |
| ID | WA200001346 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | HeyTaco! |
| URL du site web partenaire | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL de la politique de confidentialité | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL des conditions d’utilisation | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par HeyTaco ! sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | délégué | utilisé pour faire correspondre l’utilisateur pour les transferts de données de Slack vers MS Teams | utilisé pour faire correspondre l’utilisateur pour les transferts de données de Slack vers MS Team | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| openid | délégué | utilisé pour se connecter à HeyTaco ! | utilisé pour se connecter à HeyTaco ! | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| profil | délégué | permet de capturer le nom d’utilisateur, l’image de profil, le décalage de fuseau horaire, l’ID client et l’ID d’équipe | utilisé pour capturer le nom d’utilisateur, l’avatar, le décalage de fuseau horaire, l’ID client et l’ID d’équipe | be8d11cf-265a-4974-9912-4ff28c29fc21 |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Pour indiquer à l’utilisateur qu’il a reçu un reçu et de qui il s’agit. | Adresse de messagerie (pour les activités de migration d’une plateforme à une autre) Image de profil nom (pour le message d’accueil de l’utilisateur) Fuseau horaire (pour afficher correctement les messages donnés sur la page d’activité) ID de locataire (pour l’agrégation des données par client) ID d’équipe (Pour l’agrégation des données par équipe)  |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>LES EUII et OII ne sont connectés à aucune journalisation. Seuls les types d’erreur et les types d’action.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>HeyTaco! les bases de données et les sauvegardes de données sont hébergées sur Amazon Web Services (AWS). 

Les opérations du centre de données Amazon ont été agréées sous ISO 27001 , SOC 1 et SOC 2/SSAE 16/ISAE 3402 (précédemment SAS 70 Type II ), PCI Niveau 1 , FISMA Modéré et Sarbanes-Oxley (SOX).

Lorsque vous envoyez des informations via notre service, vos informations sont protégées et chiffrées au repos et en transit via des connexions sécurisées. Nous implémentons diverses mesures de sécurité pour maintenir la sécurité de vos informations personnelles.

Nous avons la gestion des accès privilégiés en place pour protéger les données sur nos serveurs.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

