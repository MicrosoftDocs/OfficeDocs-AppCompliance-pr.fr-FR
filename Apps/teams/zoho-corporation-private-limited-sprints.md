---
title: Informations d’application pour Zoho Sprints par Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Zoho Sprints, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ab4f76f0563b92d9e5ca6129ffba013069db37f1
ms.sourcegitcommit: 9199fd569c5e7c5dd338abd87428c94798a22352
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/23/2022
ms.locfileid: "63753138"
---
# <a name="zoho-sprints"></a>Zoho Sprints

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/153059f1-912e-45d6-a13a-037675d66974" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000188" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Zoho Corporation Private Limited à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Zoho Sprints |
| ID | WA200000188 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Zoho Corporation Private Limited |
| URL du site web partenaire | [https://www.zoho.com/sprints/](https://www.zoho.com/sprints/) |
| URL de la politique de confidentialité | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL des conditions d’utilisation | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Zoho Corporation Private Limited sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | délégué | L’ID du dossier alendar est stocké pour synchroniser les contacts entre Zoho Sprints et Microsoft &amp; , vice-versa. |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| Contacts.ReadWrite | délégué | L’ID du dossier contacts est stocké pour synchroniser les contacts. |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| Files.Read.All | délégué |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| Files.Read.Selected | délégué | UserPrincipalName est stocké pour l’identification de l’utilisateur. | Lire des fichiers sélectionnés par l’utilisateur | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| User.Read | délégué |  | Activer la connexion et lire le profil utilisateur | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| User.ReadBasic.All | délégué |  | Autoriser les utilisateurs à importer des utilisateurs Office365 dans Zoho Sprints. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| email | délégué |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| offline_access | délégué |  | Gérer l’accès aux données auxquelles vous avez accordé l’accès | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous ne collectons pas d’EUII/PII dans la télémétrie et les journaux. Nous avons mis en place des scripts pour rechercher et alerter la résolution de ces données visibles.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Le client peut sélectionner les données qui doivent être chiffrées via EAR (Chiffrement au repos) avec des restrictions de sécurité. Les mots de passe sont hachés par défaut. L’accès logique aux serveurs est fourni par le &amp; biais d’un réseau dédié isolé et est hautement sécurisé et


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

