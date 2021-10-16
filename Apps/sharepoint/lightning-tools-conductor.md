---
title: Informations sur l’application pour les outils d’éclairage de flash à l’aide des outils d’éclairage
ms.author: elmalova
author: elenamalova
ms.date: 09/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour les outils d’éclairage - Flash - Vitesse, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9541cab6ba5fcd7da59cfe43c89e2e3bf3fceab9
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412043"
---
# <a name="lightning-tools-lightning-conductor"></a>Flash d’outils - Flash

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001926" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par les outils De flash à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Flash d’outils - Flash |
| ID | WA200001926 |
| Office 365 clients pris en charge | SharePoint 2016 ou ultérieure |
| Nom de la société partenaire | Outils De flash |
| URL du site web partenaire | [https://lightningtools.com](https://lightningtools.com) |
| URL de la politique de confidentialité | [https://lightningtools.com/lightning-conductor-cswp-privacy...](https://lightningtools.com/lightning-conductor-cswp-privacy-policy) |
| URL des conditions d’utilisation | [https://lightningtools.com/lightning-tools-lightning-conduc...](https://lightningtools.com/lightning-tools-lightning-conductor-client-side-web-part-software-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par les outils De flash sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | application | Pour interroger et signaler des informations de calendrier | L’assistant de flash n’utilise pas de base de données ni de données de magasin. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Contacts.Read | application | Aucune donnée n’est collectée ou stockée. Les données sont utilisées pour afficher le nom d’affichage des contacts des utilisateurs actuels | L’assistant de flash n’utilise pas de base de données ni de données de magasin. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Directory.Read.All | application | Afficher les utilisateurs dans la lumière | L’assistant de flash n’utilise pas de base de données ni de données de magasin. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Files.Read.All | application | Afficher OneDrive fichiers de l’éclairage | L’assistant de flash n’utilise pas de base de données ni de données de magasin. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Mail.Read | application | Si la requête de l’assistant De flash affiche des messages à partir de la boîte aux lettres des utilisateurs actuels | L’assistant de flash n’utilise pas de base de données ni de données de magasin. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| People.Read.All | application | Pour afficher l’affichage des personnes dans l’Assistant Lumière si vous interrogez des utilisateurs en tant que membres d’un site. | L’assistant de flash n’utilise pas de base de données ni de données de magasin. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Presence.Read.All | application | Pour afficher la présence des utilisateurs dans la carte de personnes | L’assistant de flash n’utilise pas de base de données ni de données de magasin. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Sites.Read.All | application | Pour éumer les sites dans la vue d’arborescence de l’arborescence De l’Arbre de la lumière | L’assistant de flash n’utilise pas de base de données ni de données de magasin. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.



#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Aucun OII ou EUII n’apparaît dans la télémétrie ou les journaux des applications.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Les données au sein de l’application résident dans le client. Les outils De flash ne stockent ni ne traitéent aucune donnée en dehors du client. 

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par les outils De flash sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

