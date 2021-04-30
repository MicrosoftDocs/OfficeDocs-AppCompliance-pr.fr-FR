---
title: Informations sur l'application pour LeBoxéreur par Insiten
ms.author: elmalova
author: elenamalova
ms.date: 01/12/2021
ms.topic: article
ms.service: attestation
description: Toutes les informations de sécurité et de conformité disponibles pour LeBoxétère, ses stratégies de gestion des données, ses informations de catalogue d'applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 19ff04953cb67cdcfcd6ea0b430ed3c1eb56f081
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093689"
---
# <a name="tacklebox"></a>TackleBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 12, 2021</p>

* <a href="https://teams.microsoft.com/l/app/dc37dab6-b497-4259-9aad-e40bfa023796" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002310" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Insiten à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | TackleBox |
| ID | WA200002310 |
| Fonctionnalités | Onglet, Connecteur |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Insiten |
| URL du site web partenaire | [https://tacklebox.app/](https://tacklebox.app/) |
| URL de la Teams d'informations sur l'application | [https://tacklebox.app](https://tacklebox.app) |
| URL de la politique de confidentialité | [https://tacklebox.app/privacy/](https://tacklebox.app/privacy/) |
| URL des conditions d'utilisation | [https://tacklebox.app/terms/](https://tacklebox.app/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l'application

Ces informations ont été fournies par Insiten sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l'application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l'aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d'autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d'application Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | délégué | Permet aux utilisateurs de parcourir leurs OneDrive, dossiers et fichiers . lier des fichiers à l'outil lire Excel fichiers pour extraire automatiquement des graphiques, des graphiques, des tableaux, des zones d'impression et des plages nommées ; créer et mettre à jour PowerPoint fichiers visuels avec Excel visuels | ID de lecteur, ID de dossier, ID de fichier, lien d'affichage, créé par, date de création, modifié par, date de modification, ID de version, nom de fichier | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| Sites.Read.All | délégué | Autoriser les utilisateurs à parcourir et à lier Excel fichiers situés dans des canaux Teams privés | Aucune | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| User.Read | délégué | Permet à l'application de lire le profil des utilisateurs inscrits et de réessigner leur adresse e-mail pour les notifications | E-mail | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| openid | délégué | Permet aux utilisateurs de se connecter à notre application à l'aide Microsoft 365 compte | ID de client et ID d'objet pour l'utilisateur | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| profil | délégué | Permet à l'application d'afficher le profil de base des utilisateurs (nom, nom d'utilisateur) pour faire la démonstration de la collaboration | UPN, Prénom, Nom | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l'application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l'application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l'application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d'identification de l'utilisateur final (EUII) : la liste (prénom, nom, nom d'affichage, adresse e-mail) d'un membre d'une équipe ou d'une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n'est accessible.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d'identification organisationnelle (OII) ou d'identification de l'utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Adresses e-mail et noms de compte. Les comptes désactivés et les détails des utilisateurs associés sont purgés au bout de 3 mois.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l'organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l'audit, l'archivage, la stratégie de l'utilisateur final, etc.

>Non applicable : toutes les données sont stockées dans Microsoft Azure

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l'analyse de données d'informations d'identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d'identité

Ces informations ont été fournies par Insiten sur la façon dont cette application gère l'authentification, l'autorisation, les meilleures pratiques d'inscription de l'application et d'autres critères d'identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d'identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft'intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d'authentification Microsoft) pour l'authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d'accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l'location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
