---
title: Informations sur l’application pour lapope- par-t-elle
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour L’pop, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3865c07aca73134fd9029ee0550559d9a4f93fd2
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281325"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Lapop à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Cloverpop |
| ID | WA200001803 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Cloverpop |
| URL du site web partenaire | [https://www.cloverpop.com/](https://www.cloverpop.com/) |
| URL de la politique de confidentialité | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par LesisteurPop sur la façon dont cette application collecte et stocke les données organisationnelles, ainsi que sur le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | stocker des données utilisateur telles que. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Lorsque les utilisateurs créent et interagissent avec les décisions, nous les associeons à l’utilisateur, à l’équipe et à l’organisation qui les ont créées. Nous devons également afficher cette propriété dans une expérience utilisateur conviviale. Par conséquent, nous stockons des informations d’affichage, par exemple, l'&#8217;avatar. | permet à l’utilisateur de se connecter et donne à l’application l’accès à son UPN pour activer l'&#8221; de connexion silencieuse : e-mail, nom, oid, tid, givenName, nom de famille, nom de famille, avatar de l’utilisateur(photo), nom complet de l’organisation | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| openid | délégué | Stockez des données utilisateur telles que. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Lorsque les utilisateurs créent et interagissent avec les décisions, nous les associeons à l’utilisateur, à l’équipe et à l’organisation qui les ont créées. Nous devons également afficher cette propriété dans une expérience utilisateur conviviale. Par conséquent, nous stockons des informations d’affichage, par exemple, l'&#8217;avatar. | Pour implémenter &#8220;se Teams&#8221; sur notre application web. | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| profil | délégué | Stockez des données utilisateur telles que. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Lorsque les utilisateurs créent et interagissent avec les décisions, nous les associeons à l’utilisateur, à l’équipe et à l’organisation qui les ont créées. Nous devons également afficher cette propriété dans une expérience utilisateur conviviale. Par conséquent, nous stockons des informations d’affichage, par exemple, l'&#8217;avatar. | Pour implémenter &#8220;se Teams&#8221; sur notre application web. | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Nous accédons aux données de prénom/nom d’affichage afin d’afficher avec précision les actions entreprises par des utilisateurs spécifiques en relation avec une décision. Nous utilisons l’adresse de messagerie comme identificateur unique pour chaque utilisateur dans notre base de données, car nous permettons à chaque utilisateur d’appartenir à plusieurs organisations. Nous accédons uniquement à ces données lorsqu’ils interagissent avec notre application, par exemple s’ils répondent à un sondage. | Nous stockons les données de prénom/nom d’affichage afin d’afficher avec précision les actions entreprises par des utilisateurs spécifiques en relation avec une décision.  Nous stockons l’adresse de messagerie, car nous l’utilisons comme identificateur unique pour chaque utilisateur dans notre base de données, car nous permettons à chaque utilisateur d’appartenir à plusieurs organisations. Nous stockons ces données uniquement lorsqu’ils interagissent avec notre application, par exemple s’ils répondent à un sondage. Nos données de décision sont supposées être un système d’enregistrement pour les décisions. Il est donc important que nous stockions les données pour identifier la façon dont chaque utilisateur impliqué dans une décision a contribué à cette décision. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Oui.
L’ID d’équipe s’affiche dans nos journaux lorsque notre application est en interaction avec une équipe.
Nous avons un accès limité à nos journaux de production pour nos trois fondateurs basés aux États-Unis.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>L’application Derpop est conçue à l’aide de Ruby on Rails et est hébergée sur le PaaS Heroku (plateforme en tant que service) qui utilise AWS pour son infrastructure cloud. Heroku et AWS ont tous deux des rapports SOC accessibles. Notre application utilise PostgreSQL pour le stockage de données chiffrées au repos et est un environnement multi-clients.
 
L’ensemble de notre code est composé de tests automatisés qui couvrent la sécurité de l’accès aux données. Chaque build fait l’objet d’un processus rigoureux de révision du code pour la sécurité et d’un processus de test d’assurance qualité manuel qui inclut également des vérifications de l’authentification des utilisateurs et de l’accès aux données par le biais des actions utilisateur disponibles. Il existe une séparation claire entre notre environnement de production et tous les autres environnements, tels que le développement et les tests.
 
Seuls les membres du personnel sélectionnés ont accès à l’environnement de production et à la base de données : les fondateurs de l’entreprise et une petite poignée d’employés qui ont subi des vérifications des antécédents et ont des besoins quantifiés (par exemple, le support client).

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

