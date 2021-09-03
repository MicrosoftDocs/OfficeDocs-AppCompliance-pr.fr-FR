---
title: Informations d’application pour WorkInSync par MoveInSync
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour WorkInSync, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c3976dcaddcc5121b58cd65836b19df1f057e79b
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873803"
---
# <a name="workinsync"></a>WorkInSync

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/4e00663a-be72-4de1-a163-269a477a7a6e" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002974" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par MoveInSync à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | WorkInSync |
| ID | WA200002974 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | MoveInSync |
| URL du site web partenaire | [https://www.workinsync.io](https://www.workinsync.io) |
| URL de la Teams d’informations sur l’application | [https://www.workinsync.io/teams-app-for-workinsync/](https://www.workinsync.io/teams-app-for-workinsync/) |
| URL de la politique de confidentialité | [https://www.workinsync.io/privacy-policy/](https://www.workinsync.io/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.workinsync.io/terms-and-condition/](https://www.workinsync.io/terms-and-condition/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par MoveInSync sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | délégué | 1. Pour obtenir les détails transitifs des membres du groupe. Ils sont utilisés dans l’onglet Activité de l’équipe lorsqu’ils sont installés dans le contexte du canal. 2. Pour obtenir la liste des détails du profil utilisateur des &amp;  utilisateurs de l’organisation. Ceux-ci sont utilisés lorsque l’onglet Activité d’équipe est installé dans un contexte personnel, comme un retour pour afficher l’aperçu de collègues en cas d’échec de l’API de personnes (utilisateurs non outlook) | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| People.Read | délégué | Pour que les personnes les plus liées à l’utilisateur connecté s’affiche dans l’onglet Activité d’équipe sont installées dans le contexte personnel. | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read | délégué | Pour obtenir des informations de présence d’une liste d’utilisateurs dans l’onglet Activité d’équipe dans le contexte personnel et de canal | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read.All | délégué | Pour obtenir des informations de présence d’une liste d’utilisateurs dans l’onglet Activité d’équipe dans le contexte personnel et de canal | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.Read.All | application | Permet d’obtenir les informations du gestionnaire de rapports d’un utilisateur pour envoyer des notifications de réservation et d’enregistrement/checkout au responsable | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.ReadBasic.All | délégué | Utilisé pour lire la photo de profil d’un employé | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| email | délégué | Nécessaire pour obtenir un jeton DSO à l’aide Teams bibliothèque cliente | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| offline_access | délégué | Nécessaire pour obtenir un jeton DSO à l’aide Teams bibliothèque cliente | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| openid | délégué | Nécessaire pour obtenir un jeton DSO à l’aide Teams bibliothèque cliente | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| profil | délégué | Nécessaire pour obtenir un jeton DSO à l’aide Teams bibliothèque cliente | Aucun | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. Nous lisons l’adresse e-mail de l’employé (nom d’utilisateur principal) pour la faire correspondre à la liste des utilisateurs inscrits avec WorkInSync.  | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données ne sont pas partagées avec ou stockées dans les systèmes partenaires. Tous les magasins de données sont entièrement propriété et géré par WorkInSync seul.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par MoveInSync sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Authentification multifacteur |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/><br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
