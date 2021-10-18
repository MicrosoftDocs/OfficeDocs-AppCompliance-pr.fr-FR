---
title: Informations sur l’application de Valdonn par Kickle
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Waldo, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 88766f29eb80c8d9378fc117b42e688db3dff755
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434583"
---
# <a name="waldo"></a>Waldo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 30, 2021</p>

* <a href="https://teams.microsoft.com/l/app/1d041f16-ab49-4627-bfda-6b60ad2cab6a" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003139" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Kickle to Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Waldo |
| ID | WA200003139 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Kickle |
| URL du site web partenaire | [https://hellowaldo.app](https://hellowaldo.app) |
| URL de la Teams d’informations sur l’application | [https://hellowaldo.app/takeatour/](https://hellowaldo.app/takeatour/) |
| URL de la politique de confidentialité | [https://hellowaldo.app/privacy-policy/](https://hellowaldo.app/privacy-policy/) |
| URL des conditions d’utilisation | [https://hellowaldo.app/terms-and-conditions](https://hellowaldo.app/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Kickle sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | délégué | En fonction de votre historique de conversation, Waldo identifie vos collègues. Cette liste est utilisée par la suite pour vous montrer l’état dans l’affichage Calendrier. | Waldo stocke l’ID utilisateur de chaque collègue. Ces ID sont utilisés pour afficher la liste des collègues avec qui nous sommes utilisés. | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.Read | délégué | Cette autorisation est utilisée par la personne du composant de l’Graph Shared Computer Toolkit | S/O | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.ReadBasic.All | délégué | Cette autorisation est utilisée par la personne du composant de l’Graph Shared Computer Toolkit | S/O | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| offline_access | délégué | Utilisé par l’application pour effectuer des tâches en arrière-plan pour le compte de l’utilisateur (jeton de renouvellement pour l’authentification) | S/O | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| openid | délégué | Requis pour l’authentification | S/O | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>L’organisation peut voir les administrateurs, les contacts administratifs et les contacts techniques à l’aide de https://app.hellowaldo.app/admin-orga-contacts .  L’organisation peut nous contacter hello@kickle.com pour supprimer des informations d’identification personnelle de notre application. Cela peut limiter le service que nous pouvons fournir.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Kickle sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Non |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
