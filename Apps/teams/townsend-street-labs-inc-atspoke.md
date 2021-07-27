---
title: Informations sur l’application pour atSpoke par Les ateliers de La rue Dupont, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour atSpoke, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2d72ea33577e386c61be6bcd09feeba813e9e1f5
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528100"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Les Ateliers De La Rue, Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | atSpoke |
| ID | WA200001454 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Townsend Street Labs, Inc. |
| URL du site web partenaire | [https://www.atspoke.com/](https://www.atspoke.com/) |
| URL de la politique de confidentialité | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.atspoke.com/terms-of-service/](https://www.atspoke.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par LaBoe street Labs, Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | délégué | atSpoke stocke l’ID de groupe Microsoft | Permet de lire et d’écrire des informations de groupe entre atSpoke et Microsoft Teams.  | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| User.ReadWrite.All | délégué | atSpoke stocke le courrier électronique et l’ID utilisateur de l’utilisateur | Permet de lire et d’écrire des informations utilisateur entre atSpoke et Microsoft Teams. | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| offline_access | délégué | atSpoke ne stocke pas de données pour cela. | Cette fonction est utilisée pour la synchronisation en arrière-plan. | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Oui, nous utilisons des services tiers pour l’efficacité opérationnelle. Google, Inc. : données stockées sur des volumes logiques, des sauvegardes de stockage dans le réseau Google Cloud natif, des journaux de service et d’API ou des journaux d’application. Les événements transactionnels consignés peuvent contenir des identificateurs d’utilisateur, des informations de contact et du contenu client. MongoDB, Inc.: Données stockées dans des collections de bases de données en nuage. - Contenu client qui inclut les demandes classées par les utilisateurs, les réponses aux demandes ajoutées par les utilisateurs et les articles de connaissances ajoutés par les utilisateurs. - Identificateurs d’utilisateur (nom, e-mail, avatar et numéro de téléphone utilisés pour créer un compte d’utilisateur Spoke). Mailgun Technologies, Inc.: Identificateur d’utilisateur et informations de contact pour envoyer des communications par courrier électronique (par exemple, nom et courrier électronique). Twilio, Inc.: Numéro de téléphone de l’utilisateur et contenu client : contenu échangé au moyen de l’utilisation des services de Twilio&#8217;, tels que le texte, les corps des messages, les médias vocaux et vidéo, les images et le son. Mixpanel, Inc. : les données personnelles transférées incluent le nom, la messagerie, l’adresse IP et les données personnelles incluses dans le contenu du message. Cloudinary, Inc.: Contenu client basé sur un fichier soumis par les utilisateurs finaux. Elasticsearch, Inc.: Les événements transactionnels de l’application journalisé peuvent contenir du texte tronqué à partir du contenu client. Stitch, Inc. : informations de contact, informations d’utilisation, identificateurs non traditionnels des utilisateurs autorisés de l’abonné et autres données personnelles que l’abonné ou ses utilisateurs autorisés soumettent à la plateforme. Mode Analytics, Inc.: Informations d’identificateur d’utilisateur pour fournir des analyses par utilisateur. DataDog : les événements transactionnels d’application consignés peuvent contenir du texte tronqué à partir du contenu client ; la rétention du journal est de 14 jours. Fullstory, Inc.: Recordings of actions taken on our web user interface; inclut le compte d’utilisateur de Spoke à des fins d’identification. |  | Nous utilisons l’API REST Bot Framework. Nous utilisons cette API pour envoyer et recevoir des messages au service de bot askSpoke. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Il permet à atSpoke de synchroniser les utilisateurs à partir Microsoft Teams pour créer des utilisateurs et définir des autorisations. | atSpoke stocke uniquement le courrier électronique Microsoft Teams les utilisateurs peuvent se connecter à atSpoke en tant qu’utilisateur valide. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Dans les journaux de nos applications, il y a le prénom et le nom d’un utilisateur, l’adresse e-mail de l’utilisateur et l’ID d’objet affecté à Azure pour les utilisateurs et les groupes. Les journaux sont conservés uniquement pendant 14 jours, date à laquelle ils expirent automatiquement. L’accès aux journaux est protégé contre la falsification et seuls certains membres du personnel ont accès à l’affichage des journaux.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données d’application sont stockées dans une instance MongoDB gérée. L’accès à la base de données Atlas MongoDB du service géré est fourni via un processus standard de demande d’accès utilisateur nécessitant des approbations. Des révisions périodiques de l’accès des utilisateurs sont effectuées avec la signature de gestion. Nous limitons le nombre d’employés ayant accès aux données client sensibles et nous n’autoriseons pas la modification des données à partir d’ordinateurs directement.&#8232; L’accès à distance à cette base de données nécessite une authentification multifacteur. La base de données et toutes les sauvegardes sont chiffrées au repos à l’aide du chiffrement AES-256 bits.


#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

