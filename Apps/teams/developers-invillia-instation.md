---
title: Informations d’application pour InStation par les développeurs Invillia
ms.author: elmalova
author: elenamalova
ms.date: 06/30/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour InStation, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 33ef3024f1b0e9b70cb6445e28c71ee1f6de22be
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411772"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 6, 2020</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par les développeurs Invillia à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | InStation |
| ID | WA200001701 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Développeurs Invillia |
| URL du site web partenaire | [https://invillia.com/](https://invillia.com/) |
| URL de la politique de confidentialité | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL des conditions d’utilisation | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par les développeurs Invillia sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.Read.All | délégué | stores : id, join_url, join_web_url et chat_id. Permet à l’application de créer des réunions | stores : id, join_url, join_web_url et chat_id. Permet à l’application de créer des réunions | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| OnlineMeetings.ReadWrite.All | délégué | stores : id, join_url, join_web_url et chat_id. Permet à l’application de créer des réunions | stores : id, join_url, join_web_url et chat_id. Permet à l’application de créer des réunions | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| Presence.Read | délégué | Permet à l’application de connecter l’organisation lors de sa première étape | activité et disponibilité. Permet à l’application de capturer l’état des utilisateurs . | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| Presence.Read.All | délégué | Permet à l’application de se connecter à l’organisation lors de la première étape, | activité et disponibilité. Permet à l’application de capturer l’état des utilisateurs . | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| User.Read | délégué | stores: id, mail, display name, surname and picture. Permet à l’application de rechercher des données utilisateur . | stores: id, mail, display name, surname and picture. Permet à l’application de rechercher des données utilisateur . | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| User.Read.All | délégué | stores: id, mail, display name, surname and picture. Permet à l’application de rechercher des données utilisateur . | stores: id, mail, display name, surname and picture. Permet à l’application de rechercher des données utilisateur . | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| email | délégué | Permet à l’application de capturer les informations de base&#180;administrateur lors de la première connexion | Permet à l’application de capturer les informations de base&#180;administrateur lors de la première connexion | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| offline_access | délégué | stores : jeton et jeton d’actualisation. Permet à l’application d’effectuer une actualisation sur le jeton MS | stores : jeton et jeton d’actualisation. Permet à l’application d’effectuer une actualisation sur le jeton MS | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| openid | délégué | Permet à l’application de connecter l’organisation lors de sa première étape | Permet à l’application de connecter l’organisation lors de sa première étape | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| profil | délégué | Permet à l’application de capturer les informations de base&#180;administrateur lors de la première connexion . | Permet à l’application de capturer les informations de base&#180;administrateur lors de la première connexion . | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous enregistreons uniquement les journaux d’utilisation utilisateur dans notre application.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous enregistreons uniquement les journaux d’utilisation utilisateur dans notre application. Rien de confidentiel, ne nécessitant aucun chiffrement et seuls nos administrateurs spécifiques ont accès à ces données.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


