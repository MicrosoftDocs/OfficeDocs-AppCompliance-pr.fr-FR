---
title: Informations d’application pour COCO par Hexaware Technologies Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 09/27/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour COCO, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8e0dbf1b70767805b01cb6a318e4d00c3399c8ee
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414590"
---
# <a name="coco"></a>COCO

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: August 9, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c3f021f9-1fe2-44c7-972e-58f3cd0e7762" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001468" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Hexaware Technologies Ltd. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | COCO |
| ID | WA200001468 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Hexaware Technologies Ltd. |
| URL du site web partenaire | [https://hexaware.com](https://hexaware.com) |
| URL de la Teams d’informations sur l’application | [https://tinyurl.com/2c6b9cdm](https://tinyurl.com/2c6b9cdm) |
| URL de la politique de confidentialité | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf) |
| URL des conditions d’utilisation | [https://tinyurl.com/2c6b9cdm](https://tinyurl.com/2c6b9cdm) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Hexaware Technologies Ltd. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | délégué | Aucune | Accéder à l’annuaire en tant qu’utilisateur | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| Directory.Read.All | application | Aucune | Lire les données de l’annuaire | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| Directory.ReadWrite.All | délégué | Aucune | Lire et écrire les données de l’annuaire | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.Read | délégué | Aucune | Activer la connexion et lire le profil utilisateur | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.Read.All | application | Aucune | Lire les profils complets de tous les utilisateurs | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.ReadWrite.All | délégué | Aucune | Lire et écrire les profils complets de tous les utilisateurs | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| openid | délégué | Aucune | Connecter des utilisateurs | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Pour gérer les données de session | Nom, ID d’e-mail | Gestion des sessions Chatbot |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>N/A

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Hexaware Technologies Ltd. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

