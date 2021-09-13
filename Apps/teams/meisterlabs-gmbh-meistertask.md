---
title: Informations sur l’application pour QuéeTask par QuéeLabs
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour OmètreTask, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: dafbebb8b0bed7d06a3850a26ab205db0517ae5f
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281212"
---
# <a name="meistertask"></a>MeisterTask

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/4d0f0848-3fdd-4046-9976-d5568c8b71f4" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381349" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies à Microsoft par ÉvrierLabs Contrôleh :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | MeisterTask |
| ID | WA104381349 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | MeisterLabs GmbH |
| URL du site web partenaire | [https://www.meistertask.com](https://www.meistertask.com) |
| URL de la Teams d’informations sur l’application | [https://support.meistertask.com/](https://support.meistertask.com/) |
| URL de la politique de confidentialité | [https://www.meistertask.com/privacy](https://www.meistertask.com/privacy) |
| URL des conditions d’utilisation | [https://www.meistertask.com/legal](https://www.meistertask.com/legal) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par CommanderInsyth sur la façon dont cette application collecte et stocke les données organisationnelles, ainsi que sur le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | ID, displayName, adresse de messagerie. | Pour l’authentification et l’inscription. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Tous les EUII et OII mentionnés ci-dessus peuvent potentiellement se retrouver dans des fichiers journaux utilisés à des fins de débogage. Toutes les données du journal sont automatiquement supprimées au bout de 6 mois au plus tard.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les administrateurs du client peuvent supprimer leurs données et fermer leurs comptes. La période de rétention n’est pas personnalisable. L’audit n’est actuellement pas disponible. Les données générées par l’utilisateur peuvent être archivées manuellement ou accessibles via l’API publique ( https://developers.meistertask.com/) . Les stratégies de l’utilisateur final sont disponibles sur https://www.meistertask.com/privacy et https://www.meistertask.com/terms .


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35426' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35426" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

