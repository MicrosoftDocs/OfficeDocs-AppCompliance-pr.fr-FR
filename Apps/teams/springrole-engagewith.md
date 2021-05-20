---
title: Informations sur l’application pour EngageWith par SpringRole
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour EngageWith, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6bb19440f4d5e9518e917856fbe709fbcfc0792f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552755"
---
# <a name="engagewith"></a>EngageWith

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/6fb7f99a-d746-4a4b-8964-7c17d48935bb" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001915" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par SpringRole à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | EngageWith |
| ID | WA200001915 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | SpringRole |
| URL du site web partenaire | [https://engagewith.springworks.in/](https://engagewith.springworks.in/) |
| URL de la Teams d’informations sur l’application | [https://www.springworks.in/engagewith/](https://www.springworks.in/engagewith/) |
| URL de la politique de confidentialité | [https://engagewith.springworks.in/privacy-policy](https://engagewith.springworks.in/privacy-policy) |
| URL des conditions d’utilisation | [https://engagewith.springworks.in/terms-and-conditions](https://engagewith.springworks.in/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par SpringRole sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS, Mailchimp, Stripe. Nom du client, e-mail, adresse IP, informations de paiement. Nous utilisons ces tiers pour offrir la meilleure expérience client à nos clients | Nom, e-mail | ce complément n’utilise pas d’API supplémentaires |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Ces données sont utilisées pour afficher et stocker l’historique d’échange des points de &amp; récompense. Également utilisé dans la fonctionnalité principale de l’application pour donner Kudos et Lesout aux homologues | Nom, e-mail, anniversaire et anniversaire de travail. | Ces données sont utilisées pour afficher et stocker leur historique d’échange de points &amp; de récompense |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>OII : nom de l’organisation, ID de client apparaissent dans les journaux ; EUII : ID d’objet aad, nom complet, courrier électronique s’affichent dans les journaux. Période de rétention de 30 jours, suppression automatique

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Données stockées dans RDS, AWS. il est chiffré. L’accès est uniquement accessible à un ingénieur Devops, chef d’ingénierie et fondateur

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36381' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36381" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par SpringRole sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
