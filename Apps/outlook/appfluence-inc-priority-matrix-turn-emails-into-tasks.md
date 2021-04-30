---
title: "Informations sur l'application pour la matrice de priorité : transformer les e-mails en tâches par Appfluence Inc"
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
description: "Toutes les informations de sécurité et de conformité disponibles pour la matrice de priorité : transformer les courriers électroniques en tâches, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR."
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f92f29796daf072b24233bdcc9459d7db82d40bc
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094094"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>Matrice de priorité : transformer les e-mails en tâches

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: November 17, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Appfluence Inc à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Matrice de priorité : transformer les e-mails en tâches |
| ID | WA104381735 |
| Office 365 clients pris en charge | Outlook 2016 ou version ultérieure sur Windows, Outlook 2016 ou version ultérieure sur Mac, Outlook sur iOS, Outlook sur Android, Outlook sur le web |
| Nom de la société partenaire | Appfluence Inc |
| URL du site web partenaire | [https://appfluence.com/](https://appfluence.com/) |
| URL de la politique de confidentialité | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| URL des conditions d'utilisation | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par Appfluence Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d'autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d'application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | délégué | Uniquement lorsqu'un nouvel utilisateur est ajouté au compte, stockons-nous son courrier électronique. | Lors de la création d'un nouveau compte, nous l'utilisons pour suggérer d'autres membres de l'équipe. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | délégué | Uniquement lorsqu'un nouvel utilisateur est ajouté au compte, stockons-nous son courrier électronique. | Lors de la création d'un nouveau compte, nous l'utilisons pour suggérer d'autres membres de l'équipe. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | délégué | Nous stockons le jeton de connexion afin d'effectuer des demandes au nom de l'utilisateur | Actualisez le jeton sans déranger l'utilisateur. (Matrice de priorité pour Teams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | délégué | Nous ne stockons pas d'informations sur les fichiers, sauf si l'utilisateur crée explicitement et en connaissance de cause un élément de matrice prioritaire lié au fichier d'origine. | Dans notre fonctionnalité un-à-un (disponible via notre application web et également nos applications Outlook/Teams), nous utilisons cette fonctionnalité pour mettre en évidence les fichiers SharePoint/OneDrive partagés entre deux utilisateurs dans notre système, afin de faciliter les réunions et la collaboration globale. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | délégué | Les informations de profil utilisateur de base (nom d'affichage, prénom, nom, e-mail, avatar) sont stockées par nous. | Obtenez le nom de l'utilisateur, son e-mail, son avatar, pour personnaliser son compte avec nous. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| openid | délégué | Nous stockons la connexion DSO pour indiquer le mode de connexion de l'utilisateur. | Pour vous inscrire aux utilisateurs via l' sign-on unique. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | délégué | Un petit nombre d'événements de calendrier sont transformés en tâches stockées dans notre système. | Lisez les événements de calendrier afin qu'ils soient affichés dans notre vue 1:1. Également pour initialiser de nouveaux comptes.  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | délégué | Nous stockons les tâches créées dans notre système, avec un lien vers le message d'origine. | Utilisé dans notre Outlook pour transformer les e-mails en tâches et pour afficher le travail partagé en affichage 1:1. | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | délégué | Certaines tâches Outlook/Planificateur sont répliquées dans notre système pour aider les nouveaux utilisateurs. | Nous a bootstrap new user accounts with their Graph tasks. | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="add-in-data-access"></a>Accès aux données du add-in

List the permissions this app requires for accessing your organization's data, the justification and purpose for this permission (what does the app use this information for?) and whether the app stores any of this information in its databases.

>| **Autorisation**  | **Description** |
>|:----------------|:----------------|
>| ReadWrite Mailbox | Ce module peut lire ou modifier le contenu de n'importe quel élément de votre boîte aux lettres et créer des éléments. Il peut accéder à des informations personnelles, telles que le corps, l'objet, l'expéditeur, les destinataires ou les pièces jointes, dans n'importe quel élément de message ou de calendrier. Il peut envoyer ces données à un service tiers. |
>| Envoyer des données | Peut envoyer des données sur Internet |

#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui, nous utilisons le courrier électronique de l'utilisateur comme ID unique dans notre système, qui sert à suivre les erreurs d'application et à suivre les événements clés dans le système (téléchargements, connectes, versions d'application, etc.) afin que notre équipe de service clientèle puisse fournir une réponse rapide aux requêtes des clients. Dans le cadre de notre conformité R GDPR, nous supprimons toutes les données client dans les 2 semaines suivant une demande de suppression, bien que dans la pratique nous le faisons le même jour, car nous avons des scripts internes pour le faire de manière semi-automatique.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Les données d'application sont stockées en toute sécurité dans une base de données chiffrée avec un accès limité à un petit groupe d'administrateurs. Pour sécuriser davantage l'accès, nous allons appliquer l'authentification à 2 facteurs, limiter l'accès à un ensemble contrôlé d'adresses IP et localiser la base de données dans son propre sous-réseau privé, directement inaccessible à partir d'Internet ouvert.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d'identité

Ces informations ont été fournies par Appfluence Inc sur la façon dont cette application gère l'authentification, l'autorisation, les meilleures pratiques d'inscription de l'application et d'autres critères d'identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d'identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft'intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d'authentification Microsoft) pour l'authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d'accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l'location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu'est-ce que vous évitez d'utiliser ? | - URIs de redirection générique,
<br />

<br />
- Flux d'informations d'identification du mot de passe du propriétaire de la ressource (ROPC) | | Votre application expose-t-elle des API web ? | Oui, | | Votre modèle d'autorisation autorise-t-il uniquement les appels à réussir si l'application cliente reçoit le consentement approprié ? | Oui, | | Votre application utilise-t-elle les API d'aperçu ? | Aucun | | Votre application utilise-t-elle des API dépréciées ? | Aucun |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
