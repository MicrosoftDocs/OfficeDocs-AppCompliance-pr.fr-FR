---
title: Informations sur l’application pour Lacast par Technologies Openmind Inc, Les
ms.author: elmalova
author: elenamalova
ms.date: 07/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pourCast, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 714db08e839b60403a567b2cab1af888c4cb7b6f
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283624"
---
# <a name="berrycast"></a>Berrycast

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c7cde650-1e32-11eb-af14-639b3a7d6491" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002798" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Technologies Openmind Inc, Les à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Berrycast |
| ID | WA200002798 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Technologies Openmind Inc, Les |
| URL du site web partenaire | [https://www.berrycast.com](https://www.berrycast.com) |
| URL de la politique de confidentialité | [https://www.berrycast.com/privacy-policy](https://www.berrycast.com/privacy-policy) |
| URL des conditions d’utilisation | [https://www.berrycast.com/terms-of-use](https://www.berrycast.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Technologies Openmind Inc, les informations sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| People.Read | délégué | Pour obtenir tous les contacts utilisateur | L’e-mail, le nom de famille, le nom et l’image des contacts sont stockés pour fournir un accès rapide au partage des enregistrements | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| User.Read | délégué | Pour identifier l’utilisateur avec des informations de base (prénom, nom et image) | Pour afficher le prénom. nom et image dans l’application | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| email | délégué | Pour identifier l’utilisateur | Pour identifier l’utilisateur pour la journalisation et envoyer une notification | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| offline_access | délégué | Gérer l’accès aux données auxquelles vous avez accordé l’accès | N/A | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| openid | délégué | Pour identifier l’utilisateur | Pour identifier l’utilisateur pour la journalisation | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, Intercom, MixPanel, Amplitude | email, user unique identification, firstname, lastname  | Pour traiter le paiement sécurisé, pour effectuer une campagne marketing, pour avoir un service clientèle efficace et pour suivre l’analyse utilisateur pour améliorer le produit |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Email, firstname, lastname and we remove all data if the user delete his account 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous supprimons toutes les données relatives à un utilisateur s’il supprime son compte.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Technologies Openmind Inc. Moins sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Non |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
