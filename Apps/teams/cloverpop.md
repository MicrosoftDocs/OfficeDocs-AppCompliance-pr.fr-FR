---
title: Informations d’application pour Cloverpop par Cloverpop
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Cloverpop, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: eaee7a04f4d8e74f97eef1fae358f80a0c3e2249
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553225"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Août 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Cloverpop à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Cloverpop |
| ID | WA200001803 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Cloverpop |
| URL du site web partenaire | [https://www.cloverpop.com](https://www.cloverpop.com) |
| URL de la politique de confidentialité | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Cloverpop sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Délégué | stocker des données utilisateur comme. e-mail, oid, givenName, familyName, avatar utilisateur, id objet utilisateur. organisation id(tenantId), nom d’affichage de l’organisation, Aussi, nous stockons sur nos équipes latérales / canaux noms, ids, membres des équipes. Lorsque les utilisateurs créent et interagissent avec les décisions, nous associons ces données à l’utilisateur, à l’équipe et à l’organisation qui les ont créées. Nous avons également besoin d’afficher cette propriété dans un UX respectueux de l’homme sont donc stocker des informations d’affichage par exemple l’utilisateur&#8217;avatar de l’utilisateur. | permet à l’utilisateur de se connecter et donne à l’application l’accès à son UPN pour activer les&#8221; de connexion silencieuse - e-mail, nom, oid, tid, givenName, nom de famille, avatar d’utilisateur(photo), affichage de l’organisationName | 1040474b-572d-4575-a423-95dd262a8b8a |
>| openid | Délégué | Stockez les données des utilisateurs comme. e-mail, oid, givenName, familyName, avatar utilisateur, id objet utilisateur. organisation id(tenantId), nom d’affichage de l’organisation, Aussi, nous stockons sur nos équipes latérales / canaux noms, ids, membres des équipes. Lorsque les utilisateurs créent et interagissent avec les décisions, nous associons ces données à l’utilisateur, à l’équipe et à l’organisation qui les ont créées. Nous avons également besoin d’afficher cette propriété dans un UX respectueux de l’homme sont donc stocker des informations d’affichage par exemple l’utilisateur&#8217;avatar de l’utilisateur. | Pour implémenter &#8220;vous connecter Teams&#8221; sur notre application Web. | 1040474b-572d-4575-a423-95dd262a8b8a |
>| profil | Délégué | Stockez les données des utilisateurs comme. e-mail, oid, givenName, familyName, avatar utilisateur, id objet utilisateur. organisation id(tenantId), nom d’affichage de l’organisation, Aussi, nous stockons sur nos équipes latérales / canaux noms, ids, membres des équipes. Lorsque les utilisateurs créent et interagissent avec les décisions, nous associons ces données à l’utilisateur, à l’équipe et à l’organisation qui les ont créées. Nous avons également besoin d’afficher cette propriété dans un UX respectueux de l’homme sont donc stocker des informations d’affichage par exemple l’utilisateur&#8217;avatar de l’utilisateur. | Pour implémenter &#8220;vous connecter Teams&#8221; sur notre application Web. | 1040474b-572d-4575-a423-95dd262a8b8a |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nous accédons aux données du nom de première/dernière/affichage afin d’afficher avec précision les mesures prises par des utilisateurs spécifiques concernant une décision. Nous utilisons l’adresse e-mail comme identifiant unique pour chaque utilisateur dans notre db car nous permettons à chaque utilisateur d’appartenir à plusieurs organisations. Nous n’accédons à ces données que lorsqu’elles interagissent avec notre application, par exemple si elles répondent à un sondage. | Nous stockons les données de nom de première/dernière/affichage afin d’afficher avec précision les mesures prises par des utilisateurs spécifiques concernant une décision.  Nous stockons l’adresse e-mail parce que nous l’utilisons comme l’identificateur unique pour chaque utilisateur dans notre db que nous permettons à chaque utilisateur d’appartenir à plusieurs organisations. Nous ne stockons ces données que lorsqu’elles interagissent avec notre application, par exemple si elles répondent à un sondage. Nos données de décision sont censées être un système d’enregistrement des décisions, il est donc important que nous stockions les données pour identifier comment chaque utilisateur impliqué dans une décision a contribué à cette décision. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Oui.
L’ID d’équipe est affiché dans nos journaux lorsque notre application est interagie avec une équipe.
Nous avons un accès limité à nos journaux de production à nos trois fondateurs qui sont tous basés aux États-Unis.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>L’application Cloverpop est construite en utilisant Ruby on Rails et est hébergée sur le Heroku PaaS (plate-forme en tant que service) qui utilise AWS pour son infrastructure cloud. Heroku et AWS ont tous deux des rapports SOC accessibles. Notre application utilise PostgreSQL pour le stockage de données crypté au repos et est un environnement multi-locataires.
 
Tout notre code a des tests automatisés écrits pour elle qui couvre la sécurité d’accès aux données. Chaque build fait l’objet d’un processus rigoureux d’examen du code pour la sécurité et d’un processus manuel de test QA qui inclut également des contrôles pour l’authentification des utilisateurs et l’accès aux données par le biais d’actions utilisateur disponibles. Il y a une séparation claire entre notre environnement de production et tous les autres environnements, tels que le développement et les essais.
 
Seul le personnel sélectionné a accès à l’environnement de production et à la base de données : les fondateurs de l’entreprise et une petite poignée d’employés contrôlés qui ont subi des vérifications des antécédents et ont un besoin quantifié (comme le soutien à la clientèle).

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

