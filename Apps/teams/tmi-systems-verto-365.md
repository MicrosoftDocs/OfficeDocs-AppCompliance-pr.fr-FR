---
title: Informations sur les applications pour Verto 365 par les systèmes TMI
ms.author: elmalova
author: elenamalova
ms.date: 09/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Verto 365, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c82879bb30fc4c24b6e4f4bdb9103a2fe2290286
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414420"
---
# <a name="verto-365"></a>Verto 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b27c082b-9d45-490a-b8bb-8dcda46c73f3" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003230" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par les systèmes TMI à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Verto 365 |
| ID | WA200003230 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Systèmes TMI |
| URL du site web partenaire | [https://www.vertocloud.co.uk](https://www.vertocloud.co.uk) |
| URL de la Teams d’informations sur l’application | [https://www.vertocloud.com](https://www.vertocloud.com) |
| URL de la politique de confidentialité | [https://vertocloud.co.uk/privacy-policy/](https://vertocloud.co.uk/privacy-policy/) |
| URL des conditions d’utilisation | [https://vertocloud.co.uk/terms-and-conditions/](https://vertocloud.co.uk/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par les systèmes TMI sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **Azure AD ID d’application** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | délégué | Informations générales sur l’utilisateur, prénom, e-mail de &amp; nom. Utilisé pour créer un compte. | Prénom, Nom, E-mail, OID. Utilisé pour créer un compte dans la base de données, OID est utilisé pour associer une connexion à un compte Verto. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| email | délégué | Informations générales sur l’utilisateur, prénom, e-mail de &amp; nom. Utilisé pour créer un compte. | Prénom, Nom, E-mail, OID. Utilisé pour créer un compte dans la base de données, OID est utilisé pour associer une connexion à un compte Verto. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| offline_access | délégué | Utilisé pour obtenir des jetons d’actualisation et persister la connexion | S/O | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| openid | délégué | Informations générales sur l’utilisateur, prénom, e-mail de &amp; nom. Utilisé pour créer un compte. | Prénom, Nom, E-mail, OID. Utilisé pour créer un compte dans la base de données, OID est utilisé pour associer une connexion à un compte Verto. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| profil | délégué | Informations générales sur l’utilisateur, prénom, e-mail de &amp; nom. Utilisé pour créer un compte. | Prénom, Nom, E-mail, OID. Utilisé pour créer un compte dans la base de données, OID est utilisé pour associer une connexion à un compte Verto. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>Les éléments services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nom de l’organisation, prénom, nom, adresse de messagerie de l’entreprise. Les stratégies de rétention sont flexibles en fonction des stratégies internes des clients, mais toujours dans le cadre du R GDPR.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Autorisations des utilisateurs finaux via la liste de contrôle d’accès. Les administrateurs peuvent supprimer ou masquer des données, le journal d’audit ne peut pas être modifié du tout par les utilisateurs finaux.

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par les systèmes TMI sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Intégrez-vous la plateforme d’identification Microsoft (Azure AD) ?  | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle Plateforme d'identités Microsoft’intégration ?  | Oui |
| Votre application utilise-t-elle MSAL (Bibliothèque d’authentification Microsoft) pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application demande-t-elle des autorisations de moindre privilège pour votre scénario ? | Oui |
| Les autorisations enregistrées statiquement de votre application reflètent-elles précisément les autorisations que votre application demande dynamiquement et incrémentiellement ? | Oui |
| Votre application prend-elle en charge l’location multiple ? | Oui |
| Votre application a-t-elle un client confidentiel ? | Non |
| Êtes-vous propriétaire de tous les URI (Unified Resource Identifier) de redirection enregistrés pour votre application ? | Oui |
| Pour votre application, qu’est-ce que vous évitez d’utiliser ? | - URIs de redirection générique,<br/><br/>- Flux ROPC (Resource Owner Password Credential) |
| Votre application expose-t-elle des API web ? | Oui |
| Votre modèle d’autorisation autorise-t-il uniquement les appels à réussir si l’application cliente reçoit le consentement approprié ? | Oui |
| Votre application utilise-t-elle les API d’aperçu ? | Non |
| Votre application utilise-t-elle des API dépréciées ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

