---
title: Informations d’application pour jobPts par Semos Cloud Cloud
ms.author: elmalova
author: elenamalova
ms.date: 07/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour JobPts, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 22c80e919a07b30f6b65dc055a514e9ce2a1eefc
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59280629"
---
# <a name="jobpts"></a>JobPts

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 7, 2021</p>

* <a href="https://teams.microsoft.com/l/app/601a47bc-f201-4398-a0cb-593ea081f265" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001849" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Semos Cloud Cloud Cloud à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | JobPts |
| ID | WA200001849 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Semos Cloud Soultions |
| URL du site web partenaire | [https://semoscloud.com](https://semoscloud.com) |
| URL de la Teams d’informations sur l’application | [https://semoscloud.com/product/jobpts](https://semoscloud.com/product/jobpts) |
| URL de la politique de confidentialité | [https://semoscloud.com/privacy-policy/](https://semoscloud.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://semoscloud.com/terms-of-use/](https://semoscloud.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par semos Cloud Cloud Cloud Sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | Lire les informations de base de l’entreprise | Aucune donnée n’est stockée | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |
>| email | délégué | Utilisé pour le mappage des utilisateurs AzureAD avec des utilisateurs dans l’outil JobPts | Aucune donnée n’est stockée | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |
>| offline_access | délégué | Maintenir l’accès aux données | Aucune donnée n’est stockée | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |
>| openid | délégué | Pour que les utilisateurs puissent se connecter avec leur compte de travail | Aucune donnée n’est stockée | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |
>| profil | délégué | Pour pouvoir voir les informations de base de l’utilisateur (nom d’utilisateur) | Aucune donnée n’est stockée | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Obtention d’informations sur l’utilisateur qui communique avec le bot | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous ne transférons aucune donnée vers les systèmes des partenaires

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Semos Cloud Cloud Sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Authentification multifacteur, restriction des emplacements utilisateur et des plages IP |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
