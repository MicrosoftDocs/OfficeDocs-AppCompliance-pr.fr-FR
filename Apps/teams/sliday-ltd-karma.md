---
title: Informations d’application pour Karma par Sliday LTD
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Karma, ses politiques de traitement des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9da5f26e68be07cc9817c50434e214de3f3784c4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551634"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Sliday LTD à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Karma |
| ID | WA104381640 WA104381640 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Sliday LTD |
| URL du site web partenaire | [https://karmabot.chat/ms](https://karmabot.chat/ms) |
| URL de la page Teams’informations d’application | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| URL de la politique de confidentialité | [https://karmabot.readme.io/v3.0/docs/privacy-policy-for-mic...](https://karmabot.readme.io/v3.0/docs/privacy-policy-for-microsoft-teams) |
| URL des conditions d’utilisation | [https://karmabot.readme.io/docs/karma-end-user-license-agre...](https://karmabot.readme.io/docs/karma-end-user-license-agreement-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Sliday LTD sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | application | Prénom, nom de famille et adresse e-mail de l’entreprise. Prénom, nom de famille pour admin face à la déclaration. Adresse e-mail pour la communication en ce qui concerne karma, les fins de facturation et l’herarchie. | Nom d’affichage du consentement admin. Connectez-vous et lisez le profil de l’utilisateur. Description du consentement de l’administrateur. Permet aux utilisateurs de se connecter à l’application, et permet à l’application de lire le profil des utilisateurs inscrits. Il permet également à l’application de lire les informations de base de l’entreprise des utilisateurs inscrits. Nom d’affichage du consentement de l’utilisateurSignez-vous et lisez votre profil. Description du consentement de l’utilisateur. Vous permet de vous connecter à l’application avec votre compte d’organisation et de laisser l’application lire votre profil. Il permet également à l’application de lire les informations de base de l’entreprise. | 9ff28b02-ccc5-4cac-9d17-4cf6987c371f |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Prénom, nom de famille et adresse e-mail de l’entreprise Prénom, nom de famille de l’administrateur faisant face à l’adresse e-mail de déclaration pour la communication en ce qui concerne Karma. Liste est nécessaire à des fins de facturation et de diviser les utilisateurs massive enpartaments distincts. | Prénom, nom de famille et adresse e-mail de l’entreprise Prénom, nom de famille pour administrateur face à la déclaration. Adresse e-mail pour la communication en ce qui concerne karma, les fins de facturation et la hiérarchie des utilisateurs karma. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Nous stockons les identifiants des locataires et des identifiants d’utilisateur dans les journaux. Les deux ne sont pas identifiables.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>1. **Une solution DLP est-elle en place ? Qu’est-ce qui est mis en œuvre pour prévenir les fuites de données?**

OUI, les données sont cryptées à la fois en transit et au repos.

2. **Quel type de mécanismes implémentez-vous pour vous assurer que l’intégrité des données est protégée contre les erreurs, la corruption ou l’utilisation abusive et à quelle fréquence sont-elles contrôlées?**

Tous les serveurs exécutent du matériel RAID avec différents niveaux raid, mais dans chaque cas, il nécessite plusieurs pannes de disque en même temps pour toute perte de données à se produire. Nous allons en toute sécurité et avons à la fois des sauvegardes automatiques et manuelles. Les bases de données sont automatiquement sauvegardées tous les jours et stockées pendant sept jours.
Les VM sont automatiquement sauvegardés chaque semaine et stockés pendant 1 mois.

**Les instantanés et les sauvegardes sont stockés sur un réseau interne non visible publiquement.**

3. **Décrivez comment vous vous assurez que les données du client sont correctement séparées de celle des autres clients dans les solutions multi-locataires et comment vous contrôlez que les données de production ne sont pas répliquées ou utilisées dans des environnements de non-production**

Stocké dans différentes bases de données.

4. **Quel type de cryptage proposez-vous (algorithmes, protocoles, longueurs de touche) pour les données en transit et les données au repos**

Toutes les données en transit sont cryptées par TLS ou SSL. HTTP est crypté par TLS 1.2 ou TLS 1.3 Trafic de base de données crypté par SSL.

Les données sont stockées dans le centre numérique de cloud océanique dans les centres de données américains.

5. **Décrivez comment vous gérez des clés de chiffrement uniques (processus, stockage, utilisation, RACI, SOD) pour votre propre usage et pour chacun de vos locataires**

Géré par Digital Ocean.

6. **Décrivez le processus de gestion de l’accès en place à la fin du fournisseur en soulignant comment vous assurez la suppression rapide des accès qui ne sont plus nécessaires et comment vous contrôlez l’adéquation des privilèges au rôle d’emploi. Décrire également les processus de revalidation et la fréquence de son exécution**

Nous utilisons l’authentification à deux facteurs pour accéder au panneau de commande. Seulement 3 personnes y ont accès, nous changeons de mot de passe chaque mois, gardons les journaux d’accès vérifiés et nous nous assurons que les personnes qui ne travaillent plus avec nous ont leurs comptes retirés de la plate-forme.

7. **Fournissez la procédure implémentée à votre fin pour gérer vos identifiants partagés (par exemple root, Sys, System, etc.), les identifiants de groupe (comptes génériques utilisés par plusieurs personnes appartenant à la même équipe par exemple) et les comptes locaux. Décrivez comment vous restreignez, enregistrez et surveillez l’utilisation et l’accès privilégiés des comptes aux dispositifs de sécurité (p. ex., hyperviseurs, pare-feu, scanners de vulnérabilité, renifleurs de réseau, API, etc.), comment vous vous assurez que les utilisateurs qui changent d’équipe ou qui partent ne peuvent plus accéder à l’ID du Groupe et quel est le niveau de traçabilité de ces identifiants.**

Nous utilisons 1Password pour partager des&#8217;d’identification sharable, nous avons un flux d’activité distinct chaque fois que la ressource partagée a été consultée à partir d’un dépôt de mot de passe partagé. Sauf si cela est absolument nécessaire, nous n’utilisons pas de comptes partagés et n’utilisons pas de comptes individuels à la place. Aucune information de la base de données Karma n’a pu être consultée via une connexion partagée. 2FA est utilisé pour accéder à 1Password pour récupérer une connexion individuelle.

8. **Décrire le processus pour s’assurer et surveiller le respect de la séparation des tâches et la fréquence à suivre**

Nous avons organisé des réunions mensuelles qui couvrent la ségrégation des droits, l’importance de l’utilisation dédiée de la connexion et 2FA chaque connexion possible.

Notre SIEM contient : journaux de pare-feu, journaux de serveurs Web et journaux d’applications. SIEM est analysé quotidiennement et à la réception. Les journaux sont conservés pendant 1 mois et retirés en toute sécurité par la suite.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

