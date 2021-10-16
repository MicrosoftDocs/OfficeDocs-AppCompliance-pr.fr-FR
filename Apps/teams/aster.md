---
title: Informations d’application pour Aster par Aster
ms.author: elmalova
author: elenamalova
ms.date: 09/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Aster, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 11edf7f1d092a565b0c69155a1c2be4213c206e2
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60415261"
---
# <a name="aster"></a>Aster

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2021</p>

* <a href="https://teams.microsoft.com/l/app/2d8e8042-66df-4605-8c3a-9ca8962f3e99" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002379" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Aster à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Aster |
| ID | WA200002379 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Aster |
| URL du site web partenaire | [https://asterapp.co](https://asterapp.co) |
| URL de la Teams d’informations sur l’application | [https://asterapp.co/solution/](https://asterapp.co/solution/) |
| URL de la politique de confidentialité | [https://asterapp.co/politique-de-confidentialite/](https://asterapp.co/politique-de-confidentialite/) |
| URL des conditions d’utilisation | [https://asterapp.co/conditions-generales/](https://asterapp.co/conditions-generales/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Aster sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | délégué | Liste des répertoires pour l’envoi de tâches de planificateur de documents Sharepoint | Aucune | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Group.ReadWrite.All | délégué | Liste des groupes pour l’envoi de tâches planificateur de documents Sharepoint dans des groupes existants ou créés | Aucune | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Notes.ReadWrite.All | délégué | Contenu des notes pour l’écriture OneNote | Aucune | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Tasks.ReadWrite.Shared | délégué | Tâches, affectation, délais | Toutes ces données pour la synchronisation des tâches Graph API avec les tâches Aster | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| User.Read | délégué | Courrier électronique de l’utilisateur pour l’identification de l’utilisateur | Courrier électronique de l’utilisateur dans les assignations par exemple | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| offline_access | délégué | Aucune donnée collectée, juste pour actualiser le jeton sans y avoir l’air | Aucune | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Pour communiquer avec l’utilisateur de manière humaine et personnalisée | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Tous les accès sont enregistrés, identifiés par les e-mails des utilisateurs

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Contrat RGPD

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Aster sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Non |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

