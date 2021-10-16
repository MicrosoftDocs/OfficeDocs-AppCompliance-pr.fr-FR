---
title: Informations sur les applications pour Smartsheet par Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 11/11/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Smartsheet, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f95e090af5a83db8053bf60582a73dd77a2905d0
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410888"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Smartsheet à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Smartsheet |
| ID | WA104380975 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Smartsheet |
| URL du site web partenaire | [https://www.smartsheet.com](https://www.smartsheet.com) |
| URL de la Teams d’informations sur l’application | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL de la politique de confidentialité | [https://www.smartsheet/legal/privacy](https://www.smartsheet/legal/privacy) |
| URL des conditions d’utilisation | [https://Default Contrat utilisateur : https://www.smartsheet.com/.. .](https://Default User Agreement: https://www.smartsheet.com/legal/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Smartsheet sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | délégué | Aucun. | Permet à notre application d’installer des applications pour le compte de l’utilisateur. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Directory.Read.All | délégué | tenantId pour la récupération des informations à afficher dans l’interface utilisateur. | Nous permet de lire les applications que ce client utilise pour vérifier si nous devons installer l’application pour ces applications. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.Read.All | délégué | teamId/groupId pour la remise des messages. | Permet à notre application de lire les informations de base sur un groupe (ou Teams équipe) ainsi que sur les conversations. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.ReadWrite.All | délégué | teamId/groupId pour la remise des messages. | Permet à notre application de démarrer de nouvelles conversations dans Teams. Cette autorisation inclut également l’étendue Read.All ci-dessus, mais nous avons également besoin de cette autorisation pour des raisons techniques. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| User.Read.All | délégué | userId. | Nous permet de lire les informations de base sur un utilisateur pendant le processus d’th. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| offline_access | délégué | refreshToken. | Permet à notre application de recevoir des jetons d’actualisation et d’actualiser le jeton d’th pour le compte de l’utilisateur lorsqu’il utilise l’application. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API Bot Framework | Oui | Nous utilisons l’API Bot Framework pour remettre des messages en tant qu’application pour l’application Teams. Smartsheet stocke les informations userId pour savoir à qui le bot Smartsheet parle. |  | Aucune |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Smartsheet stocke les informations dans un état chiffré au repos dans notre environnement de centre de données de production hébergé avec Equinix et dans AWS S3 où nous stockons les pièces jointes client dans des compartiments chiffrés privés. |  | Nous utilisons l’API bot Framework pour remettre des messages en tant qu’application pour l’application Teams. Smartsheet stocke les informations userId pour savoir à qui le bot Smartsheet parle. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Smartsheet l’utilise pour assurer le suivi des personnes que le bot parle également. Pendant le flux d’thème initial, nous créons un enregistrement de bot pour l’utilisateur dans le système de notification Smartsheet. | Pour smartsheet pour Teams bot, nous stockons les e-mails utilisateur et userId de Teams pour vous aider à suivre les personnes avec qui le bot parle.  Smartsheet stocke les tenantId pour aider à lister les groupes dont l’utilisateur fait partie dans l’annuaire et groupIds pour la remise des messages. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Non

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>La feuille de calcul chiffre toutes les informations utilisateur stockées et nos administrateurs doivent utiliser la 2FA. Smartsheet fonctionne comme un fournisseur SaaS sans affichage et, par défaut, nous ne révisons pas le contenu que les clients choisiront de télécharger ou d’entrer dans la plateforme.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


