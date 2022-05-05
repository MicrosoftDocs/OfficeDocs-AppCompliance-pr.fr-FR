---
title: Informations d’application pour Saberr par Saberr
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 02/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Saberr, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a41fb58d14186cea217bc23e09061233f87c21d8
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226148"
---
# <a name="saberr"></a>Saberr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur : 11 février 2021</p>

* <a href="https://teams.microsoft.com/l/app/d3a07709-eb0e-421c-8609-b61b0600e645" target="_blank">Afficher dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001501" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Saberr à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Saberr |
| ID | WA200001501 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Saberr |
| URL du site web du partenaire | [https://www.saberr.com](https://www.saberr.com) |
| URL de Teams page d’informations sur l’application | [https://help.saberr.com/en/articles/3854472-use-coachbot-in...](https://help.saberr.com/en/articles/3854472-use-coachbot-in-microsoft-teams-to-get-notifications-and-quick-actions) |
| URL de la politique de confidentialité | [https://help.saberr.com/en/articles/3853094-privacy-for-use...](https://help.saberr.com/en/articles/3853094-privacy-for-users-of-coachbot-s-microsoft-teams-or-slack-integrations) |
| URL des conditions d’utilisation | [https://help.saberr.com/en/articles/3853596-terms-and-condi...](https://help.saberr.com/en/articles/3853596-terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Saberr sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-ils stockées ? Justification du stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Délégué | E-mail, prénom et nom. Utilisé pour la création de compte dans notre API. | E-mail, prénom et nom. Utilisé pour la création de compte dans notre API. | [9de91aee-708c-4d9f-958b-109fdb79d993](/microsoft-365-app-certification/azure/9de91aee-708c-4d9f-958b-109fdb79d993) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et compléments basés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelles (OII). Répertoriez toutes les API Microsoft autres que Microsoft Graph utilisées par cette application.

>| **API** |  **OII est-il collecté ?** |  **Quelle OII est collectée ?** | **Justification de la collecte d’OII ?** | **OII est-il stocké ?** | **Justification du stockage d’OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft BOT API | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quel OII est transféré ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS, Slack, Pipedrive, Google, Mailchimp, Intercom, Cronofy | Nom de la société, nom d’utilisateur, adresse e-mail de l’utilisateur | Les utilisateurs doivent être associés à leur organisation afin d’utiliser des fonctionnalités telles que des réunions. Nous transférons uniquement l’EUII/OII nécessaire pour établir ces organisations dans l’application et effectuer des contrats + support avec eux. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre de l’équipe d’une équipe ou d’une conversation à laquelle elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII ?**  | **EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Nous avons besoin d’un e-mail, d’un prénom et d’un nom pour la création de compte dans notre API | e-mail, prénom, nom | Requis pour la création de compte dans notre API |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucune OII ou EUII n’apparaît dans les journaux ou les données de télémétrie des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>Nous définissons des stratégies de rétention dans tous les systèmes partenaires et appliquons les configurations de sécurité maximale disponibles (par exemple, 2FA)

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans l’examen ou l’analyse des données d’information d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36430' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36430" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Saberr sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Intégrez-vous à La plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
