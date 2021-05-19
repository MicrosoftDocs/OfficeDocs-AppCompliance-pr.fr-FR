---
title: Informations de demande pour LawToolBox par LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour LawToolBox, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
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
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par LawToolBox.com Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | LawToolBox |
| ID | WA104381656 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | LawToolBox.com Inc. |
| URL du site web partenaire | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL de la page Teams’informations d’application | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| URL de la politique de confidentialité | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par LawToolBox.com Inc. sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Délégué |  | [Facultatif] Lisez le calendrier de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite | Délégué |  | Pour créer le calendrier, invitez-le au calendrier de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite.Shared | Délégué |  | Pour créer le calendrier, invitez-vous à un calendrier partagé. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite | Délégué |  | [Facultatif]- lire les contacts utilisateur et connecter les utilisateurs d’une liste de contacts à l’autre. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite.Shared | Délégué |  | [Facultatif]- lire les contacts partagés par les utilisateurs pour servir la liste des contacts pertinents à l’affaire. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.AccessAsUser.All | Délégué |  | [Facultatif] Lisez les informations des groupes et des utilisateurs en tant qu’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.ReadWrite.All | Délégué |  | [Facultatif] Lisez les informations des groupes et des utilisateurs en tant qu’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read | Délégué |  | [Facultatif] Lisez les données de l’OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read.All | Délégué |  | [Facultatif]-Lire les données de l’OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite | Délégué |  | [Facultatif]-Lire et modifier les fichiers dans le contenu d’un OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite.All | Délégué |  | [Facultatif] Lisez/écrivez le fichier de OneDrive’utilisateur associé à la Question. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Group.ReadWrite.All | Délégué | GroupID, Nom de groupe, GroupEmail | Nous créons un Groupe pour chaque matière créée dans notre système. Cela permet aux utilisateurs de stocker des informations liées à la matière dans le Groupe, ce qui permet d’économiser leurs données dans leur propre locataire. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Read | Délégué |  | [Facultatif] [InProgress] Lisez l’e-mail de l’utilisateur pour Matters. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite | Délégué |  | [Facultatif] [InProgress] Lire/Écrire des e-mails pour les utilisateurs. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite.Shared | Délégué |  | [Facultatif] [InProgress] Lire/Écrire des e-mails pour les utilisateurs. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Send | Délégué |  | [Facultatif] [InProgress] Envoyez des dates limites par e-mail en tant qu’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Tasks.ReadWrite.Shared | Délégué |  | [Facultatif]-[InProgress] Lire les dates limites d’écriture comme tâche pour les utilisateurs. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.Read | Délégué |  | Lisez les informations de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite | Délégué |  | Lire/écrire les informations de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite.All | Délégué |  | Lire/écrire les informations de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| email | Délégué | Email, Office365 UserID, ObjectID, TenantID. | Lisez l’adresse e-mail de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| profil | Délégué |  | Lisez les informations de profil de l’utilisateur. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Identifier l’utilisateur nouvellement ajouté dans l’équipe et vérifier s’il y a une piste potentielle | E-mail, UserId |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>E-mail utilisateur, UserID, AccessToken, Groupes d’informations dans notre journal de débogage

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Nous conservons les dossiers à moins que nous ne recevions une demande de suppression des données.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

