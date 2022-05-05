---
title: Information for Wrike for Office Documents by Wrike Inc.
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour Wrike pour les documents Office, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4a4839637f40d86c24537bbac722110a1260ff7f
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226038"
---
# <a name="information-about-wrike-for-office-documents"></a>Informations sur Wrike pour les documents Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur : 23 mars 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Wrike Inc. à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Wrike pour les documents Office |
| ID | WA104379841 |
| Office 365 clients pris en charge | Excel 2016 ou version ultérieure sur Windows, Word 2013 ou version ultérieure le Windows, PowerPoint 2013 ou version ultérieure sur Windows, Excel 2016 ou version ultérieure sur Mac, Excel sur le Web, Word 2016 ou version ultérieure sur Mac, Word sur le web, PowerPoint 2016 ou ultérieur sur Mac, PowerPoint sur le web |
| Nom de la société partenaire | Wrike Inc. |
| URL du site web du partenaire | [https://www.wrike.com/](https://www.wrike.com/) |
| URL de la politique de confidentialité | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| URL des conditions d’utilisation | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Wrike Inc. a fourni ces informations sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>Cette application n’utilise pas Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et compléments basés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelles (OII). Répertoriez toutes les API Microsoft autres que Microsoft Graph utilisées par cette application.

>| **API** |  **OII est-il collecté ?** |  **Quelle OII est collectée ?** | **Justification de la collecte d’OII ?** | **OII est-il stocké ?** | **Justification du stockage d’OII ?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Interface API JavaScript pour Office | Oui | Le complément utilise l’API Office.js pour s’intégrer à l’application Office. |  | Aucune donnée organisationnelle n’est stockée dans les bases de données wrike. |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quel OII est transféré ?** | **Justification du transfert d’OII ?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike a les intégrations avec les fournisseurs suivants qui ont accès à certaines données : Marketo est un service de capture de prospects de messagerie - seuls les noms et les e-mails leur sont fournis. La sensibilisation est un engagement commercial basé sur le cloud : seuls des noms et des e-mails leur sont fournis. Système Salesforce CRM : contient les informations de contact et de facturation (aucune donnée sensible) des clients. Zuora - facturation et facturation des clients. Une DPA est en place pour tous les fournisseurs. |  | Nous utilisons l’API Office JS, mais nous ne collectons/ne traitons/stockons aucune information organisationnelle. |



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Non

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>Wrike a une architecture mutualisée qui sépare logiquement les clients&#8217; données par le biais du contrôle d’accès en fonction des métadonnées client. Ces métadonnées sont associées au locataire spécifique et à ses droits d’accès en fonction des règles d’accès en fonction du rôle dans le compte Wrike spécifique. Les données sont isolées logiquement et séparées, et l’accès aux données est uniquement disponible via l’application pour garantir la sécurité et la confidentialité. La sécurité au niveau de l’application empêche les locataires d’accéder ou de modifier les données d’application appartenant à un autre locataire. L’application wrike dispose de mécanismes d’authentification, de contrôle d’accès en fonction du rôle, d’autorisation et de partage et de contrôle de données étendus (voir https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles et https://help.wrike.com/hc/en-us/articles/209602969) qui autorisent l’accès aux données pour les utilisateurs autorisés uniquement. En outre, le chiffrement au repos est appliqué aux fichiers utilisateur chargés sur les serveurs Wrike dans le stockage de fichiers via l’application web et l’API ; les fichiers sont automatiquement chiffrés à l’aide du chiffrement AES 256 bits. En outre, tous les serveurs sont chiffrés au repos à l’aide du chiffrement du système de fichiers, et de plus Wrike offre le complément Wrike Lock pour la clé de chiffrement gérée par un client, voir https://www.wrike.com/add-on-wrike-lock/ et https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock. En tant que couche supplémentaire de sécurité des données, Wrike offre des fonctionnalités d’audit et de création de rapports qui permettent aux administrateurs d’effectuer des examens de sécurité complets tout en étant en mesure d’améliorer la visibilité de ce qui se passe dans leur compte Wrike. Vous trouverez plus de détails sur https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports. Enfin, Wrike fournit des fonctionnalités permettant le suivi granulaire des rôles d’accès pour aider les clients à auditer entièrement le partage de données existant pour voir les détails sur https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports.
L’accès aux données client peut être pris en compte dans deux cas :
- Accès par l’équipe du support wrike : en cas de résolution ou de vérification du problème, le support technique doit accéder à votre compte ; que l’accès ne peut être accordé que par vous. Cela est activé par un jeton de sécurité généré par le système que vous fournissez hors bande à notre équipe de support technique, ce qui permet au support technique d’approfondir la résolution de votre problème pendant un laps de temps limité. Cette approche systémique garantit une confidentialité supplémentaire pour vos données stockées dans Wrike.
- Accès par l’équipe opérationnelle Wrike : l’équipe opérationnelle wrike est responsable de la maintenance et de la prise en charge de l’environnement de production, notamment la surveillance, la mise à jour corrective et la remise des nouvelles builds en production, etc. Dans ce cas, l’accès est strictement interdit à la fois des aspects procéduraux et techniques, et des contrôles d’autorisation forts, notamment vpN, 2FA et certificat personnel, mais pas limités, sont en place. De plus, il est surveillé en détail à l’aide de HIDS (Système de détection d’intrusion basé sur l’hôte) et examiné par l’équipe de sécurité opérationnelle Wrike. Dans le cas d’Amazon KMS (fonctionnalité Wrike Lock), les données client sont stockées chiffrées dans la base de données Wrike. Les données ne sont donc pas directement ou indirectement disponibles par l’équipe opérationnelle Wrike, car elles peuvent être déchiffrées à l’aide de l’accès à Amazon KMS du client, qui est géré et contrôlé uniquement par le client.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans l’examen ou l’analyse des données d’information d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

