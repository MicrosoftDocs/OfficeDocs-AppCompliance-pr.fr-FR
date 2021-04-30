---
title: Informations d'application pour Salesforce par salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour Salesforce, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 88e6a4913e3a3c85ea76fd58c1a724f957c9a3e6
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094041"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par salesforce.com à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Salesforce |
| ID | WA104379334 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | salesforce.com |
| URL du site web partenaire | [https://www.salesforce.com/](https://www.salesforce.com/) |
| URL de la politique de confidentialité | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| URL des conditions d'utilisation | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par salesforce.com sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n'utilise pas Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l'aide d'autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d'identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu'est-ce qu'OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Interface API JavaScript pour Office | Oui | Le add-in utilise les fonctions de Office.js et EWS pour copier le contenu et les pièces jointes d'un e-mail qu'un utilisateur Outlook a décidé de se connecter à Salesforce. Des fonctionnalités similaires sont utilisées côté calendrier pour enregistrer des rendez-vous dans Salesforce. |  | Le complément utilise des fonctions telles que getUserIdentityTokenAsync pour obtenir l'identité utilisateur Outlook actuelle, GetItem (.js et EWS) pour obtenir et définir AdditionalProperties et le contenu du message électronique actuel lors de l'enregistrement dans les enregistrements Salesforce, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder, CreateItem (.js), which is used to create a draft message. |  |
>| Services Web Exchange (EWS) | Oui | Le add-in utilise les fonctions de Office.js et EWS pour copier le contenu et les pièces jointes d'un e-mail qu'un utilisateur Outlook a décidé de se connecter à Salesforce. Des fonctionnalités similaires sont utilisées côté calendrier pour enregistrer des rendez-vous dans Salesforce. |  | Le complément utilise des fonctions telles que getUserIdentityTokenAsync pour obtenir l'identité utilisateur Outlook actuelle, GetItem (.js et EWS) pour obtenir et définir AdditionalProperties et le contenu du message électronique actuel lors de l'enregistrement dans les enregistrements Salesforce, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder, CreateItem (.js), which is used to create a draft message. |  |

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

>Non

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Le stockage Salesforce est décrit dans le Guide de sécurité à l' https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

