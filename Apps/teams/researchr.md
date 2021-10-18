---
title: Informations d’application pour researcHR par KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
ms.date: 08/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour researcHR, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c66735e8d928de6cd469773477be5a9258128c16
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429111"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par KBE&#26666;&#24335;&#20250;&#31038; à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | researcHR |
| ID | WA200002557 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | KBE&#26666;&#24335;&#20250;&#31038; |
| URL du site web partenaire | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| URL de la Teams d’informations sur l’application | [https://app.researchr.work](https://app.researchr.work) |
| URL de la politique de confidentialité | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| URL des conditions d’utilisation | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par KBE&#26666;&#24335;&#20250;&#31038; sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | application | Nous utilisons cette étendue pour permettre à notre bot de créer un canal sur le client Teams client. Voir : https://docs.microsoft.com/en-us/graph/api/channel-post | Nous ne stockons pas ces données dans notre base de données. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Directory.Read.All | application | Nous utilisons cette étendue pour obtenir les ID de canal et les noms pour afficher ces données sur notre site web. Voir : https://docs.microsoft.com/en-us/graph/api/channel-list | Nous ne stockons pas ces données dans notre base de données. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Group.Read.All | application | Nous utilisons cette étendue pour obtenir les ID de canal et les noms pour afficher ces données sur notre site web. Voir : https://docs.microsoft.com/en-us/graph/api/channel-list | Nous ne stockons pas ces données dans notre base de données. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Team.ReadBasic.All | application | Nous utilisons cette étendue pour obtenir les membres de l’équipe afin que les utilisateurs peuvent voir leurs membres sur notre site web. Voir : https://docs.microsoft.com/en-us/graph/api/group-list-members | Nous ne stockons pas ces données dans la base de données. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.Read.All | application | Nous utilisons cette étendue pour obtenir les canaux joints de l’utilisateur afin que les utilisateurs peuvent voir leurs équipes jointes sur notre site web. Voir : https://docs.microsoft.com/en-us/graph/api/user-list-joinedteams | Nous ne stockons pas ces données dans notre base de données. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.ReadBasic.All | délégué | Nous utilisons cette étendue pour activer la connexion OAuth et collecter l’ID AAD de l’utilisateur, le jeton d’accès et le jeton d’actualisation. Voir : https://docs.microsoft.com/en-us/graph/auth-v2-user | Nous stockons l’ID AAD, le jeton d’accès et le jeton d’actualisation de l’utilisateur dans notre base de données afin que l’utilisateur puisse se connecter à notre site web avec OAuth. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| offline_access | délégué | Nous utilisons cette étendue pour obtenir le jeton d’actualisation afin que nous pouvons actualiser le jeton d’accès des utilisateurs authentés sans aucune interaction utilisateur. Voir : https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#offline_access | Nous stockons le jeton d’actualisation dans notre base de données afin de pouvoir actualiser le jeton d’accès sans aucune interaction utilisateur. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Toutes les données de la base de données sont chiffrées. Les sauvegardes des données de base de données seront prises et stockées pendant une certaine période conformément à notre stratégie d’exploitation interne. Si un utilisateur annule ce service, nous supprimons les informations utilisateur de l’utilisateur sans délai, sauf dans la mesure nécessaire pour respecter les obligations de stockage prévues par la loi. Voici les détails. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par KBE&#26666;&#24335;&#20250;&#31038; sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
