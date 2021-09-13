---
title: Informations sur l’application pour officeatwork | S’il s’Office par officeatwork
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour officeatwork | S’il s’Office, ses stratégies de gestion des données, ses Microsoft Cloud App Security catalogue d’applications et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 902198ce1bb7e3b805c2b6c20879a6b77b144954
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282892"
---
# <a name="officeatwork--template-chooser-for-office"></a>officeatwork | S’il s’Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: June 23, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380050" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par officeatwork à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | officeatwork - S’il s’il s’Office |
| ID | WA104380050 |
| Office 365 clients pris en charge | Excel sur iPad, Excel 2016 ou ultérieur sur Mac, Excel 2013 ou une Windows, Excel sur le Web, Word sur iPad, Word 2016 ou ultérieur sur Mac, Word sur le web, Word 2013 ou ultérieur sur Windows, PowerPoint sur iPad, PowerPoint 2016 ou ultérieur sur Mac, PowerPoint sur le web, PowerPoint 2013 ou ultérieur sur Windows, Project 2016 ou une ultérieure sur Windows |
| Nom de la société partenaire | officeatwork |
| URL du site web partenaire | [https://www.officeatwork.com](https://www.officeatwork.com) |
| URL de la politique de confidentialité | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| URL des conditions d’utilisation | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par officeatwork sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | délégué | Aucune donnée n’est stockée. | Favoris : pour pouvoir lire et écrire des données aux utilisateurs OneDrive ; OneDrive : pour pouvoir lire et écrire des données aux utilisateurs OneDrive. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| Group.ReadWrite.All | délégué | Aucune donnée n’est stockée. | Teams : pour pouvoir lire et écrire des données dans un groupe. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| GroupMember.Read.All | délégué | Aucune donnée n’est stockée. | SharePoint En ligne : autorisation de l’utilisateur pour activer la lecture des données à SharePoint Online. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| Sites.Read.All | délégué | Aucune donnée n’est stockée. | SharePoint En ligne : pour activer la lecture de données à SharePoint Online. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| User.Read | délégué | Aucune donnée n’est stockée. | Sing-In : pour permettre à l’application Officeatwork de lire les propriétés de base de l’utilisateur. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| User.Read.All | délégué | Aucune donnée n’est stockée. | Teams : pour savoir à quels groupes appartient un utilisateur. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| offline_access | délégué | Aucune donnée n’est stockée. | Sing-In : pour activer la sign-in automatique via des jetons d’actualisation, comme sans, les utilisateurs doivent se connecter manuellement chaque fois qu’ils lancent l’application officeatwork. Cette étendue est uniquement requise pour les applications hôtes non-SSO. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| openid | délégué | Aucune donnée n’est stockée. | Sing-In : pour permettre aux utilisateurs de se connecter à l’application Officeatwork avec leur compte d’organisation et/ou Microsoft | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| profil | délégué | Aucune donnée n’est stockée. | Sing-In : pour afficher l’utilisateur inscrit dans l’application officeatwork. Cela permet d’assurer/de confirmer à l’utilisateur quel compte a été utilisé pour se connecter à l’application officeatwork. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API REST SharePoint | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui, les événements incluent les oid et tenantId et sont envoyés à Azure AppInsights. Les événements sont automatiquement supprimés après 90 jours. Si un client souhaite que ces données soit supprimées, il peut utiliser le lien fourni dans la déclaration de confidentialité pour lancer la suppression de ces données.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données des paramètres des applications (indicateurs de fonctionnalité, nom complet de l’organisation, tenantId, liste des oids administrateurs) sont stockées dans une instance de base de données Azure Cosmos (un fichier par client). Les fichiers de la DB sont chiffrés et l’accès est limité aux ingénieurs officeatwork et au personnel de support technique sélectionnés. Le client peut accéder aux données des paramètres de l’application Officeatwork et les manipuler à l’aide du Centre d’administration Web App.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par officeatwork sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Paramètres de sécurité par défaut |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Non |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
