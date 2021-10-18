---
title: Informations sur l’application salesforce par salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Salesforce, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b15f111d61d974a71eade2e5a3322ea3ee3431ca
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429742"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par salesforce.com à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Salesforce |
| ID | WA104379334 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou une ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | salesforce.com |
| URL du site web partenaire | [https://www.salesforce.com](https://www.salesforce.com) |
| URL de la politique de confidentialité | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| URL des conditions d’utilisation | [https://www.salesforce.com/content/dam/web/en_us/www/docume...](https://www.salesforce.com/content/dam/web/en_us/www/documents/legal/Agreements/software-order-form-supplements/Salesforce_Outlook_TOU_Order_Form_Addendum.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par salesforce.com sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Quels OII sont collectés ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Interface API JavaScript pour Office | Oui | Le add-in utilise les fonctions de Office.js et EWS pour copier le contenu et les pièces jointes d’un e-mail qu’un utilisateur Outlook a décidé de se connecter à Salesforce. Des fonctionnalités similaires sont utilisées côté calendrier pour enregistrer les rendez-vous dans Salesforce. | Le add-in utilise les fonctions de Office.js et EWS pour copier le contenu et les pièces jointes d’un e-mail qu’un utilisateur Outlook a décidé de se connecter à Salesforce. Des fonctionnalités similaires sont utilisées côté calendrier pour enregistrer les rendez-vous dans Salesforce. | Le add-in utilise des fonctions telles que getUserIdentityTokenAsync pour obtenir l’identité Outlook utilisateur actuel, GetItem (.js and EWS) to get and set AdditionalProperties and the content of the current email message when saving to Salesforce records, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder,  CreateItem (.js), qui est utilisé pour créer un brouillon de message. | Le add-in utilise des fonctions telles que getUserIdentityTokenAsync pour obtenir l’identité Outlook utilisateur actuel, GetItem (.js and EWS) to get and set AdditionalProperties and the content of the current email message when saving to Salesforce records, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder,  CreateItem (.js), qui est utilisé pour créer un brouillon de message. |
>| Services Web Exchange (EWS) | Oui | Le add-in utilise les fonctions de Office.js et EWS pour copier le contenu et les pièces jointes d’un e-mail qu’un utilisateur Outlook a décidé de se connecter à Salesforce. Des fonctionnalités similaires sont utilisées côté calendrier pour enregistrer les rendez-vous dans Salesforce. | Le add-in utilise les fonctions de Office.js et EWS pour copier le contenu et les pièces jointes d’un e-mail qu’un utilisateur Outlook a décidé de se connecter à Salesforce. Des fonctionnalités similaires sont utilisées côté calendrier pour enregistrer les rendez-vous dans Salesforce. | Le add-in utilise des fonctions telles que getUserIdentityTokenAsync pour obtenir l’identité Outlook utilisateur actuel, GetItem (.js and EWS) to get and set AdditionalProperties and the content of the current email message when saving to Salesforce records, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder,  CreateItem (.js), qui est utilisé pour créer un brouillon de message. | Le add-in utilise des fonctions telles que getUserIdentityTokenAsync pour obtenir l’identité Outlook utilisateur actuel, GetItem (.js and EWS) to get and set AdditionalProperties and the content of the current email message when saving to Salesforce records, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder,  CreateItem (.js), qui est utilisé pour créer un brouillon de message. |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Non

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Le stockage Salesforce est décrit dans le Guide de sécurité à l' https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par salesforce.com sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
