---
title: Informations d’application pour Cloud Cloud cloud par Atlassian
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Cloud, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f73952983dd6b9788bcd61d71e55e5815de5f937
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411148"
---
# <a name="confluence-cloud"></a>Confluence Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/30bb610c-6321-40fe-a047-056e7d0dac96" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003113" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Atlassian à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Confluence Cloud |
| ID | WA200003113 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Atlassian |
| URL du site web partenaire | [https://www.atlassian.com](https://www.atlassian.com) |
| URL de la politique de confidentialité | [https://www.atlassian.com/legal/privacy-policy](https://www.atlassian.com/legal/privacy-policy) |
| URL des conditions d’utilisation | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Atlassian sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | délégué | - Nous lisons la liste des membres de conversation dans une réunion, afin de connaître la liste des invités à la réunion.   - Nous lisons les noms d&#8217; utilisateurs et les adresses de messagerie que nous affichons de manière conditionnable dans notre application de réunion. Par exemple, affichez le nom de l’utilisateur actuel prenant des notes de réunion.   - Notre application lit l’événement de calendrier de l&#8217;utilisateur dans lequel notre application a été ajoutée à une réunion afin que nous lisez des informations de base sur la réunion, telles que le titre de la réunion. | Les exemples de contenu que nous collectons et stockons sont les suivants : le résumé et la description ajoutés à un problème JIRA, les pages que vous créez dans Contrôle, vos référentiels et requêtes pull dans Bitbucket, les commentaires que vous entrez dans le cadre d’un incident dans la page d’état et les commentaires que vous nous fournissez. Le contenu inclut également les fichiers et les liens que vous téléchargez vers les services. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| Chat.ReadBasic | délégué |  - Nous lisons la liste des membres de conversation dans une réunion, afin de connaître la liste des invités à la réunion.   - Nous lisons les noms d&#8217; utilisateurs et les adresses de messagerie que nous affichons de manière conditionnable dans notre application de réunion. Par exemple, affichez le nom de l’utilisateur actuel prenant des notes de réunion.   - Notre application lit l’événement de calendrier de l&#8217;utilisateur dans lequel notre application a été ajoutée à une réunion afin que nous lisez des informations de base sur la réunion, telles que le titre de la réunion. | Les exemples de contenu que nous collectons et stockons sont les suivants : le résumé et la description ajoutés à un problème JIRA, les pages que vous créez dans Contrôle, vos référentiels et requêtes pull dans Bitbucket, les commentaires que vous entrez dans le cadre d’un incident dans la page d’état et les commentaires que vous nous fournissez. Le contenu inclut également les fichiers et les liens que vous téléchargez vers les services. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| User.ReadBasic.All | délégué | - Nous lisons la liste des membres de conversation dans une réunion, afin de connaître la liste des invités à la réunion.   - Nous lisons les noms d&#8217; utilisateurs et les adresses de messagerie que nous affichons de manière conditionnable dans notre application de réunion. Par exemple, affichez le nom de l’utilisateur actuel prenant des notes de réunion.   - Notre application lit l’événement de calendrier de l&#8217;utilisateur dans lequel notre application a été ajoutée à une réunion afin que nous lisez des informations de base sur la réunion, telles que le titre de la réunion. | Les exemples de contenu que nous collectons et stockons sont les suivants : le résumé et la description ajoutés à un problème JIRA, les pages que vous créez dans Contrôle, vos référentiels et requêtes pull dans Bitbucket, les commentaires que vous entrez dans le cadre d’un incident dans la page d’état et les commentaires que vous nous fournissez. Le contenu inclut également les fichiers et les liens que vous téléchargez vers les services. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| email | délégué | - Nous lisons la liste des membres de conversation dans une réunion, afin de connaître la liste des invités à la réunion.   - Nous lisons les noms d&#8217; utilisateurs et les adresses de messagerie que nous affichons de manière conditionnable dans notre application de réunion. Par exemple, affichez le nom de l’utilisateur actuel prenant des notes de réunion.   - Notre application lit l’événement de calendrier de l&#8217;utilisateur dans lequel notre application a été ajoutée à une réunion afin que nous lisez des informations de base sur la réunion, telles que le titre de la réunion. | Les exemples de contenu que nous collectons et stockons sont les suivants : le résumé et la description ajoutés à un problème JIRA, les pages que vous créez dans Contrôle, vos référentiels et requêtes pull dans Bitbucket, les commentaires que vous entrez dans le cadre d’un incident dans la page d’état et les commentaires que vous nous fournissez. Le contenu inclut également les fichiers et les liens que vous téléchargez vers les services. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| offline_access | délégué | - Nous lisons la liste des membres de conversation dans une réunion, afin de connaître la liste des invités à la réunion.   - Nous lisons les noms d&#8217; utilisateurs et les adresses de messagerie que nous affichons de manière conditionnable dans notre application de réunion. Par exemple, affichez le nom de l’utilisateur actuel prenant des notes de réunion.   - Notre application lit l’événement de calendrier de l&#8217;utilisateur dans lequel notre application a été ajoutée à une réunion afin que nous lisez des informations de base sur la réunion, telles que le titre de la réunion. | Les exemples de contenu que nous collectons et stockons sont les suivants : le résumé et la description ajoutés à un problème JIRA, les pages que vous créez dans Contrôle, vos référentiels et requêtes pull dans Bitbucket, les commentaires que vous entrez dans le cadre d’un incident dans la page d’état et les commentaires que vous nous fournissez. Le contenu inclut également les fichiers et les liens que vous téléchargez vers les services. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| openid | délégué |  - Nous lisons la liste des membres de conversation dans une réunion, afin de connaître la liste des invités à la réunion.   - Nous lisons les noms d&#8217; utilisateurs et les adresses de messagerie que nous affichons de manière conditionnable dans notre application de réunion. Par exemple, affichez le nom de l’utilisateur actuel prenant des notes de réunion.   - Notre application lit l’événement de calendrier de l&#8217;utilisateur dans lequel notre application a été ajoutée à une réunion afin que nous lisez des informations de base sur la réunion, telles que le titre de la réunion. | Les exemples de contenu que nous collectons et stockons sont les suivants : le résumé et la description ajoutés à un problème JIRA, les pages que vous créez dans Contrôle, vos référentiels et requêtes pull dans Bitbucket, les commentaires que vous entrez dans le cadre d’un incident dans la page d’état et les commentaires que vous nous fournissez. Le contenu inclut également les fichiers et les liens que vous téléchargez vers les services. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| profil | délégué |  - Nous lisons la liste des membres de conversation dans une réunion, afin de connaître la liste des invités à la réunion.   - Nous lisons les noms d&#8217; utilisateurs et les adresses de messagerie que nous affichons de manière conditionnable dans notre application de réunion. Par exemple, affichez le nom de l’utilisateur actuel prenant des notes de réunion.   - Notre application lit l’événement de calendrier de l&#8217;utilisateur dans lequel notre application a été ajoutée à une réunion afin que nous lisez des informations de base sur la réunion, telles que le titre de la réunion. | Les exemples de contenu que nous collectons et stockons sont les suivants : le résumé et la description ajoutés à un problème JIRA, les pages que vous créez dans Contrôle, vos référentiels et requêtes pull dans Bitbucket, les commentaires que vous entrez dans le cadre d’un incident dans la page d’état et les commentaires que vous nous fournissez. Le contenu inclut également les fichiers et les liens que vous téléchargez vers les services. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>https://www.atlassian.com/trust/privacy/how-we-handle-your-data

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Atlassian sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Non |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

