---
title: Informations sur l’application pour l’engagement commercial de sensibilisation Outlook par sensibilisation
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour l’engagement commercial de sensibilisation pour Outlook, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d3b2a00ddb4023a54e78825c2382c1dbdad6f28a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430724"
---
# <a name="outreach-sales-engagement-for-outlook"></a>Engagement commercial de sensibilisation pour Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 14, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381052" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par la sensibilisation à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Engagement commercial de sensibilisation pour Outlook |
| ID | WA104381052 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | Sensibilisation |
| URL du site web partenaire | [https://www.outreach.io](https://www.outreach.io) |
| URL de la politique de confidentialité | [https://www.outreach.io/legal/privacy-policy/](https://www.outreach.io/legal/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.outreach.io/terms](https://www.outreach.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par la communauté sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook API de add-in , API EWS , API REST O36 | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Salesforce CRM | L’intégration de la promotion avec Salesforce permet une synchronisation bi-directionnelle sécurisée d’un jeu de données limité entre les deux services: Nom de l’organisation, adresse e-mail et nom d’utilisateur. | La synchronisation bi-directionnelle intelligente de la sensibilisation garantit une fidélité totale entre les données des deux systèmes. Toutes les activités exécutées dans le &#8212; de &#8212; appels, e-mails, etc. &#8212; sont automatiquement enregistrées dans Salesforce et la résolution des conflits détecte et résout les conflits pour maintenir la proximité des données. Il fonctionne dans les éditions Salesforce Aloha et Flash. |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>La sensibilisation n’applique pas de périodes de rétention aux données&#8217;client. La sensibilisation fonctionne en tant que processeur de données et, en tant que telle, ne modifie jamais les données de nos clients&#8217;sans leur autorisation expresse. Toutes les données client sont supprimées 60 jours après la fin de la relation professionnelle, selon notre MSA et DPA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Pour des raisons contractuelles et réglementaires, il est également nécessaire de fournir à tous les clients une notification en temps opportun de l’utilisation d’un nouveau sous-traitant ou d’un changement de sous-traitant. Pour la plupart des clients de proximité, il s’agit d’une période de 30 jours. Toutefois, nous avons quelques clients ayant des exigences de préavis de 60 et 90 jours. Aucune donnée client ne peut être transférée tant que la notification juridiquement requise d’un nouveau sous-processus n’a pas été envoyée à tous les clients et que la période applicable requise n’a pas été écoulée.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par la sensibilisation sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
