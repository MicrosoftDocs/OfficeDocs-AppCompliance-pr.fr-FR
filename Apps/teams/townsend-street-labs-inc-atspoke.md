---
title: Informations sur les demandes sur mesure par Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour atSpoke, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9a159ce3ac976eb1916cd94b3eb1cf002f8e13c1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551194"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Juin 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Townsend Street Labs, Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | atSpoke |
| ID | WA200001454 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Townsend Street Labs, Inc. |
| URL du site web partenaire | [https://www.atspoke.com](https://www.atspoke.com) |
| URL de la politique de confidentialité | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces renseignements ont été fournis par Townsend Street Labs, Inc. sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données recueillies par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Délégué | atSpoke stocke l’ID du groupe Microsoft | Permet la possibilité de lire et d’écrire des informations de groupe entre atSpoke et Microsoft Teams.  | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| User.ReadWrite.All | Délégué | atSpoke stocke l’e-mail de l’utilisateur et l’identifiant de l’utilisateur | Permet la possibilité de lire et d’écrire des informations utilisateur entre atSpoke et Microsoft Teams. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| offline_access | Délégué | atSpoke ne stocke aucune donnée pour cela. | Ceci est utilisé pour la synchronisation d’arrière-plan. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Oui, nous utilisons des services tiers pour l’efficacité opérationnelle. Google, Inc.: Données stockées sur des volumes logiques, sauvegardes de stockage dans le réseau Google Cloud natif, journaux de service et API ou journaux d’applications. Les événements transactionnels enregistrés peuvent contenir des identifiants d’utilisateur, des coordonnées et du contenu client. MongoDB, Inc. : Données stockées dans des collections de bases de données basées sur le cloud. - Contenu client qui comprend les demandes déposées par les utilisateurs, les réponses aux demandes ajoutées par les utilisateurs et les articles de connaissances ajoutés par les utilisateurs. - Identifiants d’utilisateur (nom, e-mail, avatar et numéro de téléphone utilisés pour créer un compte d’utilisateur Spoke). Mailgun Technologies, Inc.: Identifiant d’utilisateur et coordonnées pour envoyer des communications par courriel (c.-à-d. nom et courriel). Twilio, Inc.: Numéro de téléphone utilisateur et contenu client : contenu échangé au moyen de l’utilisation des services de Twilio&#8217;, tels que le texte, les corps de messages, les médias vocaux et vidéo, les images et le son. Mixpanel, Inc. : Les données personnelles transférées comprennent le nom, le courriel, l’adresse IP et les données personnelles incluses dans le contenu des messages. Cloudinary, Inc.: Contenu client basé sur les fichiers soumis par les utilisateurs finaux. Elasticsearch, Inc. : Les événements transactionnels d’applications enregistrées peuvent contenir du texte tronqué à partir du contenu du client. Stitch, Inc.: Coordonnées, informations d’utilisation, identifiants non traditionnels des utilisateurs autorisés de l’abonné et autres données personnelles que l’abonné ou ses utilisateurs autorisés soumettent à la plate-forme. Mode Analytics, Inc.: Informations sur l’identificateur de l’utilisateur pour fournir des analyses par utilisateur. DataDog : Les événements transactionnels d’applications enregistrées peuvent contenir du texte tronqué à partir du contenu du client; la conservation du journal est de 14 jours. Fullstory, Inc.: Enregistrements des mesures prises sur notre interface utilisateur Web; inclut le compte d’utilisateur de Spoke à des fins d’identification. |  | Nous utilisons l’API Bot Framework REST. Nous utilisons cette API pour envoyer et recevoir des messages au service de bot askSpoke. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Il permet à atSpoke de synchroniser les utilisateurs à partir Microsoft Teams de créer des utilisateurs et de définir des autorisations. | atSpoke ne stocke l’e-mail que Microsoft Teams utilisateurs peuvent se connecter à Sur mesure en tant qu’utilisateur valide. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Dans nos journaux d’application, il y a le prénom et le nom de famille d’un utilisateur, l’adresse e-mail de l’utilisateur et l’identifiant d’objet attribué à Azure pour les utilisateurs et les groupes. Les journaux ne sont conservés que pendant 14 jours, période à laquelle ils expirent automatiquement. L’accès au journal est protégé contre la falsification et seul certains membres du personnel ont accès pour afficher les journaux.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données d’application sont stockées dans une instance MongoDB gérée. L’accès au service géré Atlas MongoDB Database est prévu par le biais d’un processus normalisé de demande d’accès aux utilisateurs nécessitant des approbations. Des examens périodiques de l’accès des utilisateurs sont effectués avec l’inscription de la direction. Nous limitons le nombre d’employés ayant accès à des données clients sensibles et nous n’permettons pas de modifier directement les données des machines.&#8232; L’accès à distance à cette base de données nécessite une authentification multifactorielle. La base de données et toutes les sauvegardes sont cryptées au repos à l’aide du chiffrement AES-256 bits.


#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

