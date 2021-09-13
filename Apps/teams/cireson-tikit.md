---
title: Informations sur l’application pour Tikit par Luison
ms.author: elmalova
author: elenamalova
ms.date: 05/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Tikit, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c17273ad8e2cdc9bd2f60ce5a3157f1f8473bb88
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281355"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 4, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Ce dernier à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Tikit |
| ID | WA200002602 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Cireson |
| URL du site web partenaire | [https://tikit.ai](https://tikit.ai) |
| URL de la Teams d’informations sur l’application | [https://tikit.ai](https://tikit.ai) |
| URL de la politique de confidentialité | [https://tikit.ai/privacy-statement/](https://tikit.ai/privacy-statement/) |
| URL des conditions d’utilisation | [https://tikit.ai/terms-service/](https://tikit.ai/terms-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Cette application sur la façon dont cette application collecte et stocke les données organisationnelles, ainsi que sur le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Device.Read | application | Informations de graphique utilisateur utilisées pour l' sign-on unique, via la communication du bot teams  | Nous stockons les rôles d’utilisateur, le nom de famille, le nom donné, le courrier électronique, l’ID AAD, Teams’utilisateur. Cette information est utilisée pour l’authentification d’application, la sécurité, RBAC, l’intégration des équipes, les notifications d’équipes et le mappage des relations utilisateur   | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| Directory.AccessAsUser.All | délégué | Noms de groupes et rôles pour RBAC | Nom de &amp; rôle de nom de groupe, doit fournir un contrôle d’accès mappé sécurisé. | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| Directory.Read.All | délégué | Noms de groupes et rôles pour RBAC | Nom de &amp; rôle de nom de groupe, doit fournir un contrôle d’accès mappé sécurisé. | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| Group.Read.All | les deux | Noms de groupes et rôles pour RBAC | Noms de groupes et rôles pour RBAC | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| User.Read | délégué | Rôles utilisateur, nom de famille, nom donné, e-mail, ID AAD, Teams’utilisateur, utilisé pour l’authentification  | Rôles utilisateur, nom de famille, nom donné, e-mail, ID AAD, Teams’utilisateur, utilisé pour l’authentification  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| User.Read.All | application | Rôles utilisateur, nom de famille, nom donné, e-mail, ID AAD, Teams’utilisateur, utilisé pour l’authentification  | Rôles utilisateur, nom de famille, nom donné, e-mail, ID AAD, Teams’utilisateur, utilisé pour l’authentification  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| User.ReadBasic.All | délégué | Rôles utilisateur, nom de famille, nom donné, e-mail, ID AAD, Teams’utilisateur, utilisé pour l’authentification  | Rôles utilisateur, nom de famille, nom donné, e-mail, ID AAD, Teams’utilisateur, utilisé pour l’authentification  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| email | délégué | Courrier électronique de l’utilisateur utilisé pour la connexion et l’identification associée des entités associées. &quot;Utilisateur affecté&quot; | Courrier électronique de l’utilisateur utilisé pour la connexion et l’identification associée des entités associées. &quot;Utilisateur affecté&quot; | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| openid | délégué | utilisé pour l’authentification via MSAL selon les besoins  | utilisé pour l’authentification via MSAL selon les besoins  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| profil | délégué | utilisé pour l’authentification via MSAL selon les besoins  | utilisé pour l’authentification via MSAL selon les besoins  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| QnA Maker | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Nom et e-mail du demandeur de ticket pour les relations d’entité &quot; utilisateur&quot;  | Nom et e-mail  | for user entity relationships &quot; Ticket Requestor&quot;  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous stockons le nom de la société, l’ID de locataire, le courrier électronique, l’ID client du bot dans les informations d’application, avec une stratégie de rétention de 30 dat.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous n’avons pas de données dans les systèmes partenaires.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies parFactson sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Authentification multifacteur, autoriser uniquement les appareils inscrits à Intune à accéder à des services spécifiques, limiter les emplacements utilisateur et la plage d’adresses IP |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
