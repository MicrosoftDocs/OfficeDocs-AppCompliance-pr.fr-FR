---
title: Informations d’application pour CatchEm par chimu Software
ms.author: elmalova
author: elenamalova
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour CatchEm, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ba7936c4896fa9c6fc77eee773b6c52bec0af19d
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60435548"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Chimu Software à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | CatchEm |
| ID | WA200002639 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Logiciel Chimu |
| URL du site web partenaire | [https://chimusoftware.com](https://chimusoftware.com) |
| URL de la Teams d’informations sur l’application | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| URL de la politique de confidentialité | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| URL des conditions d’utilisation | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Chimu Software sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | délégué | Cette autorisation est nécessaire pour déterminer les contacts d’un utilisateur de l’application. AadObjectId : pour identifier un utilisateur de manière unique. TenantId : pour déterminer si un contact est interne ou externe à l’utilisateur. DisplayName, GivenName, Surname : pour identifier les contacts des utilisateurs de l’application. Adresse de messagerie, UserPrincipalName : pour faire la distinction entre les contacts du même nom et autoriser la fonctionnalité de clic &quot; sur &quot; la conversation. ID de conversation le plus récent : pour activer &quot; la fonctionnalité Cliquer pour &quot; discuter | Cette autorisation est nécessaire pour déterminer les contacts d’un utilisateur de l’application. AadObjectId : pour identifier un utilisateur de manière unique. TenantId : pour déterminer si un contact est interne ou externe à l’utilisateur. DisplayName, GivenName, Surname : pour identifier les contacts des utilisateurs de l’application. Adresse de messagerie, UserPrincipalName : pour faire la distinction entre les contacts du même nom et autoriser la fonctionnalité de clic &quot; sur &quot; la conversation. ID de conversation le plus récent : pour activer &quot; la fonctionnalité Cliquer pour &quot; discuter | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| People.Read | délégué | Pour améliorer la précision des données pour les contacts externes. DisplayName : pour identifier les contacts des utilisateurs de l’application. | Pour améliorer la précision des données pour les contacts externes. DisplayName : pour identifier les contacts des utilisateurs de l’application. | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| Presence.Read.All | délégué | État de présence actuel des contacts | S/O | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsActivity.Send | les deux | Pour envoyer des notifications aux utilisateurs lorsqu’un statut de présence des contacts change | S/O | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsAppInstallation.ReadWriteSelfForUser | délégué | Pour activer les mises à jour automatiques pour l’application | S/O | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.Read | délégué | AadObjectId : pour identifier un utilisateur de manière unique. TenantId : pour déterminer si un contact est interne ou externe à l’utilisateur. DisplayName, GivenName, Surname : pour identifier les contacts des utilisateurs de l’application. Messagerie électronique, adresses de messagerie instantanée, UserPrincipalName : pour faire la distinction entre les contacts du même nom et autoriser la fonctionnalité de clic &quot; &quot; pour la conversation. CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime : suppression automatique des données utilisateur pour les utilisateurs désactivés | AadObjectId : pour identifier un utilisateur de manière unique. TenantId : pour déterminer si un contact est interne ou externe à l’utilisateur. DisplayName, GivenName, Surname : pour identifier les contacts des utilisateurs de l’application. Messagerie électronique, adresses de messagerie instantanée, UserPrincipalName : pour faire la distinction entre les contacts du même nom et autoriser la fonctionnalité de clic &quot; &quot; pour la conversation. CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime : suppression automatique des données utilisateur pour les utilisateurs désactivés | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.ReadBasic.All | délégué | Pour améliorer la précision des données pour les contacts internes. AadObjectId : pour identifier un utilisateur de manière unique. TenantId : pour déterminer si un contact est interne ou externe à l’utilisateur. DisplayName, GivenName, Surname : pour identifier les contacts des utilisateurs de l’application. Adresse de messagerie, UserPrincipalName : pour faire la distinction entre les contacts du même nom et autoriser la fonctionnalité de clic &quot; sur &quot; la conversation. | Pour améliorer la précision des données pour les contacts internes. AadObjectId : pour identifier un utilisateur de manière unique. TenantId : pour déterminer si un contact est interne ou externe à l’utilisateur. DisplayName, GivenName, Surname : pour identifier les contacts des utilisateurs de l’application. Adresse de messagerie, UserPrincipalName : pour faire la distinction entre les contacts du même nom et autoriser la fonctionnalité de clic &quot; sur &quot; la conversation. | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| offline_access | délégué | Graph de sécurité, pour permettre à l’application de notifier les modifications de présence des contacts et de mettre à jour les listes de contacts lorsque l’utilisateur n’utilise pas activement l’application | Graph de sécurité | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| La balise de la fonctionnalité de message doit utiliser le nom complet du &quot; contact &quot; pour l’afficher à l’utilisateur de l’application. | Nom complet du contact | Pour être en mesure de présenter le nom du contact à l’utilisateur de l’application |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>S/O

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Chimu Software sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Non |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
