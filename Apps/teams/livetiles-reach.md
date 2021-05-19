---
title: Informations d’application pour Reach par LiveTiles
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Reach, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83df050a6f58bc1d0b7d49239b40ddf2ba80849a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551995"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Mars 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par LiveTiles à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Reach |
| ID | WA200002045 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | LiveTiles |
| URL du site web partenaire | [https://livetilesglobal.com](https://livetilesglobal.com) |
| URL de la page Teams’informations d’application | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| URL de la politique de confidentialité | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| URL des conditions d’utilisation | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par LiveTiles sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Send | application | none | none | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | Délégué | Nom d’affichage d’utilisateur, adresse e-mail utilisateur, UPN. Requis pour permettre aux utilisateurs de se connecter à l’application et d’obtenir des informations de base de l’utilisateur connecté, telles que le nom de l’écran. L’adresse e-mail est utilisée pour envoyer des notifications par e-mail.  | Nom d’affichage d’utilisateur, adresse e-mail utilisateur, UPN. Requis pour permettre aux utilisateurs de se connecter à l’application et d’obtenir des informations de base de l’utilisateur connecté, telles que le nom de l’écran. L’adresse e-mail est utilisée pour envoyer des notifications par e-mail.  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | Délégué | Nom d’affichage de l’utilisateur, adresse e-mail utilisateur, UPN, Département utilisateur, Titre du travail de l’utilisateur, Numéro de Téléphone mobile utilisateur, Numéro de Téléphone d’entreprise utilisateur, Office’utilisateur. Requis pour permettre aux utilisateurs de rechercher d’autres utilisateurs dans l’application (Annuaire téléphonique) et de voir le profil de base et les coordonnées des autres utilisateurs.  | aucune | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | application | Membres du groupe, groupes AD dans l’annuaire. Les membres de groupe des utilisateurs sont stockés dans un cache afin de minimiser les appels vers Microsoft Graph API. Requis pour permettre aux utilisateurs de rechercher des groupes d’annuaires actifs. En outre, cette autorisation est nécessaire pour que l’application résolve l’adhésion de groupe AD des utilisateurs dans les travaux Web du backend. | Membre du groupe des utilisateurs. Les membres de groupe des utilisateurs sont stockés dans un cache afin de minimiser les appels vers Microsoft Graph API. Requis pour permettre aux utilisateurs de rechercher des groupes d’annuaires actifs. En outre, cette autorisation est nécessaire pour que l’application résolve l’adhésion de groupe AD des utilisateurs dans les travaux Web du backend.  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | application | Les données récupérées à partir du profil de l’utilisateur dépendent de la configuration de fonctionnalité de ciblage d’audience spécifiée dans l’application. Requis pour permettre à l’application de lire les profils des utilisateurs sans un utilisateur connecté. La lecture des données de profil est nécessaire pour la fonction de ciblage des informations au sein de l’application, de sorte que les informations sont affichées à des utilisateurs spécifiques en fonction d’une valeur de propriété de profil spécifique.  | aucune | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| SendGrid, OneSignal | adresse e-mail, nom d’affichage | Envoyer une notification à l’utilisateur par e-mail et notifications push mobile |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>adresse e-mail, UPN. maximum. 60 jours de rétention, après qu’ils sont enlevés

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les administrateurs peuvent contacter le support pour toute demande

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par LiveTiles sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Non |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Énumérer les types de politiques prises en charge | Authentification multifacteurs, restriction des emplacements des utilisateurs et des plages IP |
| Votre application demande-t-elle le moins d’autorisations de privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles fidèlement les autorisations que votre application demandera de manière dynamique et progressive ? | Oui |
| Votre application prend-elle en charge la multi-location ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Possédez-vous l’ensemble de l’identifiant de ressources unifié (URI) redirigé enregistré pour votre application ? | Oui |
| Pour votre application, qu’évitez-vous d’utiliser ? | - Wildcard rediriger les URL,<br/>- OAuth2 Implicite Flow, sauf si nécessaire pour un SPA<br/>- Flux d’identification de mot de passe propriétaire de ressources (ROPC) |
| Votre application expose-t-elle des API Web ? | Oui |
| Votre modèle d’autorisation ne permet-il aux appels de réussir que si l’application client reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de prévisualisation ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
