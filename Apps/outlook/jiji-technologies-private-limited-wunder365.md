---
title: Informations sur l’application pour Wunder365 par JiJi Technologies Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Wunder365, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f5c07b646cd3d23d6a1fbda2c9bd5ef7b4973f32
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281716"
---
# <a name="wunder365"></a>Wunder365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 15, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000391" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par JiJi Technologies Private Limited à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Wunder365 |
| ID | WA200000391 |
| Office 365 clients pris en charge | Outlook 2016 ou ultérieure sur Windows, Outlook 2016 ou une ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | JiJi Technologies Private Limited |
| URL du site web partenaire | [https://www.jijitechnologies.com](https://www.jijitechnologies.com) |
| URL de la politique de confidentialité | [https://www.wunder365.com/outlook-addin-privacy-policy](https://www.wunder365.com/outlook-addin-privacy-policy) |
| URL des conditions d’utilisation | [https://www.wunder365.com/terms-of-service](https://www.wunder365.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par JiJi Technologies Private Limited sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | délégué | Aucune donnée stockée. | Pour obtenir/mettre à jour les tâches du Planificateur, publiez les mises à jour de tâches dans le canal d’équipe | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| Mail.Send | délégué | Aucune donnée stockée. | Autoriser l’application à envoyer des notifications par courrier électronique aux utilisateurs | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| offline_access | délégué | Aucune donnée stockée. | Pour maintenir la session de l’utilisateur. | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| openid | délégué | Aucune donnée stockée. | Permet aux utilisateurs de se connecter avec un compte d’organisation | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| profil | délégué | UPN, ID utilisateur, ID de messagerie, ID de locataire pour la vérification de licence, licence gratuite. | Permet aux utilisateurs de se connecter avec un compte d’organisation | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous nous connectons à Azure Application Informations. Nous consignons l’ID de locataire et l’identifiant de messagerie de l’utilisateur pour identifier les problèmes et aider les clients à résoudre les problèmes.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Toutes les applications Web et Stockage ressources sont situées dans un abonnement qui n’est pas connecté à notre entreprise AAD avec uniquement des administrateurs qui ont accès aux ressources. 2FA est requis pour ces administrateurs. 


#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par JiJi Technologies Private Limited sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Exiger une authentification multifacteur pour les utilisateurs ayant des rôles d’administration, exiger une authentification multifacteur pour les tâches de gestion Azure, bloquer les ouvertures de signature pour les utilisateurs qui tentent d’utiliser des protocoles d’authentification hérités, exiger des emplacements fiables pour l’inscription à l’authentification multifacteur Azure AD, bloquer ou accorder l’accès à partir d’emplacements spécifiques, Blocage du comportement de la signature à risque |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
