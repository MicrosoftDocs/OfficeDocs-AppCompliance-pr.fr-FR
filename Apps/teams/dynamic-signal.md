---
title: Informations d’application pour le signal dynamique par signal dynamique
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour le signal dynamique, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5b5906e8eee51821481de11c3cbd720600d4c36e
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521797"
---
# <a name="dynamic-signal"></a>Signal dynamique

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par le signal dynamique à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Signal dynamique |
| ID | WA200000102 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Signal dynamique |
| URL du site web partenaire | [https://www.dynamicsignal.com](https://www.dynamicsignal.com) |
| URL de la Teams d’informations sur l’application | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL de la politique de confidentialité | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL des conditions d’utilisation | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Dynamic Signal sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | Le signal dynamique synchronise les utilisateurs d’Azure AD avec sa plateforme pour permettre une activation et une désactivation simplifiées des utilisateurs en temps réel. Les données sont stockées dans le signal dynamique pour permettre aux utilisateurs d’utiliser cette application pendant la synchronisation. | Lire les autorisations d’un utilisateur spécifique pour synchroniser les utilisateurs de la plateforme Signal dynamique avec Azure AD. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| User.Read.All | délégué | Le signal dynamique synchronise les utilisateurs d’Azure AD avec sa plateforme pour permettre une activation et une désactivation simplifiées des utilisateurs en temps réel. Les données sont stockées dans le signal dynamique pour permettre aux utilisateurs d’utiliser cette application pendant la synchronisation. | Lire les autorisations d’un utilisateur spécifique pour synchroniser les utilisateurs de la plateforme Signal dynamique avec Azure AD. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| offline_access | délégué | Le signal dynamique synchronise les utilisateurs d’Azure AD avec sa plateforme pour permettre une activation et une désactivation simplifiées des utilisateurs en temps réel. Les données sont stockées dans le signal dynamique pour permettre aux utilisateurs d’utiliser cette application pendant la synchronisation. | Conserver l’accès aux groupes et aux équipes du client. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| openid | délégué | Le signal dynamique synchronise les utilisateurs d’Azure AD avec sa plateforme pour permettre une activation et une désactivation simplifiées des utilisateurs en temps réel. Les données sont stockées dans le signal dynamique pour permettre aux utilisateurs d’utiliser cette application pendant la synchronisation. | Authentifier les utilisateurs avec l’application de signal dynamique. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| openid sign in using openid directory.readwrite.all access to the tenant’s domain and groups, add an app to a team offline_access retain access to the tenant’s groups and teams | openid Autoriser l’authentification indépendante. accès directory.readwrite.all au domaine et aux groupes du client, ajoutez une application à une offline_access conservez l’accès aux groupes et équipes du client Remarque : l’application du signal dynamique utilise le bot d’équipes pour appliquer des groupes et des autorisations créés au sein du signal dynamique à Teams afin qu’un utilisateur actif dans le signal dynamique accède aux mêmes groupes et utilisateurs qu’au sein de Teams. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>L’application et la plateforme Dynamic Signal utilisent les informations utilisateur pour faciliter l’intégration avec Microsoft Teams. Ces informations sont accessibles aux utilisateurs ayant les autorisations appropriées au sein de la plateforme De signal dynamique. Les informations pertinentes sont Nom, Nom complet et Courrier électronique. Ces informations sont stockées dans les journaux de la plateforme De signal dynamique conformément à la stratégie de l’organisation respective avec la licence Signal dynamique.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données d’informations d’identification personnelle collectées lors de l’inscription et stockées dans la plateforme De signal dynamique incluent : prénom, nom, e-mail/identificateur et tous les champs personnalisés qui sont définies par la marque et/ou les partenaires de l’agence. Lorsque des membres utilisent Facebook ou Twitter à l’aide d’oAuth Registration, certaines des données utilisateur exposées sont présentées à la plateforme De signal dynamique pour pré-remplir les données. Ces données incluent le nom, l’emplacement et la photo. Les utilisateurs ont le contrôle sur les informations et les données présentées aux utilisateurs dans les pages bio de la communauté. Les membres peuvent choisir de charger des photos personnelles ou de marque, de connecter des comptes/canaux sociaux et des points d’utilisation dans le programme à présenter dans la page bio.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

