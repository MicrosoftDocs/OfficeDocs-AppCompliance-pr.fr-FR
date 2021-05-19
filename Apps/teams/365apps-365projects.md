---
title: Informations d’application pour 365Projets par 365Apps
ms.author: elmalova
author: elenamalova
ms.date: 03/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour 365Projets, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d760c1c5bacf37fa23e26f4a9a15eb7dbbd75bb1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553465"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Mars 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par 365Apps à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | 365Projects |
| ID | WA200002160 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | 365Apps |
| URL du site web partenaire | [https://365projects.app](https://365projects.app) |
| URL de la page Teams’informations d’application | [https://365projects.app](https://365projects.app) |
| URL de la politique de confidentialité | [https://365projects.app/privacy](https://365projects.app/privacy) |
| URL des conditions d’utilisation | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par 365Apps sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | Délégué | canaux au sein de l’équipe pour relier le projet à la chaîne | canaux au sein de l’équipe pour relier le projet à la chaîne | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.Read.All | Délégué | obtenir des tâches de planificateur d’équipe / planificateur, il sera préférable si une autre portée moins privilèges permettent à l’application d’obtenir des plans d’utilisateur et des tâches de plans, mais malheureusement il n’y a pas de portées qui permettent cette | pas stocker en DB | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.ReadWrite.All | application | Créer Teams  | non stockés dans DB | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| People.Read | Délégué | nom d’utilisateur, pour les ajouter en tant que membres de l’équipe ou leur assigner des tâches | l’utilisateur Guid est stocké dans l’affectation de tâches | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Team.ReadBasic.All | Délégué | Rejoint noms d’équipe, pour lier le projet à Teams Chaîne | L’équipe Guid est stockée dans les métadonnées du projet pour établir le lien | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read | Délégué | obtenir des informations utilisateur pour les montrer dans l’en-tête  | e-mail utilisateur est stocké en tant que propriétaire lors de la première provision du locataire | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read.All | Délégué | lire les utilisateurs pour mettre à jour l’affectation des tâches | seul l’utilisateur Guid est stocké aucune information personnelle identifiée n’est stockée dans la DB | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>App ne stocke pas les données utilisateur en dehors de Guid de l’administrateur de l’application (premier utilisateur à utiliser l’application au sein du locataire) 

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par 365Apps sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

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
| Pour votre application, qu’évitez-vous d’utiliser ? | ,<br/>- OAuth2 Implicite Flow, sauf si nécessaire pour un SPA<br/> |
| Votre application expose-t-elle des API Web ? | Oui |
| Votre modèle d’autorisation ne permet-il aux appels de réussir que si l’application client reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de prévisualisation ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
