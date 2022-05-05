---
title: Informations sur l’application pour le vérificateur
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour le vérificateur, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4722985246d95eca6e865a0eaa602010f12cb99b
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225288"
---
# <a name="application-information-for-verifier-by-officeatwork"></a>Informations d’application pour le vérificateur par officeatwork

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur : 23 juin 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.verifier" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par officeatwork à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Vérificateur |
| ID | officeatwork-ag.verifier |
| Nom de la société partenaire | officeatwork |
| URL du site web du partenaire | [https://www.officeatwork.com](https://www.officeatwork.com) |
| URL de la politique de confidentialité | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| URL des conditions d’utilisation | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par officeatwork sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>| **Permission**  | **Type d’autorisation (délégué/application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-ils stockées ? Justification du stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.Read | Délégué | Aucune donnée n’est stockée. | OneDrive : pour pouvoir lire les fichiers de l’utilisateur connecté | 8cf0fbc9-28f7-4bfb-94db-237b049fcbf7 |
>| Files.Read.All | Délégué | Aucune donnée n’est stockée. | Teams : pour lire tous les fichiers auxquels l’utilisateur connecté a accès. | 8cf0fbc9-28f7-4bfb-94db-237b049fcbf7 |
>| Sites.Read.All | Délégué | Aucune donnée n’est stockée. | SharePoint Online : pour activer la lecture des données à partir de SharePoint Online, l’utilisateur connecté a accès. | 8cf0fbc9-28f7-4bfb-94db-237b049fcbf7 |
>| User.Read | Délégué | Aucune donnée n’est stockée. | Connexion : pour permettre à l’application Officeatwork de lire les propriétés de base de l’utilisateur. | 8cf0fbc9-28f7-4bfb-94db-237b049fcbf7 |
>| offline_access | Délégué | Aucune donnée n’est stockée. | Connexion : pour activer la connexion automatique via des jetons d’actualisation, comme sans, les utilisateurs doivent se connecter manuellement chaque fois qu’ils lancent l’application officeatwork. Cette étendue est uniquement requise pour les applications hôtes non compatibles avec l’authentification unique. | 8cf0fbc9-28f7-4bfb-94db-237b049fcbf7 |
>| openid | Délégué | Aucune donnée n’est stockée. | Sing-In : pour permettre aux utilisateurs de se connecter à l’application Officeatwork avec leur organisation et/ou leur compte Microsoft. | 8cf0fbc9-28f7-4bfb-94db-237b049fcbf7 |
>| profil | Délégué | Aucune donnée n’est stockée. | Sing-In : pour afficher l’utilisateur connecté dans l’application Officeatwork. Cela permet d’assurer/de confirmer à l’utilisateur quel compte a été utilisé pour se connecter à l’application officeatwork. | 8cf0fbc9-28f7-4bfb-94db-237b049fcbf7 |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et compléments basés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelles (OII). Répertoriez toutes les API Microsoft autres que Microsoft Graph utilisées par cette application.

>| **API** |  **OII est-il collecté ?** |  **Quelle OII est collectée ?** | **Justification de la collecte d’OII ?** | **OII est-il stocké ?** | **Justification du stockage d’OII ?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API REST SharePoint | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>Les non-services Microsoft ne sont pas utilisées.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui, les événements incluent l’oid et tenantId et sont envoyés à Azure AppInsights. Les événements sont automatiquement supprimés après 90 jours. Si un client souhaite supprimer ces données, il peut utiliser le lien fourni dans la déclaration de confidentialité pour lancer la suppression de ces données.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>Les données des paramètres des applications (indicateurs de fonctionnalités, nom complet de l’organisation, tenantId, liste des oids administrateurs) sont stockées dans une instance Azure Cosmos DB (un fichier par locataire). Les fichiers de base de données sont chiffrés et l’accès est limité aux ingénieurs officeatwork et au personnel du support technique sélectionnés. Le client peut accéder aux données des paramètres de l’application Officeatwork et les manipuler à l’aide de l’application web Admin Center.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans l’examen ou l’analyse des données d’information d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35755' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35755" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par officeatwork sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Intégrez-vous à La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle d’intégration Plateforme d'identités Microsoft ?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Répertorier les types de stratégies prises en charge | Paramètres de sécurité par défaut |
| Votre application demande-t-elle des autorisations de privilège minimum pour votre scénario ? | Oui |
| Les autorisations inscrites statiquement de votre application reflètent-elles précisément les autorisations demandées par votre application de manière dynamique et incrémentielle ? | Non |
| Votre application prend-elle en charge la mutualisation ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de l’URI (Identificateur de ressource unifié) de redirection inscrit pour votre application ? | Oui |
| Pour votre application, que pouvez-vous éviter d’utiliser ? | - URI de redirection par caractères génériques,<br/>- Flow implicite OAuth2, sauf si nécessaire pour une spa<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle des API de préversion ? | Non |
| Votre application utilise-t-elle des API déconseillées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
