---
title: Informations sur l’application pour Lemux par Plumm Health LTD
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Plumm, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8fef6e74339b611b06d39e6bbe32f9661e20656c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429872"
---
# <a name="plumm"></a>Plumm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d66da813-3337-4f88-8e08-f01c0bbb8f34" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003326" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par La société d’assurance maladie (LTD) à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Plumm |
| ID | WA200003326 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Plumm Health LTD |
| URL du site web partenaire | [https://www.plummhealth.com](https://www.plummhealth.com) |
| URL de la Teams d’informations sur l’application | [https://www.plummhealth.com/about-us](https://www.plummhealth.com/about-us) |
| URL de la politique de confidentialité | [https://www.plummhealth.com/privacy-policy](https://www.plummhealth.com/privacy-policy) |
| URL des conditions d’utilisation | [https://www.plummhealth.com/terms-of-use](https://www.plummhealth.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par l’entreprise Plumm Health LTD sur la façon dont cette application collecte et stocke les données organisationnelles, ainsi que sur le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | application | Nous utilisons l’userID dans cette autorisation. Il est utilisé pour envoyer les notifications requises à l’utilisateur en fonction de son utilisation de notre service. Ceci est important pour que l’utilisateur reçoie les notifications appropriées pour son compte sur notre application. | Dans cette autorisation, nous ne stockons aucune donnée dans notre base de données. En fait, nous utilisons l’userID pour envoyer une notification appropriée à chaque utilisateur en fonction de son utilisation. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| TeamsAppInstallation.ReadWriteForUser.All | application | Nous recevons l’ID d’installation à l’aide de cette autorisation. Ceci est important pour nous afin de pouvoir envoyer la notification appropriée et correcte pour chaque utilisateur individuel. | Nous ne stockons pas de données dans notre application à l’aide de cette autorisation. Nous n’en avons pas besoin, car nous avons uniquement besoin de l’ID d’installation qui est obtenu au moment de l’utilisation en fournissant l’ID d’utilisateur. Cela est obtenu dynamiquement au moment de l’run-time, par conséquent, il n’est pas nécessaire de stocker l’ID d’installation. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read | délégué | Nous collectons le nom, l’image et le courrier électronique de nos utilisateurs par le biais de cette autorisation. Cette opération est nécessaire pour pouvoir identifier des utilisateurs individuels et ces points de données doivent être affichés lorsque cela est nécessaire, par exemple une page de profil individuelle et lors d’une communication par courrier électronique/notification. | Ces autorisations permettent à notre application de voir le profil de base de nos utilisateurs (nom, image, e-mail). Ces données seront utilisées pour afficher le nom et/ou l’image de profil de l’utilisateur sur son compte d’application avec nous, ainsi que sur la communication par courrier électronique et/ou la notification. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read.All | application | Cette autorisation permet à notre application de lire les profils utilisateur sans utilisateur. Dans ce cas, nous collectons uniquement le nom, l’image de profil et le courrier électronique. Cette opération est nécessaire pour pouvoir identifier des utilisateurs individuels et ces points de données doivent être affichés lorsque cela est nécessaire, par exemple une page de profil individuelle et lors d’une communication par courrier électronique/notification. | Ces autorisations permettent à notre application de voir le profil de base de nos utilisateurs (nom, image, e-mail). Ces données seront utilisées pour afficher le nom et/ou l’image de profil de l’utilisateur sur son compte d’application avec nous, ainsi que sur la communication par courrier électronique et/ou la notification. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| email | délégué | L’ID de courrier de l’utilisateur est collecté. Nous avons besoin de ces données pour accorder l’accès à l’utilisateur pour nos services, nous connectons à notre application et recevons des notifications concernant leurs comptes et nos services sur cet ID de courrier électronique.  | L’ID de courrier électronique est stocké dans la base de données. Nous devons stocker l’ID de courrier électronique afin d’identifier de manière unique les utilisateurs, de leur fournir l’accès à notre application, de les aider à se connecter et de les aider à recevoir des notifications concernant leur compte avec nous. Par exemple, un utilisateur avec un ID de abc@xyz.com peut accéder à notre application et à nos services lorsqu’il se connecte à Teams avec cet &quot; &quot; ID de messagerie. En fonction de l’utilisation, nous pouvons envoyer des notifications à cet utilisateur sur son ID de courrier. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| openid | délégué | Pour cette autorisation, nous ne collectons aucune donnée.  | Pour cette autorisation, nous ne collectons aucune donnée. Cette autorisation permet aux utilisateurs de se connecter à notre application avec leur ID de courrier électronique de travail et permet à l’application de voir les informations de profil utilisateur de base. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| profil | délégué | Nous collectons le nom, l’image et le courrier électronique de nos utilisateurs par le biais de cette autorisation. Cette opération est nécessaire pour pouvoir identifier des utilisateurs individuels et ces points de données doivent être affichés lorsque cela est nécessaire, par exemple une page de profil individuelle et lors d’une communication par courrier électronique/notification. | Ces autorisations permettent à notre application de voir le profil de base de nos utilisateurs (nom, image, e-mail). Ces données seront utilisées pour afficher le nom et/ou l’image de profil de l’utilisateur sur son compte d’application avec nous, ainsi que sur la communication par courrier électronique et/ou la notification. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom | Prénom, Nom, E-mail | Intercom est notre CRM qui nous aide à gérer la communication avec tous nos utilisateurs. C’est pourquoi nous devons envoyer le prénom, le nom de famille et l’ID de messagerie de nos utilisateurs au CRM afin que les messages/e-mails appropriés soient envoyés aux utilisateurs. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous stockons les données d’utilisation du service telles que le nombre de sessions de groupe utilisées, les cours vus, les salles d’affichage, la date des sessions, etc. Nous conservons les données de nos utilisateurs jusqu’à ce que l’utilisateur demande spécifiquement la suppression ou l’oubli de leur compte.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous gérons les données envoyées au CRM via notre serveur. Les données minimales requises pour le fonctionnement sont transmises au CRM (Intercom). Elle conserve un contrôle total sur les données transmises au CRM, la rétention des données sur Intercom et leur suppression. Voici un lien pour passer en revue les stratégies de données client d’Intercom : https://www.intercom.com/legal/terms-and-policies#customer-data

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Plumm Health LTD sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Non |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | ,<br/><br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
