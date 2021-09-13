---
title: Informations sur l’application pour rappel par 88 personnes limitées
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Remind, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f39e0c35b88e3212743e30c7ab5ac40c74c708c3
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59280012"
---
# <a name="remind"></a>Rappeler

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par 88 Personnes limitées à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Rappeler |
| ID | WA200001444 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | 88 Ventures Limited |
| URL du site web partenaire | [https://moonbearapp.com](https://moonbearapp.com) |
| URL de la politique de confidentialité | [https://teamsreminder.app/#privacy](https://teamsreminder.app/#privacy) |
| URL des conditions d’utilisation | [https://teamsreminder.app/#terms](https://teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par 88 Contrôles Limited sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | délégué | aucune information stockée dans la base de données | permet à l’administrateur de parcourir l’annuaire d’utilisateurs de l’organisation pour les utilisateurs qui ont fixé des rappels publics | [88546d4f-9973-4716-98e4-cd181c04bc2d](https://docs.microsoft.com/microsoft-365-app-certification/azure/88546d4f-9973-4716-98e4-cd181c04bc2d) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| (1) Lorsqu’un utilisateur définit un rappel sur un message, le bot tente d’obtenir le nom de la personne qui a envoyé le message à l’origine pour afficher ces informations dans la liste des rappels de l’utilisateur (2) Lorsqu’un utilisateur définit un rappel pour un autre canal ou membre de conversation, le bot tente d’obtenir l’identité (utilisateur ou bot) et le nom de l’utilisateur mentionné pour l’afficher dans la liste de rappels de l’utilisateur | (1) Lorsqu’un utilisateur définit un rappel sur un message, le bot tente d’obtenir le nom de la personne qui a envoyé le message à l’origine pour afficher ces informations dans la liste des rappels de l’utilisateur (2) Lorsqu’un utilisateur définit un rappel pour un autre canal ou membre de conversation, le bot tente d’obtenir l’identité (utilisateur ou bot) et le nom de l’utilisateur mentionné pour l’afficher dans la liste de rappels de l’utilisateur |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun EEUI et OII n’est partagé avec la fonctionnalité de télémétrie ou de journalisation

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Chiffrement au repos, authentification à deux facteurs (2FA) pour restreindre l’accès à notre infrastructure informatique et aux données client, plages d’adresses IP protégées entre les systèmes

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

