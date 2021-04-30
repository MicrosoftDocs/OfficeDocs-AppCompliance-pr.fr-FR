---
title: Informations d'application pour Wrike Office Documents par Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour Wrike pour les documents Office, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6ecbf74b4ef8e3f4203e01d0039b0573070e071e
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093391"
---
# <a name="wrike-for-office-documents"></a>Wrike for Office Documents

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: March 23, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Wrike Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Wrike for Office Documents |
| ID | WA104379841 |
| Office 365 clients pris en charge | Excel 2016 ou ultérieur sur Windows, Word 2013 ou une ultérieure sur Windows, PowerPoint 2013 ou ultérieur sur Windows, Excel 2016 ou ultérieur sur Mac, Excel sur le Web, Word 2016 ou ultérieur sur Mac, Word sur le web, PowerPoint 2016 ou ultérieur sur Mac, PowerPoint sur le web |
| Nom de la société partenaire | Wrike Inc. |
| URL du site web partenaire | [https://wrike.com/](https://wrike.com/) |
| URL de la politique de confidentialité | [https://www.wrike.com/privacy](https://www.wrike.com/privacy) |
| URL des conditions d'utilisation | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par Wrike Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n'utilise pas Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l'aide d'autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d'identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu'est-ce qu'OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Interface API JavaScript pour Office | Oui | Le add-in utilise l'API Office.js pour s'intégrer à l Office'application. |  | Aucune donnée organisationnelle n'est stockée dans les bases de données wrike. |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d'OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike a les intégrations avec les fournisseurs suivants qui ont accès à certaines données : Marketo est un chef de messagerie qui capture des services ; seuls les noms et les e-mails leur sont fournis. La sensibilisation est l'engagement commercial basé sur le cloud : seuls les noms et les e-mails leur sont fournis. Système Salesforce CRM : dispose d'informations de contact et d'informations de facturation (aucune donnée sensible) des clients. Zuora : facturation et facturation des clients. Une DPA est en place pour tous les fournisseurs. |  | Nous utilisons JS Office API, mais nous ne collectons/ne stockons pas d'informations organisationnelles. |



#### <a name="add-in-data-access"></a>Accès aux données du add-in

List the permissions this app requires for accessing your organization's data, the justification and purpose for this permission (what does the app use this information for?) and whether the app stores any of this information in its databases.

>| **Autorisation**  | **Description** |
>|:----------------|:----------------|
>| ReadWrite Document | Peut lire et apporter des modifications à votre document |
>| Envoyer des données | Peut envoyer des données sur Internet |

#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Non

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Wrike possède une architecture multi-clients qui sépare logiquement les clients&#8217; données via un contrôle d'accès basé sur les métadonnées des clients. Ces métadonnées sont associées au client spécifique et à ses droits d'accès conformément aux règles d'accès basées sur les rôles dans le compte Wrike spécifique. Les données sont logiquement isolées et séparées, et l'accès aux données est disponible uniquement par le biais de l'application pour garantir la sécurité et la confidentialité. La sécurité au niveau de l'application empêche les clients d'accéder aux données d'application d'un autre client ou de les modifier. L'application wrike dispose de mécanismes d'authentification étendu, de contrôle d'accès basé sur les rôles, d'autorisation, de partage et de contrôle des données (voir et autoriser l'accès aux données pour les utilisateurs autorisés https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles https://help.wrike.com/hc/en-us/articles/209602969) uniquement). En outre, le chiffrement au repos est appliqué pour les fichiers utilisateur chargés sur les serveurs Wrike dans le stockage de fichiers via l'application web et l'API ; Les fichiers sont automatiquement chiffrés à l'aide du chiffrement AES 256 bits. En outre, tous les serveurs sont chiffrés au repos à l'aide du chiffrement du système de fichiers, et en outre Wrike offre un add-in Wrike Lock pour la clé de chiffrement gérée par un client, voir https://www.wrike.com/add-on-wrike-lock/ et https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . En tant que couche supplémentaire de sécurité des données, Wrike offre des fonctionnalités d'audit et de rapport qui permettent aux administrateurs d'effectuer des révisions de sécurité complètes tout en étant en mesure d'accroître la visibilité sur ce qui se passe dans leur compte Wrike, plus de détails sont disponibles sur https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Enfin, Wrike fournit des fonctionnalités permettant le suivi granulaire des rôles d'accès pour aider les clients à auditer entièrement le partage de données existant. https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports
L'accès aux données client peut être pris en compte dans deux cas :
- Accès par l'équipe de support technique Wrike : en cas de dépannage ou de vérification du problème, le support technique doit accéder à votre compte. cet accès ne peut être accordé que par vous. Cela est activé par un jeton de sécurité généré par le système que vous fournissez hors bande à notre équipe de support technique, ce qui permet au support technique de se pencher plus en profondeur sur la résolution de votre problème pendant un laps de temps limité. Cette approche d'attaque garantit une confidentialité supplémentaire pour vos données stockées dans Wrike.
- Accès par l'équipe opérationnelle Wrike : l'équipe opérationnelle wrike est responsable de la maintenance et de la prise en charge de l'environnement de production, y compris la surveillance, la correction et la mise à jour, la livraison des nouvelles builds en production, etc. Dans ce cas, l'accès est strictement interdit aux aspects procéduraux et techniques, et des contrôles d'autorisation renforcés, y compris, mais sans s'y limiter, vpn, 2FA et certificat personnel sont en place. En outre, il est surveillé en détail à l'aide du service HIDS (Host-based Intrusion Detection System) et examiné par l'équipe Wrike Operational Security. Dans le cas d'Amazon KMS (fonctionnalité de verrouillage wrike), les données client sont stockées chiffrées dans la base de données Wrike, de sorte que les données ne sont pas directement ou indirectement disponibles par l'équipe opérationnelle Wrike, car les données peuvent être déchiffrées à l'aide de l'accès au KMS Amazon du client, qui est géré et contrôlé par le client uniquement.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

