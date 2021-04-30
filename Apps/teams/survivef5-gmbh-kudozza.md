---
title: Informations sur l'application pour Kudozza par surviveF5
ms.author: elmalova
author: elenamalova
ms.date: 03/10/2021
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour Kudozza, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5c6cc9153dc72d8f14140536c1aa91d5315d1660
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094126"
---
# <a name="kudozza"></a>Kudozza

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 10, 2021</p>

* <a href="https://teams.microsoft.com/l/app/61a58a9f-3474-4d14-bda6-6547194a7381" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002599" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par surviveF5 Contrôleh à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Kudozza |
| ID | WA200002599 |
| Fonctionnalités | Bot, Onglet, Extension de la messagerie |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | surviveF5 GmbH |
| URL du site web partenaire | [https://www.kudozza.com](https://www.kudozza.com) |
| URL de la Teams d'informations sur l'application | [https://kudozza.com](https://kudozza.com) |
| URL de la politique de confidentialité | [https://www.kudozza.com/privacy](https://www.kudozza.com/privacy) |
| URL des conditions d'utilisation | [https://www.kudozza.com/terms](https://www.kudozza.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par surviveF5 Contrôleh sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n'utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d'OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS | userId, teamId, tenantId, username | Le service et la base de données sont hébergés dans AWS.  |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d'identification de l'utilisateur final (EUII) : la liste (prénom, nom, nom d'affichage, adresse e-mail) d'un membre d'une équipe ou d'une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l'accès à EUII ?**  | **L'EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l'EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Kudos sont envoyés à d'autres personnes et le message doit être renvoyé fréquemment. Un classement est également fourni, ce qui rend nécessaire le magasinage des noms et des ID des utilisateurs à l'aide de l'application Kudozza. | userid, username | Kudos sont envoyés à d'autres personnes et le message doit être renvoyé fréquemment. Un classement est également fourni, ce qui rend nécessaire le magasinage des noms et des ID des utilisateurs à l'aide de l'application Kudozza. |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>tenantId, teamId, userId. La stratégie de rétention est de 14 jours.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Par DPA. Stratégies utilisateur d'audit et d'ent.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36547' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36547" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d'identité

Ces informations ont été fournies par surviveF5 Contrôleh sur la façon dont cette application gère l'authentification, l'autorisation, les meilleures pratiques d'inscription d'application et d'autres critères d'identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d'identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft'intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d'authentification Microsoft) pour l'authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d'accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l'location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu'est-ce que vous évitez d'utiliser ? | - URIs de redirection générique,
<br />
- OAuth2 implicit Flow, unless required for a SPA
<br />
- Flux d'informations d'identification du mot de passe du propriétaire de la ressource (ROPC) | | Votre application expose-t-elle des API web ? | Oui, | | Votre modèle d'autorisation autorise-t-il uniquement les appels à réussir si l'application cliente reçoit le consentement approprié ? | Oui, | | Votre application utilise-t-elle les API d'aperçu ? | Aucun | | Votre application utilise-t-elle des API dépréciées ? | Aucun |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
