---
title: Informations d’application pour OnePlaceMail pour Outlook par OnePlace Solutions
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour OnePlaceMail for Outlook, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5094d1ad5e7b028ac115529de16ddb9cbef2086f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552495"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail pour Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Janvier 31, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par OnePlace Solutions à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | OnePlaceMail pour Outlook |
| ID | WA104380723 |
| Office 365 clients soutenus | Outlook 2013 ou plus tard sur Windows, Outlook 2016 ou plus tard sur Mac, Outlook sur iOS, Outlook sur Android, Outlook sur le web |
| Nom de l’entreprise partenaire | OnePlace Solutions |
| URL du site web partenaire | [https://www.oneplacesolutions.com/](https://www.oneplacesolutions.com/) |
| URL de la politique de confidentialité | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL des conditions d’utilisation | [https://www.oneplacesolutions.com/oneplacemailapp-eula](https://www.oneplacesolutions.com/oneplacemailapp-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par OnePlace Solutions sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Délégué | Requis pour déterminer Teams l’utilisateur actuel est membre de. | Aucune | 44a72516-136f-4a55-ae26-ef09977230be |
>| Mail.ReadWrite.Shared | Délégué | Requis pour accéder aux propriétés du courrier pour définir SharePoint colonnes et ajouter le Transfert à SharePoint catégorie sur l’élément mail | Aucune | 44a72516-136f-4a55-ae26-ef09977230be |
>| MailboxSettings.ReadWrite | Délégué | Aucune donnée collectée ou utilisée, ceci est utilisé pour ajouter une catégorie à la liste de catégorie principale dans une boîte aux lettres des utilisateurs | Aucune | 44a72516-136f-4a55-ae26-ef09977230be |
>| Sites.ReadWrite.All | Délégué | Nécessaire pour définir des propriétés sur les éléments que l’application a téléchargés SharePoint. | Aucune | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.Read | Délégué | Requis pour l’authentification à la Graph Microsoft. | Les données suivantes sont stockées par l’application dans une base de données et sont utilisées pour le suivi des licences d’abonnement et d’utilisateur : Identifiant d’utilisateur, E-mail, Prénom, Nom de famille. | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | Délégué | Requis pour afficher l’image de profil de l’utilisateur dans le champ de ramasseur de personnes. | Aucune | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | Délégué | Requis pour afficher l’image de profil de l’utilisateur dans le champ de ramasseur de personnes. | Aucune | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadWrite.All | Délégué | Requis pour déterminer si le service Teams est activé au sein des utilisateurs Office 365 location. | Aucune | 44a72516-136f-4a55-ae26-ef09977230be |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les modules complémentaires intégrés à Microsoft 365 peuvent utiliser d’autres API Microsoft que Microsoft Graph pour recueillir ou traiter des informations organisationnelles identifiables (OII). Énumérez toutes les API Microsoft autres que Microsoft Graph utilisations de cette application.

>| **API** |  **L’ŒIL est-il recueilli?** |  **Quel OII est recueilli?** | **Justification de la collecte de l’ŒII?** | **OII est-il stocké ?** | **Justification pour stocker OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Oui | SharePoint URL, noms de bibliothèque/liste/dossier | Les informations organisationnelles accessibles sont utilisées pour faciliter le processus d’enregistrement des e-mails et des pièces jointes de Exchange à SharePoint. Ces données supplémentaires ne sont pas stockées au repos et sont cryptées en transit. Des exemples de ces données incluent les valeurs SharePoint colonnes telles que les valeurs de colonne Choix, les valeurs taxonomie, les noms de type de contenu, les noms de dossiers, les noms de site.  | Bien que ces données ne sont pas stockées ou collectées par l’application, elles peuvent apparaître dans la télémétrie/journaux où elles sont conservées pendant 90 jours. | Les données ne sont pas stockées |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Le service Chargify est utilisé pour la gestion des abonnements et la facturation. Pour la création d’abonnement in-app (gratuit), le prénom, le nom de famille, l’adresse e-mail de l’utilisateur sont partagés avec Chargify. Pour les abonnements achetés (qui supportent plusieurs utilisateurs licenciés), les détails individuels de l’utilisateur ne sont pas partagés avec le service Chargify. | Adresse de messagerie | Pour être en mesure de communiquer les événements du cycle de vie de l’abonnement à l’utilisateur |



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>EUII et OII apparaissent en télémétrie. Ces informations sont stockées dans Application Insights, cryptées au repos, contrôlées et supprimées après 90 jours

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données stockées dans l’application sont cryptées en transit et au repos. Nous comptons sur Office 365 pour nos applications, de sorte que nous ne stockons pas les mots de passe des utilisateurs dans notre système. L’accès aux données stockées/journaux/télémétrie est étroitement contrôlé par le personnel de l’administration interne ayant la nécessité d’accéder à l’information dans le but d’exécuter et de surveiller l’état de santé de l’application. Two-Factor'authentification appliquée à tout le personnel de l’administration interne.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par OnePlace Solutions sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’enregistrement des applications et d’autres critères d’identité.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Vous intégrez-vous à la plate-forme Microsoft Identify Platform (Azure AD)?  | Oui |
| Avez-vous examiné et respecté toutes les pratiques exemplaires applicables décrites dans la liste de vérification Plateforme d’identités Microsoft’intégration?  | Oui |
| Votre application utilise-t-elle MSAL (Microsoft Authentication Library) pour l’authentification ? | Oui |
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
