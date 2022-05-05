---
title: Informations d’application pour ProdBot par Prodoscore
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour ProdBot, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1634f86ba35e82ae4a76992cf9a548e5f33ea21d
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225108"
---
# <a name="prodbot"></a>ProdBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur : 23 février 2021</p>

* <a href="https://teams.microsoft.com/l/app/6f98aae5-4f72-4c33-80a4-ed2153da796a" target="_blank">Afficher dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002620" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Prodoscore à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | ProdBot |
| ID | WA200002620 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Prodoscore |
| URL du site web du partenaire | [https://www.prodoscore.com](https://www.prodoscore.com) |
| URL de Teams page d’informations sur l’application | [https://www.prodoscore.com/how-it-works/](https://www.prodoscore.com/how-it-works/) |
| URL de la politique de confidentialité | [https://www.prodoscore.com/privacy-policy/](https://www.prodoscore.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.prodoscore.com/terms-of-service/](https://www.prodoscore.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Prodoscore sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quel OII est transféré ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud Platform | Nom de domaine | L’inscription à l’application utilise le nom de domaine d’une organisation pour identifier l’organisation de façon unique. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre de l’équipe d’une équipe ou d’une conversation à laquelle elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucune OII ou EUII n’apparaît dans les journaux ou les données de télémétrie des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>Nous avons exposé l’API/point de terminaison pour les systèmes partenaires

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans l’examen ou l’analyse des données d’information d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36556' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36556" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Prodoscore sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Intégrez-vous à La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle d’intégration Plateforme d'identités Microsoft ?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations inscrites statiquement de votre application reflètent-elles précisément les autorisations demandées par votre application de manière dynamique et incrémentielle ? | Oui |
| Votre application prend-elle en charge la mutualisation ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de l’URI (Identificateur de ressource unifié) de redirection inscrit pour votre application ? | Oui |
| Pour votre application, que pouvez-vous éviter d’utiliser ? | - URI de redirection par caractères génériques,<br/><br/> |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle des API de préversion ? | Oui |
| Votre application utilise-t-elle des API déconseillées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
