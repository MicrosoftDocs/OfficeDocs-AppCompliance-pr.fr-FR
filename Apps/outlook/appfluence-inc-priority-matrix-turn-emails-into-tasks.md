---
title: Informations d’application pour Matrix prioritaire - Transformez les e-mails en tâches par Appfluence Inc
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations disponibles sur la sécurité et la conformité pour Priority Matrix - Transformez les e-mails en tâches, ses politiques de traitement des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9843ece5a330f4a8b8adb6f1388a4a26e12dbe21
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553755"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>Matrix prioritaire - Transformez les e-mails en tâches

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur le: Avril 16, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Appfluence Inc à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Matrix prioritaire - Transformez les e-mails en tâches |
| ID | WA104381735 WA104381735 |
| Office 365 clients soutenus | Outlook 2016 ou plus tard Windows, Outlook 2016 ou plus tard sur Mac, Outlook sur iOS, Outlook sur Android, Outlook sur le web |
| Nom de l’entreprise partenaire | Appfluence Inc |
| URL du site web partenaire | [https://appfluence.com/](https://appfluence.com/) |
| URL de la politique de confidentialité | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| URL des conditions d’utilisation | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Appfluence Inc sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Délégué | Ce n’est que lorsqu’un nouvel utilisateur est ajouté au compte que nous stockons son e-mail. | Sur la création de nouveaux comptes, nous l’utilisons pour suggérer d’autres membres de l’équipe. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | Délégué | Ce n’est que lorsqu’un nouvel utilisateur est ajouté au compte que nous stockons son e-mail. | Sur la création de nouveaux comptes, nous l’utilisons pour suggérer d’autres membres de l’équipe. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | Délégué | Nous stockons le jeton de connexion afin d’effectuer des demandes pour le compte de l’utilisateur | Actualisez le jeton sans déranger l’utilisateur. (Matrice prioritaire pour Teams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | Délégué | Nous ne stockons aucune information de fichier, à moins que l’utilisateur crée explicitement et sciemment un élément Matrix prioritaire qui se lie au fichier d’origine. | Dans notre fonctionnalité en tête-à-tête (disponible via notre application Web et aussi nos modules Outlook/Teams), nous utilisons cette fonctionnalité pour mettre en évidence les fichiers SharePoint/OneDrive qui sont partagés entre deux utilisateurs de notre système, afin de faciliter les réunions et la collaboration globale. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | Délégué | Les informations de base du profil d’utilisateur (nom d’affichage, prénom, nom de famille, e-mail, avatar) sont stockées par nous. | Obtenez le nom, l’e-mail, l’avatar de l’utilisateur, pour personnaliser son compte avec nous. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| openid | Délégué | Nous stockons la connexion SSO pour indiquer le mode de connexion pour l’utilisateur. | Afin de vous connecter aux utilisateurs via une seule inscription. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | Délégué | Un petit nombre d’événements calendendaux sont transformés en tâches stockées dans notre système. | Lisez les événements du calendrier afin qu’ils puissent être affichés dans notre vue 1:1. Aussi pour para para paraser de nouveaux comptes.  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | Délégué | Nous stockons les tâches créées dans notre système, avec un lien vers le message original. | Utilisé dans nos Outlook add-in pour transformer les e-mails en tâches, et pour afficher le travail partagé en vue 1:1. | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | Délégué | Certaines Outlook/Planificateur sont répliquées dans notre système pour aider les nouveaux utilisateurs. | Nous bootstrap nouveaux comptes d’utilisateurs avec leurs Graph tâches. | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Oui, nous utilisons l’e-mail de l’utilisateur comme identifiant unique dans notre système, et qui est utilisé pour retracer les erreurs d’application, et pour suivre les événements clés du système (téléchargements, inscriptions, versions d’applications, etc)afin que notre équipe de service à la clientèle puisse fournir une réponse rapide aux requêtes des clients. Dans le cadre de notre conformité GDPR, nous supprimons toutes les données clients dans les 2 semaines suivant une demande de suppression, bien que dans la pratique nous le faisons le même jour, car nous avons des scripts internes pour le faire d’une manière semi-automatique.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données d’application sont stockées en toute sécurité dans une base de données cryptée dont l’accès est limité à un petit groupe d’administrateurs. Afin de sécuriser davantage l’accès, nous appliquons l’authentification à deux facteurs, limitons l’accès à un ensemble contrôlé d’adresses IP et localisez la base de données dans son propre sous-réseau privé, directement inaccessible à partir de l’Internet ouvert.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Appfluence Inc sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle le moins d’autorisations de privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles fidèlement les autorisations que votre application demandera de manière dynamique et progressive ? | Oui |
| Votre application prend-elle en charge la multi-location ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Possédez-vous l’ensemble de l’identifiant de ressources unifié (URI) redirigé enregistré pour votre application ? | Oui |
| Pour votre application, qu’évitez-vous d’utiliser ? | - Wildcard rediriger les URL,<br/><br/>- Flux d’identification de mot de passe propriétaire de ressources (ROPC) |
| Votre application expose-t-elle des API Web ? | Oui |
| Votre modèle d’autorisation ne permet-il aux appels de réussir que si l’application client reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de prévisualisation ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
