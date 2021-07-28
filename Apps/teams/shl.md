---
title: Informations d’application pour SHL par SHL
ms.author: elmalova
author: elenamalova
ms.date: 06/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour SHL, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5c5b98779e7c038d809a8ecaee60fee1cdf0ca71
ms.sourcegitcommit: 0f47d02fff001cd7cba6a7ab9e276e020cfc053e
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/27/2021
ms.locfileid: "53609955"
---
# <a name="shl"></a>SHL

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 25, 2021</p>

* <a href="https://teams.microsoft.com/l/app/0c52adc0-18a0-45ca-b6ee-154cf1ef87e2" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002887" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SHL à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | SHL |
| ID | WA200002887 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | SHL |
| URL du site web partenaire | [https://shl.com](https://shl.com) |
| URL de la Teams d’informations sur l’application | [https://www.shl.com/en/about/](https://www.shl.com/en/about/) |
| URL de la politique de confidentialité | [https://www.shl.com/en/privacy/administrator-data-protectio...](https://www.shl.com/en/privacy/administrator-data-protection-notice/) |
| URL des conditions d’utilisation | [https://www.shl.com/en/terms-of-service/](https://www.shl.com/en/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par SHL sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | délégué | Emplacements partagés disponibles | N/A | [afd2c390-8b78-40fa-913b-7fc5911e884a](https://docs.microsoft.com/microsoft-365-app-certification/azure/afd2c390-8b78-40fa-913b-7fc5911e884a) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Nous transférons des données aux services de notre propre application (Talentcentral : https://talentcentral.eu.shl.com/admin) | EUII : nom d’utilisateur et ID d’utilisateur des équipes Microsoft Teams | Le nom d’utilisateur Teams’application est utilisé dans notre autre application qui déclenche des messages électroniques avec son nom d’utilisateur. et identificateur d’utilisateur que nous conserverons comme identificateur et mappages avec notre application&#8217;'ID utilisateur. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Le nom d’utilisateur Teams’application est utilisé dans notre autre application qui déclenche des messages électroniques avec son nom d’utilisateur. et identificateur utilisateur que nous conserverons en tant qu’identificateur et que nous mappages avec l’ID&#8217;'utilisateur de notre application | Nom d’utilisateur microsoft teams et ID d’utilisateur teams | Le nom d’utilisateur Teams’application est utilisé dans notre autre application qui déclenche des messages électroniques avec son nom d’utilisateur. et identificateur utilisateur que nous conserverons en tant qu’identificateur et que nous mappages avec l’ID&#8217;'utilisateur de notre application |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous ne contrôlons pas les données, nous les traiterons simplement.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par SHL sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
