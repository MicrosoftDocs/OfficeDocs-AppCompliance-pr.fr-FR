---
title: Informations d’application pour Salesforce par salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Salesforce, ses politiques de traitement des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29c00595a806c5144b34701ba54860353f9cafc0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553705"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par salesforce.com à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Salesforce |
| ID | WA104379334 |
| Office 365 clients soutenus | Outlook 2013 ou plus tard sur Windows, Outlook 2016 ou plus tard sur Mac, Outlook sur le web |
| Nom de l’entreprise partenaire | salesforce.com |
| URL du site web partenaire | [https://www.salesforce.com/](https://www.salesforce.com/) |
| URL de la politique de confidentialité | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| URL des conditions d’utilisation | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par salesforce.com sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>Cette application n’utilise pas microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les modules complémentaires intégrés à Microsoft 365 peuvent utiliser d’autres API Microsoft que Microsoft Graph pour recueillir ou traiter des informations organisationnelles identifiables (OII). Énumérez toutes les API Microsoft autres que Microsoft Graph utilisations de cette application.

>| **API** |  **L’ŒIL est-il recueilli?** |  **Quel OII est recueilli?** | **Justification de la collecte de l’ŒII?** | **OII est-il stocké ?** | **Justification pour stocker OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Interface API JavaScript pour Office | Oui | L’add-in utilise les fonctions de Office.js et EWS pour copier du contenu et des pièces jointes sur un e-mail qu’un utilisateur Outlook a décidé de se connecter à Salesforce. Des fonctionnalités similaires sont utilisées du côté du calendrier, pour enregistrer les rendez-vous dans Salesforce. |  | L’add-in utilise des fonctions telles que getUserIdentityTokenAsync pour obtenir l’identité utilisateur Outlook actuelle, GetItem (.js et EWS) pour obtenir et définir additionalproperties et le contenu du message électronique actuel lors de l’enregistrement des enregistrements Salesforce, GetAttachment (EWS) pour récupérer les pièces jointes de Exchange et ajouter à l’e-mail Salesforce jumelé, UpdateItem (.js), GetFolder (.js) pour obtenir le dossier brouillons, CreateItem (.js), qui est utilisé pour créer un projet de message. |  |
>| Services Web Exchange (EWS) | Oui | L’add-in utilise les fonctions de Office.js et EWS pour copier du contenu et des pièces jointes sur un e-mail qu’un utilisateur Outlook a décidé de se connecter à Salesforce. Des fonctionnalités similaires sont utilisées du côté du calendrier, pour enregistrer les rendez-vous dans Salesforce. |  | L’add-in utilise des fonctions telles que getUserIdentityTokenAsync pour obtenir l’identité utilisateur Outlook actuelle, GetItem (.js et EWS) pour obtenir et définir additionalproperties et le contenu du message électronique actuel lors de l’enregistrement des enregistrements Salesforce, GetAttachment (EWS) pour récupérer les pièces jointes de Exchange et ajouter à l’e-mail Salesforce jumelé, UpdateItem (.js), GetFolder (.js) pour obtenir le dossier brouillons, CreateItem (.js), qui est utilisé pour créer un projet de message. |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Non

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Le stockage Salesforce est décrit dans le Guide de sécurité à https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

