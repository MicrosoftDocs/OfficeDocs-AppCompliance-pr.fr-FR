---
title: Informations sur les applications harmon.ie pour Outlook par harmon.ie Corporation
ms.author: elmalova
author: elenamalova
ms.date: 01/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour harmon.ie pour Outlook, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e63a6614f0e0d6fb62cae5343982f4118a4c9168
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53526480"
---
# <a name="harmonie-for-outlook"></a>harmon.ie pour Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 4, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA103004101" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par harmon.ie Corporation à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | harmon.ie pour Outlook |
| ID | WA103004101 |
| Office 365 clients pris en charge | Outlook 2013 ou version ultérieure sur Windows, Outlook 2016 ou version ultérieure sur Mac, Outlook sur iOS, Outlook sur Android, Outlook sur le web |
| Nom de la société partenaire | harmon.ie Corporation |
| URL du site web partenaire | [https://harmon.ie](https://harmon.ie) |
| URL de la politique de confidentialité | [https://harmon.ie/legal/privacy-policy](https://harmon.ie/legal/privacy-policy) |
| URL des conditions d’utilisation | [https://harmon.ie/legal/eula](https://harmon.ie/legal/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par harmon.ie Corporation sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | délégué | Requis par harmon.ie pour Outlook permettre aux utilisateurs de se connecter et d’obtenir le rôle de l’utilisateur | aucune | [170cef4c-862a-443c-b02a-c5ba04ecc7f3](https://docs.microsoft.com/microsoft-365-app-certification/azure/170cef4c-862a-443c-b02a-c5ba04ecc7f3) |
>| Files.ReadWrite.All | délégué | Requis par harmon.ie pour Outlook pour lui permettre de transférer des pièces jointes à partir de Outlook et de &amp; l’enregistrer dans SharePoint | aucune | [170cef4c-862a-443c-b02a-c5ba04ecc7f3](https://docs.microsoft.com/microsoft-365-app-certification/azure/170cef4c-862a-443c-b02a-c5ba04ecc7f3) |
>| Mail.ReadWrite | délégué | Requis par harmon.ie pour Outlook pour lui permettre de transférer des pièces jointes à partir de Outlook et de &amp; l’enregistrer dans SharePoint | aucune | [170cef4c-862a-443c-b02a-c5ba04ecc7f3](https://docs.microsoft.com/microsoft-365-app-certification/azure/170cef4c-862a-443c-b02a-c5ba04ecc7f3) |
>| User.Read | délégué | Requis par le harmon.ie pour Outlook pour résoudre l’image de profil des utilisateurs | aucune | [170cef4c-862a-443c-b02a-c5ba04ecc7f3](https://docs.microsoft.com/microsoft-365-app-certification/azure/170cef4c-862a-443c-b02a-c5ba04ecc7f3) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Utilisateurs et données d’utilisation upn

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>-

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36360' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36360" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par harmon.ie Corporation sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
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
