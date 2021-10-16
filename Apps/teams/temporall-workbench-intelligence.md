---
title: Informations sur l’application pour Workbench Intelligence par Temporel
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Workbench Intelligence, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7adf907a083a4fcf5c7c57fe0cf048ba771d0d6e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414430"
---
# <a name="workbench-intelligence"></a>Workbench Intelligence

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d5630318-189a-4912-abae-99b1f8f82cce" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002705" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Le Temps à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Workbench Intelligence |
| ID | WA200002705 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Temporel |
| URL du site web partenaire | [https://www.temporall.com](https://www.temporall.com) |
| URL de la Teams d’informations sur l’application | [https://www.temporall.com/teams_intelligence/](https://www.temporall.com/teams_intelligence/) |
| URL de la politique de confidentialité | [https://temporall.com/privacy-policy/](https://temporall.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.temporall.com/eula](https://www.temporall.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Le Temps sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | délégué | Obtient la liste des applications Teams installées pour pouvoir obtenir l’ID de l’application locale pour l’ID externe connu. | ID de l’application locale. Nécessaire pour pouvoir identifier l’application lorsqu’elle est installée sur un autre client. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Channel.ReadBasic.All | application | Nom de l’ID &amp; de canal. Justification : autoriser la jointation/la sortie du canal pour synchroniser l’activité des messages.  | Objet de données brutes renvoyé par l’obtention du canal. Justification : Workbench temporel permet aux utilisateurs de filtrer et de catégoriser les données en fonction des canaux. Ces données brutes sont enregistrées pour avoir une référence à l’objet d’origine | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| ChannelMessage.Read.All | application | Type &amp; d’activité de message, ainsi que la cible de &amp; l’expéditeur. Données reçues à partir de ces itinéraires : /teams/${teamId}/channels/${channelId}/messages /teams/${teamId}/channels/${channelId}/messages/${messageId}. Justification : pour pouvoir calculer un rapport de mesures sur &amp; l’activité des messages. Cela constitue le cœur de notre module d’analyse réseau d’organisation pour pouvoir dessiner un diagramme d’activité entre les équipes des &amp; utilisateurs. | Nous détectons la quantité de nouveaux messages/réponses/réactions/mentions stockant ces mesures avec l’objet &amp; de message brut renvoyé. Les données sont requises car elles font partie de nos fonctionnalités principales. L’exécution d’une analyse sur les données de message nécessite qu’elle soit enregistrée dans la base de données pour des performances optimales , ce qui réduit également la nécessité d’appels de suivi pour les mêmes données. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Directory.Read.All | application | ClientId, liste des utilisateurs, liste des organisations et sous-canaux. Justification : Nécessaire pour lire les &amp; utilisateurs de synchronisation dans Temporall Workbench | Nom d’utilisateur, e-mail, icône, référence de conversation. Justification :&#160;Workbench temporel permet aux utilisateurs de filtrer et de catégoriser les données en fonction des canaux. Les données d’organisation sont stockées pour se reconnecter aux équipes après l’installation | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Group.ReadWrite.All | application | Nom de l’ID &amp; de groupe. Justification : pour installer l’application sur chaque groupe/canal | Nom de l’ID &amp; de groupe avec l’objet de données brutes à référencer. Justification : Workbench temporel permet aux utilisateurs de filtrer et de catégoriser les données en fonction des groupes/équipes. Ces données brutes sont enregistrées pour avoir une référence à l’objet d’origine | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamMember.Read.All | application | Appartenance de l’utilisateur à l’équipe. Justification : autorise la synchronisation de tous les utilisateurs de Teams avec à Temporall Workbench | Adresse e-mail, nom et nom de famille. Justification : autoriser la mise en correspondance d’utilisateurs dans teams avec des utilisateurs dans Le Workbench temporel afin d’autoriser la synchronisation des utilisateurs par courrier électronique. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForTeam.All | application | Lire la liste des applications installées pour Team. Justification : vérifiez si notre application est déjà installée, sinon, elle est installée pour être en mesure d’obtenir l’activité des messages via l’api de graphique | S/O | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForUser.All | application | Lire la liste des applications installées. Vérifiez si notre application est déjà installée, sinon l’installe pour interagir avec l’utilisateur via un questionnaire | N/A | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| User.Read | délégué | Informations de base sur &amp; la société des utilisateurs. Justification : utilisée pour catégoriser l’activité des messages par utilisateur, permet au bot de participer à une messagerie proactive. | Nom d’utilisateur, e-mail, icône, référence de conversation. Justification : permet à notre bot d’envoyer de manière proactive des messages aux utilisateurs avec des informations pertinentes. Grouper des utilisateurs pour l’affichage des données | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud | Informations LDAP | Notre plateforme réside sur la plateforme Google Cloud |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>https://temporall.com/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Temporall sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

