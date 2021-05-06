---
title: Informations d’application pour OpenAgora par Open Agora
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour OpenAgora, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 686d19238196db87387b7574c738e0e09746d047
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250452"
---
# <a name="openagora"></a>OpenAgora

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/cb6d958a-d969-4081-8272-71fa94f1697f" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381473" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Open Agora à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | OpenAgora |
| ID | WA104381473 |
| Fonctionnalités | Bot, Onglet |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Open Agora |
| URL du site web partenaire | [https://www.open-agora.com/en/products/teams](https://www.open-agora.com/en/products/teams) |
| URL de la Teams d’informations sur l’application | [https://www.open-agora.com/en/products/teams/support](https://www.open-agora.com/en/products/teams/support) |
| URL de la politique de confidentialité | [https://www.open-agora.com/en/products/teams/privacy-policy](https://www.open-agora.com/en/products/teams/privacy-policy) |
| URL des conditions d’utilisation | [https://www.open-agora.com/en/terms](https://www.open-agora.com/en/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Open Agora sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | délégué | ID&#8217;'Azure Active Directory utilisateur. | Identification de l’utilisateur, pour s’assurer que les utilisateurs peuvent voir et gérer uniquement les données visibles pour eux. |  |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| **Nom** utilisé pour afficher le nom du votant. **Courrier** électronique : utilisé pour identifier l’utilisateur dans les équipes et les conversations ; utilisé comme identificateur unique du votant ; permet de répondre aux commentaires des utilisateurs au sein Teams. Aucun courrier non sollicité n’est envoyé aux utilisateurs. | Prénom et nom, nom d’affichage, adresse e-mail |  |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Tous les EUII et OII peuvent être récupérés via les journaux des applications, avec le même niveau de sécurité que toutes les données d’application (serveurs privés, isolation de conteneur, accès restreint).
Les données du journal sont supprimées au bout de 2 ans.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Sur demande, les données client peuvent être auditées à tout moment et supprimées après la désinstallation de l’application.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35694' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35694" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

