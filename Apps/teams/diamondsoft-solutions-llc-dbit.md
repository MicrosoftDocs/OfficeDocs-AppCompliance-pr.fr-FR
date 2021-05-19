---
title: Informations d’application pour DBit par Diamondsoft Solutions, LLC
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour DBit, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 23995f613c3c3b6d7b2ab7d161f8710ccddf07d0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553955"
---
# <a name="dbit"></a>DBit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Juin 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/b28bb657-8edd-47ae-a912-c5fc11b3e89e" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001536" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Diamondsoft Solutions, LLC à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | DBit |
| ID | WA200001536 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Diamondsoft Solutions, LLC |
| URL du site web partenaire | [https://www.dbit.io/index.html](https://www.dbit.io/index.html) |
| URL de la politique de confidentialité | [https://www.dbit.io/privacypolicy.html](https://www.dbit.io/privacypolicy.html) |
| URL des conditions d’utilisation | [https://www.dbit.io/termsofuse.html](https://www.dbit.io/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Diamondsoft Solutions, LLC sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Délégué | Nous ne stockons pas Graph informations dans notre système ou bases de données. | Activer la connexion et lire le profil utilisateur | 1533d702-7604-463a-9fa3-63077c425e76 |
>| email | Délégué | Nous ne stockons pas Graph informations dans notre système ou bases de données. | Afficher l’adresse de messagerie des utilisateurs | 1533d702-7604-463a-9fa3-63077c425e76 |
>| offline_access | Délégué | Nous ne stockons pas Graph informations dans notre système ou bases de données. | Gérer l’accès aux données auxquelles vous avez accordé l’accès | 1533d702-7604-463a-9fa3-63077c425e76 |
>| openid | Délégué | Nous ne stockons pas Graph informations dans notre système ou bases de données. | Connecter des utilisateurs | 1533d702-7604-463a-9fa3-63077c425e76 |
>| profil | Délégué | Nous ne stockons pas Graph informations dans notre système ou bases de données. | Afficher le profil de base des utilisateurs | 1533d702-7604-463a-9fa3-63077c425e76 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Pour créer un message de bienvenue | Nous ne stockons pas les informations de liste dans notre système ou bases de données. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Nous ne recueillons pas ces renseignements.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Nous utilisons Azure Cache Redis, la durée de vie maximale des données dans le cache est de 300 minutes. Les éléments de données de cache sont cryptés avec AES256. Seul le service d’application peut se connecter à Azure Cache Redis via SSL, la chaîne de connexion est stockée dans Azure Environmental Variable.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

