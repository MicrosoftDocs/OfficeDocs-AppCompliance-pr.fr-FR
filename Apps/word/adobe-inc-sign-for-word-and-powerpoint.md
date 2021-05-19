---
title: Informations d’application pour Adobe Sign for Word et PowerPoint par Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour Adobe Sign for Word et PowerPoint, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: aa9b4a19f83574d7d9428bbf979ac7ee1375227c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552665"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Signe pour mot et PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur le: Février 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Adobe Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Adobe Signe pour mot et PowerPoint |
| ID | WA104381155 |
| Office 365 clients soutenus | Word 2016 ou plus tard sur Mac, PowerPoint Service Pack 1 2013 ou plus tard sur Windows, Word 2013 Service Pack 1 ou plus tard sur Windows, Word sur le web, PowerPoint sur le web, PowerPoint 2016 ou plus tard sur Mac |
| Nom de l’entreprise partenaire | Adobe Inc. |
| URL du site web partenaire | [https://www.adobe.com/](https://www.adobe.com/) |
| URL de la politique de confidentialité | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| URL des conditions d’utilisation | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Adobe Inc. sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | Délégué | Pour remplir le document ci-joint, envoyez et récepteurz des e-mails, et du contenu de message des e-mails au signe Adobe pour envoyer pour la signature. Il s’agit d’économiser du temps à l’utilisateur pour retaper ces champs dans Adobe Sign. Une fois qu’un accord est signé, nous composons automatiquement un nouvel e-mail pour que l’utilisateur envoie un e-mail pour informer ses destinataires que la transaction est effectuée. | Adobe Sign enregistrera les pièces jointes sous forme de fichiers temporaires, qui ont une expiration de 24 heures. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| People.Read | Délégué | Pour remplir automatiquement l’adresse e-mail dans &quot; l’expérience Envoyer pour la &quot; signature, en tapant quelques lettres initiales, n’obligez pas les utilisateurs à taper l’ensemble des e-mails. | Adobe Sign ne stockera que les destinataires e-mail et displayName dans les accords. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| User.Read | Délégué | Pour lire le profil de l’utilisateur et faire correspondre son profil (essentiellement, son e-mail et son utilisateur) à notre base de données afin qu’ils puissent utiliser Adobe Sign. | Pour lire le profil de l’utilisateur et faire correspondre son profil (essentiellement, son e-mail et son utilisateur) à notre base de données afin qu’ils puissent utiliser Adobe Sign. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| offline_access | Délégué | Pour actualiser le jeton d’accès, lorsque le jeton actuel est expiré. Par exemple, lorsque l’utilisateur est dans &quot; une fenêtre d’envoi de signature &quot; et la laisse inactif trop longtemps, nous devons actualiser un nouveau jeton lorsque l’utilisateur est actif. | Pour actualiser le jeton d’accès, lorsque le jeton actuel est expiré. Par exemple, lorsque l’utilisateur est dans &quot; une fenêtre d’envoi de signature &quot; et la laisse inactif trop longtemps, nous devons actualiser un nouveau jeton lorsque l’utilisateur est actif. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| openid | Délégué | E-mail et UserId. Pour connecter l’utilisateur pour s’assurer de leur consentement à l’autorisation d’utiliser l’application Adobe Sign.  | L’e-mail est l’identificateur unique pour les utilisateurs d’Adobe Sign. Nous stockons l’iD par e-mail afin que nous puissions cartographier toutes les activités de cet utilisateur à son enregistrement Adobe Sign.  | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Nos journaux contiennent suffisamment d’informations pour être en mesure d’identifier et de résoudre les problèmes des clients. Les journaux sont conservés pendant 90 jours et l’accès est restreint. Notre boutique de données a mis au jour les informations d’identification pour l’authentification pendant que l’utilisateur est hors ligne. La stratégie de conservation des bases de données est de 30 jours par rapport à la dernière

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Nous n’avons aucune interaction d’administrateur client dans notre système pour Microsoft Teams application.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Adobe Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle le moins d’autorisations de privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles fidèlement les autorisations que votre application demandera de manière dynamique et progressive ? | Oui |
| Votre application prend-elle en charge la multi-location ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Possédez-vous l’ensemble de l’identifiant de ressources unifié (URI) redirigé enregistré pour votre application ? | Oui |
| Pour votre application, qu’évitez-vous d’utiliser ? | - Wildcard rediriger les URL,<br/>- OAuth2 Implicite Flow, sauf si nécessaire pour un SPA<br/>- Flux d’identification de mot de passe propriétaire de ressources (ROPC) |
| Votre application expose-t-elle des API Web ? | Oui |
| Votre modèle d’autorisation ne permet-il aux appels de réussir que si l’application client reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de prévisualisation ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
