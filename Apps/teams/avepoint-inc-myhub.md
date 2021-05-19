---
title: Informations d’application pour MyHub par AvePoint, inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/21/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour MyHub, ses politiques de traitement des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ccf5367ea692731bafcdc03d04ab4dad2e76c976
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553385"
---
# <a name="myhub"></a>MyHub

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur sur: Décembre 21, 2020</p>

* <a href="https://teams.microsoft.com/l/app/c3ff6344-f6f0-4bfa-8697-b9d47b32ca4b" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000726" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par AvePoint, inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | MyHub |
| ID | WA200000726 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | AvePoint, Inc. |
| URL du site web partenaire | [https://www.avepoint.com](https://www.avepoint.com) |
| URL de la politique de confidentialité | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| URL des conditions d’utilisation | [https://www.avepoint.com/company/terms-and-conditions/](https://www.avepoint.com/company/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par AvePoint, inc. sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | les deux | les données de configuration d’application sont stockées du point de vue de la manipulation des données | Lire les données de l’annuaire | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Group.ReadWrite.All | les deux | les données de configuration d’application sont stockées du point de vue de la manipulation des données | Lire et écrire tous les groupes | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Mail.Send | Délégué | les données de configuration d’application sont stockées du point de vue de la manipulation des données | Envoyer un courrier électronique en tant qu’utilisateur | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Reports.Read.All | application | les données de configuration d’application sont stockées du point de vue de la manipulation des données | Accéder en lecture à tous les rapports d’utilisation | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.FullControl.All | application | les données de configuration d’application sont stockées du point de vue de la manipulation des données | Contrôler pleinement toutes les collections de sites | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.Read.All | application | les données de configuration d’application sont stockées du point de vue de la manipulation des données | Lire des éléments dans toutes les collections de sites  | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.ReadWrite.All | Délégué | les données de configuration d’application sont stockées du point de vue de la manipulation des données | Modifier ou supprimer des éléments dans toutes les collections de sites | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| User.Read.All | les deux | les données de configuration d’application sont stockées du point de vue de la manipulation des données | Lire tous les utilisateurs&#8217; profils complets | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Oui, l’e-mail de l’utilisateur et l’id locataire apparaîtront dans les journaux. Les journaux sont stockés dans un emplacement sécurisé et seul le personnel autorisé peut y accéder pendant le dépannage. Les journaux seront archivés après 60 jours à des fins d’audit de sécurité et seront supprimés au bout d’un an.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données de l’application sont stockées dans Azure SQL Database et stockage Azure. Les SQL azuréens et stockage Azure cryptage sont activés.
Seuls les administrateurs autorisés peuvent accéder aux données. MFA est nécessaire pour que les administrateurs se connectent. Les opérations sont vérifiées. La liste blanche ip est également utilisée pour restreindre l’accès aux données.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

