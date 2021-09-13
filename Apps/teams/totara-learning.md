---
title: Informations d’application pour Totara par Totara Learning
ms.author: elmalova
author: elenamalova
ms.date: 07/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Totara, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 5537ae869e4003664d71d4f04036548c432a1b8b
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281080"
---
# <a name="totara"></a>Totara

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5022e09d-d2f9-499f-8925-554c324ad23a" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003222" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Totara Learning à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Totara |
| ID | WA200003222 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Totara Learning |
| URL du site web partenaire | [https://www.totaralearning.com](https://www.totaralearning.com) |
| URL de la Teams d’informations sur l’application | [https://www.totaralearning.com/products/totara-talent-exper...](https://www.totaralearning.com/products/totara-talent-experience-platform) |
| URL de la politique de confidentialité | [https://www.totaralearning.com/en/privacy-policy](https://www.totaralearning.com/en/privacy-policy) |
| URL des conditions d’utilisation | [https://www.totaralearning.com/en/solutions/totara-cloud/te...](https://www.totaralearning.com/en/solutions/totara-cloud/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Totara Learning sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | Pour connecter l’utilisateur d’équipes à l’utilisateur système local via l’adresse e-mail | teams_id /mschannelid : pour connecter l’utilisateur local à l’utilisateur teams. Ces données sont stockées dans l’instance hébergée du client, et non dans nos serveurs. | [5022e09d-d2f9-499f-8925-554c324ad23a](https://docs.microsoft.com/microsoft-365-app-certification/azure/5022e09d-d2f9-499f-8925-554c324ad23a) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Notre application interagit directement avec l’instance hébergée de notre client, plutôt que tout service appartenant à nous ou à nos partenaires.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Totara Learning sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
