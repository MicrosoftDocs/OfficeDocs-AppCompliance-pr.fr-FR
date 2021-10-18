---
title: Informations d’application pour Senso par Senso
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Senso, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3e538fddf6ca799348ca010c7553a0dd1439fba1
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429572"
---
# <a name="senso"></a>Senso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3973b9d4-b50e-472d-8145-8967e01379b4" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002571" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Senso à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Senso |
| ID | WA200002571 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Senso |
| URL du site web partenaire | [https://www.senso.cloud](https://www.senso.cloud) |
| URL de la Teams d’informations sur l’application | [https://www.senso.cloud/safeguarding-microsoft-teams/](https://www.senso.cloud/safeguarding-microsoft-teams/) |
| URL de la politique de confidentialité | [https://www.senso.cloud/privacy](https://www.senso.cloud/privacy) |
| URL des conditions d’utilisation | [https://www.senso.cloud/eula](https://www.senso.cloud/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Senso sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | application | Lisez les noms et descriptions des canaux pour identifier l’endroit où une violation a été signalée.   | Lorsqu’une violation se produit, le nom de l’expéditeur (De), le(s) nom(s) des destinataires (À), le nom du canal, la date, l’heure et les messages de ce canal de conversation sont enregistrés pour fournir un contexte à une violation.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMember.Read.All | application | Lire la liste des membres et les messages de conversation de tous les canaux. | Lorsqu’une violation se produit, le nom de l’expéditeur (De), le(s) nom(s) des destinataires (À), le nom du canal, la date, l’heure et les messages de ce canal de conversation sont enregistrés pour fournir un contexte à une violation.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMessage.Read.All | application | Lire tous les messages du canal | Lorsqu’une violation se produit, le nom de l’expéditeur (De), le(s) nom(s) des destinataires (À), le nom du canal, la date, l’heure et les messages de ce canal de conversation sont enregistrés pour fournir un contexte à une violation.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Chat.Read.All | application | Lire tous les messages de conversations. | Lorsqu’une violation se produit, le nom de l’expéditeur (De), le(s) nom(s) des destinataires (À), le nom du canal, la date, l’heure et les messages de ce canal de conversation sont enregistrés pour fournir un contexte à une violation.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Directory.Read.All | application | Lire les données d’annuaire | Lorsqu’une violation se produit, le nom de l’expéditeur (De), le(s) nom(s) des destinataires (À), le nom du canal, la date, l’heure et les messages de ce canal de conversation sont enregistrés pour fournir un contexte à une violation.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Files.Read.All | application | Lire les fichiers dans toutes les collections de sites | Lorsqu’une violation se produit, le nom de l’expéditeur (De), le(s) nom(s) des destinataires (À), le nom du canal, la date, l’heure et les messages de ce canal de conversation sont enregistrés pour fournir un contexte à une violation.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read | délégué | Activer la connexion et lire le profil utilisateur | Utilisé pour l' sign-on unique | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read.All | application | Lire les profils complets de tous les utilisateurs | Lorsqu’une violation se produit, le nom de l’expéditeur (De), le(s) nom(s) des destinataires (À), le nom du canal, la date, l’heure et les messages de ce canal de conversation sont enregistrés pour fournir un contexte à une violation.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Senso.cloud utilise les sous-processeurs suivants pour les performances de son service : https://www.senso.cloud/privacy-policy/ Section 5. Divulgations de vos données personnelles. | Les types de données que nous partageons avec des comptes tiers et des fournisseurs tiers sont définies dans la section 5, colonne de droite du tableau ( https://www.senso.cloud/privacy-policy/) . | La base légale du traitement de chacun d’eux est basée sur les performances d’un contrat avec vous ou nécessaires pour nos intérêts légitimes (pour l’exécution de notre entreprise, l’archivage des données, la mise en service de l’administration et des services informatiques, la sécurité du réseau, afin d’éviter les fraudes et les violations de données. Par exemple, l’adresse de messagerie professionnelle, l’adresse e-mail est requise pour envoyer les notifications de contact de facturation au client ou, si vous payez par carte de crédit, des informations sont requises pour lever des tickets de support lorsque vous accédez au support client. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Senso.cloud utilise les sous-processeurs suivants pour les performances de son service : https://www.senso.cloud/privacy-policy/ Section 5. Divulgations de vos données personnelles. | Les types de données que nous partageons avec des comptes tiers et des fournisseurs tiers sont définies dans la section 5, colonne de droite du tableau ( https://www.senso.cloud/privacy-policy/) . | La base légale du traitement de chacun d’eux est basée sur les performances d’un contrat avec vous ou nécessaires pour nos intérêts légitimes (pour l’exécution de notre entreprise, l’archivage des données, la mise en service de l’administration et des services informatiques, la sécurité du réseau, afin d’éviter les fraudes et les violations de données. Par exemple, l’adresse de messagerie professionnelle, l’adresse e-mail est requise pour envoyer les notifications de contact de facturation au client ou, si vous payez par carte de crédit, des informations sont requises pour lever des tickets de support lorsque vous accédez au support client. |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou télémétrie de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Senso surveille les messages de conversation par rapport aux bibliothèques de détection des menaces par mot clé et image.  Si une correspondance se produit, nous logons les informations suivantes sur le déclencheur de violation ; Heure et date, ID de site, expression/image, gravité, De, À, Nom du canal, État et déclenchement de la bibliothèque pour révision par l’utilisateur final.  Nous ne conserverons les informations d’identification des informations d’identification que tant que nécessaire pour remplir les objectifs que nous avons collectés, y compris pour répondre à toutes les exigences légales, opérationnelles, comptables ou de rapport.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Accès limité aux développeurs senior, à l’adresse IP verrouillée, à l’authentification à 2 facteurs et aux pistes d’audit.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) de données apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Senso sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Autorisations d’accès en fonction du rôle |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/><br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
