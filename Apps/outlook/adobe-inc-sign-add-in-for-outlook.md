---
title: Informations d'application pour adobe sign Add-In pour Outlook par Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour Adobe Sign Add-In pour Outlook, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5ae63ddb614784164870b24508e0782bce49dd48
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094105"
---
# <a name="adobe-sign-add-in-for-outlook"></a>Adobe Sign Add-In for Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381158" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Adobe Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Adobe Sign Add-In for Outlook |
| ID | WA104381158 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | Adobe Inc. |
| URL du site web partenaire | [https://www.adobe.com/](https://www.adobe.com/) |
| URL de la politique de confidentialité | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL des conditions d'utilisation | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par Adobe Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d'autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d'application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | application | Nous avons besoin de données de l'e-mail pour retirer le rapport Adobe Sign History et Audit Trail de chaque transaction. https://helpx.adobe.com/sign/using/audit-reports-transaction-history.html | Pour remplir le document joint, les e-mails de l'expéditeur et du destinataire, ainsi que le contenu des messages électroniques envoyés à Adobe sign to send for signature. Cela permet à l'utilisateur de gagner du temps pour retaper ces champs dans Adobe Sign. Une fois qu'un contrat est signé, nous rédigeons automatiquement un nouveau courrier électronique pour que l'utilisateur envoie un courrier électronique pour informer ses destinataires que la transaction est effectuée. |  |
>| People.Read | délégué |  | Pour remplir automatiquement l'adresse e-mail dans l'expérience Envoyer pour signature, en tapant des lettres initiales, n'exigez pas que les utilisateurs tapent l'intégralité &quot; &quot; des e-mails. |  |
>| User.Read | délégué |  | Pour lire le profil de l'utilisateur et faire correspondre son profil (en fait, son courrier électronique) à notre base de données afin qu'il puisse utiliser Adobe Sign. |  |
>| offline_access | délégué |  | Pour actualiser le jeton d'accès, lorsque le jeton actuel a expiré. Par exemple, lorsque l'utilisateur se trouve dans une fenêtre d'envoi de signature et la laisse inactive pendant trop longtemps, nous devons actualiser un nouveau jeton lorsque &quot; &quot; l'utilisateur est actif. |  |
>| openid | délégué | La messagerie électronique est l'identificateur unique pour les utilisateurs dans Adobe Sign. Nous stockons l'ID de courrier électronique afin de pouvoir ma mapiller toutes les activités de cet utilisateur sur son enregistrement Adobe Sign.  | Pour que l'utilisateur se connecte afin de s'assurer de son consentement pour l'autorisation d'utiliser l'application Adobe Sign. |  |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="add-in-data-access"></a>Accès aux données du add-in

List the permissions this app requires for accessing your organization's data, the justification and purpose for this permission (what does the app use this information for?) and whether the app stores any of this information in its databases.

>| **Autorisation**  | **Description** |
>|:----------------|:----------------|
>| ReadWrite Mailbox | Ce module peut lire ou modifier le contenu de n'importe quel élément de votre boîte aux lettres et créer des éléments. Il peut accéder à des informations personnelles, telles que le corps, l'objet, l'expéditeur, les destinataires ou les pièces jointes, dans n'importe quel élément de message ou de calendrier. Il peut envoyer ces données à un service tiers. |
>| Envoyer des données | Peut envoyer des données sur Internet |

#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun. Nous ne déconnectons pas les EUII ou OII dans la télémétrie ou les journaux. Le processus est nos propres examens de sécurité qui nous valident que nous ne le faisons pas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Nous n'avons aucune interaction de l'administrateur client dans notre système pour Microsoft Teams application.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

