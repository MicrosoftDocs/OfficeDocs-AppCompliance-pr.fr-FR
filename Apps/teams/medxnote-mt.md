---
title: Informations sur l’application pour Medxnote MT par Medxnote
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Medxnote MT, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5eff51e5045f299ad8fe9e8335b3c5dac41af919
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281217"
---
# <a name="medxnote-mt"></a>Medxnote MT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/02ffb7cc-5fcd-4b31-bcbd-b24bbca74cc7" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001823" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Medxnote à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Medxnote MT |
| ID | WA200001823 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Medxnote |
| URL du site web partenaire | [https://medxnote.com/](https://medxnote.com/) |
| URL de la politique de confidentialité | [https://medxnote.com/privacy-policy/](https://medxnote.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://medxnote.com/terms-conditions/](https://medxnote.com/terms-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Medxnote sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read.All | application | nous mettre en cache le nom et le courrier électronique, utilisés côté hôpital pour vérifier les privilèges des utilisateurs | lors de l’envoi de messages à certaines reprises Le nom et l’adresse e-mail sont ajoutés, nous mettre en cache ces données côté serveur, il est également utilisé pour la vérification facultative des privilèges côté hôpital | [fc70bbbe-91c4-4d8f-a9c9-a022068d5752](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc70bbbe-91c4-4d8f-a9c9-a022068d5752) |
>| openid | délégué | nous mettre en cache l’ID de session, l’ID utilisateur, le jeton du porteur et le courrier électronique, utilisés pour la signature des utilisateurs dans le module de tâche | l’utiliser pour se connecter aux utilisateurs dans le module de tâche, nous stockons l’ID de session, userid, e-mail, jetons du porteur | [fc70bbbe-91c4-4d8f-a9c9-a022068d5752](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc70bbbe-91c4-4d8f-a9c9-a022068d5752) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>l’adresse e-mail, le nom, l’ID de locataire et l’ID de canal peuvent apparaître dans les journaux Toutes les données du journal sont automatiquement supprimées au bout d’un mois au plus tard.
L’accès à ceux-ci est limité à quelques administrateurs d’organisation qui ont un accès 2FA appliqué.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>L’accès est limité à quelques administrateurs d’organisation qui ont un accès 2FA appliqué.
les systèmes critiques sont accessibles uniquement à partir de certaines adresses IP ;

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

