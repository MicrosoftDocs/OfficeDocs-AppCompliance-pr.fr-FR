---
title: Informations sur les demandes pour Wrike par Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations disponibles sur la sécurité et la conformité pour Wrike, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4ef844f9bf25ffa41a6054aa6ffcbebdb94be223
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550764"
---
# <a name="wrike"></a>Wrike

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur le: Mars 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/05274a45-7312-4c23-8f64-d57fe4a28d6d" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381390" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Wrike Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Wrike |
| ID | WA104381390 WA104381390 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Wrike Inc. |
| URL du site web partenaire | [https://www.wrike.com](https://www.wrike.com) |
| URL de la page Teams’informations d’application | [https://help.wrike.com/hc/en-us/articles/115001825869-Micro...](https://help.wrike.com/hc/en-us/articles/115001825869-Microsoft-Teams) |
| URL de la politique de confidentialité | [https://www.wrike.com/security/privacy/](https://www.wrike.com/security/privacy/) |
| URL des conditions d’utilisation | [https://www.wrike.com/security/terms/](https://www.wrike.com/security/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Wrike Inc. sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>Cette application n’utilise pas microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les modules complémentaires intégrés à Microsoft 365 peuvent utiliser d’autres API Microsoft que Microsoft Graph pour recueillir ou traiter des informations organisationnelles identifiables (OII). Énumérez toutes les API Microsoft autres que Microsoft Graph utilisations de cette application.

>| **API** |  **L’ŒIL est-il recueilli?** |  **Quel OII est recueilli?** | **Justification de la collecte de l’ŒII?** | **OII est-il stocké ?** | **Justification pour stocker OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Interface API JavaScript pour Office | Oui | L’add-in utilise l'Office.js api pour s’intégrer à l’application Office’application. |  | Aucune donnée organisationnelle n’est stockée dans les bases de données de Wrike. |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike a les intégrations avec les fournisseurs suivants qui ont accès à certaines données: Marketo est e-mail plomb capturer des services - seuls les noms et les e-mails leur sont fournis. La sensibilisation est basée sur le Cloud engagement des ventes - seuls les noms et les e-mails leur sont fournis. Système CRM Salesforce - a des coordonnées et des informations de facturation (pas de données sensibles) des clients. Zuora - clients de facturation et de facturation. Il y a un DPA en place pour tous les fournisseurs. |  | Nous utilisons JS Office API, mais nous ne recueillons/ne stockons aucune information organisationnelle. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Non

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Wrike dispose d’une architecture multi-locataires qui sépare logiquement les clients&#8217; grâce au contrôle d’accès basé sur les métadonnées clients. Ces métadonnées sont associées au locataire spécifique et à ses droits d’accès conformément aux règles d’accès basées sur le rôle dans le compte Wrike spécifique. Les données sont logiquement isolées et séparées, et l’accès aux données n’est disponible que par l’application pour assurer la sécurité et la confidentialité. La sécurité au niveau de l’application empêche les locataires d’accéder ou de modifier les données d’application appartenant à un autre locataire. L’application de Wrike dispose d’authentification étendue, d’un contrôle d’accès basé sur les fonctions, d’une autorisation et de mécanismes de partage et de contrôle des données (voir https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles et qui https://help.wrike.com/hc/en-us/articles/209602969) permettent l’accès aux données uniquement pour les utilisateurs autorisés). En outre, le chiffrement au repos est appliqué pour les fichiers utilisateur téléchargés sur les serveurs Wrike dans le stockage de fichiers via l’application Web et l’API; les fichiers sont automatiquement cryptés à l’aide du chiffrement AES 256 bits. En outre, tous les serveurs sont cryptés au repos en utilisant le chiffrement du système de fichiers, et en outre Wrike offre Wrike Lock add-in pour clé de cryptage géré par un client, https://www.wrike.com/add-on-wrike-lock/ voir et https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . En tant que couche supplémentaire de sécurité des données, Wrike offre des fonctionnalités d’audit et de reporting qui permettent aux administrateurs d’effectuer des examens de sécurité complets tout en étant en mesure d’accroître la visibilité sur ce qui se passe dans leur compte Wrike, plus de détails peuvent être trouvés à https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Enfin, Wrike fournit des fonctionnalités permettant le suivi granulaire des rôles d’accès pour aider les clients à auditer pleinement le partage de données existant voir les détails à https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports .
L’accès aux données des clients peut être envisagé dans deux cas :
- Accès par l’équipe de support Wrike : en cas de dépannage ou de vérification du problème, il faut un support pour accéder à votre compte; cet accès ne peut être accordé que par vous seul. Cela est activé par un jeton de sécurité généré par un système que vous fournissez hors bande à notre équipe de support, ce qui permet au Support de approfondir la résolution de votre problème pendant un temps limité. Cette approche systémique garantit une confidentialité supplémentaire pour vos données stockées dans Wrike.
- Accès par l’équipe opérationnelle de Wrike : L’équipe opérationnelle de Wrike est responsable de la maintenance et du soutien de l’environnement de production, y compris la surveillance, le patchage et la mise à jour, la livraison des nouvelles constructions à la production, etc. L’accès en l’espèce est strictement interdit tant sur le plan procédural que technique, et de solides contrôles d’autorisation, y compris mais non limités, vpn, 2FA et certificat personnel sont en place, en outre, il est surveillé en détail à l’aide de HIDS (Host-based Intrusion Detection System) et examiné par wrike équipe de sécurité opérationnelle. Dans le cas d’Amazon KMS (fonctionnalité Wrike Lock), les données client sont stockées cryptées dans la base de données Wrike, de sorte que les données ne sont pas directement ou indirectement disponibles par l’équipe wrike operational, car les données peuvent être décryptées en utilisant l’accès au KMS Amazon du client, qui est géré et contrôlé par le client seulement.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

