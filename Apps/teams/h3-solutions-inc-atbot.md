---
title: Informations d’application pour AtBot par H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour AtBot, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3f56d0b3eb19f5bed8f7092507c8605af936b911
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552135"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par H3 Solutions, Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | AtBot |
| ID | WA104381219 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | H3 Solutions, Inc. |
| URL du site web partenaire | [https://atbot.io](https://atbot.io) |
| URL de la page Teams’informations d’application | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL de la politique de confidentialité | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL des conditions d’utilisation | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par H3 Solutions, Inc. sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | application | Nom du groupe AAD, AAD Group GUID, UPN | Énumérez les groupes AAD pour permettre la coupe de sécurité des compétences bot. Énumérez les utilisateurs pour pouvoir appliquer des licences. Énumérer les utilisateurs à ajouter en tant qu’administrateurs/contributeurs | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | Délégué | Nom du groupe AAD, AAD Group GUID, UPN | Énumérez les groupes AAD pour permettre la coupe de sécurité des compétences bot. Énumérez les utilisateurs pour pouvoir appliquer des licences. Énumérer les utilisateurs à ajouter en tant qu’administrateurs/contributeurs | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| People.Read | Délégué | Non | Énumérez les personnes dans une action Get Person de Flow.  Permet au bot de récupérer les personnes à partir du point de terminaison /People dans Microsoft Graph. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | Délégué | Pièce d’identité du locataire, UPN | Nous donne accès à l’identifiant de locataire de l’utilisateur&#8217;et UPN pour nous permettre de lier les flux / applications logiques créées aux utilisateurs qui les ont créés. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| email | Délégué | Non | Nous donne accès à l’adresse e-mail de l’utilisateur. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | Délégué | Accéder/Actualiser les jetons. | Nous permet d’utiliser un jeton de rafraîchissement pour garder les utilisateurs connectés. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| openid | Délégué | Non | Permet aux utilisateurs de se connecter. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| profil | Délégué | UPN | Accès à l’UPN de l’utilisateur. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| La création de mentions dans les messages de chat générés par des bots | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Identifiant locataire, UPN Nous utilisons les aperçus d’applications et nos journaux dureront 90 jours avant d’être automatiquement archivés. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les administrateurs ont la possibilité de supprimer les configurations de bot qui peuvent contenir des noms de groupe AAD/GUID.
Lors de l’annulation du service, tous les UPN seront supprimés de la base de données des licences.
Voir 'Azure Services' sous Data Residency.  Une grande partie des données spécifiques au client produites via l’utilisation d’AtBot sont stockées dans le locataire du client et donc les administrateurs de ce locataire ont le plein contrôle des données là-bas.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

