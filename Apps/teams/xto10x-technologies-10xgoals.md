---
title: Informations sur les applications pour 10xGoals par xto10x Technologies
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour 10xGoals, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 82730906a833ef43df8a3eafaee1111cf6889472
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411359"
---
# <a name="10xgoals"></a>10xGoals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 8, 2021</p>

* <a href="https://teams.microsoft.com/l/app/950aa4fb-0583-4b13-9b5f-bbc92b9cc376" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003122" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par xto10x Technologies à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | 10xGoals |
| ID | WA200003122 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Technologies xto10x |
| URL du site web partenaire | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| URL de la Teams d’informations sur l’application | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| URL de la politique de confidentialité | [https://www.xto10x.com/security/privacy-policy/](https://www.xto10x.com/security/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.xto10x.com/security/terms-of-use/](https://www.xto10x.com/security/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par xto10x Technologies sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | application | Le courrier électronique et l’ID Azure des utilisateurs sont récupérés afin que l’application puisse installer l’application de manière proactive pour tous les utilisateurs de l’organisation.  | Comme cette application nécessite d’abord un abonnement au service 10xGoals, la messagerie électronique de l’utilisateur et l’ID Azure de l’utilisateur sont envoyés au service 10xGoals afin que, lorsqu’une activité se produit sur cet utilisateur, elle puisse envoyer une notification proactive à l’application Teams de l’utilisateur. | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | application | Elle est requise pour que l’application puisse récupérer teamsAppDefinition pour l’administrateur, puis s’installer de manière proactive pour tous les utilisateurs de l’organisation.  | Rien n’est stocké dans la base de données qui est récupérée à partir de cette api. | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 10xGoals, AWS | messagerie de l’utilisateur et AzureId de l’utilisateur.  | Comme cette application nécessite d’abord un abonnement au service 10xGoals, la messagerie électronique de l’utilisateur et l’ID Azure de l’utilisateur sont envoyés au service 10xGoals afin que, lorsqu’une activité est liée à cet utilisateur, le système puisse envoyer une notification proactive à l’utilisateur. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Comme cette application nécessite d’abord un abonnement au service 10xGoals, la messagerie électronique de l’utilisateur et l’ID Azure de l’utilisateur sont envoyés au service 10xGoals afin que, lorsqu’une activité se produit sur cet utilisateur, elle puisse envoyer une notification proactive à l’application Teams de l’utilisateur. | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>TenantId of org is stored to have difference welcome message depending on whether a tenant has granted required permissions or not. Si un client a déjà accordé des autorisations à d’autres utilisateurs de cette organisation, il n’est pas nécessaire de revoir ce flux d’octroi d’autorisations.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>N/A

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par xto10x Technologies sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Non |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

