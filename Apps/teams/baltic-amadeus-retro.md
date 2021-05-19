---
title: Informations d’application pour Retro par Baltic Amadeus
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Retro, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553455"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Novembre 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Baltic Amadeus à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Retro |
| ID | WA200001892 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Baltic Amadeus |
| URL du site web partenaire | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL de la politique de confidentialité | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL des conditions d’utilisation | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Baltic Amadeus sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>Cette application n’utilise pas microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Retro app a sa propre API Web qui n’est pas considéré comme un service Microsoft. Comme mentionné précédemment, il stocke email et fullname pour l’identification et les buts appropriés d’affichage de contenu. Ces données ne sont envoyées nulle part ailleurs. En outre, Retro dispose d’une fonctionnalité optionnelle pour exporter des données sprint vers l’espace de confluence atlassienne. Pour ce faire, l’utilisateur doit entrer son nom d’utilisateur et son mot de passe confluents. Ces données ne sont utilisées que pour faire des demandes authentifiées pour confluence api pour le compte de l’utilisateur et ne sont stockées ni enregistrées nulle part. |  | Retro a sa propre API Web qui est également enregistrée dans azure. Pour l’utiliser, l’utilisateur doit être authentifié via Microsoft Identity Platform. L’utilisateur doit être authentifié afin que l’application Retro puisse serveur contenu spécifique à l’utilisateur |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot accède à la liste afin de vérifier quel membre a rejoint ou quitté l’équipe. Sur cette base, il ajoute ou désactive cet utilisateur du projet afin que l’utilisateur ne soit plus affiché dans la liste des participants au sprint. | E-mail et FullName sont liés entre eux et sont stockés dans la base de données. Le courrier électronique est utilisé pour l’identification de l’utilisateur afin d’afficher le contenu approprié pour l’utilisateur connecté. FullName est utilisé pour afficher des puproses, afin que d’autres utilisateurs puissent savoir pour qui ils évaluent ou écrivent des commentaires.  |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Non. Le seul processus qui génère la télémétrie /journaux dans l’application Retro est l’enregistrement des erreurs. Les journaux d’erreurs n’incluent pas d’EUII ou d’OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données sont stockées dans la base de données serveur sql azure. Il est stocké via l’application Retro et retro bot.
Par défaut, la base de données sql azure est activée pour le chiffrement transparent des données.
La base de données est verrouillée derrière l’authentification de base.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

