---
title: Informations d’application pour Adobe Sign pour Word et PowerPoint par Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 02/22/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour Adobe Sign pour Word et PowerPoint, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 199ab1c46f52102d9f6eb0e10a44c7c0603376bf
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430012"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Sign pour Word et PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: February 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Adobe Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Adobe Sign pour Word et PowerPoint |
| ID | WA104381155 |
| Office 365 clients pris en charge | Word 2016 ou une ultérieure sur Mac, Word sur le web, Word 2013 Service Pack 1 ou ultérieur sur Windows, PowerPoint 2016 ou ultérieur sur Mac, PowerPoint sur le web, PowerPoint 2013 Service Pack 1 ou une Windows |
| Nom de la société partenaire | Adobe Inc. |
| URL du site web partenaire | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| URL de la politique de confidentialité | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL des conditions d’utilisation | [https://www.adobe.com/legal/licenses-terms.html](https://www.adobe.com/legal/licenses-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Adobe Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite | délégué | Pour remplir le document joint, les e-mails de l’expéditeur et du destinataire, ainsi que le contenu des messages électroniques envoyés à Adobe sign to send for signature. Cela permet à l’utilisateur de gagner du temps pour retaper ces champs dans Adobe Sign. Une fois qu’un contrat est signé, nous rédigeons automatiquement un nouveau courrier électronique pour que l’utilisateur envoie un courrier électronique pour informer ses destinataires que la transaction est effectuée. | Adobe Sign enregistre les pièces jointes en tant que fichiers temporaires, dont l’expiration est de 24 heures. | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| People.Read | délégué | Pour remplir automatiquement l’adresse e-mail dans l’expérience Envoyer pour signature, en tapant des lettres initiales, n’exigez pas que les utilisateurs tapent l’intégralité &quot; &quot; des e-mails. | Adobe Sign stocke uniquement les messages électroniques et displayName des destinataires dans les contrats. | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| User.Read | délégué | Pour lire le profil de l’utilisateur et faire correspondre son profil (en fait, son e-mail et userId) à notre base de données afin qu’il puisse utiliser Adobe Sign. | Pour lire le profil de l’utilisateur et faire correspondre son profil (en fait, son e-mail et userId) à notre base de données afin qu’il puisse utiliser Adobe Sign. | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| offline_access | délégué | Pour actualiser le jeton d’accès, lorsque le jeton actuel a expiré. Par exemple, lorsque l’utilisateur se trouve dans une fenêtre d’envoi de signature et la laisse inactive pendant trop longtemps, nous devons actualiser un nouveau jeton lorsque &quot; &quot; l’utilisateur est actif. | Pour actualiser le jeton d’accès, lorsque le jeton actuel a expiré. Par exemple, lorsque l’utilisateur se trouve dans une fenêtre d’envoi de signature et la laisse inactive pendant trop longtemps, nous devons actualiser un nouveau jeton lorsque &quot; &quot; l’utilisateur est actif. | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| openid | délégué | E-mail et UserId. Pour que l’utilisateur se connecte afin de s’assurer de son consentement pour l’autorisation d’utiliser l’application Adobe Sign.  | La messagerie électronique est l’identificateur unique pour les utilisateurs dans Adobe Sign. Nous stockons l’ID de courrier électronique afin de pouvoir ma mapiller toutes les activités de cet utilisateur sur son enregistrement Adobe Sign.  | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nos journaux contiennent suffisamment d’informations pour pouvoir identifier et résoudre les problèmes des clients. Les journaux sont conservés pendant 90 jours et l’accès est restreint. Notre base de données stocke des informations d’identification hachées pour l’authentification lorsque l’utilisateur est hors connexion. La stratégie de rétention de base de données est de 30 jours à partir de la dernière utilisation

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous n’avons aucune interaction de l’administrateur client dans notre système pour Microsoft Teams application.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Adobe Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
