---
title: Informations d’application pour SalesTim par SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations disponibles sur la sécurité et la conformité pour SalesTim, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9094f50723c7094f895d21f8a9569dedbb5863b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553915"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur le: Octobre 27, 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SalesTim à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | SalesTim |
| ID | WA200001393 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | SalesTim |
| URL du site web partenaire | [https://www.salestim.com](https://www.salestim.com) |
| URL de la politique de confidentialité | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| URL des conditions d’utilisation | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par SalesTim sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Délégué | NON | Permettez à l’application d’installer et de mettre à jour ses propres paquets dans le catalogue d’applications d’entreprise. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Délégué | Nous&#8217;stocker uniquement des iD utilisateurs, et non des données de profil. | Permet à un utilisateur de sélectionner d’autres utilisateurs à divers endroits de l’application, comme la sélection des approbateurs dans un flux de travail. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Délégué | Nous&#8217;de stocker uniquement des groupes/équipes, nous&#8217;pas stocker le contenu des groupes/équipes. | Permet à l’application de créer des groupes, de lire toutes les propriétés de groupe et les adhésions pour le compte de l’utilisateur connecté. En outre, elle permet aux propriétaires de groupes de gérer leurs groupes et aux membres de groupes de mettre à jour le contenu des groupes. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Délégué | Nous&#8217;les métadonnées de cette action, telles que la date de notification, le destinataire (ID uniquement), demander une pièce d’identité. | Permet à l’application d’envoyer des e-mails de notification par exemple lors d’un workflow d’approbation. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Délégué | Nous utilisons certains services Azure pour stocker des données, en particulier Redis sur Azure et Cosmos DB | Permet à l’application de gérer les lecteurs (fichiers et dossiers) associés à une équipe, lors d’un processus de provision de l’équipe. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Délégué | Nous&#8217;stocker uniquement des iD utilisateurs, et non des données de profil. | Permet à l’application de lire l’ensemble complet des propriétés de profil, des rapports et des gestionnaires de tout utilisateur. Il est utilisé en particulier pendant le processus de ciblage de l’audience, pour filtrer certains contenus en fonction du profil utilisateur actuel. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| hors ligneaccess | Délégué | Non | Permet à l’application d’effectuer certaines opérations et actions de fond en tant qu’utilisateur. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Nous utilisons Intercom comme principale application de support. L’Interphone peut contenir des informations de base sur le profil de l’utilisateur, telles que décrites ici : https://developers.salestim.com/platform/datamanagement.html#support-data |  | Nous utilisons les API GitHub générer automatiquement des problèmes à partir de notre environnement de production. Nous stockons également quelques journaux techniques dans les GitHub (comme décrit ici: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Ces problèmes et journaux peuvent contenir certaines informations de base sur le profil de l’utilisateur. Ces problèmes et journaux sont automatiquement supprimés tous les 15 jours. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Toutes les données collectées sont décrites ici https://developers.salestim.com/platform/datamanagement.html#application-data : comme décrit, les journaux sont temporairement stockés pendant 15 jours puis supprimés automatiquement.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>La plupart des données sont stockées dans Azure Cosmos DB.
L’accès à l’environnement de production est limité à deux personnes, et ces comptes admin sont appliqués par l’AMF.
Ces comptes sont dédiés et différents de nos comptes d’entreprise.
Les données sont cryptées au repos dans tous les services Azure que nous utilisons.
Les déploiements vers les environnements de production sont automatisés par l’intermédiaire d’une branche protégée dédiée dans GitHub environnement, où seulement deux personnes peuvent approuver les modifications.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

