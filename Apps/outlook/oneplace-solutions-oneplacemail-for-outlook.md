---
title: Informations d’application pour OnePlaceMail pour Outlook solutions OnePlace
ms.author: elmalova
author: elenamalova
ms.date: 09/30/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour OnePlaceMail pour Outlook, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 196720a00525971f29618d48436cf11b37a3aaac
ms.sourcegitcommit: 874e586a5a9a5eb0c5c5aae0c59f7c75c0742ec4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/01/2021
ms.locfileid: "60080645"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail for Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 30, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par OnePlace Solutions à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | OnePlaceMail for Outlook |
| ID | WA104380723 |
| Office 365 clients pris en charge | Outlook 2013 ou version ultérieure sur Windows, Outlook 2016 ou version ultérieure sur Mac, Outlook sur iOS, Outlook sur Android, Outlook sur le web |
| Nom de la société partenaire | OnePlace Solutions |
| URL du site web partenaire | [https://www.oneplacesolutions.com](https://www.oneplacesolutions.com) |
| URL de la politique de confidentialité | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL des conditions d’utilisation | [https://www.oneplacesolutions.com/eula.html](https://www.oneplacesolutions.com/eula.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par OnePlace Solutions sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | délégué | Obligatoire pour déterminer Teams dont l’utilisateur actuel est membre. | Aucune | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Mail.ReadWrite.Shared | délégué | Obligatoire pour accéder aux propriétés de messagerie pour définir SharePoint colonnes et ajouter la catégorie Transféré SharePoint sur l’élément de courrier | Aucune | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| MailboxSettings.ReadWrite | délégué | Aucune donnée collectée ou utilisée, utilisée pour ajouter une catégorie à la liste principale des catégories dans une boîte aux lettres d’utilisateurs | Néant | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Sites.ReadWrite.All | délégué | Obligatoire pour définir des propriétés sur les éléments que l’application a téléchargés vers SharePoint. | Aucune | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.Read | délégué | Requis pour l’authentification à l’Graph Microsoft. | Les données suivantes sont stockées par l’application dans une base de données et sont utilisées pour le suivi des abonnements et des licences utilisateur : ID utilisateur, e-mail, prénom, nom. | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | délégué | Obligatoire pour afficher l’image de profil utilisateur dans le champ S sélectionneur de personnes. | Aucun | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | délégué | Obligatoire pour afficher l’image de profil utilisateur dans le champ S sélectionneur de personnes. | Néant | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadWrite.All | délégué | Obligatoire pour déterminer si le service Teams est activé au sein de la location Office 365 utilisateurs. | Néant | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | Oui | SharePoint URL, bibliothèque/liste/noms de dossiers | Les informations organisationnelles accessibles par sont utilisées pour faciliter le processus d’enregistrement du courrier électronique et des pièces jointes Exchange à SharePoint. Ces données supplémentaires ne sont pas stockées au repos et sont chiffrées en transit. Ces données incluent des exemples de SharePoint de colonnes telles que les valeurs de colonne Choice, les valeurs de taxonomie, les noms de types de contenu, les noms de dossiers, les noms de sites.  | Bien que ces données ne sont pas stockées ou collectées par l’application, elles peuvent apparaître dans la télémétrie/les journaux où elles sont conservées pendant 90 jours. | Les données ne sont pas stockées |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Le service Chargify est utilisé pour la gestion et la facturation des abonnements. Pour la création d’un abonnement in-app (gratuit), le prénom, le nom et l’adresse de messagerie de l’utilisateur sont partagés avec Chargify. Pour les abonnements achetés (qui supportent plusieurs utilisateurs sous licence), les détails des utilisateurs individuels ne sont pas partagés avec le service Chargify. | Adresse de messagerie | Pour être en mesure de communiquer des événements de cycle de vie d’abonnement à l’utilisateur |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>LES EUII et OII apparaissent dans la télémétrie. Ces informations sont stockées dans l’application Informations, chiffrées au repos, accessibles contrôlées et supprimées après 90 jours

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données stockées dans l’application sont chiffrées en transit et au repos. Nous nous appuyons Office 365 informations d’identification pour nos applications, donc nous ne stockons pas les mots de passe utilisateur dans notre système. L’accès aux données stockées/journaux/télémétrie est étroitement contrôlé au personnel de l’administration interne, ayant besoin d’accéder aux informations dans le but d’exécution et de surveillance de l’état de l’application. Two-Factor'authentification appliquée pour tous les membres du personnel d’administration interne.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par OnePlace Solutions sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
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
