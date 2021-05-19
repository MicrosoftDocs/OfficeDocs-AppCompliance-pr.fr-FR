---
title: Informations d’application pour l’outil de reporting iPlanner Office 365 Planner par iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations disponibles sur la sécurité et la conformité pour l’outil de reporting iPlanner pour Office 365 Planner, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a577fcc75982703bfae0de740a7e69d9d13e509a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548764"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>outil de reporting iPlanner pour Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par iGlobe à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | outil de reporting iPlanner pour Office 365 Planner |
| ID | WA104380686 |
| Office 365 clients soutenus | Excel 2016 ou plus tard Windows, Excel sur le Web, Excel 2016 ou plus tard sur Mac |
| Nom de l’entreprise partenaire | iGlobe |
| URL du site web partenaire | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL de la politique de confidentialité | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL des conditions d’utilisation | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par iGlobe sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour créer une entrée de calendrier dans le calendrier de l’utilisateur&#8217;calendrier de la tâche à la date d’échéance de la tâche. |  |
>| Directory.AccessAsUser.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour vérifier que l’utilisateur a le consentement et avoir accès à l’API. |  |
>| Directory.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour obtenir la tâche de planificateur Outlook To Do, e-mails signalés et les mettre à jour. Pour créer une nouvelle tâche de planificateur. |  |
>| Files.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour accéder au fichier en tant que fichiers de pièce jointe et de téléchargement à une tâche. |  |
>| Group.Read.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour obtenir la liste des plan et mettre à jour la tâche. |  |
>| Group.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour obtenir la tâche de planificateur et ajouter de nouvelles tâches mettre à jour le seau et la ligne de natation. |  |
>| Mail.Read | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | User.Read, pour obtenir la tâche de planificateur Outlook To Do, e-mails signalés et les mettre à jour. Pour créer une nouvelle tâche de planificateur |  |
>| Mail.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour montrer les mails et envoyer du courrier. |  |
>| Mail.ReadWrite.All | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Obtenez le sujet du courrier à partir du courrier sélectionné. Permet à l’application d’obtenir des informations à partir de l’e-mail sélectionné permettant de copier le champ de description dans la description de la tâche et permettant d’enregistrer les pièces jointes du courrier ou le courrier lui-même à la tâche. Envoyer une notification. |  |
>| Tasks.ReadWrite | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Pour obtenir la signature dans les utilisateurs Outlook To Do et mettre à jour User.Read, pour obtenir la tâche de planificateur Outlook To Do, les e-mails signalés et de les mettre à jour. Pour créer une nouvelle tâche de planificateur. |  |
>| User.Read | Délégué | Aucune donnée n’est stockée dans les bases de données d’applications. | Activer la connexion et lire le profil utilisateur |  |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>iGlobe recueille des données pour fonctionner efficacement et vous fournir les meilleures expériences avec nos produits et services. Pour l’octroi de licences : Données collectées pour administrer le compte de licence de votre organisation&#8217;, par exemple lorsque vous déployez un add-in gratuit, créez un abonnement d’essai ou achetez un abonnement. Les informations suivantes sont recueillies. 
- À des fins financières : Nom et adresse de l’entreprise
- Utilisateurs abonnés : nom d’utilisateur et e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Toutes les données sont sur le propre locataire du client. Aucune donnée d’application n’est stockée. Un module d’ajout moderne s’exécute dans un navigateur bac à sable, &#8220;hors processus&#8221;. Il interagit avec les données des utilisateurs en utilisant services Microsoft. L’add-in ne peut accéder qu’aux données avec lesquelles l’utilisateur travaille.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

