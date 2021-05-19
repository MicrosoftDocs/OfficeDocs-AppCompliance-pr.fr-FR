---
title: Informations d’application pour FormMachines pour SharePoint par ENTERPRISE DIGITAL MACHINES PTY LTD
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour FormMachines for SharePoint, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4c423cac4f879ba4f73a9bba5f9004acb4cfa21a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553545"
---
# <a name="formmachines-for-sharepoint"></a>FormMachines pour SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Novembre 3, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000357" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ENTERPRISE DIGITAL MACHINES PTY LTD à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | FormMachines pour SharePoint |
| ID | WA200000357 |
| Office 365 clients soutenus | SharePoint 2016 ou plus tard |
| Nom de l’entreprise partenaire | MACHINES NUMÉRIQUES D’ENTREPRISE PTY LTD |
| URL du site web partenaire | [https://www.formmachines.com/](https://www.formmachines.com/) |
| URL de la politique de confidentialité | [https://www.formmachines.com/?dirKey=fm-privacy](https://www.formmachines.com/?dirKey=fm-privacy) |
| URL des conditions d’utilisation | [https://www.formmachines.com/?dirKey=fm-terms-of-use](https://www.formmachines.com/?dirKey=fm-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par ENTERPRISE DIGITAL MACHINES PTY LTD sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Délégué | (connexion, e-mail, Azure Guid, displayName, first_login_date_time) | permet à l’utilisateur de se connecter et donne à l’application l’accès à son UPN pour activer la connexion silencieuse, nous permet d’identifier chaque utilisateur unique | 8c87660f-d36f-41f6-b0ae-025253f380aa |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>. Nous n’en connectons que les erreurs . Dans notre journal des erreurs, nous ne déconnectons que les informations liées aux erreurs. Quel client ou client a déclenché une erreur particulière n’est pas collecté . Seuls les ingénieurs de support ont accès aux journaux d’erreurs . Les journaux d’erreurs sont consultés en ligne, non téléchargés et consultés. Les journaux d’erreurs sont supprimés automatiquement après 30 jours

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>. Les données sont stockées dans des centres de données basés à Azure aux États-Unis. Les données fournies par le client telles que les modèles et les soumissions sont chiffrées dans la DB . Les pièces jointes de fichiers sont stockées dans des conteneurs BLOB Azure privés, les utilisateurs doivent les authentifier avant d’y accéder. Nous avons au maximum deux administrateurs qui peuvent accéder à nos actifs de production, pour le dépannage et le déploiement. Ces deux comptes admin sont divisés différemment de tous les autres comptes. Le nombre d’accès admin ne dépassera jamais deux

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

