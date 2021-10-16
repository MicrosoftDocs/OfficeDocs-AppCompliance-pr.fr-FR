---
title: Informations sur l’application pour le connecteur VOIP cloud DE LATP par COMMUNICATIONS POP
ms.author: elmalova
author: elenamalova
ms.date: 10/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour le connecteur VOIP cloud POP, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 42930c1020e86aeb6f55fb81929f30285e17dae3
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414971"
---
# <a name="popp-cloud-voip-connector"></a>CONNECTEUR VOIP cloud POPP

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 20, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b8e57f6b-31cf-468e-9e99-81f0395cb1f9" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003306" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par LES COMMUNICATIONS POP à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | CONNECTEUR VOIP cloud POPP |
| ID | WA200003306 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Communications POPP |
| URL du site web partenaire | [https://popp.com](https://popp.com) |
| URL de la politique de confidentialité | [https://popp.com/terms/privacy-policy/](https://popp.com/terms/privacy-policy/) |
| URL des conditions d’utilisation | [https://popp.com/pvnterms/](https://popp.com/pvnterms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par les communications POP sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | délégué | ID utilisateur et noms d’affichage des membres du canal actuel. L’application l’utilise pour présenter à l’utilisateur la liste des membres du canal à appeler. | Le métaswitch ne stocke pas ces données. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| Chat.Read | délégué |  Quelles données sont collectées ou utilisées ? Ajoutez une justification pour la collecte ou l’utilisation des données. ID utilisateur et noms d’affichage des membres de la conversation en cours. L’application l’utilise pour présenter à l’utilisateur une liste de membres de conversation à appeler. | Le métaswitch ne stocke pas ces données. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| TeamMember.Read.All | délégué | ID d’utilisateur et noms d’affichage des membres de l’équipe actuelle. L’application l’utilise pour présenter à l’utilisateur la liste des membres de l’équipe à appeler. | Le métaswitch ne stocke pas ces données. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| User.Read.All | délégué |  Quelles données sont collectées ou utilisées ? Ajoutez une justification pour la collecte ou l’utilisation des données. Numéros de téléphone professionnels et mobiles des utilisateurs. Cette procédure est requise pour que les appels téléphoniques vers ces numéros soient lancés. |   Le métaswitch ne stocke pas ces données | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| openid | délégué | Jeton d’autorisation pour l’utilisateur, autorisant l’application à accéder aux autres points de terminaison Graph API répertoriés en leur nom. | Le métaswitch ne stocke pas ces données. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les compléments créés sur Microsoft 365 peuvent utiliser des API Microsoft supplémentaires autres que Microsoft Graph pour collecter ou traiter des informations d’identification organisationnelle (OII). List any Microsoft APIs other than Microsoft Graph this app uses.

>| **API** |  **OII est-il collecté ?** |  **Qu’est-ce qu’OII collecté ?** | **Justification de la collecte des OII ?** | **OII est-il stocké ?** | **Justification du stockage des OII ?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Plateforme d’identités Microsoft | Non |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Réseaux metaswitch et communications POP | L’OII suivant est transféré vers le serveur de bot hébergé MCT : les ID d’équipe d’ID de client Azure AD Canal/ID de conversation Le contenu du message est également transféré, ce qui peut éventuellement inclure OII Les OII suivants peuvent être transférés vers l’API JSON CommPortal : Téléphone nombres d’utilisateurs dans un groupe d’entreprise Les domaines des adresses e-mail adresses IP des utilisateurs | Ajoutez une justification pour la raison pour laquelle vous devez transférer OII L'&#8217;l’objectif principal de l’application est de faciliter les appels téléphoniques. Si un utilisateur tente d’effectuer un appel téléphonique, ces informations doivent être fournies pour se connecter à son compte CommPortal et corréler l’appel à l’utilisateur correct.  L’OII transféré vers le serveur de bot hébergé MCT est intégré à l’API Bot Framework qui est utilisée pour l’intégration à Teams et ne peut pas être évitée. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| L'&#8217;principale de l’application est de faciliter les appels téléphoniques. Si un utilisateur tente d’effectuer un appel téléphonique, l’EUII de toutes les parties de l’appel doit être fourni pour établir l’appel entre les utilisateurs téléphoniques corrects. | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Metaswitch et POP ne stockent pas les données plus longtemps que la nécessité immédiate de charger les pages web MCT à partir de CommPortal Web. Les données ne sont pas conservées et sont immédiatement supprimées.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par LES COMMUNICATIONS POP sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Non |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Liste des types de stratégies pris en charge | Stratégies d’accès conditionnel dans la mesure où cette prise en charge est fournie automatiquement par la bibliothèque MSAL utilisée pour l’authentification.  |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Non |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/><br/> |
| Votre application expose-t-elle des API web ? | Non |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

