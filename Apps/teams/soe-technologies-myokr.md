---
title: Informations d’application pour myOKR par SOE Technologies
ms.author: elmalova
author: elenamalova
ms.date: 10/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour myOKR, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c4a3e8872b8042f0114925c0e89de12b98ef5440
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411469"
---
# <a name="myokr"></a>myOKR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c0b70874-2c95-4be7-a0cb-0d893e25a2a3" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003308" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SOE Technologies à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | myOKR |
| ID | WA200003308 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | SOE Technologies |
| URL du site web partenaire | [https://www.myokr.co](https://www.myokr.co) |
| URL de la Teams d’informations sur l’application | [https://www.myokr.co](https://www.myokr.co) |
| URL de la politique de confidentialité | [https://www.myokr.co/privacy](https://www.myokr.co/privacy) |
| URL des conditions d’utilisation | [https://www.myokr.co/terms](https://www.myokr.co/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par SOE Technologies sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | délégué | Obtenir les détails du calendrier utilisateur pour créer une réunion 1:1 dans le calendrier de l’utilisateur, mettre à jour ou supprimer une réunion créée par ma plateformeOKR et afficher les créneaux horaires libres | Nous stockons l’ID de calendrier créé et l’URL de jointage dans la base de données pour les réunions créées dans la plateforme myOKR | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read | délégué | Nous utilisons l’ID d’objet azure de l’utilisateur pour faire en sorte que l’utilisateur se connecte à mon applicationOKR à l’aide de l’authentification Microsoft par rapport au courrier électronique | messagerie utilisateur et ID d’objet azure active | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read.All | application | Synchroniser les informations utilisateur avec la plateforme myOKR et affiche l’analyse de l’application myOKR à l’administrateur en fonction de différentes coupures d’utilisateurs telles que l’emplacement, le responsable du &amp; service | Nous stockons les informations d’ID d’utilisateur, de nom, de courrier électronique, de service, de titre et de responsable dans le système myOKR | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| offline_access | délégué | ID Azure Active Directory de l’utilisateur | Nous utilisons l’accès hors connexion pour créer des réunions périodiques dans le calendrier de l’utilisateur | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| openid | délégué | Nous utilisons l’ID d’objet Azure de l’utilisateur pour effectuer une connexion utilisateur à mon applicationOKR à l’aide de l’authentification Microsoft | L’ID Azure actif de l’utilisateur est stocké par rapport à l’e-mail | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| L’ID Utilisateur Active Azure Directory est stocké par rapport au courrier électronique de l’utilisateur pour envoyer des messages proactifs par le bot. | Email, Name, Manager Information, Title, User Azure Active Directory ID  | Ces informations sont utilisées dans l’application myOKR pour créer un compte d’utilisateur, permettre au responsable d’afficher les détails de son utilisateur sur platfrom, autoriser l’administrateur à afficher l’analyse globale et les rapports en fonction du service, de l’emplacement et du responsable |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Le SPOC de l’organisation nous communique pour la fermeture du service et ses données sont supprimées après 30 jours après l’estimation et supprimées des back-ups de base de données après 30 jours supplémentaires.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par SOE Technologies sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

