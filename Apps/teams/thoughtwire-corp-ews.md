---
title: Informations sur l’application pour ThoughtWire EWS par ThoughtWire Corp.
ms.author: elmalova
author: elenamalova
ms.date: 06/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour ThoughtWire EWS, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 5ed53bb0a29a287cd0102b7f7e2e2fdd782b2c10
ms.sourcegitcommit: 9010c9bace5d935309eae5098f5a126a55270eb6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/18/2021
ms.locfileid: "59438426"
---
# <a name="thoughtwire-ews"></a>ThoughtWire EWS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ed27363f-755e-4658-b7bf-409d475959d6" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003239" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ThoughtWire Corp. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | ThoughtWire EWS |
| ID | WA200003239 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | ThoughtWire Corp. |
| URL du site web partenaire | [https://thoughtwire.com](https://thoughtwire.com) |
| URL de la politique de confidentialité | [https://thoughtwire.com/privacy-policy](https://thoughtwire.com/privacy-policy) |
| URL des conditions d’utilisation | [https://www.thoughtwire.com/end-user-license-agreement/](https://www.thoughtwire.com/end-user-license-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par ThoughtWire Corp. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Create | application | Permet à l’application de créer des groupes/équipes pour les hôpitals/unités. | Aucun | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| Group.ReadWrite.All | application | Requis pour que l’application détermine les groupes qu’elle peut avoir besoin de créer/re-créer et pour gérer l’appartenance. | Aucun | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| GroupMember.ReadWrite.All | application | Requis pour que l’application puisse gérer l’appartenance au groupe. c’est-à-dire, en ajoutant/supprimant des membres d’une équipe lorsque les équipes changent. | Aucun | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamMember.ReadWrite.All | application | Requis pour que l’application puisse gérer l’appartenance au groupe. c’est-à-dire, en ajoutant/supprimant des membres d’une équipe lorsque les équipes changent. | Aucun | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamsAppInstallation.ReadWriteForTeam | application | Permet à l’application d’installer automatiquement le bot ThoughtWire pour les équipes qu’elle crée/gère. | Aucun | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| User.Read | application | Autorisez l’application à récupérer le nom d’utilisateur /AADID d’un utilisateur selon les besoins lors de la gestion de l’appartenance et/ou de la récupération du nom d’utilisateur pour identifier l’utilisateur au sein de notre application. | Aucun | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Le nom d’utilisateur est requis pour identifier l’utilisateur qui effectue des actions. | Nom d’utilisateur et ID d’utilisateur | Audit des notifications et des événements. |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>ThoughtWire sélectionne les partenaires qui répondent ou dépassent nos propres processus de contrôle des données. Les données ne sont pas fournies aux systèmes partenaires, sauf en cas d’absolue nécessité. Tous les services ThoughtWire et les systèmes partenaires associés sont vérifiés et approuvés par les clients.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par ThoughtWire Corp. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Non |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
