---
title: Informations sur l’application pour Weekly10 par Binary Limited
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Weekly10, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: e0b197ba692a1516f12c6268ccd6f8ad723146af
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428841"
---
# <a name="weekly10"></a>Weekly10

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 19, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c80cee99-d17f-4b2d-a2a4-57652ffd2a4b" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001441" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Binary Binaire Limitée à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Weekly10 |
| ID | WA200001441 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Binary Binaire Limited |
| URL du site web partenaire | [https://www.weekly10.com](https://www.weekly10.com) |
| URL de la Teams d’informations sur l’application | [https://www.weekly10.com/integrations/microsoft-teams/](https://www.weekly10.com/integrations/microsoft-teams/) |
| URL de la politique de confidentialité | [https://www.weekly10.com/terms/privacy](https://www.weekly10.com/terms/privacy) |
| URL des conditions d’utilisation | [https://www.weekly10.com/terms/customer](https://www.weekly10.com/terms/customer) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Binary Limited sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | application | Synchronisation des utilisateurs de Azure AD vers Weekly10 (facultatif) | Données d’identité d’utilisateur : nom d’utilisateur principal, e-mail, prénom, nom et responsable. | [2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb](https://docs.microsoft.com/microsoft-365-app-certification/azure/2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb) |
>| Calendars.ReadWrite | application | Vérification de la disponibilité des employés et de la réservation automatisée des réunions (facultatif). | Les heures de disponibilité des employés (pas les détails) et lorsqu’une réunion est réservée, la référence à cette réunion. Ces données sont utilisées pour comprendre si un employé est en dehors du bureau pour une expérience transparente et pour réserver des réunions en 1:1 ou des révisions de performances. | [494610b2-b490-4f54-8384-312d6f9b4869](https://docs.microsoft.com/microsoft-365-app-certification/azure/494610b2-b490-4f54-8384-312d6f9b4869) |
>| User.Read | délégué | Vérification de l’utilisateur à des fins DSO sur le Azure AD. | Aucune donnée supplémentaire n’est conservée en dehors des informations de jeton. | [6fd1421e-89e8-4a8b-bd01-9397656a50d5](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fd1421e-89e8-4a8b-bd01-9397656a50d5) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Nous accédons uniquement à l Teams’ID d’utilisateur de la personne. Cela signifie que le bot peut répondre d’une manière spécifique à cet utilisateur. | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nom d’organisation et noms d’utilisateur en cas de bogue ou de problème signalé. Les journaux sont stockés dans ce format pendant 30 jours, puis supprimés.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Toutes les données résidant dans Weekly10 peuvent être contrôlées par des administrateurs spécifiés. Lorsque vous modifiez des stratégies dans Weekly10, cela a un impact direct sur les données Microsoft Azure (où résident les données clientes).

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Binary Limited sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/><br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
