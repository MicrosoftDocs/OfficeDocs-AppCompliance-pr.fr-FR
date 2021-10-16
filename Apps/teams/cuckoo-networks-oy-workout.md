---
title: Informations sur l’application pour les programmes d’entreprise Coooo par Coo Networks Oy
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour CooOo, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b8a661024c7dba8bc782f97db23456bedf8a579b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412474"
---
# <a name="cuckoo-workout"></a>Entraînement du coucou

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/71138876-8738-4935-95b6-ae7c2fbe4e54" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002750" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Coooo Networks Oy à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Entraînement du coucou |
| ID | WA200002750 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Cuckoo Networks Oy |
| URL du site web partenaire | [https://cuckooworkout.com](https://cuckooworkout.com) |
| URL de la Teams d’informations sur l’application | [https://cuckooworkout.com](https://cuckooworkout.com) |
| URL de la politique de confidentialité | [https://cuckooworkout.com/service-privacy-policy/](https://cuckooworkout.com/service-privacy-policy/) |
| URL des conditions d’utilisation | [https://cuckooworkout.com/terms-of-service/](https://cuckooworkout.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Coo Networks Oy sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | Nom d’utilisateur, ID de client pour les communications et le mappage d’abonnement | Nom d’utilisateur, ID de client pour les communications et le mappage d’abonnement | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| email | délégué | Courrier électronique requis pour l’authentification et la prise en charge | Courrier électronique requis pour l’authentification et la prise en charge | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| offline_access | délégué | N/A | N/A | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| openid | délégué | ID utilisateur pour l’authentification | ID utilisateur pour l’authentification | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| profil | délégué | ID de profil pour l’authentification | ID de profil pour l’authentification | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Amazon AWS | ID client | Pour faire correspondre l’utilisateur au plan d’abonnement de l’entreprise  |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Suivi de l’authentification et de la progression | Teams’utilisateur, ID de client | Suivi de l’authentification et de la progression |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Conversations, vues vidéo, paramètres utilisateur, langue. Stratégies de rétention et de suppression conformément au R GDPR.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Le super administrateur peut effectuer la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41840' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41840" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Coo Networks Oy sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

