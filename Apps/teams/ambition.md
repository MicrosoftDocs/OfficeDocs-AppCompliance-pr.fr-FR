---
title: Informations sur l’application pour l’application De Quézy
ms.author: elmalova
author: elenamalova
ms.date: 08/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Elle, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 41a69c23e64a1059d99c18511837cb166bcf27a0
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410468"
---
# <a name="ambition"></a>Ambition

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/250ef61a-9fa3-434b-ae2a-0ecbe3f8116b" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003159" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Lee à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Ambition |
| ID | WA200003159 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Ambition |
| URL du site web partenaire | [https://ambition.com](https://ambition.com) |
| URL de la Teams d’informations sur l’application | [https://ambition.com](https://ambition.com) |
| URL de la politique de confidentialité | [https://ambition.com/privacy/](https://ambition.com/privacy/) |
| URL des conditions d’utilisation | [https://ambition.com/pages/terms/](https://ambition.com/pages/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Cette application sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | délégué | Envoyer des notifications de notifications au canal | Nom de l’ID &amp; de canal. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| Group.Read.All | délégué | Configurer une notification de flux de travail Workflow vers un canal particulier au sein d’une équipe. | ID du nom de &amp; l’équipe. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.Read | délégué | Pour identifier l’administrateur qui a autorisé l’application Contrôle | Nom &amp; d’e-mail des utilisateurs, pour synchroniser avec les utilisateurs Dente | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.ReadBasic.All | délégué | Les e-mails de noms &amp; d’utilisateurs, pour synchroniser les utilisateurs avec leurs comptes). | Les e-mails de noms &amp; d’utilisateur sont stockés. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| offline_access | délégué | Pour synchroniser Microsoft Teams données pendant que les utilisateurs sont hors connexion. | Le jeton d’actualisation du jeton d’accès OAuth &amp; est stocké. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| openid | délégué | Cette option est requise pour utiliser la fonctionnalité de signature de Microsoft. | S/O | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://ambition.com/pages/subprocessors/ | Prénom de l’employé, nom, adresse e-mail | Fonctions d’affichage/recherche/filtrage |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| À des fins d’affichage.  | Nomme &amp; les e-mails. | Pour lier les utilisateurs Microsoft à leurs comptes). |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>https://ambition.com/privacy/

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Autorisations d’accès nécessaires.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Cette application sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
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

