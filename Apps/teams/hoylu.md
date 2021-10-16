---
title: Informations d’application pour Hoylu par Hoylu
ms.author: elmalova
author: elenamalova
ms.date: 06/09/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Hoylu, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a091c480731e69a51ec002f24f6d62924a814b7b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412333"
---
# <a name="hoylu"></a>Hoylu

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 20, 2020</p>

* <a href="https://teams.microsoft.com/l/app/732e01bc-570a-43ac-9671-8c7fc4152662" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001573" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Hoylu à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Hoylu |
| ID | WA200001573 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Hoylu |
| URL du site web partenaire | [https://hoylu.com](https://hoylu.com) |
| URL de la politique de confidentialité | [https://www.hoylu.com/privacy-policy/](https://www.hoylu.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.hoylu.com/terms-of-use/](https://www.hoylu.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Hoylu sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui. La journalisation est effectuée pour la sécurité des applications, et les euii et OII sont collectés sous la forme du prénom et du nom, du courrier électronique, de l’adresse IP, de l’ID d’organisation. Le fournisseur de journalisation de Hoylu est Datadog. Datadog a certifié sa conformité avec l’infrastructure de bouclier de protection des données UE-États-Unis et est un registre STAR pour la Cloud Security Alliance (CSA). Datadog poursuit également des validations tierces indépendantes clés de sa sécurité, de ses processus et de ses services, y compris la réalisation de l’audit SOC 2 Type II. Un utilisateur peut demander la suppression de ces informations par le biais d’un processus conforme au R GDPR à tout moment.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données d’application sont stockées dans Microsoft Azure Cloud Services, et tous les protocoles de chiffrement utilisés sont conformes à la norme FIPS 140-2. ces données de production sont uniquement accessibles par les administrateurs d’infrastructure (PMA). L’administration des comptes pour l’organisation s’effectue Azure AD avec 2FA.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35933' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35933" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


