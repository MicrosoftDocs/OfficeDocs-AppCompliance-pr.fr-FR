---
title: Informations sur l’application Power BI collaboration par Ataira
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Power BI Collaboration, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2e015b1596c02f6841609f1dba61577f25c738e4
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411913"
---
# <a name="power-bi-collaboration"></a>Power BI Collaboration

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 14, 2021</p>

* <a href="https://teams.microsoft.com/l/app/90381cb0-998f-4ba3-9699-130201de5ddb" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381384" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Ataira à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Power BI Collaboration |
| ID | WA104381384 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Ataira |
| URL du site web partenaire | [https://www.ataira.com](https://www.ataira.com) |
| URL de la Teams d’informations sur l’application | [https://www.ataira.com/Microsoft/PowerBI/Collaboration](https://www.ataira.com/Microsoft/PowerBI/Collaboration) |
| URL de la politique de confidentialité | [https://www.ataira.com/PrivacyPolicy](https://www.ataira.com/PrivacyPolicy) |
| URL des conditions d’utilisation | [https://www.ataira.com/TermsofUse](https://www.ataira.com/TermsofUse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Ataira sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | Autorisations également pour ChannelMessage.Send Team.ReadBasic.All User.Read. Ceux-ci sont utilisés pour permettre à l’utilisateur de sélectionner Teams groupe et canal de notifications | Surveillance de l’utilisation, des erreurs et des licences. [callback_group_id] ,[datetime_id] ,[session_id] ,[app_type] ,[raw_url] ,[user_id] ,[list_name] ,[user_name] ,[state] ,[priority] ,[user_domain] ,[url_text] ,[group_name] ,[title_name] ,[comments] ,[file_name] ,[description] ,[group_pbi_name] ,[item_type] ,[organization_id] ,[user_objectid] ,[organization_displayName] ,[group_id] | [00738e07-f9a4-4bf5-b6f9-851ec7ea31d5](https://docs.microsoft.com/microsoft-365-app-certification/azure/00738e07-f9a4-4bf5-b6f9-851ec7ea31d5) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| https://analysis.windows.net/powerbi/api/ | Oui | messagerie de l’utilisateur, nom de l’espace de travail, nom de l’élément, URL d’incorporation | Utilisé pour remplir les rapports et les tableaux de bord dans l’interface SharePoint de l’application | [api_pbi_id] ,[datetime_id] ,[session_id] ,[user_name] ,[user_domain] ,[WorkSpace_Name] ,[WorkSpace_Id] ,[item_Id] ,[item_type] ,[item_name] ,[webUrl] ,[embedUrl] ,[displayName] ,[item_title] ,[isOwnedByMe] | Surveillance de l’utilisation, des erreurs et des licences |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Métadon données requises pour remplir les rapports Power BI tableaux de bord, l’authentification à Graph Teams API. D’autres stratégies de confidentialité et de données sont disponibles sur le site web. https://www.ataira.com/PrivacyPolicy Puis, dans la page de configuration de l’application, spécifiquement à la confidentialité des données. https://www.ataira.com/Microsoft/PowerBI/CollaborationSupport

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>S/O

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41844" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Ataira sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Authentification multifacteur permettant uniquement aux appareils inscrits à Intune d’accéder à des services spécifiques Limitant les emplacements utilisateur et les plages IP |
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

