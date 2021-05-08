---
title: Informations sur l’application pour le suivi des factures et du temps - Facture Zoho par Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour la facture et le suivi du temps - Zoho Invoice, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 97c065f0cdb0efbc005353cd6f6e459a67303651
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52253235"
---
# <a name="invoice-and-time-tracking---zoho-invoice"></a>Facture et suivi du temps : facture Zoho

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381067" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Zoho Corporation Private Limited à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Facture et suivi du temps : facture Zoho |
| ID | WA104381067 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | Zoho Corporation Private Limited |
| URL du site web partenaire | [https://www.zoho.com/](https://www.zoho.com/) |
| URL de la politique de confidentialité | [https://zoho.com/privacy.html](https://zoho.com/privacy.html) |
| URL des conditions d’utilisation | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Zoho Corporation Private Limited sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Contacts.Read | délégué |  |  Autoriser les utilisateurs à synchroniser les contacts Office365 avec Zoho Invoice. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Mail.Read | délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Mail.Send | délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Export.All | délégué |  | Autoriser l’utilisateur à exporter toutes les informations associées à l’utilisateur. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | délégué |  | Autoriser les utilisateurs à se connecter et à lire le profil utilisateur. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | délégué |  | Autoriser les utilisateurs à importer des utilisateurs Office365 vers Zoho. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profil | délégué |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="add-in-data-access"></a>Accès aux données du add-in

List the permissions this app requires for accessing your organization’s data, the justification and purpose for this permission (what does the app use this information for?) and whether the app stores any of this information in its databases.

>| **Autorisation**  | **Description** |
>|:----------------|:----------------|
>| Lire l’élément | Ce module complémentaire peut accéder à des informations personnelles sur le message actif, telles que les noms des expéditeurs, les noms des destinataires, les adresses e-mail, le corps du message et les informations de pièce jointe. Le add-in peut envoyer ces données à un service tiers. D’autres éléments de votre boîte&#8217;ne peuvent pas être lus ou modifiés. |
>| Envoyer des données | Peut envoyer des données sur Internet |

#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous ne collectons pas d’EUII/PII dans la télémétrie et les journaux.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données sont récupérées uniquement après le consentement de l’utilisateur. L’accès logique aux serveurs est fourni via un réseau dédié isolé et est &amp; hautement sécurisé et surveillé. Ce réseau est protégé par pare-feu, 2- Factor Authentication et Kerberos Authent


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28305' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28305" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

