---
title: Informations sur l’application pour Neelix.Team par Neelix.IO
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Neelix.Team, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 968a4ffad3d1c5893414ea3e672474330fc37553
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60437138"
---
# <a name="neelixteam"></a>Neelix.Team

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 10, 2021</p>

* <a href="https://teams.microsoft.com/l/app/bed170ee-dbd7-4efa-b48e-b0937ded1689" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003047" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par les Neelix.IO à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Neelix.Team |
| ID | WA200003047 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Neelix.IO |
| URL du site web partenaire | [https://www.neelix.team](https://www.neelix.team) |
| URL de la Teams d’informations sur l’application | [https://www.neelix.team](https://www.neelix.team) |
| URL de la politique de confidentialité | [https://www.neelix.team/data-security-policy](https://www.neelix.team/data-security-policy) |
| URL des conditions d’utilisation | [https://www.neelix.io/terms-of-use-en](https://www.neelix.io/terms-of-use-en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Neelix.IO sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | délégué | l’application utilise les noms et les ID de canal pour permettre aux utilisateurs de gérer leurs préférences par défaut lors de l’envoi de commentaires à partir de MS Treams | Les noms et les ID de canal sont stockés pour la gestion des valeurs par défaut pour plus de commodité pour l’utilisateur | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| Team.ReadBasic.All | délégué | l’application utilise les noms et les ID d’équipe pour permettre aux utilisateurs de gérer leurs préférences par défaut lors de l’envoi de commentaires à partir de MS Treams | Les noms et les ID d’équipe sont stockés. Ces données nous permettent de configurer des paramètres par défaut pratiques qui permettent l’exécution plus rapide du formulaire de commentaires. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| email | délégué | Le courrier électronique est utilisé dans le cadre de l’inscription de l’utilisateur dans Neelix. Après l’inscription initiale, le courrier électronique est utilisé pour les notifications.  | Le courrier électronique est stocké sur le profil utilisateur. Le courrier électronique est également utilisé pour vérifier que l’utilisateur n’essaie pas d’utiliser le même courrier électronique via un autre canal oauth. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| offline_access | délégué | Utilisé pour obtenir le jeton d’actualisation |  le jeton d’actualisation est stocké afin d’obtenir un nouveau jeton d’accès | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| profil | délégué | Le nom d’utilisateur est utilisé pour créer un compte d’utilisateur lors de l’inscription auprès de Neelix.  | Le nom d’utilisateur est stocké dans le compte d’utilisateur. Cela est nécessaire pour que les autres membres de l’équipe le soient dans leur journal d’équipe. L’utilisateur peut mettre à jour le nom stocké dans Neelix. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| User.Read | délégué | L’application bot utilise user.read pour pouvoir envoyer des informations à l’utilisateur afin que la plateforme principale Neelix puisse identifier l’utilisateur. | Les informations ne sont pas stockées | [bed170ee-dbd7-4efa-b48e-b0937ded1689](https://docs.microsoft.com/microsoft-365-app-certification/azure/bed170ee-dbd7-4efa-b48e-b0937ded1689) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Plateforme d’identités Microsoft | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Les ID de client sont envoyés à notre service back-end en cours d’exécution sur la plateforme Cloud Google | ID de client | Les ID de client sont utilisés à des fins d’identification utilisateur pendant oauth |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| L’application utilise l’ID utilisateur pour identifier l’utilisateur par rapport aux informations inscrites sur la plateforme Neelix | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Les ID de client sont enregistrés dans les journaux système. La stratégie de rétention des journaux est de 30 jours.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Stratégie de l’utilisateur final, procédures de conformité R GDPR, procédures d’annulation de compte et de collecte de données

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Neelix.IO sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
