---
title: Informations d’application pour Myfone par Flexfone
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Myfone, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 37967a116553b7c7b83b1809c9b23a56822be5ed
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282819"
---
# <a name="myfone"></a>Myfone

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5f447fa4-da1f-4651-a0da-d2488a404c19" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000716" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Flexfone à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Myfone |
| ID | WA200000716 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Flexfone |
| URL du site web partenaire | [https://flexfone.dk](https://flexfone.dk) |
| URL de la Teams d’informations sur l’application | [https://faq.flexfone.dk/da](https://faq.flexfone.dk/da) |
| URL de la politique de confidentialité | [https://flexfone.dk/privatlivs-og-cookiepolitik](https://flexfone.dk/privatlivs-og-cookiepolitik) |
| URL des conditions d’utilisation | [https://flexfone.dk/Content/pdf/Slutkundebetingelser.pdf](https://flexfone.dk/Content/pdf/Slutkundebetingelser.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Flexfone sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | délégué | Les calendriers sont utilisés pour que les utilisateurs puissent afficher leurs calendriers à leurs collègues et utiliser les réunions pour la configuration de leur téléphonie | Les calendriers sont utilisés pour que les utilisateurs puissent afficher leurs calendriers à leurs collègues et utiliser les réunions pour la configuration de leur téléphonie | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| Contacts.Read | délégué | Les contacts des utilisateurs peuvent être stockés s’ils souhaitent les afficher dans l’application afin de faciliter la numérotation des contacts | Les contacts des utilisateurs peuvent être stockés s’ils souhaitent les afficher dans l’application afin de faciliter la numérotation des contacts | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| User.Read | délégué | La lecture utilisateur dans cette application est utilisée à des fins d’identification. | La lecture utilisateur dans cette application est utilisée à des fins d’identification. | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| User.Read | délégué | Nous ne stockons pas les données. L’application est simplement utilisée à des fins d’authentification | Nous ne stockons pas les données. L’application est simplement utilisée à des fins d’authentification | [f0199b83-0ca3-4b41-a23b-d9b234484438](https://docs.microsoft.com/microsoft-365-app-certification/azure/f0199b83-0ca3-4b41-a23b-d9b234484438) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| EWS. AccessAsUser.All | Oui | Nom de la société, noms d’employés et numéros de téléphone | Pour être en mesure d’afficher les données aux utilisateurs dans l’application et de les utiliser | Nom de la société, noms d’employés et numéros de téléphone | Pour être en mesure d’afficher les données aux utilisateurs dans l’application et de les utiliser |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Communications du ruban, Voxxa, team.blue, Fakturaservice.dk A/S, Élastique | Nom de la société, noms d’employés et numéros de téléphone | Le Ruban fournit notre Teams SBC. Voxotte est utilisé pour les numéros internationaux, mais uniquement si vous en avez. team.blue est notre fournisseur d’hébergement. FakturaService.dk A/S est utilisé pour la facturation. Élastique utilisé pour la journalisation |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Chaque utilisateur est un employé d’une société qui utilise nos services. Un administrateur peut supprimer et modifier des données. Les DPA sont également en place avant que les utilisateurs finaux n’y accèdent

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Flexfone sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription de l’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous La plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Authentification multifacteur |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/>- OAuth2 Implicit Flow, sauf si requis pour une SPA<br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Oui |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
