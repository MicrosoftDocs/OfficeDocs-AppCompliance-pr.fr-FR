---
title: Informations d’application pour Trivia par Springworks HR Tech
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Trivia, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: fbd1b9f5f308f3690a9d55a40993ba6122e8f81b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553845"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Janvier 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Springworks HR Tech à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Trivia |
| ID | WA200001956 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Springworks HR Tech |
| URL du site web partenaire | [https://springworks.in/](https://springworks.in/) |
| URL de la page Teams’informations d’application | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| URL de la politique de confidentialité | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| URL des conditions d’utilisation | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Springworks HR Tech sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | Délégué | Non | Pour obtenir la liste des Teams que l’utilisateur fait partie de | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| Team.ReadBasic.All | Délégué | Oui, le stockage de la liste des équipes dans lesquelles le bot a été ajouté | Recueillir des informations de base sur toutes les équipes présentes dans un espace de travail | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| User.Read.All | Délégué | Oui, pour stocker aadObjectId unique d’un utilisateur. Aussi divers détails de l’utilisateur comme nom d’utilisateur, e-mail, etc et l’afficher sur le tableau de bord Trivia | Pour obtenir les détails de tous les utilisateurs présents dans un espace de travail | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| openid | Délégué | Oui, pour stocker les utilisateurs qui se connectent à l’application. |  Permettre à l’utilisateur d’utiliser l’application avec son compte et l’application pour utiliser les données de l’utilisateur | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| profil | Délégué | Oui, pour stocker les identifiants des utilisateurs et les noms des hôtes de quiz et d’autres fonctionnalités, et les identifier de manière unique | Pour lire les informations de profil de base de l’utilisateur comme le nom d’utilisateur, envoyez un e-mail | 43bc466a-7678-476f-b904-2d933c5bbfc3 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS, Mailchimp, Stripe.  | Nom du client, e-mail, IP, informations de paiement | Nous utilisons ces tiers pour offrir la meilleure expérience client à nos clients |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Ces données sont utilisées pour afficher et stocker la liste des participants à un quiz et à d’autres fonctionnalités de ce type. | Nom, Email | Oui, stocker les données de l’hôte et des participants de quiz et d’autres fonctionnalités pour l’analyse et la communication avec l’hôte en cas d’erreurs |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>OII : nom de l’organisation, pièce d’identité du locataire apparaissent dans les journaux; EUII: aad Object ID, nom complet, e-mail apparaissent dans les journaux. nous avons un poste de 30 jours de période de rétention que les journaux sont automatiquement supprimés. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Données stockées dans RDS, AWS. il est crypté. L’accès n’est qu’à un ingénieur DevOps, ingénieur principal et fondateur

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Springworks HR Tech sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
