---
title: Informations d’application pour Sheetgo par SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Sheetgo, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b9dca68847e1a96a68db641b5f874248bfa978bb
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250122"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002067" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SHEETGO EUROPE SL à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Sheetgo |
| ID | WA200002067 |
| Fonctionnalités | Tab |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | SHEETGO EUROPE SL |
| URL du site web partenaire | [https://www.sheetgo.com](https://www.sheetgo.com) |
| URL de la politique de confidentialité | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| URL des conditions d’utilisation | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par SHEETGO EUROPE SL sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| MongoDB : enregistrer les données système et utilisateur afin de fonctionner, Google BigQuery : enregistrer l’utilisation du système d’enregistrement, Google Firestore : un système qui maintient et orchestre l’état de nos microservices, Stripe : système de paiement |  | Ces applications n’utilisent pas d’API Microsoft supplémentaires |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>La télémétrie/journaux inclut l’adresse de messagerie de l’utilisateur uniquement en tant qu’informations d’identification de l’utilisateur final. Lorsque l’utilisateur le demande, l’équipe de support technique de l’application exécute une routine automatique interne qui estompe les adresses de messagerie dans les journaux/télémétrie et rend les données utilisateur non identifiables.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>MongoDB : enregistrer les données système et utilisateur afin de fonctionner Google BigQuery : enregistrer le système enregistre l’utilisation google Firestore : un système qui maintient et orchestre l’état de nos microservices. Les seules données critiques transitant par ce service sont les informations d’identification de l’utilisateur, qui sont chiffrées à l’aide d’AES256 Stripe : Système de paiement.
 
Toutes les données en transit utilisent HTTPS pour les connexions sécurisées et toutes les données sensibles sont chiffrées à l’aide d’AES256

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

