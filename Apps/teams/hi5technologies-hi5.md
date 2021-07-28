---
title: Informations sur l’application hi5 par Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 07/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Hi5, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1356b3e31e309379e1943dc5ca59e10c72c23410
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525598"
---
# <a name="hi5"></a>Hi5

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Hi5Technologies à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Hi5 |
| ID | WA200001610 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Hi5Technologies |
| URL du site web partenaire | [https://www.get5.io](https://www.get5.io) |
| URL de la Teams d’informations sur l’application | [https://help.get5.io](https://help.get5.io) |
| URL de la politique de confidentialité | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| URL des conditions d’utilisation | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Hi5Technologies sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit les approuver par ajout de notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Requis pour la connexion et l’authentification SSO sur notre serveur | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| email | délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit les approuver par ajout de notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Requis pour la connexion et l’authentification SSO sur notre serveur | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| offline_access | délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit les approuver par ajout de notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Maintient que l’utilisateur voit les informations correctes et que nous pouvons envoyer les informations correctes à d’autres personnes rejoignant le même espace de travail/entreprise. | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| openid | délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit les approuver par ajout de notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Requis pour la connexion et l’authentification SSO sur notre serveur | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| profil | délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit les approuver par ajout de notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Requis pour la connexion et l’authentification SSO sur notre serveur | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Pour informer l’utilisateur dans un canal qu’un hi5 lui a été attribué | Aucune information n’est stockée, l’utilisateur sera simplement @ par la carte renvoyée dans le canal | Aucune information n’est stockée, l’utilisateur sera simplement @ par la carte renvoyée dans le canal |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Non, Hi5 est simplement iFramed dans et toutes les données sont stockées en toute sécurité.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous utilisons OAuth et fournissons 3 options de connexion :
- Googles SSO (OAuth).
- Microsoft SSO (OAuth).
- Notre propre chiffrement qui est une combinaison de chiffrement SHA et AES.
Une fois authentifié et connecté, votre niveau d’autorisation vous accorde l’accès aux sections autorisées dans la plateforme Hi5.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Hi5Technologies sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Non |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
