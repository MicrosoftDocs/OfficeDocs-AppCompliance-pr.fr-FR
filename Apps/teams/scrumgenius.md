---
title: Informations d’application pour ScrumGenius par ScrumGenius
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour ScrumGenius, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ba3b54f7d99672d657b200bf36725d0c7bf03d83
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553905"
---
# <a name="scrumgenius"></a>ScrumGenius

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/14510476-fa9d-4dad-add9-aa5975a60a8b" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381097" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par ScrumGenius à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | ScrumGenius |
| ID | WA104381097 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | ScrumGenius |
| URL du site web partenaire | [https://scrumgenius.com/](https://scrumgenius.com/) |
| URL de la politique de confidentialité | [https://scrumgenius.com/privacy/](https://scrumgenius.com/privacy/) |
| URL des conditions d’utilisation | [https://scrumgenius.com/tos/](https://scrumgenius.com/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par ScrumGenius sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Délégué | Dates de vacances définies dans le calendrier de l’utilisateur. | Pour les utilisateurs de synchroniser leurs vacances avec ScrumGenius. |  |
>| User.Read | Délégué | Nom de l’utilisateur et adresse e-mail. | Pour permettre à l’utilisateur de se connecter à Microsoft Login. |  |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nous accédons à la liste de l’équipe, donc quand un administrateur d’équipe installe scrumgenius, nous pouvons synchroniser le reste de la liste de l’équipe avec scrumgenius afin que nous puissions les border avec notre plate-forme pour être en mesure de leur permettre de configurer un rapport de standup et d’affecter les membres de l’équipe qui devrait obtenir le rapport. | prénom, nom de famille, nom d’affichage, adresse e-mail |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Non. Nous attachons l’utilisateur à notre identifiant interne pour les journaux.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Oui, nos données d’application sont cryptées en transit et au repos. Seule l’application Web peut accéder directement à la DB. L’accès extérieur est restreint, et nous utilisons des plages IP pour protéger l’accès.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35745' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35745" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

