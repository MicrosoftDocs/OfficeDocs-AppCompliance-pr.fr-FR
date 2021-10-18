---
title: Informations sur l’application pour Apprendre parIviivio
ms.author: elmalova
author: elenamalova
ms.date: 03/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Learn, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c72b5800b40d0a587ebed4e8997d698d9eb5a483
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60432869"
---
# <a name="learn"></a>Apprendre

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 31, 2020</p>

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Leivio à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Apprendre |
| ID | WA200001308 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Witivio |
| URL du site web partenaire | [https://www.witivio.com](https://www.witivio.com) |
| URL de la politique de confidentialité | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| URL des conditions d’utilisation | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Leivio sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | S/O | Nous collectons l’UPN et l’ID AAD pour l’autorisation. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| User.ReadBasic.All | délégué | S/O | Nous collectons l’UPN et l’ID AAD pour l’autorisation. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| openid | délégué | S/O | Nous collectons l’UPN et l’ID AAD pour l’autorisation. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| profil | délégué | S/O | Nous collectons l’UPN et l’ID AAD pour l’autorisation. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Nous utilisons la liste de présence pour : 1) autorisation (accorder l’accès au bot), 2) détecter le prénom pour fournir une UX conviviale, 3) Pour gérer les chatlogs pour l’administrateur d’entreprise du bot | N/A. Ou les bots sont uniquement personnels |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>La télémétrie du bot contient l’UPN et le AAD diagnostics fr ID.
Seuls les administrateurs PROD/Run ont accès à la télémétrie de production. Les journaux sont stockés pendant 90 jours et peuvent être supprimés sur demande sur un support.witivio.com portail dédié ou par courrier électronique dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Leivio utilise uniquement des composants Azure, déployés dans la région Europe du Nord. Nous utilisons les informations sur les applications et Cosmos base de données pour l’analyse et le stockage des données.
Le MFA est utilisé pour tous les utilisateurs, y compris les administrateurs. Les administrateurs ont un compte d’utilisateur (pour la station de travail) et un compte privilégié pour accéder aux ressources Azure.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

