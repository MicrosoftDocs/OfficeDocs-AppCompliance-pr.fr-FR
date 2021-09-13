---
title: Informations sur l’application pour l’espace d’application par Appspace, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 07/08/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Appspace, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 592194c022b276a07d7fb91d9c0253724d8f28e7
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279957"
---
# <a name="appspace"></a>Appspace

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 8, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9a866c4-e5cf-47f2-932c-db14cb89008f" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001738" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Appspace, Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Appspace |
| ID | WA200001738 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Appspace, Inc. |
| URL du site web partenaire | [https://www.appspace.com](https://www.appspace.com) |
| URL de la Teams d’informations sur l’application | [https://www.appspace.com](https://www.appspace.com) |
| URL de la politique de confidentialité | [https://www.appspace.com/legal/privacy-policy/](https://www.appspace.com/legal/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.appspace.com/legal/user-agreement/](https://www.appspace.com/legal/user-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Appspace, Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Team.ReadBasic.All | délégué | Obtenez les équipes à qui appartient l’utilisateur. | Le cache d’application peut contenir les équipes et les ID à qui le compte d’utilisateur/service a accès. Ces données restent chiffrées tout au long de leur cycle de vie. | [a9a866c4-e5cf-47f2-932c-db14cb89008f](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9a866c4-e5cf-47f2-932c-db14cb89008f) |
>| User.ReadBasic.All | délégué | Lire les propriétés de profil de base d’autres utilisateurs de votre organisation au nom de l’utilisateur inscrit. Cela inclut le nom d’affichage, le nom et prénom, l’adresse e-mail, les extensions ouvertes et la photo. Permet également à l’application de lire le profil complet de l’utilisateur connecté. | Le nom d’utilisateur de l’utilisateur connecté est persistant pour permettre aux utilisateurs d’identifier l’utilisateur ou le compte de service qu’ils ont lié à la plateforme d’espace d’application. | [a9a866c4-e5cf-47f2-932c-db14cb89008f](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9a866c4-e5cf-47f2-932c-db14cb89008f) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous chiffrons les données dans nos systèmes de façon à maintenir un contrôle total du cycle de vie des données.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35872' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35872" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Appspace, Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
