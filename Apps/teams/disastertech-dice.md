---
title: Informations d’application pour DisasterTech DICE par DisasterTech
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour DisasterTech DICE, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d8eec2ad9c7047a33dae446943c3ab2d934cc78c
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525708"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par DisasterTech à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | DisasterTech DICE |
| ID | WA200001909 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | DisasterTech |
| URL du site web partenaire | [https://www.disastertech.com](https://www.disastertech.com) |
| URL de la politique de confidentialité | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| URL des conditions d’utilisation | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par DisasterTech sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | Adresse de messagerie de l’utilisateur stockée pour l’établissement des droits d’accès et nom d’utilisateur pour identifier les utilisateurs par leur nom | Permet à l’utilisateur de se connecter et donne à l’application accès à son UPN pour activer la connexion silencieuse, ainsi que Teams connexion, également pour établir des noms d’utilisateurs et des adresses e-mail. | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| email | délégué | Aucun | Requis pour les Teams'Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| offline_access | délégué | Aucun | Requis pour les Teams'Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| openid | délégué | Aucun | Requis pour les Teams'Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| profil | délégué | Aucun | Requis pour Teams l' sign-on unique. | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous stockons le nom d’utilisateur, le prénom et le nom dans une base de données PostgreSQL hébergée par Azure pour permettre aux utilisateurs de collaborer dans l’application. Les contrôles sont que seuls les employés de la technologie d’urgence ont un accès direct à la base de données. Lorsqu’un utilisateur est supprimé de l’application, nous archiveons les informations. Les utilisateurs conservent le droit de supprimer leurs données personnelles du système à tout moment. Toutefois, la suppression de ces informations interdira également leur utilisation de l’application.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données d’application sont stockées dans une base de données PostgreSQL dans Azure qui est chiffrée au repos. Aucun utilisateur n’a un accès direct à la base de données ou à l’API principale. Tous les appels d’API sont protégés par un jeton d’accès Active Directory.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

