---
title: Informations sur les demandes pour remind par 88 Ventures Limited
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Remind, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8e2124ed68b2e9d750c8bc6a229eca0ccad200b5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552445"
---
# <a name="remind"></a>Rappeler

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Septembre 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par 88 Ventures Limited à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Rappeler |
| ID | WA200001444 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | 88 Ventures Limited |
| URL du site web partenaire | [https://www.teamsreminder.app](https://www.teamsreminder.app) |
| URL de la politique de confidentialité | [https://www.teamsreminder.app/#privacy](https://www.teamsreminder.app/#privacy) |
| URL des conditions d’utilisation | [https://www.teamsreminder.app/#terms](https://www.teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par 88 Ventures Limited sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | Délégué | aucune information stockée dans la base de données | permet à l’administrateur de parcourir l’annuaire des utilisateurs de l’organisation pour les utilisateurs qui ont défini des rappels publics | 88546d4f-9973-4716-98e4-cd181c04bc2d |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| (1) Lorsqu’un utilisateur définit un rappel sur un message, le bot tente d’obtenir le nom de la personne qui a envoyé le message à l’origine pour afficher ces informations dans la liste de rappels de l’utilisateur (2) Lorsqu’un utilisateur définit un rappel pour un autre canal ou membre de chat, le bot tente d’obtenir l’identité (utilisateur ou bot) et le nom de l’utilisateur mentionné pour l’afficher dans la liste de rappel de l’utilisateur | (1) Lorsqu’un utilisateur définit un rappel sur un message, le bot tente d’obtenir le nom de la personne qui a envoyé le message à l’origine pour afficher ces informations dans la liste de rappels de l’utilisateur (2) Lorsqu’un utilisateur définit un rappel pour un autre canal ou membre de chat, le bot tente d’obtenir l’identité (utilisateur ou bot) et le nom de l’utilisateur mentionné pour l’afficher dans la liste de rappel de l’utilisateur |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Aucune EEUI et OII n’est partagée avec des fonctionnalités de télémétrie ou d’enregistrement

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Cryptage au repos, authentification à deux facteurs (2FA) pour restreindre l’accès à notre infrastructure informatique et aux données des clients, gammes IP protégées entre les systèmes

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

