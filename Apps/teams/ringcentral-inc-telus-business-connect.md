---
title: Informations sur l’application POUR LES ENTREPRISES CONNECTER entreprise par RingCentral, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour LA CONNECTER BUSINESS, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 465b92171bb82a617d2369298037c06fce1fa84a
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413446"
---
# <a name="telus-business-connect"></a>TELUS Business Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 4, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d5001eed-f63e-4a7d-9b49-bf8272c934cd" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002300" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par RingCentral, Inc. à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | TELUS Business Connect |
| ID | WA200002300 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | RingCentral, Inc. |
| URL du site web partenaire | [https://www.ringcentral.com](https://www.ringcentral.com) |
| URL de la Teams d’informations sur l’application | [https://appsource.microsoft.com/en-us/product/office/WA2000...](https://appsource.microsoft.com/en-us/product/office/WA200002300) |
| URL de la politique de confidentialité | [https://www.telus.com/en/about/privacy/](https://www.telus.com/en/about/privacy/) |
| URL des conditions d’utilisation | [https://telus.com/BusinessConnect/ServiceTerms](https://telus.com/BusinessConnect/ServiceTerms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par RingCentral, Inc. sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | délégué |  Permet à l’application d’envoyer un événement d’invitation à une réunion via son calendrier | Aucune | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read | délégué |  Permet à l’application de lire un&#8217;profil de base (e-mail, nom) afin d’obtenir des correspondances de contact à notre fin. Permet également aux utilisateurs de se connecter et de lier leur compte O365 au compte RingCentral |  Email, first name, last name | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read.All | délégué | Permet à l’application de lire le profil complet d’un utilisateur avec des numéros de téléphone afin d’effectuer des appels téléphoniques avec nos services. | Aucune | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| offline_access | délégué |  Permet à l’application d’obtenir et de mettre à jour le jeton oauth |  Jeton d’accès, jeton d’actualisation pour accéder à l’API Graph MS | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Lorsque nous utilisons une autre organisation, nous contrôlons toujours vos informations personnelles. Nous avons également des contrôles stricts en place pour nous assurer qu&#8217;est correctement protégé. Enfin, la section ci-dessus décrit les situations dans lesquelles vos informations personnelles sont partagées avec d’autres organisations, organismes publics et organismes chargés de l’application de la loi.  Lorsque nous partageons vos informations avec d’autres organisations, nous&#8217;nous assurerons qu’elles&#8217;protégées, aussi loin que possible.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par RingCentral, Inc. sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

