---
title: Informations d’application pour Sheetgo fournies par SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Passez en revue toutes les informations de sécurité et de conformité disponibles pour Sheetgo, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 001ad5dcce2a95885420f8413bfbfe03562eb5b2
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/26/2022
ms.locfileid: "65690429"
---
# <a name="sheetgo-application-information"></a>Informations sur l’application Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur : 3 novembre 2020</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">Afficher dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/en-US/product/office/WA200002128?tab=Overview" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SHEETGO EUROPE SL à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Sheetgo |
| ID | WA200002067 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | SHEETGO EUROPE SL |
| URL du site web du partenaire | [https://www.sheetgo.com/](https://www.sheetgo.com/) |
| URL de la politique de confidentialité | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| URL des conditions d’utilisation | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par SHEETGO EUROPE SL sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quel OII est transféré ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| MongoDB : Enregistrer les données système et utilisateur afin de fonctionner, Google BigQuery : Enregistrer l’utilisation des journaux système, Google Firestore : un système qui gère et orchestre l’état de nos microservices, Stripe : Système de paiement |  | Ces applications n’utilisent pas d’API Microsoft supplémentaires |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre de l’équipe d’une équipe ou d’une conversation à laquelle elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>La télémétrie/les journaux d’activité incluent l’adresse e-mail de l’utilisateur uniquement en tant qu’informations d’identification de l’utilisateur final. Lorsque l’utilisateur le demande, l’équipe du support technique de l’application exécute une routine automatique interne qui floute les adresses de messagerie entre les données de télémétrie/les journaux et rend les données utilisateur plus identifiables.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>MongoDB : Enregistrer les données système et utilisateur afin de fonctionner avec Google BigQuery : Enregistrer les journaux système d’utilisation de Google Firestore : système qui gère et orchestre l’état de nos microservices. Les seules données critiques de ce service transitent par les informations d’identification de l’utilisateur, qui sont chiffrées à l’aide d’AES256 Stripe: Payment system.
 
Toutes les données en transit utilisent HTTPS pour des connexions sécurisées et toutes les données sensibles sont chiffrées à l’aide d’AES256

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans l’examen ou l’analyse des données d’information d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

