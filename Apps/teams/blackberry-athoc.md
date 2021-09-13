---
title: Informations d’application pour BlackBerry AtHoc par BlackBerry
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour BlackBerry AtHoc, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 38d1d54293b3f406a0a5c8028850dae27a9c9294
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279945"
---
# <a name="blackberry-athoc"></a>BlackBerry AtHoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003065" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par BlackBerry à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | BlackBerry AtHoc |
| ID | WA200003065 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | BlackBerry |
| URL du site web partenaire | [https://www.blackberry.com](https://www.blackberry.com) |
| URL de la Teams d’informations sur l’application | [https://www.blackberry.com/us/en/products/blackberry-athoc](https://www.blackberry.com/us/en/products/blackberry-athoc) |
| URL de la politique de confidentialité | [https://www.blackberry.com/us/en/legal/privacy-policy](https://www.blackberry.com/us/en/legal/privacy-policy) |
| URL des conditions d’utilisation | [https://www.athoc.com/pss/terms.html#](https://www.athoc.com/pss/terms.html#) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par BlackBerry sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | délégué | Nous accédons aux informations de base de l’utilisateur&#8217;telles que le nom principal et le lien vers le canal général des équipes (pour lequel l’utilisateur est autorisé) à envoyer une carte d’alerte aux équipes. | Nous ne&#8217;pas stocker les données utilisateur dans la base de données, mais dans la mémoire du bot. Nous stockons le nom principal de l’utilisateur, jeton AAD, jeton BlackBerry AtHoc, préférence/configuration blackBerry AtHoc Server dans la mémoire du bot. Vous avez besoin des informations nécessaires pour envoyer une demande d’API à l’API Microsoft Graph et à notre serveur BlackBerry AtHoc. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| Group.Read.All | délégué | Nous accédons aux informations de base de l’utilisateur&#8217;telles que le nom principal et le lien vers le canal général des équipes (pour lequel l’utilisateur est autorisé) à envoyer une carte d’alerte aux équipes. | Nous ne&#8217;pas stocker les données utilisateur dans la base de données, mais dans la mémoire du bot. Nous stockons le nom principal de l’utilisateur, jeton AAD, jeton BlackBerry AtHoc, préférence/configuration blackBerry AtHoc Server dans la mémoire du bot. Vous avez besoin des informations nécessaires pour envoyer une demande d’API à l’API Microsoft Graph et à notre serveur BlackBerry AtHoc. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| User.Read | délégué | Nous accédons aux informations de base de l’utilisateur&#8217;telles que le nom principal et le lien vers le canal général des équipes (pour lequel l’utilisateur est autorisé) à envoyer une carte d’alerte aux équipes. | Nous ne&#8217;pas stocker les données utilisateur dans la base de données, mais dans la mémoire du bot. Nous stockons le nom principal de l’utilisateur, jeton AAD, jeton BlackBerry AtHoc, préférence/configuration blackBerry AtHoc Server dans la mémoire du bot. Vous avez besoin des informations nécessaires pour envoyer une demande d’API à l’API Microsoft Graph et à notre serveur BlackBerry AtHoc. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| email | délégué | Nous accédons aux informations de base de l’utilisateur&#8217;telles que le nom principal et le lien vers le canal général des équipes (pour lequel l’utilisateur est autorisé) à envoyer une carte d’alerte aux équipes. | Nous ne&#8217;pas stocker les données utilisateur dans la base de données, mais dans la mémoire du bot. Nous stockons le nom principal de l’utilisateur, jeton AAD, jeton BlackBerry AtHoc, préférence/configuration blackBerry AtHoc Server dans la mémoire du bot. Vous avez besoin des informations nécessaires pour envoyer une demande d’API à l’API Microsoft Graph et à notre serveur BlackBerry AtHoc. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| openid | délégué | Nous accédons aux informations de base de l’utilisateur&#8217;telles que le nom principal et le lien vers le canal général des équipes (pour lequel l’utilisateur est autorisé) à envoyer une carte d’alerte aux équipes. | Nous ne&#8217;pas stocker les données utilisateur dans la base de données, mais dans la mémoire du bot. Nous stockons le nom principal de l’utilisateur, jeton AAD, jeton BlackBerry AtHoc, préférence/configuration blackBerry AtHoc Server dans la mémoire du bot. Vous avez besoin des informations nécessaires pour envoyer une demande d’API à l’API Microsoft Graph et à notre serveur BlackBerry AtHoc. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| profil | délégué | Nous accédons aux informations de base de l’utilisateur&#8217;telles que le nom principal et le lien vers le canal général des équipes (pour lequel l’utilisateur est autorisé) à envoyer une carte d’alerte aux équipes. | Nous ne&#8217;pas stocker les données utilisateur dans la base de données, mais dans la mémoire du bot. Nous stockons le nom principal de l’utilisateur, jeton AAD, jeton BlackBerry AtHoc, préférence/configuration blackBerry AtHoc Server dans la mémoire du bot. Vous avez besoin des informations nécessaires pour envoyer une demande d’API à l’API Microsoft Graph et à notre serveur BlackBerry AtHoc. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |


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

>N/A

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par BlackBerry sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
