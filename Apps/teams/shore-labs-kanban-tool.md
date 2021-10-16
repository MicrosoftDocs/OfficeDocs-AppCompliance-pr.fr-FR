---
title: Informations sur l’application pour l’outil Kanban par labs Labs
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour l’outil Kanban, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7422dcff9386dbb64599660eea58941d2a862b13
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413396"
---
# <a name="kanban-tool"></a>Kanban Tool

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b3c15d4f-1972-4836-a1eb-7575dd56a17e" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002121" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Labs Labs à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Kanban Tool |
| ID | WA200002121 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Shore Labs |
| URL du site web partenaire | [https://www.shorelabs.com](https://www.shorelabs.com) |
| URL de la Teams d’informations sur l’application | [https://kanbantool.com](https://kanbantool.com) |
| URL de la politique de confidentialité | [https://kanbantool.com/policy/privacy](https://kanbantool.com/policy/privacy) |
| URL des conditions d’utilisation | [https://kanbantool.com/policy/terms-of-service](https://kanbantool.com/policy/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par labs Labs sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | délégué | Adresse de messagerie de l’utilisateur pour la communication, la correspondance d’identité et la remise des notifications. | Adresse de messagerie. | [4e820d60-9e62-403c-accd-857b987cc13c](https://docs.microsoft.com/microsoft-365-app-certification/azure/4e820d60-9e62-403c-accd-857b987cc13c) |
>| Team.ReadBasic.All | délégué | Identificateurs et noms des équipes dont l’utilisateur est un membre direct. Ils sont utilisés pour affecter automatiquement des utilisateurs à des groupes corrects dans l’outil Kanban. | Les identificateurs d’équipe et les noms dont l’utilisateur est un membre direct sont mappés à des groupes dans l’outil Kanban. Cela permet de gérer l’accès basé sur les groupes et de partager des Boards Kanban entre différentes équipes dans la même organisation. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| User.Read | délégué | Informations de base sur l’entreprise des utilisateurs inscrits. Il est utilisé pour remplir les détails du compte des nouveaux comptes et pour reconnaître les utilisateurs qui appartiennent à votre organisation afin de fournir la fonctionnalité Sign-On unique. | Nom et identificateur Microsoft unique de votre organisation. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| offline_access | délégué | Autorise la fonctionnalité « Se connecter avec Microsoft » et la synchronisation des données à qui vous avez accordé l’accès à l’application, lors de la connexion de l’utilisateur. | Conservez l’accès aux données à qui vous avez accordé l’accès. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| openid | délégué | Ouvrez les jetons d’ID qui permettent aux utilisateurs de se connectent à l’application avec leurs comptes professionnels ou scolaires via le bouton « Se connectez avec Microsoft ». | Identificateur immuable pour le compte d’utilisateur dans le système d’identité Microsoft. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| profil | délégué | Nom d’utilisateur à utiliser pour le repas automatique dans l’outil Kanban et rester synchronisé avec les modifications apportées aux Microsoft Teams. | Nom complet de l’utilisateur. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| L’outil Kanban utilise les sous-processeurs suivants pour les performances de son service : https://kanbantool.com/policy/privacy#appointed-subprocessors |   | Nous utilisons ces tiers pour fournir et maintenir l’infrastructure technique et aider au traitement de facturation et de paiement. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous collectons automatiquement des informations techniques sur votre compte et votre activité dans le service. Ces informations sont stockées dans des fichiers journaux internes et peuvent inclure des données OII et EUII, si elles font partie de l’activité que vous avez réalisée. Nous ne partageons pas de fichiers journaux avec des tiers. L’objectif de la collecte des données du journal est d’obtenir des raisons juridiques et réglementaires, de déterminer la source de toute violation potentielle de la sécurité ou utilisation abusive du service, de limiter le taux de demandes et de profilage des performances.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les administrateurs de comptes ont un accès total, y compris la possibilité de modifier et de supprimer des données personnelles liées à leur compte, et sont les contrôleurs de données réels.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par labs Labs sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | ,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

