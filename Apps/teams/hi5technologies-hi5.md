---
title: Informations d’application pour Hi5 par Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Hi5, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 983f86210f224bc492f54a7ab65192dee5b4ad6c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552115"
---
# <a name="hi5"></a>Hi5

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Novembre 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Hi5Technologies à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Hi5 |
| ID | WA200001610 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Hi5Technologies |
| URL du site web partenaire | [https://www.get5.io/](https://www.get5.io/) |
| URL de la politique de confidentialité | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| URL des conditions d’utilisation | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Hi5Technologies sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit l’approuver en ajoutant des notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Requis pour la connexion SSO et l’authentification contre notre serveur | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| email | Délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit l’approuver en ajoutant des notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Requis pour la connexion SSO et l’authentification contre notre serveur | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| offline_access | Délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit l’approuver en ajoutant des notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Maintient que l’utilisateur voit les informations correctes et nous pouvons envoyer les informations correctes à d’autres qui rejoignent la même entreprise / espace de travail. | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| openid | Délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit l’approuver en ajoutant des notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Requis pour la connexion SSO et l’authentification contre notre serveur | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| profil | Délégué | Nous stockons uniquement les informations de session des utilisateurs à partir de Teams et l’utilisateur doit l’approuver en ajoutant des notifications (ils peuvent les supprimer à tout moment). Aucune autre information n’est stockée. | Requis pour la connexion SSO et l’authentification contre notre serveur | 7cb50e3e-0427-409e-90d2-638eb28217c3 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Pour informer l’utilisateur d’un canal qu’on lui a donné un Hi5 | Aucune information n’est stockée, l’utilisateur sera juste @ par la carte renvoyée dans le canal |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Non, Hi5 est simplement iFramed et toutes les données sont stockées en toute sécurité.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Nous utilisons OAuth et fournissons 3 options de connexion :
- Googles SSO (OAuth).
- Microsoft SSO (OAuth).
- Notre propre cryptage qui est une combinaison de cryptage SHA et AES.
Une fois authentifié et connecté, votre niveau d’autorisation vous donne accès aux sections autorisées de la plate-forme Hi5.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

