---
title: Informations d’application pour l’add-in StarLeaf Outlook par StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour l’add-in StarLeaf pour Outlook, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f201131be32c743550a02a24e653f784a1d91817
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552475"
---
# <a name="starleaf-add-in-for-outlook"></a>Ajout starleaf pour Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Août 24, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par StarLeaf à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Ajout starleaf pour Outlook |
| ID | WA104381343 |
| Office 365 clients soutenus | Outlook 2013 ou plus tard sur Windows, Outlook 2016 ou plus tard sur Mac, Outlook sur le web |
| Nom de l’entreprise partenaire | StarLeaf |
| URL du site web partenaire | [https://www.starleaf.com/](https://www.starleaf.com/) |
| URL de la politique de confidentialité | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| URL des conditions d’utilisation | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par StarLeaf sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | application | nous stockons l’iCalUId des réunions, l’heure/date de la réunion, les adresses e-mail des participants et une propriété étendue à valeur unique que nous lisons et écrivons sur la réunion en utilisant l’interface de propriétés personnalisées Office.js. L’iCalUId est utilisé pour corréler la réunion dans le calendrier de perspectives d&#8217;utilisateur avec la réunion vidéo sur notre service. L’heure/la date et les participants sont utilisés pour fournir une réunion vidéo au bon moment aux bonnes personnes sur notre service. SVEP sont habitués à notre addin O365 pour fournir une interface pour les utilisateurs de définir des détails sur la réunion vidéo sur notre service tels que l’enregistrement. | utilisé pour s’abonner aux notifications webhook pour suivre les modifications apportées par les utilisateurs aux événements de leurs calendriers et mettre à jour notre service pour le garder cohérent. Il est également utilisé pour créer des événements dans leur calendrier lorsqu’un utilisateur interagit avec notre application Teams et planifie une réunion sur notre service. | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | application | nous stockons le jeton de rafraîchissement oauth pour être en mesure de se connecter. Nous stockons l’id de profil des utilisateurs pour être en mesure de comparer avec les tentatives futures OAuth de cet utilisateur et nous nous assurons que nous ne&#8217;pas stocker leurs coordonnées deux fois.  | permettre aux utilisateurs de se connecter à l’application et permet à notre application d’obtenir l’adresse e-mail de l’utilisateur&#8217;de corréler leur connexion avec un compte sur notre service.  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Si des problèmes de support technique surviennent, les données organisationnelles peuvent être transférées à SalesForce pour la gestion de cas. Si l’utilisateur utilise la fonction de connexion PSTN, l’appel passe par Twilio, Plivo ou Voxbone |  | N/A |



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Oui. Les journaux incluent les noms d’utilisateur, les adresses IP, les enregistrements de détails d’appel, les informations sur la qualité de connexion (perte de paquets, débit), le type d’appareil, les progrès des appels. L’information est à la disposition de l’équipe de soutien technique et des développeurs principaux pour diagnostiquer les problèmes de service. Les données sont anonymisées après 90 jours. Les contrôles de protection de ces données sont vérifiés dans le cadre de notre certification ISO/IEC 27001.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données sont stockées sur les serveurs journaux de StarLeaf&#8217;dans le centre de données dans lequel se trouve le compte de l’utilisateur&#8217;, et sauvegardées vers un ou plusieurs centres de données dans la même juridiction. L’accès aux données se fait par compte utilisateur individuel à l’aide de mots de passe par utilisateur qui sont vérifiés en force. Les comptes d&#8217;utilisateurs de service starLeaf sont vérifiés automatiquement par rapport aux systèmes RH et aux groupes d’annuaires actifs de l’entreprise pour alerter l’équipe sécurité et conformité en cas d’anomalies.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

