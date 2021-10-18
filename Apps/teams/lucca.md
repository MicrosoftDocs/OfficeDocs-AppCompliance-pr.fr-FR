---
title: Informations sur l’application pour Lucca par Lucca
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Lucca, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c0ca2e6c6d07dd80afff02a4d9e5081e55633637
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60423166"
---
# <a name="lucca"></a>Lucques

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/53628f6a-ac66-4fde-8945-d639c8da4c0d" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001650" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Lucca à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Lucques |
| ID | WA200001650 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Lucques |
| URL du site web partenaire | [https://www.lucca.fr](https://www.lucca.fr) |
| URL de la politique de confidentialité | [https://www.lucca.fr/privacy-policy](https://www.lucca.fr/privacy-policy) |
| URL des conditions d’utilisation | [https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/Ter...](https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/TermsAndConditions.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Lucca sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | délégué | Aucune donnée n’est collectée. Nous les avons utilisés pour filtrer la planification de l’affichage. Seuls les utilisateurs qui sont dans le canal ont leur planification affichée | Aucune donnée n’est stockée | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Chat.ReadWrite | application | Aucune donnée n’est collectée ou utilisée. L’application publie uniquement un message contenant les absents du jour | Aucune donnée n’est stockée | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Group.Read.All | application | Nous collectons le GroupId pour savoir dans quel groupe l’application doit envoyer le message avec les absents.  | Nous stockons uniquement le GroupId pour enregistrer la configuration que l’utilisateur a réalisée. Il nous permet de savoir dans quel groupe envoyer le message | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read | délégué | Utilisé pour se connecter aux utilisateurs | Aucune donnée n’est stockée | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read.All | application | Utilisé pour lire les profils utilisateur | Aucune donnée n’est stockée | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| email | délégué | Utilisé pour afficher le courrier électronique de l’utilisateur dans l’onglet de l’application | Aucune donnée n’est stockée | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| openid | délégué | Utilisé pour connecter l’utilisateur | Aucune donnée n’est stockée | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| profil | délégué | Utilisé pour afficher le profil utilisateur dans l’onglet de l’application | Aucune donnée n’est stockée | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |


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

>stratégie de l’utilisateur final

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Lucca sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
