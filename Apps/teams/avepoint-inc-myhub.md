---
title: Informations d’application pour MyHub par AvePoint, inc.
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour MyHub, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 60e092ce616ab93cc661149f5f936b900277f0de
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430886"
---
# <a name="myhub"></a>MyHub

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: August 24, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c3ff6344-f6f0-4bfa-8697-b9d47b32ca4b" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000726" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par AvePoint, inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | MyHub |
| ID | WA200000726 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | AvePoint, Inc. |
| URL du site web partenaire | [https://www.avepoint.com](https://www.avepoint.com) |
| URL de la Teams d’informations sur l’application | [https://www.avepoint.com/products/cloud/myhub](https://www.avepoint.com/products/cloud/myhub) |
| URL de la politique de confidentialité | [https://www.avepoint.com/privacy-policy/](https://www.avepoint.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par AvePoint, inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | les deux | les données de configuration d’application sont stockées du point de vue de la gestion des données ; | Lire les données de l’annuaire | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Group.ReadWrite.All | les deux | les données de configuration d’application sont stockées du point de vue de la gestion des données ; | Lire et écrire tous les groupes | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Mail.Send | délégué | les données de configuration d’application sont stockées du point de vue de la gestion des données ; | Envoyer un courrier électronique en tant qu’utilisateur | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Reports.Read.All | application | les données de configuration d’application sont stockées du point de vue de la gestion des données ; | Accéder en lecture à tous les rapports d’utilisation | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.FullControl.All | application | les données de configuration d’application sont stockées du point de vue de la gestion des données ; | Contrôler pleinement toutes les collections de sites | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.Read.All | application | les données de configuration d’application sont stockées du point de vue de la gestion des données ; | Lire des éléments dans toutes les collections de sites | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.ReadWrite.All | délégué | les données de configuration d’application sont stockées du point de vue de la gestion des données ; | Modifier ou supprimer des éléments dans toutes les collections de sites | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| User.Read.All | les deux | les données de configuration d’application sont stockées du point de vue de la gestion des données ; | Lire tous les utilisateurs&#8217; profils complets | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui, le courrier électronique et l’ID client de l’utilisateur apparaissent dans les journaux. Les journaux sont stockés dans un emplacement sécurisé et seul le personnel autorisé peut y accéder lors du dépannage. Les journaux seront archivés après 60 jours à des fins d’audit de sécurité et supprimés au bout d’un an.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données de l’application sont stockées dans Azure SQL Database et stockage Azure. Le chiffrement SQL azure stockage Azure est activé.
Seuls les administrateurs autorisés peuvent accéder aux données. L’authentification MFA est requise pour que les administrateurs se connectent. Les opérations sont auditées. La liste d’adresses IP est également utilisée pour restreindre l’accès aux données.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par AvePoint, inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | L’application se fédéré avec Azure AD, afin que toutes les règles d’accès conditionnel soient utilisées. |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
