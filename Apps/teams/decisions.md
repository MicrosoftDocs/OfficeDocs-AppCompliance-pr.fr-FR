---
title: Informations sur l’application pour les décisions prises par décision
ms.author: elmalova
author: elenamalova
ms.date: 06/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour les décisions, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 19a710fc8edbcb5243b81755ce3d61e8bcaa5b25
ms.sourcegitcommit: 3660f89e183c638979a31c295ac059daa6c387dd
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/18/2021
ms.locfileid: "58391877"
---
# <a name="decisions"></a>Décisions

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par les décisions prises à l’aide de Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Décisions |
| ID | WA104381880 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Décisions |
| URL du site web partenaire | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| URL de la Teams d’informations sur l’application | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| URL de la politique de confidentialité | [https://www.meetingdecisions.com/privacy](https://www.meetingdecisions.com/privacy) |
| URL des conditions d’utilisation | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par des décisions sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | délégué | Permet de lire les informations du calendrier de l&#8217;pour activer des fonctionnalités telles que la liste de réunions et la recherche. Elle permet également à l’utilisateur de supprimer des réunions spécifiques du calendrier lorsque l’élément est supprimé des décisions. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils du client uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Chat.ReadWrite | délégué | Utilisé pour envoyer des décisions de vote et créer des listes de haut-parleurs pour des éléments d’ordre du jour individuels directement à la Microsoft Teams conversation de réunion. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils du client uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | délégué | Permet de collecter des informations de base sur Office 365 client lors de l’inscription, telles que le nom du client et les domaines vérifiés. Il est également nécessaire de vérifier les appartenances aux groupes. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils du client uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | délégué | Utilisé pour lire les fichiers partagés avec l’utilisateur afin de les fusionner dans le carnet de réunions PDF. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils du client uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | délégué | Permet de fournir aux utilisateurs la prise en charge des annotations de fichiers personnels. Les fichiers annotés sont stockés en privé dans les&#8217;'OneDrive Entreprise. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils du client uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | délégué | Permet de créer des structures de dossiers dans Office 365 site&#8217;groupe SharePoint pour les agendas de réunion, les fichiers associés et les conversations de groupe.   Remarque : les utilisateurs de décisions n’auront jamais accès à des ressources (par exemple, des groupes) à qui ils n’ont pas déjà accès dans le client Office 365 de votre organisation. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils du client uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Mail.Send | délégué | Permet aux utilisateurs de décisions d’envoyer des notifications aux participants à la réunion, telles que des mises à jour de l’agenda et des liens vers la réunion pour les co-auteurs. Les messages électroniques sont envoyés aux participants à la réunion ou à la liste de distribution sélectionnée par le propriétaire de la réunion. Toutes les notifications et tous les e-mails envoyés le sont activement par les utilisateurs de décisions.  Remarque : cela ne permet pas à l’utilisateur d’accéder à sa boîte de réception par le biais de Décisions. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils du client uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| MailboxSettings.Read | délégué | Permet d’identifier un utilisateur&#8217;préférences de langue. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils du client uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Notes.ReadWrite | délégué | Permet de configurer des blocs-notes privés pour les réunions afin de prendre des notes et de préparer des remarques et des questions. Il permet également de stocker les minutes de réunion de groupe dans leur bloc-notes partagé OneNote, si le groupe choisit d’utiliser OneNote. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils du client uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Sites.ReadWrite.All | délégué | Utilisez cette propriété pour créer des structures de dossiers dans des canaux privés pour les informations de réunion. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils clients uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Tasks.ReadWrite | délégué | Utilisé pour synchroniser les tâches et les décisions avec le Planificateur Microsoft. Il permet également aux utilisateurs d’exporter des tâches et des décisions vers Excel. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils clients uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser | délégué | Requis pour installer par programme l’application Décisions dans la conversation. Ceci est obligatoire avant d’ajouter l’onglet Décisions pour l’expérience de réunion. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils clients uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser.All | délégué | Requis pour installer par programme l’application Décisions dans la conversation. Ceci est obligatoire avant d’ajouter l’onglet Décisions pour l’expérience de réunion. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils clients uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Create | délégué | Ajout de l’onglet Réunion/Canal dans Teams. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils clients uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Read.All | délégué | Obligatoire pour vérifier si l’onglet est installé ou non. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils clients uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| User.ReadBasic.All | délégué | Utilisé pour afficher le prénom et le nom, la photo et l’adresse e-mail des membres du groupe et des participants externes. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils clients uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| profil | délégué | Utilisé pour se connecter. | Les données client sont stockées dans le client&#8217;client Office 365 client et que toutes les données client sont traitées sur les appareils clients uniquement. La base de données Decisions conserve uniquement les références aux objets dans le client Office 365 clients, et non aux données réelles. Pour plus https://www.meetingdecisions.com/security-and-privacy d’informations, voir. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données fournies par le client lors de l’utilisation du logiciel sont uniquement disponibles pour le client.  Le service est livré sur les services Microsoft Office 365 cloud et les Microsoft Azure. Toutes les données client sont stockées dans le client Microsoft Office 365 client. Toutes les données stockées ou traitées sur le service sont anonymes et ne sont pas accessibles à des personnes individuelles. De ce fait, les décisions ne stockent, ne collectent pas ou ne traitéent pas de données personnelles au nom du client.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par des décisions sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Tous |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
