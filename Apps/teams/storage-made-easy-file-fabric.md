---
title: Informations d’application pour La structure de fichiers Stockage facilité
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour La structure de fichiers, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 6176cbf56aa94dd460e5f3e60127e65339d05157
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430746"
---
# <a name="file-fabric"></a>File Fabric

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 30, 2021</p>

* <a href="https://teams.microsoft.com/l/app/bd063a87-1e4d-42cf-baea-8cab71839e35" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003017" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Stockage Facilité d’accès à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | File Fabric |
| ID | WA200003017 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Storage Made Easy |
| URL du site web partenaire | [https://storagemadeeasy.com](https://storagemadeeasy.com) |
| URL de la Teams d’informations sur l’application | [https://docs.storagemadeeasy.com/microsoft-teams](https://docs.storagemadeeasy.com/microsoft-teams) |
| URL de la politique de confidentialité | [https://www.storagemadeeasy.com/privacy](https://www.storagemadeeasy.com/privacy) |
| URL des conditions d’utilisation | [https://www.storagemadeeasy.com/terms](https://www.storagemadeeasy.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Stockage Faciliter la collecte et le stock des données organisationnelles par cette application, ainsi que le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite | application | Données de fichier lues ou écrites lorsque l’utilisateur télécharge, télécharge ou modifie des fichiers spécifiés via l’application. | Données de fichier non stockées. | [0752d800-857f-49bd-87eb-e60985516c67](https://docs.microsoft.com/microsoft-365-app-certification/azure/0752d800-857f-49bd-87eb-e60985516c67) |
>| Sites.ReadWrite.All | application | Métadonnées collectées pour tous les fichiers&#8217;utilisateur et dossiers fournissant une vue fédérée dans tous les services de fichiers. | Métadonnées mises en cache pour accélérer la navigation et la recherche. | [0752d800-857f-49bd-87eb-e60985516c67](https://docs.microsoft.com/microsoft-365-app-certification/azure/0752d800-857f-49bd-87eb-e60985516c67) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Stockage Blob Azure | Oui | Métadonnées et données d’objet | Métadonnées collectées pour tous les fichiers&#8217;utilisateur et dossiers fournissant une vue fédérée dans tous les services de fichiers. Objets lus ou écrits lorsque l’utilisateur télécharge, télécharge ou modifie des objets spécifiés via l’application. | Les métadonnées d’objet sont stockées | Métadonnées mises en cache pour accélérer la navigation et la recherche. |
>| Office pour le web | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| L’utilisateur peut s’authentifier et se connecter à tous les services de stockage qu’il contrôle. | Les métadonnées de fichier et d’objet sont mises en cache pour la navigation et la recherche fédérées. Les données sont transférées lorsque des fichiers ou des objets spécifiques sont lus et mis à jour. | Les métadonnées fournissent une vue fédérée dans le stockage. Le transfert de données permet un accès universel sécurisé. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Accords de traitement des données selon le R GDPR

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Stockage Facilité de gestion de l’authentification, de l’autorisation, des meilleures pratiques d’inscription d’application et d’autres critères d’identité.

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
