---
title: Informations sur les demandes pour CalendarHero par CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour CalendarHero, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d27858000c591c320cfadc301ea16ddf2fac89bd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553316"
---
# <a name="calendarhero"></a>CalendrierHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Mars 17, 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par CalendarHero Inc à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | CalendrierHero |
| ID | WA200000150 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | CalendrierHero Inc |
| URL du site web partenaire | [https://calendarhero.com](https://calendarhero.com) |
| URL de la page Teams’informations d’application | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL de la politique de confidentialité | [https://calendarhero.com/privacy](https://calendarhero.com/privacy) |
| URL des conditions d’utilisation | [https://calendarhero.com/terms-of-use](https://calendarhero.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par CalendarHero Inc sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | les deux | Les réunions sont mises en cache dans notre mongoDB sur Azure, mais les descriptions sont cryptées. | Accès aux événements du calendrier de l’utilisateur. |  |
>| Contacts.ReadWrite | les deux | Nom des contacts et adresse e-mail. | Lisez les contacts de l’utilisateur (afin que nous puissions les inviter à une réunion). |  |
>| Group.Read.All | les deux | Nom du groupe et membres. | (Facultatif) lire les groupes d’utilisateurs d’entreprise (pour la planification avec les groupes). |  |
>| Mail.Read | les deux | Contactez e-mail/nom, fréquence/recency des interactions. | (Facultatif) est utilisé pour lire les méta-données par e-mail à sous qui sont les contacts les plus importants de l’utilisateur (via Machine Learning). |  |
>| MailboxSettings.ReadWrite | les deux | Fuseau horaire de l’utilisateur. | Fuseau horaire de l’utilisateur. |  |
>| User.Read.All | les deux | E-mail nom de &amp; l’utilisateur (stocké comme un contact). | (Facultatif) lire les utilisateurs de l’entreprise (pour la planification avec des collègues) |  |
>| offline_access | application | Non | Nous avons besoin de lire et d’écrire à travers notre back-end à tout moment, sans que l’utilisateur soit présent. |  |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| importer des noms/e-mails de collègues afin que notre assistant de réunion bot puisse planifier des réunions avec eux | &amp;e-mail nom. les deux sont stockés dans notre base de données pour une recherche rapide et pour une recherche partielle de nom (par exemple. rencontrer Joe P) |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>L’adresse e-mail d’un utilisateur et/ou d’un contact est utilisée pour enregistrer des événements à LogDNA, notre fournisseur de journalisation.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Toutes les données sont stockées dans le centre de données cloud MS Azure situé à Québec, Canada. Plusieurs champs sont cryptés avec AES256. L’accès à la base de données n’est accessible qu’aux ingénieurs et à nos serveurs back-end par le biais d’informations d’identification au niveau utilisateur/service.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

