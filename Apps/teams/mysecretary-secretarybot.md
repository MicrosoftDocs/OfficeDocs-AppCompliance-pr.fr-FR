---
title: Informations de demande pour SecretaryBot par MySecretary
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour SecretaryBot, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bff3e6ebffc94861dc4112375ac943124b4fe386
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551884"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par MySecretary à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | SecretaryBot |
| ID | WA104381085 WA104381085 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | MySecretary |
| URL du site web partenaire | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| URL de la page Teams’informations d’application | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| URL de la politique de confidentialité | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par MySecretary sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read.Shared | Délégué |  | Récupérez les informations sur le temps libre des utilisateurs et de leurs collègues. |  |
>| Calendars.ReadWrite | Délégué |  | Envoyez la demande de réunion au lieu de l’utilisateur. |  |
>| MailboxSettings.Read | Délégué | Stockez le langage pour afficher le langage correct. Économisez le fuseau horaire pour appeler MS Graph api calendrier correctement | Récupérez le langage et le paramètre de fuseau horaire de l’utilisateur. |  |
>| People.Read | Délégué |  | Essayez de trouver des collègues qui ont de solides relations avec l’utilisateur. |  |
>| User.Read | Délégué | Stockez le nom d’utilisateur, la ville, le pays et le langauge pour l’analyse des utilisateurs. Stockez les e-mails pour contacter le client. Nous n’avons jamais utilisé d’adresse e-mail, mais nous pouvons l’utiliser pour le support. | Essayez de trouver le pays de l’utilisateur et la langue préférée. Il est utilisé pour la sauvegarde pour MailboxSettings.Read. |  |
>| email | Délégué | Voir ci-dessus. | Pour stocker le courrier électronique. |  |
>| openid | Délégué |  | Pour l’authentification OpenID. |  |
>| profil | Délégué | Enregistrez OID pour identifier l’id unique de l’utilisateur dans le système d’identité MS. | Obtenir le nom d’utilisateur et OID. Essayez d’utiliser OID pour vous connecter Outlook Addin à l’avenir. |  |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Utilisez cette infromation pour planifier la réunion d’équipe | Non |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Les données OII ou EUII apparaissent dans la télémétrie ou les journaux.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Nous ne fournissons pas encore de contrôle administratif aux utilisateurs finaux, mais si les utilisateurs finaux nous demandent de supprimer des données, nous pouvons suivre leur demande.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

