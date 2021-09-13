---
title: Informations d’application pour LMS365 par ELEARNINGFORCE International Aps
ms.author: elmalova
author: elenamalova
ms.date: 07/28/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour LMS365, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ab9a29c84b57da2f2a21a20bb22f6a1545fd6d2e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281937"
---
# <a name="lms365"></a>LMS365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: July 28, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ELEARNINGFORCE International Aps à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | LMS365 |
| ID | elearningforce.lms365_spfx |
| Nom de la société partenaire | ELEARNINGFORCE International Aps |
| URL du site web partenaire | [https://www.elearningforce.com](https://www.elearningforce.com) |
| URL de la politique de confidentialité | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| URL des conditions d’utilisation | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par ELEARNINGFORCE International Aps sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| GroupMember.Read.All | application | Aucun | Permet à l’application de développer les membres du groupe AD, ce qui est nécessaire pour inscrire un groupe d’utilisateurs aux cours. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| Mail.Send | délégué | Aucun | L’autorisation est demandée dynamiquement lors de la configuration du compte de messagerie pour la notification. Permet à l’application d’envoyer des courriers électroniques de notification | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| RoleManagement.Read.Directory | application | Aucun | Permet à l’application d’obtenir SharePoint domaine pendant la mise en service du client. Le domaine est utilisé pour la construction d’URL. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Invite.All | délégué | Aucun | Permet à l’application d’inviter des utilisateurs externes au nom de l’utilisateur actuellement connecté | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read | délégué | Aucun | Connectez-vous et lisez le profil utilisateur. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read.All | délégué | Aucun | Permet à l’application de lire le profil complet de l’utilisateur actuellement connecté. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read.All | application | Permet à l’application de lire le profil utilisateur complet. Il est&#8217;lire les utilisateurs et les responsables&#8217; pour créer des rapports de hiérarchie. | Les données personnelles suivantes sont stockées dans une base de données dédiée pour le client respectif utilisé pour les fonctionnalités du tableau de bord du Gestionnaire de gestion &amp; de l’apprentissage au sein de l’application. Nom du compte, nom complet de l’utilisateur, adresse e-mail, service, fonction, Office, pays, ville, ID de gestionnaire/e-mail | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| profil | délégué | Aucun | Afficher le profil de base de l’utilisateur. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui, nous utilisons la télémétrie/les journaux Informations Log Analytics qui sont utilisés uniquement pour la prise de vue des problèmes et qui ont une stratégie de rétention de 90 jours après laquelle toutes les données sont supprimées.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>LMS365 est doté d’une fonction Purge qui supprime toutes les données personnelles des clients LMS365 Database.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par ELEARNINGFORCE International Aps sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Plateformes d’appareil, état de l’appareil, applications clientes |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
