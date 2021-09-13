---
title: Informations d’application pour Saberr par Saberr
ms.author: elmalova
author: elenamalova
ms.date: 02/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Saberr, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4445df9966efc07b0aa2e80b4ec7c061b451e343
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283666"
---
# <a name="saberr"></a>Saberr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 11, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d3a07709-eb0e-421c-8609-b61b0600e645" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001501" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Saberr à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Saberr |
| ID | WA200001501 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Saberr |
| URL du site web partenaire | [https://www.saberr.com](https://www.saberr.com) |
| URL de la Teams d’informations sur l’application | [https://help.saberr.com/en/articles/3854472-use-coachbot-in...](https://help.saberr.com/en/articles/3854472-use-coachbot-in-microsoft-teams-to-get-notifications-and-quick-actions) |
| URL de la politique de confidentialité | [https://help.saberr.com/en/articles/3853094-privacy-for-use...](https://help.saberr.com/en/articles/3853094-privacy-for-users-of-coachbot-s-microsoft-teams-or-slack-integrations) |
| URL des conditions d’utilisation | [https://help.saberr.com/en/articles/3853596-terms-and-condi...](https://help.saberr.com/en/articles/3853596-terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Cette information a été fournie par Saberr sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | E-mail, prénom et nom de famille. Utilisé pour la création de compte dans notre API. | E-mail, prénom et nom de famille. Utilisé pour la création de compte dans notre API. | [9de91aee-708c-4d9f-958b-109fdb79d993](https://docs.microsoft.com/microsoft-365-app-certification/azure/9de91aee-708c-4d9f-958b-109fdb79d993) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft BOT API | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS, Slack, Pipedrive, Google, Mailchimp, Intercom, Cronofy | Nom de la société, nom d’utilisateur, adresse de messagerie de l’utilisateur | Les utilisateurs doivent être associés à leur organisation pour pouvoir utiliser des fonctionnalités telles que les réunions. Nous transférons uniquement les EUII/OII nécessaires pour établir ces organisations dans l’application et mener des contrats + prise en charge avec elles. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Nous avons besoin d’e-mail, de prénom et de nom de famille pour la création de compte dans notre API | e-mail, prénom, nom | Requis pour la création de compte dans notre API |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous avons configuré des stratégies de rétention dans tous les systèmes partenaires et appliqué les configurations de sécurité maximales disponibles (par exemple, 2FA)

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36430' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36430" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Cette information a été fournie par Saberr sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
