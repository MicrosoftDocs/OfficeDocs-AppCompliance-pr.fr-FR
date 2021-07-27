---
title: Informations sur l’application du connecteur FormMachines pour SharePoint entreprise DIGITAL MACHINES PTY LTD
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour formMachines Connector pour SharePoint, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 56c08c242cb3822ebaea854026fb3f758768b7bf
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53522224"
---
# <a name="formmachines-connector-for-sharepoint"></a>Connecteur FormMachines pour SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000357" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ENTERPRISE DIGITAL MACHINES PTY LTD à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Connecteur FormMachines pour SharePoint |
| ID | WA200000357 |
| Office 365 clients pris en charge | SharePoint 2016 ou ultérieure |
| Nom de la société partenaire | ENTERPRISE DIGITAL MACHINES PTY LTD |
| URL du site web partenaire | [https://www.formmachines.com](https://www.formmachines.com) |
| URL de la politique de confidentialité | [https://www.formmachines.com?dirKey=fm-privacy](https://www.formmachines.com?dirKey=fm-privacy) |
| URL des conditions d’utilisation | [https://www.formmachines.com?dirKey=fm-terms-of-use](https://www.formmachines.com?dirKey=fm-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par ENTERPRISE DIGITAL MACHINES PTY LTD sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | (connexion, courrier électronique, Azure Guid, displayName, first_login_date_time) | permet à l’utilisateur de se connecter et donne à l’application l’accès à son UPN pour activer la connexion silencieuse, nous permet d’identifier chaque utilisateur de manière unique | [8c87660f-d36f-41f6-b0ae-025253f380aa](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c87660f-d36f-41f6-b0ae-025253f380aa) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>. Nous ne logons que les erreurs. Dans notre journal des erreurs, nous n’allons enregistrer que les informations relatives aux erreurs. Le client ou le client qui a déclenché une erreur particulière n’est pas collecté. Seuls les ingénieurs du support technique ont accès aux journaux d’erreurs. Les journaux d’erreur sont consultables en ligne, et non téléchargés et consultables. Les journaux d’erreurs sont supprimés automatiquement après 30 jours

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>. Les données sont stockées dans des centres de données Azure aux États-Unis. Les données fournies par le client, telles que les modèles et les soumissions, sont chiffrées dans la base de données. Les pièces jointes sont stockées dans des conteneurs PRIVÉs Azure BLOB, les utilisateurs doivent s’authentifier avant d’y accéder. Nous avons au maximum deux administrateurs qui peuvent accéder à nos ressources de production, pour le dépannage et le déploiement. Ces deux comptes d’administrateur sont partitionn s différemment pour tous les autres comptes. Le nombre d’accès administrateur ne dépassera jamais deux

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

