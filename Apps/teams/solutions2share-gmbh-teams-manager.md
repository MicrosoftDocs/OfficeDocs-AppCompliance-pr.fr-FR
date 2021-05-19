---
title: Informations d’application Teams manager par Solutions2Share GmbH
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Teams Manager, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f941df5497b74f3558a56c0407456b42f3b2095d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552765"
---
# <a name="teams-manager"></a>Gestionnaire Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Solutions2Share GmbH à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Gestionnaire Teams |
| ID | WA200000764 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Solutions2Share GmbH |
| URL du site web partenaire | [https://www.teams-manager.com](https://www.teams-manager.com) |
| URL de la politique de confidentialité | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| URL des conditions d’utilisation | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Solutions2Share GmbH sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | les deux | Nous stockons le TenantID et TeamId pour cartographier les modèles.  | Autoriser l’inscription Teams et aussi créer Teams. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| Notes.ReadWrite.All | application | Aucune | Permet à l’application d’ajouter des ordinateurs portables à une équipe approuvée. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read | Délégué | Aucune | Permet à l’utilisateur de se connecter et donne à l’application l’accès à son UPN pour activer la connexion silencieuse. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read.All | les deux | Nous sauvons l’id de l’utilisateur qui est entré dans la section approbation / admin. | Énumérez tous les utilisateurs pour les afficher dans le cueilleur de personnes dans l’application. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.ReadBasic.All | Délégué | Aucune | Énumérez tous les utilisateurs pour les afficher dans le cueilleur de personnes dans l’application. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Nous nous connectons à Azure Log Analytics et utilisons leurs stratégies d’archivage et de conservation.
Nous en connectons l’id locataire et l’id de l’équipe pour identifier les problèmes et aider les clients à résoudre les problèmes.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Nous avons un processus de conformité et d’exploitation pour le contrôle d’accès. Toutes les données et jetons liés à l’utilisateur sont cryptés. Les données sont stockées dans un Azure SQL Database. Nous utilisons le pare-feu pour autoriser uniquement les connexions à partir d’ip spécifiques (plages IP protégées entre les systèmes). Nous avons activé la gestion de l’accès privilégié (PMA) au sein d’Azure.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

