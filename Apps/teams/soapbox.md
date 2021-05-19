---
title: Informations d’application pour Soapbox par Soapbox
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Soapbox, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6e2b43df38aac6307c36c4a2cc8d00fe1c3fb629
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552775"
---
# <a name="soapbox"></a>Soapbox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/b49e7913-3b3f-4125-adde-2b698fc12c8b" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381501" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Soapbox à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Soapbox |
| ID | WA104381501 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Soapbox |
| URL du site web partenaire | [https://soapboxhq.com](https://soapboxhq.com) |
| URL de la page Teams’informations d’application | [https://msteams.services.soapboxhq.com/faqs](https://msteams.services.soapboxhq.com/faqs) |
| URL de la politique de confidentialité | [https://soapboxhq.com/privacy-policy/microsoft-teams](https://soapboxhq.com/privacy-policy/microsoft-teams) |
| URL des conditions d’utilisation | [https://soapboxhq.com/terms-of-service](https://soapboxhq.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Soapbox sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Délégué | Synchronisez le jeton. | L’accès au calendrier est nécessaire pour synchroniser les réunions SoapBox aux événements du calendrier |  |
>| User.Read | Délégué | Nom, e-mail, Identifiant utilisateur Microsoft. | Le nom et le courrier électronique sont utilisés pour créer des utilisateurs de SoapBox. |  |
>| offline_access | Délégué |  | L’accès hors ligne aux calendriers est nécessaire pour rendre le temps de notification SoapBox pertinent pour les événements calendendiques synchronisés. |  |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| L’application accède à Team Roster et Chat Roster nous l’utilisons pour créer des canaux d’équipe dans SoapBox avec les membres de l’équipe/chat | Nom, e-mail, identifiant utilisateur Microsoft des utilisateurs pour améliorer l’apparence et la sensation de l’application pour les utilisateurs des équipes Microsoft et s’assurer que chaque utilisateur peut s’engager pleinement dans le logiciel de réunion. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Oui. Nom, e-mail et identifiant utilisateur Microsoft apparaissent dans notre plate-forme de journalisation unifiée pendant un maximum de 30 jours pour aider à identifier les problèmes et aider les utilisateurs à utiliser la plate-forme. Après 30 jours, les données sont supprimées des serveurs d’enregistrement.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Notre infrastructure principale est stockée sur AWS dans un réseau privé. Nous avons également des bots configurés sur Heroku et Azure. L’accès aux serveurs est limité avec les exigences clés de SSH. Toutes les demandes sont terminées SSL (TLS 1.3). Nous utilisons des demandes signées pour nous assurer que le trafic de nos Bots vers la plate-forme est sécurisé. Les données sont cryptées au repos. Le personnel des opérations de Dev exige que la 2FA accède à ses comptes

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

