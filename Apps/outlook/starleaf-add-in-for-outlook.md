---
title: Informations sur l’application pour le Outlook StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour le add-in StarLeaf pour Outlook, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f201131be32c743550a02a24e653f784a1d91817
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552475"
---
# <a name="starleaf-add-in-for-outlook"></a>Le add-in StarLeaf pour Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par StarLeaf à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Le add-in StarLeaf pour Outlook |
| ID | WA104381343 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | StarLeaf |
| URL du site web partenaire | [https://www.starleaf.com/](https://www.starleaf.com/) |
| URL de la politique de confidentialité | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| URL des conditions d’utilisation | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par StarLeaf sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | application | nous stockons l’iCalUId des réunions, l’heure/la date de la réunion, les adresses e-mail des participants et une propriété à valeur unique étendue que nous lisons et écrivons sur la réunion à l’aide de l’interface des propriétés personnalisées Office.js. L’iCalUId est utilisé pour mettre en corrélation la réunion dans un&#8217;calendrier Outlook avec la réunion vidéo sur notre service. L’heure/la date et les participants sont utilisés pour fournir une réunion vidéo au bon moment aux bonnes personnes sur notre service. SvEP est utilisé avec notre addin O365 pour fournir une interface aux utilisateurs pour définir des détails sur la réunion vidéo sur notre service, comme l’enregistrement. | permet de s’abonner aux notifications webhook pour suivre les modifications apportées par les utilisateurs aux événements dans leurs calendriers et de mettre à jour notre service pour le maintenir cohérent. Il est également utilisé pour créer des événements dans son calendrier lorsqu’un utilisateur interagit avec notre application Teams et planifier une réunion sur notre service. | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | application | nous stockons le jeton d’actualisation oauth pour pouvoir se connecter. Nous stockons l’ID de profil des utilisateurs pour pouvoir comparer les futures tentatives OAuth de cet utilisateur et nous nous assurons que nous ne&#8217;pas stocker leurs détails deux fois.  | autoriser les utilisateurs à se connecter à l’application et permet à notre application d’obtenir l’adresse de messagerie de l'&#8217;pour corréler leur connexion avec un compte sur notre service.  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Si des problèmes de support technique surviennent, les données organisationnelles peuvent être transférées vers SalesForce pour la gestion des cas. Si l’utilisateur utilise la fonctionnalité de numérotation PSTN, l’appel passe par Twilio, Plivo ou Voxivo. |  | S/O |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui. Les journaux incluent les noms d’utilisateur, les adresses IP, les enregistrements des détails des appels, les informations sur la qualité de connexion (perte de paquets, vitesse de bit), le type d’appareil, la progression des appels. Les informations sont disponibles pour l’équipe de support technique et les développeurs senior pour diagnostiquer les problèmes de service. Les données sont rendues anonymes après 90 jours. Les contrôles de protection de ces données sont audités dans le cadre de notre certification ISO/IEC 27001.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données sont stockées sur les serveurs de journaux de StarLeaf&#8217;dans le centre de données où se trouve le compte de l’utilisateur&#8217;et sont enregistrées dans un ou plusieurs centres de données au sein de la même juridiction. L’accès aux données s’fait par compte d’utilisateur individuel à l’aide de mots de passe par utilisateur qui sont vérifiés de force. Les comptes d’utilisateur de service StarLeaf&#8217;sont audités automatiquement sur les systèmes RH et les groupes Active Directory d’entreprise pour alerter l’équipe sécurité et conformité si des anomalies sont détectées.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

