---
title: Informations sur les applications pour Viima par Viima Solutions Oy
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Viima, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 703c1bf3b2980fae538af764bfa1d2024a86a366
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553975"
---
# <a name="viima"></a>Viima

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Novembre 17, 2020</p>

* <a href="https://teams.microsoft.com/l/app/2bffa4e8-aac7-4d2e-976d-5a7db5c4b768" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001589" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Viima Solutions Oy à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Viima |
| ID | WA200001589 WA200001589 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Viima Solutions Oy |
| URL du site web partenaire | [https://www.viima.com/](https://www.viima.com/) |
| URL de la page Teams’informations d’application | [https://www.viima.com/product](https://www.viima.com/product) |
| URL de la politique de confidentialité | [https://www.viima.com/privacy-policy](https://www.viima.com/privacy-policy) |
| URL des conditions d’utilisation | [https://www.viima.com/terms](https://www.viima.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Viima Solutions Oy sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Délégué |  Prénoms et noms de famille, adresse UPN/e-mail, emplacement, lieu, département, emplacement du bureau. Ceux-ci sont utilisés pour connecter l’utilisateur et lui fournir des informations de profil de base dans l’application. | permet à l’utilisateur de se connecter et donne à l’application l’accès à son UPN et à ses informations de profil de base pour permettre une connexion silencieuse | b8ea7030-ce4d-4ecd-98d7-dc16d8298d1b |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Le nom de l’organisation, l’id de l’organisation Viima, les e-mails et les identifiants des utilisateurs finaux apparaissent dans les journaux. ISO27001 compatible 3ème partie vérifié contrôles en place pour un accès restreint à, et archivistique / suppression de ces données.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données sont stockées dans AWS (Irlande). L’accès aux données est limité aux seuls employés autorisés de maintenance et de soutien technique qui ont reçu une formation appropriée et qui sont protégés par un certain nombre de mesures de sécurité, telles que la 2FA, la portée IP protégée (accès uniquement à partir du réseau d’entreprise), etc. Les mesures sont compatibles ISO27001 et auditées par une tierie partie.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/33480' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/33480" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Viima Solutions Oy sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Non |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle le moins d’autorisations de privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles fidèlement les autorisations que votre application demandera de manière dynamique et progressive ? | Oui |
| Votre application prend-elle en charge la multi-location ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Oui |
| Possédez-vous l’ensemble de l’identifiant de ressources unifié (URI) redirigé enregistré pour votre application ? | Oui |
| Pour votre application, qu’évitez-vous d’utiliser ? | - Wildcard rediriger les URL,<br/>- OAuth2 Implicite Flow, sauf si nécessaire pour un SPA<br/>- Flux d’identification de mot de passe propriétaire de ressources (ROPC) |
| Votre application expose-t-elle des API Web ? | Oui |
| Votre modèle d’autorisation ne permet-il aux appels de réussir que si l’application client reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle des API de prévisualisation ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
