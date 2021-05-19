---
title: Informations d’application pour LMS365 par ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 02/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour LMS365, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 44ed1631c7d0221b463f518f2494b7a8744eef30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552215"
---
# <a name="lms365"></a>LMS365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Février 25, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ELEARNINGFORCE International à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | LMS365 |
| ID | WA104381467 WA104381467 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | ELEARNINGFORCE International |
| URL du site web partenaire | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL de la page Teams’informations d’application | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL de la politique de confidentialité | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| URL des conditions d’utilisation | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par ELEARNINGFORCE International sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | application | Aucune | Permet à l’application d’élargir les membres du groupe AD, ce qui est nécessaire pour inscrire un groupe d’utilisateurs aux cours. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | Délégué | Aucune | L’autorisation est demandée dynamiquement lors de la configuration du compte e-mail pour notification. Permet à l’application d’envoyer des e-mails de notification | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | application | Aucune | Permet à l’application d’obtenir SharePoint domaine pendant l’approvisionnement des locataires. Le domaine est utilisé pour la construction d’URL. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | Délégué | Aucune | Permet à l’application d’inviter des utilisateurs externes en cours connectés au nom de l’utilisateur | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | Délégué | Aucune | Connectez-vous et lisez le profil de l’utilisateur. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Délégué | Aucune | Permet à l’application de lire le profil complet de l’utilisateur connecté à l’actualité. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | application | Permet à l’application de lire le profil complet de l’utilisateur. Il&#8217;nécessaire de lire les utilisateurs et&#8217; pour construire des rapports hiérarchiques. | Les données personnelles suivantes sont stockées dans une base de données dédiée pour le client respectif utilisé pour les fonctionnalités du tableau de bord learner management &amp; manager au sein de l’application. Nom du compte, nom d’affichage de l’utilisateur, adresse e-mail, département, titre de l’emploi, Office, pays, ville, identité du gestionnaire/courriel | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| profil | Délégué | Aucune | Consultez le profil de base de l’utilisateur. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les modules complémentaires intégrés à Microsoft 365 peuvent utiliser d’autres API Microsoft que Microsoft Graph pour recueillir ou traiter des informations organisationnelles identifiables (OII). Énumérez toutes les API Microsoft autres que Microsoft Graph utilisations de cette application.

>| **API** |  **L’ŒIL est-il recueilli?** |  **Quel OII est recueilli?** | **Justification de la collecte de l’ŒII?** | **OII est-il stocké ?** | **Justification pour stocker OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nous n’utilisons le prénom que pour afficher un message personnalisé lorsque le Bot accueille l’utilisateur. | Les données personnelles sont stockées dans une base de données Azure dédiée pour le client respectif utilisé pour les fonctionnalités du tableau de bord learner management &amp; manager au sein de l’application LMS365. | Nom du compte, nom d’affichage de l’utilisateur, adresse e-mail, département, titre de l’emploi, Office, pays, ville, identité du gestionnaire/courriel |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Oui, nous utilisons insights Log Analytics télémétrie / journaux qui sont utilisés pour le tournage de difficulté seulement et ont une stratégie de conservation de 90 jours après quoi toutes les données sont supprimées.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>LMS365 est équipé d’une fonction purge qui supprimera toutes les données personnelles de la base de données LMS365 clients.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par ELEARNINGFORCE International sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Énumérer les types de politiques prises en charge | Plates-formes d’appareils, État de l’appareil, applications client |
| Votre application demande-t-elle le moins d’autorisations de privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles fidèlement les autorisations que votre application demandera de manière dynamique et progressive ? | Oui |
| Votre application prend-elle en charge la multi-location ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Possédez-vous l’ensemble de l’identifiant de ressources unifié (URI) redirigé enregistré pour votre application ? | Oui |
| Votre application expose-t-elle des API Web ? | Oui |
| Votre modèle d’autorisation ne permet-il aux appels de réussir que si l’application client reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de prévisualisation ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
