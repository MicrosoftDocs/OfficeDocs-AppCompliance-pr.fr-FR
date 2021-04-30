---
title: Informations d'application pour SmartWork par SmartWork d'Intumit
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour SmartWork, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3fa673b3b6488cbca428f4583fe60021734525cf
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093251"
---
# <a name="smartwork"></a>SmartWork

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 31, 2020</p>

* <a href="https://teams.microsoft.com/l/app/a938ae1e-a791-4751-9e6a-178c991fa0fa" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001149" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SmartWork d'Intumit à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | SmartWork |
| ID | WA200001149 |
| Fonctionnalités | Bot |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | SmartWork de Intumit |
| URL du site web partenaire | [https://www.intumit.com](https://www.intumit.com) |
| URL de la politique de confidentialité | [https://www.intumit.com/privacy.html](https://www.intumit.com/privacy.html) |
| URL des conditions d'utilisation | [https://www.intumit.com/english/TermsOfUse.html](https://www.intumit.com/english/TermsOfUse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par SmartWork d'Intumit sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d'autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d'application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | délégué | Utilisation de userPrincipalName pour identifier si le courrier de l'utilisateur est issu d'un AAD valide ou non | Activer la connexion et lire le profil utilisateur | a938ae1e-a791-4751-9e6a-178c991fa0fa |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d'identification de l'utilisateur final (EUII) : la liste (prénom, nom, nom d'affichage, adresse e-mail) d'un membre d'une équipe ou d'une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l'accès à EUII ?**  | **L'EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l'EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Utilisation pour identifier le courrier de l'utilisateur, qu'il provienne d'AAD valide ou non | Liste de courriers de l'utilisateur stocké pour identifier si l'utilisateur est issu d'un AAD valide ou non |  |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Non. Pendant la conversation, nous allons utiliser le mode session pour contrôler. En utilisant l'ID pour correspondre à l'élément dans la base de données, accédez aux données. Nous n'enregistrerons pas spécifiquement les informations de l'utilisateur

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Seul votre compte AAD valide peut accéder à l'application.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35852' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35852" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

