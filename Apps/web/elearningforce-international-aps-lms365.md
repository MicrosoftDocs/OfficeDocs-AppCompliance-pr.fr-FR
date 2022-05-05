---
title: Informations sur l’application pour LMS365
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour LMS365, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7136a0f4a71f54772dc250433686996f2d236a19
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65224988"
---
# <a name="application-information-for-lms365-by-elearningforce-international-aps"></a>Informations sur l’application pour LMS365 par ELEARNINGFORCE International Aps

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur : 23 juin 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ELEARNINGFORCE International Aps à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | LMS365 |
| ID | elearningforce.lms365_spfx |
| Nom de la société partenaire | ELEARNINGFORCE International Aps |
| URL du site web du partenaire | [https://www.elearningforce.com](https://www.elearningforce.com) |
| URL de la politique de confidentialité | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| URL des conditions d’utilisation | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par ELEARNINGFORCE International Aps sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>| **Permission**  | **Type d’autorisation (délégué/application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-ils stockées ? Justification du stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | application | Aucun | Permet à l’application de développer les membres du groupe AD, ce qui est nécessaire pour inscrire un groupe d’utilisateurs aux cours. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | Délégué | Aucun | L’autorisation est demandée dynamiquement lors de la configuration du compte de messagerie pour la notification. Permet à l’application d’envoyer des e-mails de notification | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | application | Aucun | Permet à l’application d’obtenir SharePoint domaine pendant l’approvisionnement du locataire. Le domaine est utilisé pour la construction d’URL. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | Délégué | Aucun | Permet à l’application d’inviter des utilisateurs externes au nom de l’utilisateur connecté actuel | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | Délégué | Aucun | Connectez-vous et lisez le profil utilisateur. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Délégué | Aucun | Permet à l’application de lire le profil complet de l’utilisateur connecté actuel. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | application | Permet à l’application de lire le profil utilisateur complet. Il&#8217;nécessaire de lire les utilisateurs&#8217; les gestionnaires pour créer des rapports hiérarchiques. | Les données personnelles suivantes sont stockées dans une base de données dédiée pour le client respectif utilisé pour les fonctionnalités du tableau de bord Learner Management &amp; Manager dans l’application. Nom du compte, nom d’affichage de l’utilisateur, adresse e-mail, département, titre du travail, Office, pays, ville, ID de gestionnaire/e-mail | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| profil | Délégué | Aucun | Affichez le profil de base de l’utilisateur. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et compléments basés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelles (OII). Répertoriez toutes les API Microsoft autres que Microsoft Graph utilisées par cette application.

>| **API** |  **OII est-il collecté ?** |  **Quelle OII est collectée ?** | **Justification de la collecte d’OII ?** | **OII est-il stocké ?** | **Justification du stockage d’OII ?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>Les non-services Microsoft ne sont pas utilisées.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui, nous utilisons Informations données de télémétrie/journaux Log Analytics, qui sont utilisées uniquement pour résoudre les problèmes et qui ont une stratégie de rétention de 90 jours après laquelle toutes les données sont supprimées.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>LMS365 est équipé d’une fonction de vidage qui supprime toutes les données personnelles de la base de données LMS365 des clients.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans l’examen ou l’analyse des données d’information d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par ELEARNINGFORCE International Aps sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Intégrez-vous à La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle d’intégration Plateforme d'identités Microsoft ?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Répertorier les types de stratégies prises en charge | Plateformes d’appareil, état de l’appareil, applications clientes |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations inscrites statiquement de votre application reflètent-elles précisément les autorisations demandées par votre application de manière dynamique et incrémentielle ? | Oui |
| Votre application prend-elle en charge la mutualisation ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de l’URI (Identificateur de ressource unifié) de redirection inscrit pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement la réussite des appels si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de préversion ? | Non |
| Votre application utilise-t-elle des API déconseillées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
