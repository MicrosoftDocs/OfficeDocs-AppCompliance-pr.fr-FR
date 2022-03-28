---
title: Informations d’application pour Zoho CRM par Zoho Corporation Pvt Ltd
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Zoho CRM, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cf56e9462093336c45902e3c368b4d8498f7a499
ms.sourcegitcommit: d8a3d237c4bd435183b9ce95c316b4d7ce9d7201
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/23/2022
ms.locfileid: "63773445"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Zoho Corporation Pvt Ltd à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Zoho CRM |
| ID | WA104382094 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Zoho Corporation Pvt Ltd |
| URL du site web partenaire | [https://www.zoho.com/](https://www.zoho.com/) |
| URL de la Teams d’informations sur l’application | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| URL de la politique de confidentialité | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL des conditions d’utilisation | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Zoho Corporation Pvt Ltd sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | délégué | L’ID de dossier de calendrier est stocké pour synchroniser les contacts de Zoho CRM avec Microsoft &amp; , et inversement. Les informations de calendrier telles event_name, event_location, participant_details sont stockées. | Permet à l’utilisateur de synchroniser des événements Office365 avec Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | délégué | L’ID du dossier contacts est stocké pour synchroniser les contacts de Zoho CRM avec Microsoft &amp; , et inversement. Les informations de contact telles first_name, last_name, l’adresse e-mail sont stockées. | Permet à l’utilisateur de synchroniser les contacts Office365 avec Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | délégué |  | Permet à l’utilisateur d’importer le fichier Office365 dans Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | délégué |  | Permet à l’utilisateur d’importer le fichier Office365 dans Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | délégué | UserPrincipalName est stocké pour l’identification de l’utilisateur | Permet à l’utilisateur d’importer le fichier Office365 dans Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | délégué | Propriétés utilisateur telles que first_name, last_name, adresse e-mail. | Lire les profils de base de tous les utilisateurs | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | délégué | UserPrincipaName est stocké pour le retrait de l’utilisateur | Afficher l’adresse e-mail de l’utilisateur | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | délégué |  | Gérer l’accès aux données auxquelles vous avez accordé l’accès | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profil | délégué |  | Afficher le profil de base de l’utilisateur | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous ne collectons pas d’EUII/PII dans la télémétrie et les journaux. Nous avons mis en place des scripts pour rechercher et alerter la résolution de ces données visibles

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Le client peut sélectionner les données qui doivent être chiffrées via EAR (Chiffrement au repos) avec des restrictions de sécurité. Les mots de passe sont hachés par défaut. L’accès logique aux serveurs est fourni par le &amp; biais d’un réseau dédié isolé et est hautement sécurisé et


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

