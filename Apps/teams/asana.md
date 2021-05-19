---
title: Informations sur les demandes d’Asana par Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Asana, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6c18bb20cdf753b1a5d998b3d7b7144f950f00c0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553405"
---
# <a name="asana"></a>Asana

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Novembre 2, 2020</p>

* <a href="https://teams.microsoft.com/l/app/f0e33e18-08fc-4511-a2a7-c6bdff367263" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001727" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Asana à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Asana |
| ID | WA200001727 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Asana |
| URL du site web partenaire | [https://asana.com/?noredirect&amp;utm_source=asana_inproduct &amp; ut...](https://asana.com/?noredirect&amp;utm_source=asana_inproduct&amp;utm_medium=organic_inproduct&amp;utm_campaign=msft_teams_launch) |
| URL de la politique de confidentialité | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL des conditions d’utilisation | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Asana sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>Cette application n’utilise pas microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| L’add-in transfère les informations de base par e-mail (expéditeur, réceptif, sujet, corps) et les pièces jointes à Asana sur demande de l’utilisateur. |  | Courriel - Lit les e-mails actuellement ouverts lorsqu’ils sont affichés dans un volet de tâches. - Lit actuellement les pièces jointes d’e-mail à télécharger sur les tâches Asana. - Cela permet aux utilisateurs de faire rapidement des tâches à Asana avec des informations à partir de courriels. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Notre application ne enregistre que les informations relatives aux données Asana. La seule fois où nous en connectons quelque chose lié à des informations utilisateur Outlook est lorsque l’utilisateur attache explicitement un e-mail ou télécharge une pièce jointe à Asana, et même alors nous ne connectons pas le contenu. Des journaux à court terme existent sur des serveurs qui peuvent inclure certaines données utilisateur, mais ils sont éphémères et limités à des périodes inférieures à 72 heures.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Enterprise clients ont garanti le chiffrement au repos à l’aide d’AES-256. Les données sont stockées sur Amazon Web Services et AWS gère les clés de chiffrement à l’aide de leur système de gestion des clés. Nous avons 2FA pour tous les administrateurs. L’accès est donné sur le principe du moindre privilège.
Vos administrateurs organisationnels Asana ont la possibilité de configurer les comptes SAML, SCIM, Service et ont une vue d’ensemble des données qui sont mises dans l’outil. Les administrateurs peuvent demander une exportation organisationnelle complète à partir de la console Admin et auditer au besoin.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

