---
title: Informations d’application pour les calendriers de contacts approuvés par le contact approuvé
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour les calendriers de contacts approuvés, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b9af5ceadaa2c4b6f5ca79f511f4533f9c63d7e5
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252985"
---
# <a name="approved-contact-calendars"></a>Calendriers de contacts approuvés

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380294" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par le contact approuvé à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Calendriers de contacts approuvés |
| ID | WA104380294 |
| Office 365 clients pris en charge | Outlook 2013 ou une Windows, Outlook 2016 ou ultérieure sur Mac, Outlook sur le web |
| Nom de la société partenaire | Contact approuvé |
| URL du site web partenaire | [https://approvedcontact.com/](https://approvedcontact.com/) |
| URL de la politique de confidentialité | [https://approvedcontact.com/Privacy%20Policy.pdf](https://approvedcontact.com/Privacy%20Policy.pdf) |
| URL des conditions d’utilisation | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par le contact approuvé sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | délégué | Pour le bot de calendrier, nous stockons les heures de libre/occupé des utilisateurs pour la recherche de périodes gratuites pour plusieurs personnes.  | Nous lisons et comparons les heures de libre/occupé et les réunions de planification. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| Contacts.Read | délégué | Oui, nous stockons les informations de contact. | Importation et synchronisation des contacts. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | délégué | Oui | Informations de profil de base. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | délégué | Non | Utilisé pour afficher les profils des collègues, comparer les temps libres et planifier des salles de conférence. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | délégué | Oui, les heures de libre/occupé pour les utilisateurs hors connexion. | Appelez Graph lorsque l’utilisateur n’utilise pas activement notre site. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| openid | délégué | Non | Office 365 SSO. | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="add-in-data-access"></a>Accès aux données du add-in

List the permissions this app requires for accessing your organization’s data, the justification and purpose for this permission (what does the app use this information for?) and whether the app stores any of this information in its databases.

>| **Autorisation**  | **Description** |
>|:----------------|:----------------|
>| ReadWrite, élément | Ce module complémentaire peut accéder et modifier des informations personnelles dans le message actif, telles que le corps, l’objet, l’expéditeur, les destinataires et les informations de pièce jointe. Il peut envoyer ces données à un service tiers. D’autres éléments de votre boîte&#8217;ne peuvent pas être lus ou modifiés. |
>| Envoyer des données | Peut envoyer des données sur Internet |

#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui, nous logons les adresses de messagerie pour connecter les achats de licences à Commercial Appsource. Nous vous offrons la possibilité de supprimer ces informations de nos journaux.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Seuls les développeurs ont accès à nos journaux. Nous appliquez la 2FA pour l’accès à toutes les plateformes de développement.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

