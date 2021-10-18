---
title: Informations d’application pour les références d’employés par Recruitday Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour les références d’employés, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3f169a817828d56501225bd8a92752ec7f799771
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428981"
---
# <a name="employee-referrals"></a>Références d'employés

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c179cdf6-f93d-4aa3-9e2d-e934e5a81846" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002708" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Recruitday Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Références d'employés |
| ID | WA200002708 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Recruitday Inc. |
| URL du site web partenaire | [https://www.recruitday.com](https://www.recruitday.com) |
| URL de la Teams d’informations sur l’application | [https://employer.recruitday.com/solutions/employee-referral...](https://employer.recruitday.com/solutions/employee-referrals/microsoft-teams) |
| URL de la politique de confidentialité | [https://www.recruitday.com/privacy-policy](https://www.recruitday.com/privacy-policy) |
| URL des conditions d’utilisation | [https://www.recruitday.com/terms-of-use](https://www.recruitday.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Recruitday Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | les deux | Le prénom et le nom (de l’utilisateur de l’application, c’est-à-dire l’employé) seront principalement utilisés par l’utilisateur RH pour identifier facilement l’employé qui a désigné un candidat pour le suivi d’application de référence et le paiement de la rémunération. Il sera également utilisé pour traiter correctement l’employé lorsque des notifications par courrier électronique générées par le système sont envoyées. | Le prénom et le nom (de l’utilisateur de l’application, c’est-à-dire l’employé) seront principalement utilisés par l’utilisateur RH pour identifier facilement l’employé qui a désigné un candidat pour le suivi d’application de référence et le paiement de la rémunération. Il sera également utilisé pour traiter correctement l’employé lorsque des notifications par courrier électronique générées par le système sont envoyées. | [7414b436-87d1-4904-9d52-ff47885b89f1](https://docs.microsoft.com/microsoft-365-app-certification/azure/7414b436-87d1-4904-9d52-ff47885b89f1) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. Pour être traitée par Recruitday aux fins suivantes : 1.1. Créez le compte Employé 1.2. Envoyer des notifications générées par le système concernant les transactions et rappels 2. Pour être traitée par l’organisation de l’utilisateur aux fins suivantes : 2.1. Identifiez la source d’une référence 2.2. Déterminez à qui sera accordée la récompense de référence pour la référence réussie 2.3. Déterminer les employés qui ne pourront pas accéder au système (c’est-à-dire bloquer l’accès) | Prénom, Nom, Adresse e-mail | 1. Pour être traitée par Recruitday aux fins suivantes : 1.1. Créez le compte Employé 1.2. Envoyer des notifications générées par le système concernant les transactions et rappels 2. Pour être traitée par l’organisation de l’utilisateur aux fins suivantes : 2.1. Identifiez la source d’une référence 2.2. Déterminez à qui sera accordée la récompense de référence pour la référence réussie 2.3. Déterminer les employés qui ne pourront pas accéder au système (c’est-à-dire bloquer l’accès) |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>L’administrateur peut archiver les données de l’utilisateur via le portail. D’autres fonctions telles que la suppression, la mise à jour, etc. sont réalisées par demande à l’utilisateur.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Recruitday Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Non |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
