---
title: Informations d'application pour Karma par Sliday LTD
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour Karma, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d76ae661f25980b12ef5db6dff5a1253e77cc2f7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093267"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Sliday LTD à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Karma |
| ID | WA104381640 |
| Fonctionnalités | Bot, Onglet, Extension de la messagerie |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Sliday LTD |
| URL du site web partenaire | [https://karmabot.chat/ms](https://karmabot.chat/ms) |
| URL de la Teams d'informations sur l'application | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| URL de la politique de confidentialité | [https://karmabot.readme.io/v3.0/docs/privacy-policy-for-mic...](https://karmabot.readme.io/v3.0/docs/privacy-policy-for-microsoft-teams) |
| URL des conditions d'utilisation | [https://karmabot.readme.io/docs/karma-end-user-license-agre...](https://karmabot.readme.io/docs/karma-end-user-license-agreement-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par Sliday LTD sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d'autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d'application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | application | Prénom, nom et adresse de messagerie de la société. Prénom, nom de famille pour les rapports orientés administrateur. Adresse de messagerie pour la communication en ce qui concerne Karma, les objectifs de facturation et l'herarchy. | Nom complet du consentement de l'administrateur. Connectez-vous et lisez le profil utilisateur. Description du consentement de l'administrateur. Permet aux utilisateurs de se connecter à l'application et permet à l'application de lire le profil des utilisateurs qui sont inscrits. Il permet également à l'application de lire les informations de base de l'entreprise des utilisateurs inscrits. Nom complet du consentement de l'utilisateurSignez-vous et lisez votre profil. Description du consentement de l'utilisateur. Vous permet de vous inscrire à l'application avec votre compte d'organisation et de permettre à l'application de lire votre profil. Elle permet également à l'application de lire les informations de base de l'entreprise. | 9ff28b02-ccc5-4cac-9d17-4cf6987c371f |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d'identification de l'utilisateur final (EUII) : la liste (prénom, nom, nom d'affichage, adresse e-mail) d'un membre d'une équipe ou d'une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l'accès à EUII ?**  | **L'EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l'EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Prénom, nom et adresse e-mail de la société Prénom, nom de famille de l'adresse e-mail de rapport de l'administrateur pour la communication en ce qui concerne Karma. La liste de présence est requise à des fins de facturation et pour fractionner les utilisateurs de façon massive en différents départs. | Prénom, nom et adresse de messagerie de l'entreprise Prénom, nom de famille des rapports auxquels l'administrateur est confronté. Adresse de messagerie pour la communication en ce qui concerne le karma, les objectifs de facturation et la hiérarchie des utilisateurs Karma. |  |



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous stockons les ID de locataire et d'utilisateur dans les journaux. Les deux ne sont pas identifiables.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>1. **Une solution DLP est-elle en place ? Qu'est-ce qui est implémenté pour empêcher les fuites de données ?**

OUI, les données sont chiffrées à la fois en transit et au repos.

2. **Quels types de mécanismes implémentez-vous pour vous assurer que l'intégrité des données est protégée contre les erreurs, les altérations ou les mauvaises utilisations et la fréquence de contrôle**

Tous les serveurs exécutent raid matériel avec différents niveaux RAID, mais dans chaque cas, il nécessite plusieurs défaillances de lecteur en même temps pour toute perte de données se produire. Nous sommes très sûrs et nous avons des sauvegardes automatiques et manuelles. Les bases de données sont automatiquement enregistrées tous les jours et stockées pendant sept jours.
Les VM sont automatiquement enregistrées toutes les semaines et stockées pendant 1 mois.

**Les captures instantanées et les sauvegardes sont stockées sur un réseau interne non visible publiquement.**

3. **Décrire comment vous vous assurez que les données du client sont correctement séparées des autres clients dans des solutions multi-clients et comment vous contrôlez que les données de production ne sont pas répliquées ou utilisées dans des environnements hors production**

Stocké dans différentes bases de données.

4. **Quel type de chiffrement proposez-vous (algorithmes, protocoles, longueurs de clés) pour les données en transit et les données au repos**

Toutes les données en transit sont chiffrées par TLS ou SSL. HTTP est chiffré par le trafic de base de données TLS 1.2 ou TLS 1.3 chiffré par SSL.

Les données sont stockées dans le centre cloud de l'océan numérique dans les centres de données américains.

5. **Décrire comment gérer des clés de chiffrement uniques (processus, stockage, utilisation, RACI, SOD) pour votre propre utilisation et pour chacun de vos locataires**

Géré par l'océan numérique.

6. **Décrivez le processus de gestion d'accès en place à la fin du fournisseur, en vous attumant sur la façon dont vous assurez la suppression en temps voulu des accès qui ne sont plus nécessaires et sur la façon dont vous contrôlez l'adéquation des privilèges au rôle de travail. Décrire également les processus de revalidation et la fréquence de son exécution**

Nous utilisons l'authentification à deux facteurs pour accéder au panneau de contrôle. Seules 3 personnes y ont accès, nous changeons de mot de passe tous les mois, nous vérifions les journaux d'accès et nous vérifions que les comptes des personnes qui ne travaillent plus avec nous sont supprimés de la plateforme.

7. **Fournissez la procédure implémentée à votre fin pour gérer vos ID partagés (par exemple, racine, Sys, système, etc.), les ID de groupe (comptes génériques utilisés par plusieurs personnes appartenant à la même équipe, par exemple) et les comptes locaux. Décrire comment restreindre, enregistrer et surveiller l'utilisation des comptes privilégiés et l'accès aux appareils de sécurité (par exemple, les hyperviseurs, les pare-feu, les scanneurs de vulnérabilités, les renifleurs de réseau, les API, etc.), comment vous assurez que les utilisateurs qui changent d'équipe ou quittent l'équipe ne peuvent plus accéder à l'ID de groupe et quel est le niveau de traçabilité de ces ID**

Nous utilisons 1Password pour partager des&#8217;d'ID partageables, nous avons un flux d'activités distinct chaque fois que la ressource partagée a été accédée à partir d'un dépôt de mot de passe partagé. Sauf absolue nécessité, nous n'utilisons pas de comptes partagés et n'utilisons pas de comptes individuels à la place. Aucune information sur la base de données Karma n'a été accessible via une connexion partagée. 2FA permet d'accéder à 1Password pour récupérer une connexion individuelle.

8. **Décrire le processus pour s'assurer et surveiller que la séparation des tâches est respectée et à quelle fréquence elle est contrôlée**

Nous avons mené des réunions mensuelles qui couvrent la répartition des droits, l'importance de l'utilisation dédiée de la connexion et chaque connexion 2FA possible.

Notre SIEM contient : les journaux de pare-feu, les journaux de serveur web et les journaux d'applications. SIEM est analysé quotidiennement et lors de la réception. Les journaux sont conservés pendant 1 mois et supprimés en toute sécurité après cela.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

