---
title: Informations sur l’application pour isLucid par les contrats UAB
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour isLucid, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7270fa4f4a08ca820d1fe7452dea13fb107f2294
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414901"
---
# <a name="islucid"></a>isLucid

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 9, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a5711b63-5e70-4e4e-b040-0d714b64f684" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002385" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par les contrats UAB à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | isLucid |
| ID | WA200002385 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Contrats UAB |
| URL du site web partenaire | [https://islucid.com](https://islucid.com) |
| URL de la Teams d’informations sur l’application | [https://islucid.com](https://islucid.com) |
| URL de la politique de confidentialité | [https://islucid.com/privacy-policy/](https://islucid.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://islucid.com/eula/](https://islucid.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par les accords UAB Sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calls.AccessMedia.All | les deux | Avec le consentement spécifique d’un utilisateur pour chaque appel séparément (transcription initiée), il accède au flux audio. Le flux audio est transmis à un service de transcription afin que les utilisateurs obtiennent des fonctionnalités supplémentaires. | L’application stocke dans des conteneurs séparés sur Azure (stockage blob et Cosmos DB pour chaque client séparément) transcription et méta-informations associées. Cela est nécessaire pour fournir un accès supplémentaire aux informations d’une réunion pour l’utilisateur, qui a utilisé l’application et qui était dans la réunion spécifique. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Calls.JoinGroupCall.All | les deux | Avec le consentement spécifique d’un utilisateur pour chaque appel séparément (transcription initiée), il accède au flux audio. Le flux audio est transmis à un service de transcription afin que les utilisateurs obtiennent des fonctionnalités supplémentaires. | L’application stocke dans des conteneurs séparés sur Azure (stockage blob et Cosmos DB pour chaque client séparément) transcription et méta-informations associées. Cela est nécessaire pour fournir un accès supplémentaire aux informations d’une réunion pour l’utilisateur, qui a utilisé l’application et qui était dans la réunion spécifique. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Group.ReadWrite.All | les deux | Lorsque l’utilisateur utilise l’intégration avec le Planificateur Microsoft pour créer des tâches à partir de l’appel et les stocker automatiquement dans le Planificateur MS, isLucid collecte pour les groupes, plans et utilisateurs disponibles pour cet utilisateur. Sans cette autorisation, l’utilisateur ne serait pas en mesure de créer une tâche à partir de la transcription à l’aide d’isLucid | Le titre de la tâche, le créateur de tâche, l’timestamp de tâche, la description de tâche sont stockés afin que les utilisateurs peuvent accéder à l’historique des tâches, effectué à partir d’une réunion spécifique. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OnlineMeetings.Read.All | les deux | L’application collecte les titres de réunion afin que les utilisateurs plus tard (lorsque la réunion est terminée) trouvent plus facilement les transcriptions et les tâches précédentes. | Titre de la réunion, timestamp de la réunion, organisateur de la réunion | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Tasks.ReadWrite | les deux | Lorsque l’utilisateur utilise l’intégration avec le Planificateur Microsoft pour créer des tâches à partir de l’appel et les stocker automatiquement dans le Planificateur MS, isLucid collecte pour les groupes, plans et utilisateurs disponibles pour cet utilisateur. Sans cette autorisation, l’utilisateur ne serait pas en mesure de créer une tâche à partir de la transcription à l’aide d’isLucid | Le titre de la tâche, le créateur de tâche, l’timestamp de tâche, la description de tâche sont stockés afin que les utilisateurs peuvent accéder à l’historique des tâches, effectué à partir d’une réunion spécifique. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| User.ReadWrite.All | les deux | Lorsque l’utilisateur utilise l’intégration avec le Planificateur Microsoft pour créer des tâches à partir de l’appel et les stocker automatiquement dans le Planificateur MS, isLucid collecte pour les groupes, plans et utilisateurs disponibles pour cet utilisateur. Sans cette autorisation, l’utilisateur ne serait pas en mesure de créer une tâche à partir de la transcription à l’aide d’isLucid | Le titre de la tâche, le créateur de tâche, l’timestamp de tâche, la description de tâche sont stockés afin que les utilisateurs peuvent accéder à l’historique des tâches, effectué à partir d’une réunion spécifique. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| openid | les deux | ID d’utilisateur et ID de locataire collectés pour fournir Azure Active Directory de connexion à nos utilisateurs | ID utilisateur, ID de locataire pour la gestion des droits supplémentaires | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| hubspot.com | Nom, nom, adresse de messagerie Téléphone nombre d’utilisateurs nouvellement inscrits | Nous utilisons Hubspot CRM pour gérer les informations liées aux ventes |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Le bot permet l’envoi de flux audio au service de transcription. Pour fournir une transcription lisible, nous devons associer l’audio aux utilisateurs (haut-parleurs). Sans fournir de telles transcriptions d’informations, il est inutile | Nom, nom, état s’il s’agit d’un compte invité ou d’un compte Microsoft | Le bot permet l’envoi de flux audio au service de transcription. Pour fournir une transcription lisible, nous devons associer l’audio aux utilisateurs (haut-parleurs). Les informations des participants à la réunion sont également pertinentes pour permettre aux utilisateurs de voir qui ont participé à la réunion. |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Les utilisateurs qui utilisent notre service génèrent des transcriptions. Dans les transcriptions, les participants à la réunion (noms, noms) ont été présentés. Tout peut éventuellement être mentionné au cours de l’appel. Nous stockons ces données pour les utilisateurs tant qu’ils utilisent nos services. Une fois que le client a fini de nous utiliser, dans un délai de 30 jours, nous détruyons toutes les données associées.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous ne contrôlons pas les données sur nos clients lorsque les achats de clients sont pris en compte en tant que solution hébergée. Pour la solution SaaS, nous permettons aux utilisateurs d’annuler l’utilisation de nos services, puis nous supprimons Cosmos DB associée au partenaire. Nous sommes également en train d’envoyer des informations à l’API de conformité

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par les contrats UAB Sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Oui |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

