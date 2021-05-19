---
title: Informations d’application pour AVA par AvePoint, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour AVA, ses politiques de traitement des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6176bc86a6d382285623d3e3286852afd4a4ff96
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552365"
---
# <a name="ava"></a>AVA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Mars 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/93106045-6f96-41e3-8a9d-694b6bbcac60" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381883" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par AvePoint, Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | AVA |
| ID | WA104381883 WA104381883 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | AvePoint, Inc. |
| URL du site web partenaire | [https://www.avepoint.com](https://www.avepoint.com) |
| URL de la page Teams’informations d’application | [https://www.avepoint.com/support/](https://www.avepoint.com/support/) |
| URL de la politique de confidentialité | [https://www.avepoint.com/privacy-policy](https://www.avepoint.com/privacy-policy) |
| URL des conditions d’utilisation | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par AvePoint, Inc. sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite.Shared | Délégué | Aucune | Rechercher les e-mails de l’utilisateur et déplacer l’e-mail vers un dossier spécifié | 6f30434d-3cfa-4cf8-9810-6fcf79ae750a |
>| User.Read | Délégué |  Jeton d’accès de l’utilisateur - utilisé pour rechercher et restaurer les données de l’utilisateur | Permet à l’utilisateur de se connecter et de donner le jeton d’accès à l’application | 6f30434d-3cfa-4cf8-9810-6fcf79ae750a |
>| User.ReadWrite | Délégué | Nom d’affichage, Nom d’utilisateur, JobTitle, Organisation, Pays, MySiteUrl - enregistrez les informations de base de l’utilisateur qui a utilisé l’application | Obtenez les informations de base du profil de l’utilisateur | 6f30434d-3cfa-4cf8-9810-6fcf79ae750a |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les modules complémentaires intégrés à Microsoft 365 peuvent utiliser d’autres API Microsoft que Microsoft Graph pour recueillir ou traiter des informations organisationnelles identifiables (OII). Énumérez toutes les API Microsoft autres que Microsoft Graph utilisations de cette application.

>| **API** |  **L’ŒIL est-il recueilli?** |  **Quel OII est recueilli?** | **Justification de la collecte de l’ŒII?** | **OII est-il stocké ?** | **Justification pour stocker OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API REST SharePoint | Oui | Recherchez le fichier dans le recyclage du site personnel de l’utilisateur et restaurent ces fichiers. Nécessite allSites.Manage permission. |  | Aucune |  |

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

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

