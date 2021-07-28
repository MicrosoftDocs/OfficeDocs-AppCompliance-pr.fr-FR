---
title: Informations sur l’application pour Le parcage d’applications par le logiciel
ms.author: elmalova
author: elenamalova
ms.date: 05/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Le Parcager, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e79bed420b3081ae31a0abda25299610eeb1bc5f
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525508"
---
# <a name="lucidspark"></a>Lucidspark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e9ab21fa-5fd5-48bb-a85d-4de7ced89cd1" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002583" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Software à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Lucidspark |
| ID | WA200002583 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Logiciel Lucid |
| URL du site web partenaire | [https://lucid.co](https://lucid.co) |
| URL de la Teams d’informations sur l’application | [https://lucidchart.zendesk.com](https://lucidchart.zendesk.com) |
| URL de la politique de confidentialité | [https://lucid.co/privacy](https://lucid.co/privacy) |
| URL des conditions d’utilisation | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par l’éditeur de logiciels Sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | délégué | Nom et adresse de messagerie. | Les autorisations de messagerie, d’openid et de profil permettent à L’ParciersPark de générer un jeton openid pour un utilisateur et d’obtenir suffisamment d’informations de base sur l’utilisateur pour inscrire un compte de parcpark pour lui si nécessaire. Afin de vérifier les données qui proviennent de Microsoft, nous demandons d’obtenir la clé publique avec qui leur réponse est signée. Aucune autre donnée n’est reçue de Microsoft ou envoyée à Microsoft dans le cadre de notre flux d' utilisateurs sso. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| openid | délégué | Nom et adresse de messagerie. | Les autorisations de messagerie, d’openid et de profil permettent à L’ParciersPark de générer un jeton openid pour un utilisateur et d’obtenir suffisamment d’informations de base sur l’utilisateur pour inscrire un compte de parcpark pour lui si nécessaire. Afin de vérifier les données qui proviennent de Microsoft, nous demandons d’obtenir la clé publique avec qui leur réponse est signée. Aucune autre donnée n’est reçue de Microsoft ou envoyée à Microsoft dans le cadre de notre flux d' utilisateurs sso. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| profil | délégué | Nom et adresse de messagerie. | Les autorisations de messagerie, d’openid et de profil permettent à L’ParciersPark de générer un jeton openid pour un utilisateur et d’obtenir suffisamment d’informations de base sur l’utilisateur pour inscrire un compte de parcpark pour lui si nécessaire. Afin de vérifier les données qui proviennent de Microsoft, nous demandons d’obtenir la clé publique avec qui leur réponse est signée. Aucune autre donnée n’est reçue de Microsoft ou envoyée à Microsoft dans le cadre de notre flux d' utilisateurs sso. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Les données de parcage et d’chart sont stockées dans AWS etFlflflches | Nom de l’organisation, coordonnées et niveau de licence | Nous n’utilisons aucune API Microsoft. Nous utilisons openID pour obtenir des données utilisateur de base afin d’effectuer l’ouvrez-vous. Nous utilisons leur API de s’il s’agit de fichiers, mais cela ne nous donne pas accès aux fichiers de l’utilisateur autres que ceux qu’il nous envoie par le biais du s picker. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous logons les e-mails et les adresses IP pour des raisons de sécurité et de support. Tous les accès aux journaux sont enregistrés et ne peuvent pas être changés &amp; dans un système tiers. L’accès aux journaux nécessite l' mba.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données depark et d’chart sont stockées dans AWS. Il est chiffré au repos et en transit. Ce dernier utilise les règles de privilège minimum et d’mf.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies parFact Software sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
