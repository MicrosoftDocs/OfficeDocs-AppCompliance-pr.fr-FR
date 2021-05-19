---
title: Informations d’application Studi.ly par inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Studi.ly, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 26a89739809e0d398db2a823bd714aa06a2d210d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553055"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Août 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par inLogic-Office Store à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Studi.ly |
| ID | WA200001668 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | inLogic-Office Store |
| URL du site web partenaire | [https://www.studi.ly](https://www.studi.ly) |
| URL de la politique de confidentialité | [https://www.studi.ly/Studily_Privacy_Statement.pdf](https://www.studi.ly/Studily_Privacy_Statement.pdf) |
| URL des conditions d’utilisation | [https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf](https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par inLogic-Office Store sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Délégué | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | Délégué | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | Écrivez répertoire dans les groupes pour les affectations et les matériaux. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | application | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | Écrivez répertoire dans les groupes pour les affectations et les matériaux. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.Read.All | application | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | Lire Classes d’éducation, école, membres et terms.Get toutes les classes et les écoles d’un locataire pour la synchronisation dans la base de données app. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | Délégué | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | Lire Classes d’éducation, école, membres et terms.Get toutes les classes et les écoles d’un locataire pour la synchronisation dans la base de données app. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadWrite.All | application | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | Lire Classes d’éducation, école, membres et terms.Get toutes les classes et les écoles d’un locataire pour la synchronisation dans la base de données app. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | Délégué | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | LireWrite Fichiers à partir de One Drive | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | Délégué | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | Cette permission a permis à l’application d’obtenir différents événements claender pour les groupes du locataire.,subject,start,end, extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | les deux | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | Cette permission a permis à l’application d’obtenir différents événements claender pour les groupes du locataire.,subject,start,end, extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member.Read.Hidden | application |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | les deux | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | LireWrite Fichiers à partir de One Drive | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | Délégué | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | Lecture des informations utilisateur | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | Délégué | Nous stockons des classes, des écoles et des membres et des informations sur les termes de l’éducation api dans notre api et nous en avons besoin parce que si nous l’obtenons à chaque fois à partir de graphique api qui rend notre application de travail lent. Nous le synchronisons sur un événement basé sur le temps, de l’api éducation à notre base de données. | Lecture des informations utilisateur | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Ces données n’apparaissent pas dans les journaux

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Il est stocké dans la base de données Cosmos Azure et tout cryptage et stockage disponible par défaut avec la base de données cosmos s’applique à cette application.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

