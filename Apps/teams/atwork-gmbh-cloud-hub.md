---
title: Informations sur l’application pour le Cloud Hub par atwork
ms.author: elmalova
author: elenamalova
ms.date: 07/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour le Cloud Hub, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 386875fbf14ddd7409590a93462c333510b6a229
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283498"
---
# <a name="cloud-hub"></a>Cloud Hub

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 7, 2021</p>

* <a href="https://teams.microsoft.com/l/app/0c46172d-7923-422d-902e-f27aaad6994d" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003034" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par atwork Contrôleh à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Cloud Hub |
| ID | WA200003034 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | atwork GmbH |
| URL du site web partenaire | [https://www.atwork-it.com](https://www.atwork-it.com) |
| URL de la Teams d’informations sur l’application | [https://www.atwork-it.com/solutions/cloudhub/](https://www.atwork-it.com/solutions/cloudhub/) |
| URL de la politique de confidentialité | [https://www.atwork-it.com/privacystatement](https://www.atwork-it.com/privacystatement) |
| URL des conditions d’utilisation | [https://www.atwork-it.com/eula](https://www.atwork-it.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par atwork Contrôleh sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | application | Lire les noms et la description de tous les canaux | Aucun | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| Mail.Send | application | Partagez un message à une équipe Microsoft Teams par courrier électronique. | Aucun | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| TeamSettings.Read.All | application | Utilisé pour le partage au sein d’Microsoft Teams équipe. | Aucun | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| User.Read | délégué | Activer la connexion et lire le profil utilisateur | Aucun | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| User.Read.All | application | Utilisé pour le s sélectionneur de personnes pour le partage de messages. | Aucun | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API de gestion d’Office 365 | Oui | ActivityFeed.Read et ServiceHealth.Read | Rendre le flux d’activités et l’état du service disponibles pour les utilisateurs non administrateurs | Données ActivityFeed et ServiceHealth | Pour optimiser les performances  |

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

>L’application lit les données et les stocke dans un stockage de données client, fourni sous le nom SaaS. En outre, les utilisateurs ont la possibilité d’envoyer des messages en tant que messages électroniques ou de les envoyer dans des groupes. 

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par atwork ContrôleH sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Application multi-client, dépend des paramètres&#180;client |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
