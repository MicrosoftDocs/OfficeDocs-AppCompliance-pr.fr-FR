---
title: Informations d’application pour les collègues par des collègues Informations Inc
ms.author: elmalova
author: elenamalova
ms.date: 06/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour les collègues, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3dc9a5d3bcd6e5bbc356efab77ad15406e9fb772
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414630"
---
# <a name="fellow"></a>Fellow

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Les collègues Informations Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Fellow |
| ID | WA200002576 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Fellow Insights Inc |
| URL du site web partenaire | [https://fellow.app](https://fellow.app) |
| URL de la politique de confidentialité | [https://fellow.app/privacy-policy/](https://fellow.app/privacy-policy/) |
| URL des conditions d’utilisation | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par les collègues Informations Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | les deux | Un collègue se connecte aux calendriers de l’utilisateur pour lui donner la possibilité de prendre des notes sur les données. | Un collègue stocke toutes les données d’événement pour le calendrier principal de l’utilisateur. Les pièces jointes ne sont pas stockées. Il est utilisé au sein de Collègues pour fournir une expérience de prise de notes basée sur le calendrier. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Channel.ReadBasic.All | délégué | Nous collectons les noms des canaux dont un utilisateur est membre afin de leur afficher la liste des canaux à qui ils peuvent envoyer des notes. | Nous misons en cache les noms et les ID des canaux dont un utilisateur est membre, afin de permettre aux utilisateurs d’envoyer des notes de Collègues au canal spécifié. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Directory.Read.All | application | Ces données sont collectées uniquement si une installation d’administrateur est effectuée pour l’ensemble de l’organisation. Nous utilisons les données d’annuaire pour synchroniser une liste d’utilisateurs et mettre automatiquement en service des comptes. | Si et uniquement si une installation à l’échelle de l’organisation est effectuée par l’administrateur à partir des paramètres de l’espace de travail à l’intérieur de Collègues, les administrateurs ont la possibilité d’activer la synchronisation automatique de tous les utilisateurs de Azure AD en Compagnon (approvisionnement automatique). Dans ce cas, nous stockons les informations utilisateur telles que l’ID, le nom, la messagerie, le responsable et les appartenances aux groupes (pour les fonctionnalités de gestion d’équipe). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Group.Read.All | application | Ces données sont collectées uniquement si une installation d’administrateur est effectuée pour l’ensemble de l’organisation. Nous utilisons les données d’annuaire pour synchroniser une liste d’utilisateurs et mettre automatiquement en service des comptes. | Si et uniquement si une installation à l’échelle de l’organisation est effectuée par l’administrateur à partir des paramètres de l’espace de travail à l’intérieur de Collègues, les administrateurs ont la possibilité d’activer la synchronisation automatique de tous les utilisateurs de Azure AD en Compagnon (approvisionnement automatique). Dans ce cas, nous stockons les informations utilisateur telles que l’ID, le nom, la messagerie, le responsable et les appartenances aux groupes (pour les fonctionnalités de gestion d’équipe). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read | délégué | Les contacts de l’utilisateur sont collectés, dans des noms d’affichage et des adresses e-mail de contact spécifiques. Il est utilisé dans Le compagnon pour fournir une liste d’utilisateurs à inviter à inviter à une note/ partager une note avec. | Les contacts de l’utilisateur sont collectés, dans des noms d’affichage et des adresses e-mail de contact spécifiques. Il est utilisé dans Le compagnon pour fournir une liste d’utilisateurs à inviter à inviter à une note/ partager une note avec. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read.All | application | Ces données sont collectées uniquement si une installation d’administrateur est effectuée pour l’ensemble de l’organisation. Les contacts de l’utilisateur sont collectés, dans des noms d’affichage et des adresses e-mail de contact spécifiques. Il est utilisé dans Le compagnon pour fournir une liste d’utilisateurs à inviter à inviter à une note/ partager une note avec. | Si et uniquement si une installation à l’échelle de l’organisation est effectuée par l’administrateur à partir des paramètres de l’espace de travail à l’intérieur de Collègues, les administrateurs ont la possibilité d’activer la synchronisation automatique de tous les utilisateurs de Azure AD en Compagnon (approvisionnement automatique). Dans ce cas, les contacts de l’utilisateur sont collectés, dans des noms d’affichage et des adresses e-mail de contact spécifiques. Il est utilisé dans Le compagnon pour fournir une liste d’utilisateurs à inviter à inviter à une note/ partager une note avec. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Team.ReadBasic.All | délégué | La liste des équipes dont l’utilisateur fait partie est collectée. Il est utilisé au sein d’un collègue pour permettre à l’utilisateur d’envoyer des notes de collègues à une équipe. | Nous misons en cache les noms et les ID des équipes dont un utilisateur est membre, afin de permettre aux utilisateurs d’envoyer des notes de Collègues au canal d’équipe spécifié. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read | délégué | Les informations utilisateur de base sont collectées. Nom d’utilisateur, e-mail, fonction. Ces informations sont utilisées au sein de Collègues pour créer des comptes d’utilisateurs et des comptes d’entreprise. | Les informations utilisateur de base sont stockées. Nom d’utilisateur, e-mail, fonction. Ces informations sont utilisées au sein de Collègues pour gérer les comptes d’utilisateurs et les comptes d’entreprise. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read.All | application | Ces données sont collectées uniquement si une installation d’administrateur est effectuée pour l’ensemble de l’organisation. Nous utilisons les données d’annuaire pour synchroniser une liste d’utilisateurs et mettre automatiquement en service des comptes. | Si et uniquement si une installation à l’échelle de l’organisation est effectuée par l’administrateur à partir des paramètres de l’espace de travail à l’intérieur de Collègues, les administrateurs ont la possibilité d’activer la synchronisation automatique de tous les utilisateurs de Azure AD en Compagnon (approvisionnement automatique). Dans ce cas, nous stockons les informations utilisateur telles que l’ID, le nom, la messagerie, le responsable et les appartenances aux groupes (pour les fonctionnalités de gestion d’équipe). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| offline_access | délégué | Jeton d’actualisation de l’utilisateur pour conserver l’accès aux données recueillies via d’autres étendues. | Le jeton d’actualisation de l’utilisateur est stocké dans la base de données. Il est utilisé au sein de Collègues pour synchroniser des événements en arrière-plan pour l’expérience de prise de notes basée sur le calendrier, ainsi que des notifications pour la prise de notes sur les événements programmés. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Les collègues stockent les informations fournies directement par l’utilisateur, y compris les données personnelles. Il stocke également des informations provenant de systèmes tiers, telles que des données OAuth, des données de calendrier et des données d’informations personnelles telles que le nom de &amp; messagerie. Nous conservons toutes les données indéfiniment, tant que cela est nécessaire et juridiquement autorisé aux fins pour lesquelles elles ont été collectées. Nous supprimons en toute sécurité ces informations à une date antérieure lors de la réception d’une demande par les utilisateurs. Les données du journal sont conservées pendant 30 jours.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Tous les transferts de données se produisent sur des API sécurisées vers nos systèmes back-end. Un collègue utilise de nombreux contrôles pour garantir la sécurité et la confidentialité de ses systèmes, conformément à l’infrastructure SOC 2 définie par l’AICPA. Les contrôles des collègues font l’objet d’un audit annuel pour garantir une conformité continue. Un rapport SOC 2 peut être partagé sur demande et NDA.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par les collègues Informations Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | ,<br/><br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

