---
title: Informations d’application pour smart Connecter pour Jira par yasoon GmbH
ms.author: elmalova
author: elenamalova
ms.date: 01/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Smart Connecter pour Jira, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6fb1be576d588727c75f14d72db48bc3a7a8aeb5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550734"
---
# <a name="smart-connect-for-jira"></a>Smart Connect pour Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Janvier 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par yasoon GmbH à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Smart Connect pour Jira |
| ID | WA200002055 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | yasoon GmbH |
| URL du site web partenaire | [https://yasoon.com](https://yasoon.com) |
| URL de la page Teams’informations d’application | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| URL de la politique de confidentialité | [https://yasoon.com/privacy-policy-services](https://yasoon.com/privacy-policy-services) |
| URL des conditions d’utilisation | [https://yasoon.com/terms-of-use](https://yasoon.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par yasoon GmbH sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | Délégué | L’autorisation est utilisée pour laisser l’utilisateur sélectionner l’un de ces canaux rejoints dans Jira. | Id de canal, à des fins de mise en cache | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Read.Group | application | Permet à l’application d’afficher des messages de canaux liés dans Jira. | IDs de message pour lier des messages aux issues de Jira | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Send | Délégué | Aucune donnée n’est utilisée, cette API est utilisée pour permettre à l’utilisateur de répondre aux messages de canal de Jira. | Aucune | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelSettings.Read.Group | application | Utilisé pour rechercher des informations détaillées sur un canal. | Aucune | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Chat.ReadWrite | Délégué | Utilisé pour permettre à l’utilisateur d’ajouter de nouvelles réponses aux chats et de visualiser les messages de chat de Jira. | Aucune | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Member.Read.Group | application | Utilisé pour les contrôles d’autorisation, permet à l’application de valider l’adhésion de l’équipe des utilisateurs. | Aucune | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Team.ReadBasic.All | Délégué | L’autorisation est utilisée pour laisser l’utilisateur sélectionner l’une de ces équipes jointes à Jira. | Identifications d’équipe à des fins de mise en cache | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| TeamSettings.Read.Group | application | Permet à l’application de lire les paramètres de l’équipe pour respecter certaines valeurs par défaut. | Aucune | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| User.ReadBasic.All | Délégué | Permet à l’utilisateur de sélectionner des collègues à @-mention dans un message de canal | Aucune | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Atlassian Jira et peut-être l’un de nos entrepreneurs, peut être vu ici: https://go.yasoon.com/contractors | Métadonnées de messages (ids, timestamps), métadonnées utilisateur et organisationnelles (identifiants d’utilisateur, identifiants org) et adresses e-mail utilisateur | Prendre en charge les fonctionnalités de l’application (par exemple en faisant correspondre les comptes Atlassian avec Office comptes) et en permettant à notre support de résoudre les problèmes plus rapidement. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Correspondance des utilisateurs Teams compte avec le compte Atlassian Jira des utilisateurs | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Métadonnées de l’utilisateur (id)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Nous ne travaillons qu’avec des services qui offrent des garanties strictes en matière de confidentialité des données. 

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par yasoon GmbH sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle le moins d’autorisations de privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles fidèlement les autorisations que votre application demandera de manière dynamique et progressive ? | Oui |
| Votre application prend-elle en charge la multi-location ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Possédez-vous l’ensemble de l’identifiant de ressources unifié (URI) redirigé enregistré pour votre application ? | Oui |
| Pour votre application, qu’évitez-vous d’utiliser ? | - Wildcard rediriger les URL,<br/>- OAuth2 Implicite Flow, sauf si nécessaire pour un SPA<br/>- Flux d’identification de mot de passe propriétaire de ressources (ROPC) |
| Votre application expose-t-elle des API Web ? | Non |
| Votre application utilise-t-elle des API de prévisualisation ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
