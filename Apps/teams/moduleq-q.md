---
title: Informations sur l'application pour Q par ModuleQ
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour Q, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cf5a29e08636c40635dd7e40c768f56cac35c096
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093339"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 17, 2020</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ModuleQ à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Q |
| ID | WA104381433 |
| Fonctionnalités | Bot, Onglet |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | ModuleQ |
| URL du site web partenaire | [https://moduleq.com](https://moduleq.com) |
| URL de la politique de confidentialité | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| URL des conditions d'utilisation | [https://moduleq.com/terms-of-service/](https://moduleq.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par ModuleQ sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d'autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d'application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | application | stocke les données de réunion, à l'exception du corps du message et des pièces jointes | Permet à l'application de lire les événements de calendrier d'un utilisateur afin de comprendre intelligemment ses priorités professionnelles. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | délégué | Aucune | Permet à l'application d'interagir dans une équipe pour le partage de contenu. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | application | stocke les données de courrier électronique, à l'exception du corps du message et des pièces jointes | Permet à l'application de lire le courrier d'un utilisateur afin de comprendre intelligemment ses priorités professionnelles | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | délégué | e-mail utilisateur et jetons d'authentification | Permet à l'utilisateur de se connecter et de lier Office 365 compte à son compte ModuleQ | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | délégué | Aucune | Autorisez l'application à obtenir la liste des Teams dont l'utilisateur fait partie. Utilisé uniquement pour le partage  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d'identification de l'utilisateur final (EUII) : la liste (prénom, nom, nom d'affichage, adresse e-mail) d'un membre d'une équipe ou d'une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n'est accessible.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous logons un GUID d'utilisateur interne, ainsi que des noms d'organisation et des domaines. Il n'existe aucun contrôle d'archivage ou de suppression pour le moment.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Les données sont stockées dans Microsoft Azure Cloud sur plusieurs microservices en fonction de leur fonction. Toutes les données identifiables par l'utilisateur sont chiffrées côté client avec le chiffrement AES-256 avant la transmission pour le stockage. Les données peuvent être vues par les ingénieurs à des fins de débogage avec l'approbation de nos cadres supérieurs. L'accès aux données est contrôlé via vpn interne.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

