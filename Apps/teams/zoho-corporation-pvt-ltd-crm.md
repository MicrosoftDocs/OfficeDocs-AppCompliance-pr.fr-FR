---
title: Informations sur les demandes de Zoho CRM par Zoho Corporation Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Zoho CRM, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5448307eeccd20e77b25282f299b52b094077b82
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550504"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Zoho Corporation Pvt Ltd à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Zoho CRM |
| ID | WA104382094 WA104382094 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Zoho Corporation Pvt Ltd |
| URL du site web partenaire | [https://www.zoho.com/](https://www.zoho.com/) |
| URL de la page Teams’informations d’application | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| URL de la politique de confidentialité | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL des conditions d’utilisation | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Zoho Corporation Pvt Ltd sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Délégué | Calendar Folder Id est stocké pour synchroniser les contacts de Zoho CRM à Microsoft &amp; vice-versa. Les informations de calendrier event_name, event_location, participant_details sont stockées. | Permet à l’utilisateur de synchroniser les événements Office365 avec Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | Délégué | Contacts Folder Id est stocké pour synchroniser les contacts de Zoho CRM à Microsoft &amp; vice-versa. Les coordonnées comme first_name, last_name, adresse e-mail sont stockées. | Permet à l’utilisateur de synchroniser les contacts Office365 avec Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | Délégué |  | Permet à l’utilisateur d’importer le fichier Office365 à Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | Délégué |  | Permet à l’utilisateur d’importer le fichier Office365 à Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Délégué | UserPrincipalName est stocké pour identification de l’utilisateur | Permet à l’utilisateur d’importer le fichier Office365 à Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Délégué | Propriétés utilisateur comme first_name, last_name, adresse e-mail. | Lire les profils de base de tous les utilisateurs | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Délégué | UserPrincipaName est stocké pour l’indentification de l’utilisateur | Afficher l’adresse e-mail de l’utilisateur | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Délégué |  | Gérer l’accès aux données auxquelles vous avez accordé l’accès | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profil | Délégué |  | Afficher le profil de base de l’utilisateur | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Nous ne recueillons pas EUII / PII dans la télémétrie et les journaux. Nous avons des scripts en place pour rechercher et alerter pour corriger ces données étant visibles

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Le client peut sélectionner les données qui doivent être cryptées via EAR (Encryption At Rest) avec des restrictions certaat. Les mots de passe seront hachages par défaut. L’accès logique aux serveurs est assuré par un &amp; réseau dédié isolé et est hautement sécurisé et


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

