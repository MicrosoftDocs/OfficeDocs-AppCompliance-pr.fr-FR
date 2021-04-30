---
title: Informations d'application pour Asana pour Outlook par Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour Asana pour Outlook, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a166966dd5dfac55a13df3dded07bd056f3ab2ee
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094081"
---
# <a name="asana-for-outlook"></a>Asana pour Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 2, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381833" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Asana à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Asana pour Outlook |
| ID | WA104381833 |
| Office 365 clients pris en charge | Outlook 2016 ou ultérieure sur Windows, Outlook 2016 ou ultérieur sur Mac, Outlook sur le web |
| Nom de la société partenaire | Asana |
| URL du site web partenaire | [https://asana.com/](https://asana.com/) |
| URL de la politique de confidentialité | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL des conditions d'utilisation | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par Asana sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n'utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d'OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Le add-in transfère les informations de messagerie de base (expéditeur, recepient, objet, corps) et les pièces jointes à Asana lorsque l'utilisateur le demande. |  | Courrier électronique : lit les e-mails actuellement ouverts lorsqu'ils sont affichés dans un volet Des tâches. - Lit les pièces jointes de courrier actuellement ouvertes à télécharger dans les tâches Asana. - Cela permet aux utilisateurs d'effectuer rapidement des tâches dans Asana avec des informations provenant d'e-mails. |



#### <a name="add-in-data-access"></a>Accès aux données du add-in

List the permissions this app requires for accessing your organization's data, the justification and purpose for this permission (what does the app use this information for?) and whether the app stores any of this information in its databases.

>| **Autorisation**  | **Description** |
>|:----------------|:----------------|
>| ReadWrite, élément | Ce module complémentaire peut accéder et modifier des informations personnelles dans le message actif, telles que le corps, l'objet, l'expéditeur, les destinataires et les informations de pièce jointe. Il peut envoyer ces données à un service tiers. D'autres éléments de votre boîte&#8217;ne peuvent pas être lus ou modifiés. |
>| Envoyer des données | Peut envoyer des données sur Internet |

#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Notre application enregistre uniquement les informations relatives aux données Asana. La seule fois que nous journalisons des informations sur l'utilisateur Outlook, c'est lorsque l'utilisateur joint explicitement un e-mail ou télécharge une pièce jointe dans Asana, et même alors, nous ne logons pas le contenu. Les journaux à court terme existent sur des serveurs qui peuvent inclure des données utilisateur, mais ils sont éphémères et limités à des périodes inférieures à 72 heures.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Enterprise clients ont garanti le chiffrement au repos à l'aide d'AES-256. Les données sont stockées sur Amazon Web Services et AWS gère les clés de chiffrement à l'aide de leur système de gestion des clés. Nous avons 2FA pour tous les administrateurs. L'accès est accordé sur le principe du moindre privilège.
Vos administrateurs d'organisation Asana ont la possibilité de configurer des comptes SAML, SCIM, Service et d'avoir une vue d'ensemble des données qui sont placés dans l'outil. Les administrateurs peuvent demander une exportation complète de l'organisation à partir de la console Admin et auditer si nécessaire.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

