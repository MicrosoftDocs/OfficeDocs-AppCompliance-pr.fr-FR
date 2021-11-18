---
title: Informations sur l’application pour officeatwork | Assistant pour Office par officeatwork
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour officeatwork | Assistant pour Office données, ses stratégies de gestion des données, ses informations Microsoft Cloud App Security catalogue d’applications et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: caab330c79c73f1b1d5d7ab8a859c0bd3d267244
ms.sourcegitcommit: 1ae3b2c9057829f6d868439ba674d8d8d9f30663
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/18/2021
ms.locfileid: "61066462"
---
# <a name="officeatwork--wizard-for-office"></a>officeatwork | Assistant pour Office

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380519" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par officeatwork à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | officeatwork - Assistant pour Office |
| ID | WA104380519 |
| Office 365 clients pris en charge | Word 2016 ou une ultérieure sur Mac, Word 2016 ou une Windows, Word sur iPad, Word sur le web |
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

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Contacts.Read | délégué | Aucune donnée n’est stockée. | Contacts : pour activer la lecture de tous les contacts de l’utilisateur inscrit. | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| Files.Read | délégué | Aucune donnée n’est stockée. | OneDrive - Fichiers (contenu) : pour activer la lecture des fichiers de l’utilisateur inscrit. | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| Files.Read.All | délégué | Aucune donnée n’est stockée. | Teams - Fichiers (contenu) : pour activer la lecture de tous les fichiers de l’utilisateur inscrit. | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| Group.Read.All | délégué | Aucune donnée n’est stockée. | Office 365 utilisateurs - Limite au groupe : pour activer la lecture de tous les groupes de l’utilisateur inscrit. | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| Sites.Read.All | délégué | Aucune donnée n’est stockée. | SharePoint Online : pour activer la lecture de données à partir de SharePoint Online. | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| User.Read | délégué | Aucune donnée n’est stockée. | Sing-In : pour permettre à l’application Officeatwork de lire les propriétés de base de l’utilisateur. | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| User.Read.All | délégué | Aucune donnée n’est stockée. | Office 365 Utilisateurs - Toutes les propriétés : pour activer la lecture de toutes les propriétés de tous les utilisateurs. | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| User.ReadBasic.All | délégué | Aucune donnée n’est stockée. | Office 365 Utilisateurs - Propriétés de base : pour permettre la lecture des propriétés de base de tous les utilisateurs | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| offline_access | délégué | Aucune donnée n’est stockée. | Sing-In : pour activer la sign-in automatique via des jetons d’actualisation, comme sans, les utilisateurs doivent se connecter manuellement chaque fois qu’ils lancent l’application officeatwork. Cette étendue est uniquement requise pour les applications hôtes non-SSO. | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| openid | délégué | Aucune donnée n’est stockée. | Sing-In : pour permettre aux utilisateurs de se connectent à l’application officeatwork avec leur compte d’organisation et/ou Microsoft | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |
>| profil | délégué | Aucune donnée n’est stockée. | Sing-In : pour afficher l’utilisateur inscrit dans l’application officeatwork. Cela permet d’assurer/de confirmer à l’utilisateur quel compte a été utilisé pour se connecter à l’application officeatwork. | [0c67871c-ffbc-4b37-bd61-afce12b299f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c67871c-ffbc-4b37-bd61-afce12b299f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Quels OII sont collectés ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API REST SharePoint | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

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

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par officeatwork sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Paramètres de sécurité par défaut |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
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
