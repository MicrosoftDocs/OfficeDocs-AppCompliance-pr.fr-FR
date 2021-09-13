---
title: Informations sur l’application pour diagrammes de diagrammes Excel parFact Software Inc
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour les diagrammes d’diagrammes de Excel, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: eedc4340815926a96f52e2abebc2d553f07583e3
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281979"
---
# <a name="lucidchart-diagrams-for-excel"></a>Diagrammes d’image graphique pour Excel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380194" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Software Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Diagrammes d’image graphique pour Excel |
| ID | WA104380194 |
| Office 365 clients pris en charge | Excel 2016 ou une ultérieure sur Mac, Excel 2013 ou une Windows, Excel sur le Web |
| Nom de la société partenaire | Lucid Software Inc |
| URL du site web partenaire | [https://www.lucidchart.com](https://www.lucidchart.com) |
| URL de la politique de confidentialité | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL des conditions d’utilisation | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Lass Software Inc. sur la façon dont cette application collecte et stocke les données organisationnelles, ainsi que sur le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | délégué | Nom et adresse de messagerie. | Les autorisations de messagerie, d’openid et de profil permettent à Cechart de générer un jeton openid pour un utilisateur et d’obtenir suffisamment d’informations de base sur l’utilisateur pour inscrire un compte Dechart pour lui si nécessaire. Afin de vérifier les données qui proviennent de Microsoft, nous demandons d’obtenir la clé publique avec qui leur réponse est signée. Aucune autre donnée n’est reçue de Microsoft ou envoyée à Microsoft dans le cadre de notre flux d' utilisateurs sso. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | délégué | Nom et adresse de messagerie. | Les autorisations de messagerie, d’openid et de profil permettent à Cechart de générer un jeton openid pour un utilisateur et d’obtenir suffisamment d’informations de base sur l’utilisateur pour inscrire un compte Dechart pour lui si nécessaire. Afin de vérifier les données qui proviennent de Microsoft, nous demandons d’obtenir la clé publique avec qui leur réponse est signée. Aucune autre donnée n’est reçue de Microsoft ou envoyée à Microsoft dans le cadre de notre flux d' utilisateurs sso. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profil | délégué | Nom et adresse de messagerie. | Les autorisations de messagerie, d’openid et de profil permettent à Cechart de générer un jeton openid pour un utilisateur et d’obtenir suffisamment d’informations de base sur l’utilisateur pour inscrire un compte Dechart pour lui si nécessaire. Afin de vérifier les données qui proviennent de Microsoft, nous demandons d’obtenir la clé publique avec qui leur réponse est signée. Aucune autre donnée n’est reçue de Microsoft ou envoyée à Microsoft dans le cadre de notre flux d' utilisateurs sso. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Interface API JavaScript pour Office | Oui | Nous utilisons le SDK javascript Office OneDrive pour ouvrir le SDK OneDrive à l’aide de OneDrive.open(). Nous ne générons aucun jeton d’accès et nous ne faisons pas de demandes aux API OneDrive nous-mêmes ; Le SDK OneDrive s’il s’agit d’un s’il s’agit d’un fichier de recherche le fait pour nous. Nous ne pouvons voir que les noms de fichiers que l’utilisateur choisit. |  | Si l’utilisateur sélectionne un fichier à l’aide OneDrive sélecateur de fichiers, nous stockons le nom du fichier. |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Les données d’unchart sont stockées dans AWS. |  | Nous n’utilisons aucune API Microsoft. Nous utilisons openID pour obtenir des données utilisateur de base afin d’effectuer l’ouvrez-vous. Nous utilisons leur API de s’il s’agit de fichiers, mais cela ne nous donne pas accès aux fichiers de l’utilisateur autres que ceux qu’il nous envoie par le biais du s sélectionneur. |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous logons les e-mails et les adresses IP pour des raisons de sécurité et de support. Tous les accès aux journaux sont enregistrés et ne peuvent pas être changés &amp; dans un système tiers. L’accès aux journaux nécessite l' mba.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données d’unchart sont stockées dans AWS. Il est chiffré au repos et en transit. Cechart utilise les règles de privilège minimum et l’ation MFA.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

