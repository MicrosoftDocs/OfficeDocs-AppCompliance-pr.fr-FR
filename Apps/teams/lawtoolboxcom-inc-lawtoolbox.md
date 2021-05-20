---
title: Informations d’application pour LawToolBox par LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour LawToolBox, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2e97d65822a5baeb0cd78101660084e4142e98ea
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553005"
---
# <a name="lawtoolbox"></a>LawToolBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par LawToolBox.com Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | LawToolBox |
| ID | WA104381656 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | LawToolBox.com Inc. |
| URL du site web partenaire | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL de la Teams d’informations sur l’application | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| URL de la politique de confidentialité | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par LawToolBox.com Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | délégué |  | [Facultatif] Lire le calendrier de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite | délégué |  | Pour créer une invitation de calendrier dans le calendrier de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite.Shared | délégué |  | Pour créer une invitation de calendrier dans un calendrier partagé. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite | délégué |  | [Facultatif]- pour lire les contacts des utilisateurs et connecter les utilisateurs d’une liste de contacts à une autre. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite.Shared | délégué |  | [Facultatif]- pour lire les contacts partagés des utilisateurs afin de servir la liste des contacts pertinents pour le cas. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.AccessAsUser.All | délégué |  | [Facultatif] Lire les informations de groupes et d’utilisateurs en tant qu’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.ReadWrite.All | délégué |  | [Facultatif] Lire les informations de groupes et d’utilisateurs en tant qu’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read | délégué |  | [Facultatif] Lire les informations de l’OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read.All | délégué |  | [Facultatif]-Lire les informations de l’OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite | délégué |  | [Facultatif]-Lire et modifier des fichiers dans le compte d’un OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite.All | délégué |  | [Facultatif] Lire/écrire le fichier d’OneDrive associé à la matière. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Group.ReadWrite.All | délégué | GroupID, GroupName, GroupEmail | Nous créons un groupe pour chaque sujet créé dans notre système. Cette aide permet aux utilisateurs de stocker les informations relatives à la matière dans le groupe, qui enregistre à son tour leurs données dans leur propre client. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Read | délégué |  | [Facultatif] [InProgress] Lire le courrier électronique de l’utilisateur pour les questions. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite | délégué |  | [Facultatif] [InProgress] Lire/écrire des e-mails pour les utilisateurs. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite.Shared | délégué |  | [Facultatif] [InProgress] Lire/écrire des e-mails pour les utilisateurs. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Send | délégué |  | [Facultatif] [InProgress] Envoyer des échéances sur le courrier électronique en tant qu’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Tasks.ReadWrite.Shared | délégué |  | [Facultatif]-[InProgress] Read Write Deadlines as Task for users. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.Read | délégué |  | Lire les informations de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite | délégué |  | Lire/écrire les informations de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite.All | délégué |  | Lire/écrire les informations de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| email | délégué | Email, Office365 UserID, ObjectID, TenantID. | Lire l’adresse e-mail de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| profil | délégué |  | Lire les informations de profil utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Pour identifier l’utilisateur nouvellement ajouté dans l’équipe et vérifier un responsable potentiel | Email, UserId |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>User Email,UserID, AccessToken, Groups information in our debug log

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Nous conservons les enregistrements de cas, sauf si nous recevons une demande de suppression des données.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

