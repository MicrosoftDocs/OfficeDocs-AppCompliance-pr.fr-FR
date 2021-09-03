---
title: Informations d’application pour PagerDuty par PagerDuty, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour PagerDuty, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3729a9523ea4af31015f6e8111c6843e90d465f3
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873807"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par PagerDuty, Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | PagerDuty |
| ID | WA200001637 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | PagerDuty, Inc. |
| URL du site web partenaire | [https://www.pagerduty.com](https://www.pagerduty.com) |
| URL de la Teams d’informations sur l’application | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| URL de la politique de confidentialité | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par PagerDuty, Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.ReadWrite | délégué | À partir de la création ou de l’obtention d’une réponse de réunion, nous utilisons les champs join_web_url, audioConferencing. Ces champs sont nécessaires pour afficher à l’utilisateur un lien vers une réunion ou d’autres moyens de se connecter en réunion. | We save: join_web_url, audioConferencing. Ces champs sont nécessaires pour afficher à l’utilisateur un lien vers une réunion ou d’autres moyens de se connecter en réunion. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | délégué | Utilisation pour ajouter une application pagerduty à la conversation. | Utilisation pour ajouter une application pagerduty à la conversation. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadWriteForTeam.All | délégué | Utilisation pour ajouter une application pagerduty à la conversation. | Utilisation pour ajouter une application pagerduty à la conversation. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab.ReadWrite.All | délégué | Utilisation pour ajouter une application pagerduty en tant qu’onglet dans une réunion | Utilisation pour ajouter une application pagerduty en tant qu’onglet dans une réunion | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | délégué | Les données sont utilisées : id, userPrincipalName . Il est utilisé pour que les utilisateurs de Microsoft Teams les ajoutent à la réunion en tant que participants | Les données sont utilisées : id, userPrincipalName . Il est utilisé pour que les utilisateurs de Microsoft Teams les ajoutent à la réunion en tant que participants | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | délégué | Les données sont utilisées : id, userPrincipalName . Il est utilisé pour que les utilisateurs de Microsoft Teams les ajoutent à la réunion en tant que participants | Les données sont utilisées : id, userPrincipalName . Il est utilisé pour que les utilisateurs de Microsoft Teams les ajoutent à la réunion en tant que participants | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| email | délégué | Utilisation pour les demandes d’autorisation et de jeton. Les données sont utilisées : access_token, refresh_token, expires_in, étendue | access_token, refresh_token, expires_in, étendue. Ces données sont requises pour obtenir des informations sur les réunions en ligne et utilisateur | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | délégué | Utilisation pour les demandes d’autorisation et de jeton. Les données sont utilisées : access_token, refresh_token, expires_in, étendue | access_token, refresh_token, expires_in, étendue. Ces données sont reququies pour obtenir des informations sur les réunions utilisateur et en ligne | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| openid | délégué | Utilisation pour les demandes d’autorisation et de jeton. Les données sont utilisées : access_token, refresh_token, expires_in, étendue | access_token, refresh_token, expires_in, étendue. Ces données sont reququées pour obtenir des informations sur l’utilisateur et la création/obtention de réunions en ligne | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| profil | délégué | Utilisation pour les demandes d’autorisation et de jeton. Les données sont utilisées : access_token, refresh_token, expires_in, étendue | access_token, refresh_token, expires_in, étendue. Ces données sont reququées pour obtenir des informations sur l’utilisateur et la création/obtention de réunions en ligne | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings.ReadWrite | délégué | À partir de la création ou de l’obtention d’une réponse de réunion, nous utilisons les champs join_web_url, audioConferencing. Ces champs sont nécessaires pour afficher à l’utilisateur un lien vers une réunion ou d’autres moyens de se connecter en réunion. | We save: join_web_url, audioConferencing. Ces champs sont nécessaires pour afficher à l’utilisateur un lien vers une réunion ou d’autres moyens de se connecter en réunion. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | délégué | Utilisation pour ajouter une application pagerduty à la conversation. | Utilisation pour ajouter une application pagerduty à la conversation. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam.All | délégué | Utilisation pour ajouter une application pagerduty à la conversation. | Utilisation pour ajouter une application pagerduty à la conversation. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab.ReadWrite.All | délégué | Utilisation pour ajouter une application pagerduty en tant qu’onglet dans une réunion | Utilisation pour ajouter une application pagerduty en tant qu’onglet dans une réunion | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | délégué | Les données sont utilisées : id, userPrincipalName . Il est utilisé pour que les utilisateurs de Microsoft Teams les ajoutent à la réunion en tant que participants | Les données sont utilisées : id, userPrincipalName . Il est utilisé pour que les utilisateurs de Microsoft Teams les ajoutent à la réunion en tant que participants | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | délégué | Les données sont utilisées : id, userPrincipalName . Il est utilisé pour que les utilisateurs de Microsoft Teams les ajoutent à la réunion en tant que participants | Les données sont utilisées : id, userPrincipalName . Il est utilisé pour que les utilisateurs de Microsoft Teams les ajoutent à la réunion en tant que participants | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| email | délégué | Utilisation pour les demandes d’autorisation et de jeton. Les données sont utilisées : access_token, refresh_token, expires_in, étendue | access_token, refresh_token, expires_in, étendue. Ces données sont requises pour obtenir des informations sur les réunions en ligne et utilisateur | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | délégué | Utilisation pour les demandes d’autorisation et de jeton. Les données sont utilisées : access_token, refresh_token, expires_in, étendue | access_token, refresh_token, expires_in, étendue. Ces données sont requises pour obtenir des informations sur les réunions en ligne et utilisateur | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| openid | délégué | Utilisation pour les demandes d’autorisation et de jeton. Les données sont utilisées : access_token, refresh_token, expires_in, étendue | access_token, refresh_token, expires_in, étendue. Ces données sont reququées pour obtenir des informations sur l’utilisateur et la création/obtention de réunions en ligne | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| profil | délégué | Utilisation pour les demandes d’autorisation et de jeton. Les données sont utilisées : access_token, refresh_token, expires_in, étendue | access_token, refresh_token, expires_in, étendue. Ces données sont reququées pour obtenir des informations sur l’utilisateur et la création/obtention de réunions en ligne | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Les données que PagerDuty tient à jour sont limitées aux données de l’ordinateur provenant des produits de surveillance et les informations d’piI sont limitées à : adresse de messagerie d’entreprise, prénom, nom et numéro de téléphone. Vous pouvez trouver la liste des sous-processeurs ayant accès à ces données ici : https://www.pagerduty.com/subprocessors/ | Les données que PagerDuty tient à jour sont limitées aux données de l’ordinateur provenant des produits de surveillance et les informations d’piI sont limitées à : adresse de messagerie d’entreprise, prénom, nom et numéro de téléphone. Vous pouvez trouver la liste des sous-processeurs ayant accès à ces données ici : https://www.pagerduty.com/subprocessors/ | Les données que PagerDuty tient à jour sont limitées aux données de l’ordinateur provenant des produits de surveillance et les informations d’piI sont limitées à : adresse de messagerie d’entreprise, prénom, nom et numéro de téléphone. La liste des sous-processeurs ayant accès à ces données est accessible ici : Pour plus d’informations sur la confidentialité des données, voir https://www.pagerduty.com/subprocessors/ : https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>PagerDuty exige que tous les fournisseurs avec lesquels nous transférons des données soient tenus à jour par des normes de sécurité des données au moins aussi strictes que celles conservées par PagerDuty, y compris une obligation contractuelle sous la forme d’une DPA signée. Pour plus d’informations sur nos normes de sécurité des données, voir : https://www.pagerduty.com/data-security-policy/

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

Ces informations ont été fournies par PagerDuty, Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
