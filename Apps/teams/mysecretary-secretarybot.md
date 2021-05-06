---
title: Informations sur l’application PourBot par MySecretary
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour LeBot, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: db8975661eeca1c5b473e98e5d6990da6bbb2264
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250612"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par MySecretary à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | SecretaryBot |
| ID | WA104381085 |
| Fonctionnalités | Bot, Onglet |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | MySecretary |
| URL du site web partenaire | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| URL de la Teams d’informations sur l’application | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| URL de la politique de confidentialité | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par MySecretary sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read.Shared | délégué |  | Récupérer les informations de temps libre de l’utilisateur et de ses collègues. |  |
>| Calendars.ReadWrite | délégué |  | Envoyer une demande de réunion à la place de l’utilisateur. |  |
>| MailboxSettings.Read | délégué | Stocker la langue pour afficher le langage correct. Gagner du temps pour appeler MS Graph API de calendrier correctement | Récupérer le paramètre de langue et de fuseau horaire de l’utilisateur. |  |
>| People.Read | délégué |  | Essayez de trouver des collègues qui ont des relations fortes avec l’utilisateur. |  |
>| User.Read | délégué | Stockez le nom d’utilisateur, la ville, le pays et langauge pour l’analyse utilisateur. Stockez le courrier électronique pour contacter le client. Nous n’avons jamais utilisé d’adresse de messagerie, mais nous pouvons l’utiliser pour la prise en charge. | Essayez de trouver le pays et la langue préférés de l’utilisateur. Il est utilisé pour la sauvegarde de MailboxSettings.Read. |  |
>| email | délégué | Voir ci-dessus. | Pour stocker le courrier électronique. |  |
>| openid | délégué |  | Pour l’authentification OpenID. |  |
>| profil | délégué | Enregistrez OID pour identifier l’ID unique de l’utilisateur dans le système d’identité MS. | Obtention du nom d’utilisateur et de l’OID. Essayez d’utiliser OID pour la connexion Outlook le addin à l’avenir. |  |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Utilisez cette infromation pour planifier une réunion d’équipe | Non |  |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Les données OII ou EUII apparaissent dans la télémétrie ou les journaux.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous ne fournissons pas encore de contrôle administratif aux utilisateurs finaux, mais si les utilisateurs finaux nous demandent de supprimer des données, nous pouvons suivre leur demande.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

