---
title: Informations d’application pour Smartsheet par Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Smartsheet, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ddf77e7e73cc0bef1a21e72d1db328a4845a12f5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551524"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Smartsheet à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Smartsheet |
| ID | WA104380975 WA104380975 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Smartsheet |
| URL du site web partenaire | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| URL de la page Teams’informations d’application | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL de la politique de confidentialité | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| URL des conditions d’utilisation | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Smartsheet sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Délégué | Aucun. | Permet à notre application d’installer des applications pour le compte de l’utilisateur. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | Délégué | locataireId pour récupérer des informations à afficher dans l’interface utilisateur. | Nous permet de lire les applications que ce locataire utilise afin que nous puissions vérifier si nous avons besoin d’installer l’application pour eux. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | Délégué | teamId/groupId pour la livraison de messages. | Permet à notre application de lire des informations de base sur un groupe (ou Teams’équipe) ainsi que des conversations. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | Délégué | teamId/groupId pour la livraison de messages. | Permet à notre application de démarrer de nouvelles conversations en équipe. Cette autorisation inclut également la portée Read.All ci-dessus, mais nous avons besoin de celui-ci ainsi pour des raisons techniques. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | Délégué | userId. | Nous permet de lire des informations de base sur un utilisateur pendant le processus auth. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | Délégué | refreshToken. | Permet à notre application de recevoir des jetons de rafraîchissement et de rafraîchir le jeton auth au nom de l’utilisateur lorsqu’il utilise l’application. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les modules complémentaires intégrés à Microsoft 365 peuvent utiliser d’autres API Microsoft que Microsoft Graph pour recueillir ou traiter des informations organisationnelles identifiables (OII). Énumérez toutes les API Microsoft autres que Microsoft Graph utilisations de cette application.

>| **API** |  **L’ŒIL est-il recueilli?** |  **Quel OII est recueilli?** | **Justification de la collecte de l’ŒII?** | **OII est-il stocké ?** | **Justification pour stocker OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API Bot Framework | Oui | Nous utilisons l’API Bot Framework pour délivrer des messages comme application pour l’application équipes. Smartsheet stocke les informations userId pour garder une trace de qui le bot Smartsheet parle. |  | Aucune |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet stocke les informations dans un état de repos crypté dans notre environnement de centre de données de production hébergé avec Equinix et dans AWS S3 où nous stockons les pièces jointes des clients dans des seaux cryptés privés. |  | Nous utilisons l’API framework bot pour délivrer des messages comme application pour l’application équipes. Smartsheet stocke les informations userId pour garder une trace de qui le bot Smartsheet parle. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet l’utilise pour aider à garder une trace de qui le bot parle aussi. Au cours du flux initial auth, nous créons un enregistrement bot pour l’utilisateur dans le système de notification Smartsheet. | Pour Smartsheet pour Teams bot, nous stockons les e-mails des utilisateurs et userId de Teams pour aider à garder une trace de qui le bot parle.  Smartsheet stocke les locataires pour aider à énumérer les groupes dont l’utilisateur fait partie dans l’annuaire, et groupIds pour la livraison de messages. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Non

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Smartsheet crypte toutes les informations utilisateur stockées et nos administrateurs sont tenus d’utiliser 2FA. Smartsheet fonctionne comme un fournisseur SaaS sans vue et par défaut, nous n’pas examiner le contenu que les clients choisissent de télécharger ou d’entrer dans la plate-forme.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

