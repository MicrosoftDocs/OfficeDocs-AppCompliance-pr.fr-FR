---
title: Outil d’information sur les applications pour zoho campaigns pour l’automatisation du marketing par Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour l’outil Zoho Campaigns pour l’automatisation marketing, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e67de0ca2871d5432b5a29ead52194225bc51c9a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553685"
---
# <a name="zoho-campaigns-tool-for-marketing-automation"></a>Outil Zoho Campaigns pour l’automatisation marketing

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380835" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Zoho Corporation Private Limited à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Outil Zoho Campaigns pour l’automatisation marketing |
| ID | WA104380835 WA104380835 |
| Office 365 clients soutenus | Outlook 2013 ou plus tard sur Windows, Outlook 2016 ou plus tard sur Mac, Outlook sur le web |
| Nom de l’entreprise partenaire | Zoho Corporation Private Limited |
| URL du site web partenaire | [https://www.zoho.com/](https://www.zoho.com/) |
| URL de la politique de confidentialité | [https://zoho.com/privacy.html](https://zoho.com/privacy.html) |
| URL des conditions d’utilisation | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=fr-États-Unis](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Zoho Corporation Private Limited sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Délégué | L’id de calendrier est stocké pour créer des événements dans ce calendrier à partir des campagnes Zoho. | Permet à l’utilisateur d’importer l’événement calendrier Office365 aux campagnes Zoho. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Calendars.ReadWrite | Délégué |  | Permet à l’utilisateur d’ajouter des événements Zoho Campaigns au calendrier Office365. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.Read | Délégué |  Pour enregistrer les coordonnées. | Permet à l’utilisateur d’importer des contacts Office365 aux campagnes Zoho. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | Délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | Délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Délégué | Le courrier électronique est stocké pour identification de l’utilisateur. |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profil | Délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Nous ne recueillons pas EUII / PII dans la télémétrie et les journaux. Nous avons des scripts en place pour rechercher et alerter pour la fixation de ces données étant visibles.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Le client peut sélectionner les données qui doivent être cryptées via EAR (Encryption At Rest) avec des restrictions certaat. Les mots de passe seront hachages par défaut. L’accès logique aux serveurs est assuré par un &amp; réseau dédié isolé et est hautement sécurisé et


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

