---
title: Informations d'application pour ServiceDesk Plus pour la messagerie électronique par Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour ServiceDesk Plus pour la messagerie, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bf8ed2f9b56cdb5afc32d86c608603849da585ad
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094026"
---
# <a name="servicedesk-plus-for-email"></a>ServiceDesk Plus pour la messagerie

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Zoho Corporation Private Limited à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | ServiceDesk Plus pour la messagerie |
| ID | WA104381518 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | Zoho Corporation Private Limited |
| URL du site web partenaire | [https://www.zoho.com/](https://www.zoho.com/) |
| URL de la politique de confidentialité | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| URL des conditions d'utilisation | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par Zoho Corporation Private Limited sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d'autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d'application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | application |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | délégué | ID de messagerie de l'utilisateur. | Permet à l'utilisateur de se connecter et donne à l'application accès à son UPN pour activer la connexion silencieuse. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | application |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | délégué | ID de courrier électronique, nom, ID d'employé, fonction, Téléphone, Mobile, Site, Service, Paramètres régionaux, Photo de profil de l'utilisateur. | Permet d'importer les informations de base des utilisateurs à partir Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | délégué | ID de messagerie de l'utilisateur. | Afficher l'adresse e-mail de l'utilisateur. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | délégué |  | Conservez l'accès aux données à qui vous avez accordé l'accès. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profil | délégué |  | Afficher le profil de base de l'utilisateur. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="add-in-data-access"></a>Accès aux données du add-in

List the permissions this app requires for accessing your organization's data, the justification and purpose for this permission (what does the app use this information for?) and whether the app stores any of this information in its databases.

>| **Autorisation**  | **Description** |
>|:----------------|:----------------|
>| Lire l'élément | Ce module complémentaire peut accéder à des informations personnelles sur le message actif, telles que les noms des expéditeurs, les noms des destinataires, les adresses e-mail, le corps du message et les informations de pièce jointe. Le add-in peut envoyer ces données à un service tiers. D'autres éléments de votre boîte&#8217;ne peuvent pas être lus ou modifiés. |
>| Envoyer des données | Peut envoyer des données sur Internet |

#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous ne collectons pas d'EUII/PII dans la télémétrie/les journaux. Nous avons des scripts en place qui recherchent des modèles et alertent leur résolution

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Toutes les données sont chiffrées sur REST. Seules les personnes autorisées ont accès au système qui est quand même protégé par un accès, entièrement audité pour tous les types d'accès. MFA en place pour l'accès, les comptes autorisés sont conservés dans un annuaire et un hôte d'entreprise


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

