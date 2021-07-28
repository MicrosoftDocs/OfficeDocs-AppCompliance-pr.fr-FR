---
title: Informations d’application pour MindManager par Corel
ms.author: elmalova
author: elenamalova
ms.date: 05/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour MindManager, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7a431ae7736e2efa22a2d75ff3a1cfc2e1e2234f
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525738"
---
# <a name="mindmanager"></a>MindManager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/cebe4a59-b076-47f3-a7bf-79148daf82f7" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002261" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Corel à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | MindManager |
| ID | WA200002261 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Corel |
| URL du site web partenaire | [https://www.mindmanager.com](https://www.mindmanager.com) |
| URL de la politique de confidentialité | [https://www.corel.com/en/corel-privacy-policy/](https://www.corel.com/en/corel-privacy-policy/) |
| URL des conditions d’utilisation | [https://www.mindjet.com/go/mmcloudterms](https://www.mindjet.com/go/mmcloudterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Corel sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | délégué | Informations sur les modifications apportées dans un fichier MindManager qui peuvent ensuite être publiées en tant que message | métadonnées de fichier, contenu de fichier : pour le navigateur de fichiers, l’utilisateur peut parcourir ses fichiers pour ouvrir un fichier MindManager (.mmap). | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Chat.Send | délégué | Informations sur les modifications apportées dans un fichier MindManager qui peuvent ensuite être publiées en tant que message | métadonnées de fichier, contenu de fichier : pour le navigateur de fichiers, l’utilisateur peut parcourir ses fichiers pour ouvrir un fichier MindManager (.mmap). | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Files.ReadWrite | délégué | liste des sites, liste de dossiers, métadonnées de fichiers, contenu de fichier : pour le navigateur de fichiers, l’utilisateur peut parcourir ses fichiers pour ouvrir un fichier MindManager (.mmap). | - données de profil : pour identifier l’utilisateur et afficher son profil - contenu de fichier : pendant la session de co-édition (modification collaborative en temps réel sur les fichiers .mmap MindManager) | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Sites.ReadWrite.All | délégué | liste des sites, liste de dossiers, métadonnées de fichiers, contenu de fichier : pour le navigateur de fichiers, l’utilisateur peut parcourir ses fichiers pour ouvrir un fichier MindManager (.mmap). | contenu de fichier : pendant la session de co-édition (modification collaborative en temps réel sur les fichiers .mmap MindManager) | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| User.Read | délégué | données de profil : pour identifier l’utilisateur et afficher son profil | données de profil : pour identifier l’utilisateur et afficher son profil | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| offline_access | délégué | Cela nous permet d’enregistrer un fichier à son emplacement d’origine ultérieurement pour le compte de l’utilisateur, si nécessaire. | contenu de fichier : pendant la session de co-édition (modification collaborative en temps réel sur les fichiers .mmap MindManager) | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Amazon Web Services (AWS) | Nom de l’organisation, domaine de l’organisation | L’organisation a besoin d’une configuration de compte au sein de notre infrastructure d’application pour utiliser l’application dans Teams |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Abordé ici : https://www.mindjet.com/go/mmcloudterms

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Corel sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d’identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
