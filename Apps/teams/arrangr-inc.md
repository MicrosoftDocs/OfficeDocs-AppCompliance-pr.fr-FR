---
title: Informations sur l’application pour l’organisation par l’organisation, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour l’organisation, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3ccc0e501a899fcb5dc613c254de9aa62911d023
ms.sourcegitcommit: 78e63c8004c49fa95d80618b9fee424f1084e43d
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/19/2021
ms.locfileid: "58404504"
---
# <a name="arrangr"></a>Arrangeur

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/57de46f8-193a-400c-9a34-c862333aed55" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002975" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Arrangr, Inc. à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Arrangeur |
| ID | WA200002975 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Arrangeur, Inc. |
| URL du site web partenaire | [https://arrangr.com](https://arrangr.com) |
| URL de la Teams d’informations sur l’application | [https://arrangr.com/welcome](https://arrangr.com/welcome) |
| URL de la politique de confidentialité | [https://arrangr.com/privacy_policy](https://arrangr.com/privacy_policy) |
| URL des conditions d’utilisation | [https://arrangr.com/terms_of_use](https://arrangr.com/terms_of_use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Organizationalr, Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | délégué | Nous collectons les noms des calendriers des utilisateurs et des détails sur leurs événements de calendrier, afin de faciliter la planification des réunions. | Nous stockons les noms des calendriers connectés, afin qu’ils voient et modifient les calendriers qu’ils ont connectés. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Channel.ReadBasic.All | délégué | Collectez la liste des canaux disponibles pour les utilisateurs, afin de leur présenter une liste de leurs canaux pour qu’ils en sélectionnent un pour partager une invitation de l’organiseur. | Nous ne stockons pas d’informations sur les canaux de l’utilisateur | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChannelMessage.Send | délégué | Cette autorisation permet d’envoyer des invitations d’organisation aux canaux d’équipe au nom de l’utilisateur. Il n’est pas utilisé pour collecter des données. | Aucune donnée n’est stockée qui est collectée avec cette autorisation. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Chat.ReadWrite | délégué | Cette autorisation permet d’envoyer des invitations d’organisation dans une Teams conversation au nom de l’utilisateur. Cette autorisation n’est pas utilisée pour collecter des données. | Aucune donnée n’est stockée qui est collectée avec cette autorisation. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChatMessage.Send | délégué | Cette autorisation permet d’envoyer des invitations d’organiseur dans des conversations 1:1 et de groupe pour le compte de l’utilisateur. Il n’est pas utilisé pour collecter des données. | Aucune donnée n’est stockée qui est collectée avec cette autorisation. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| OnlineMeetings.ReadWrite | délégué | L’organiseur collecte Microsoft Teams liens de réunion dans le processus de génération de ces liens avec cette autorisation. Nous générons Teams réunions au nom de l’utilisateur afin qu’il puisse organiser Teams appels sur l’organisation. | Nous stockons les liens de réunion, afin qu’ils soient partagés avec les parties appropriées pour participer à la réunion. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| People.Read | délégué | Nous collectons les noms et les e-mails des personnes pertinentes pour l’utilisateur. Cela permet à l’utilisateur de les sélectionner en tant que destinataires des invitations de l’organiseur. | Si l’utilisateur finit par sélectionner un destinataire proposé par le biais de cette API, nous allons enregistrer le nom et l’e-mail de ce destinataire afin de mener la réunion et de permettre à l’utilisateur de le sélectionner à nouveau en tant que destinataire à l’avenir. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Team.ReadBasic.All | délégué | Nous collectons les noms des Teams de l’utilisateur, afin qu’il puisse sélectionner les Teams dans lesquelles il souhaite se connecter à l’organisation et l’équipe dans laquelle il souhaite partager une invitation d’organisation. | L’organiseur stocke les noms des Teams que l’utilisateur a choisi de lier à l’organisation, afin que nous pouvons afficher ces Teams dans leurs paramètres et les laisser choisir parmi ces Teams lors du choix de l’endroit où partager une invitation de l’organiseur. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| TeamsAppInstallation.ReadWriteSelfForUser | délégué | Nous lisons si notre application a été installée dans le compte Teams de l’utilisateur, afin de pouvoir lui demander s’il souhaite installer notre application, et afin de pouvoir l’installer pour lui. | Nous ne stockons pas les données collectées par le biais de cette autorisation. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| profil | délégué | Nom et adresse e-mail | Nom et adresse de messagerie, afin d’afficher à l’utilisateur le compte qu’il a connecté à notre service. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook | Oui | Nom, e-mail, noms de calendrier, informations d’événement de calendrier | Nous collectons ces informations pour permettre aux utilisateurs de connecter leur calendrier à l’organisation afin de faciliter la planification des réunions | Nom, e-mail, noms de calendrier | Nous stockons ces informations afin de pouvoir montrer aux utilisateurs les comptes et les calendriers qu’ils ont connectés à notre service |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud, SendGrid, Stripe, Quaderno | Google Cloud stocke toutes les données utilisateur, les noms d’utilisateur et les e-mails partagés avec SendGrid afin d’envoyer des courriers électroniques aux utilisateurs, des noms d’utilisateurs, des e-mails et des informations de paiement pour le traitement des paiements. Quaderno reçoit les noms d’utilisateur, les e-mails et les informations géographiques afin de vous aider à respecter la taxe sur les ventes. | Google Cloud est nécessaire au stockage des données pour mémoriser les utilisateurs et fournir les informations qu’ils ont choisi de stocker dans l’organisation. Pour envoyer des courriers électroniques à nos utilisations, nous devons fournir leurs adresses de messagerie à SendGrid. Pour collecter les paiements, nous devons traiter leurs informations de paiement dans Stripe, mais nous ne stockons pas leurs informations de paiement sur nos propres serveurs. Quaderno est nécessaire pour calculer la taxe sur les ventes et s’assurer que nous respectons les réglementations fiscales. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Les utilisateurs utiliseront notre extension de messagerie pour planifier des réunions avec d’autres personnes. Nous devons montrer à l’utilisateur le compte dans qui il est connecté, et nous devons être en mesure d’associer l’invitation qu’il envoie à l’utilisateur d’organisation correct. | Noms d’utilisateur, e-mails et informations de communication. | Ces informations sont nécessaires pour coordonner les réunions entre plusieurs parties et partager avec les détails de connexion et les personnes avec qui elles se rencontrent. |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous contrôlons les données stockées dans Google Cloud Datastore via leur API et pouvons supprimer toutes les données dont nous avons besoin. Nos utilisateurs peuvent demander la suppression de leurs comptes et la suppression de leurs données.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

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

Ces informations ont été fournies par Arrangr, Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
