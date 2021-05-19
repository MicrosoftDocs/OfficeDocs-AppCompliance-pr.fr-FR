---
title: Informations d’application pour HeyTaco! par HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour HeyTaco!, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 66739977ba4aa3eef7456d4ec60530f94065a2b9
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553125"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur sur: Novembre 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par HeyTaco! à Microsoft:

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | HeyTaco! |
| ID | WA200001346 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | HeyTaco! |
| URL du site web partenaire | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL de la politique de confidentialité | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL des conditions d’utilisation | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Cette information a été fournie par HeyTaco! sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Délégué | utilisé pour faire correspondre l’utilisateur pour les transferts de données de Slack à MS Teams | utilisé pour faire correspondre l’utilisateur pour les transferts de données de Slack à MS Team | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| openid | Délégué | utilisé pour signer la personne dans HeyTaco! | utilisé pour signer la personne dans HeyTaco! | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| profil | Délégué | utilisé pour capturer le nom d’utilisateur, l’image de profil, le décalage horaire, l’id du locataire et l’id de l’équipe | utilisé pour capturer le nom d’utilisateur, avatar, décalage horaire, id locataire, et id de l’équipe | be8d11cf-265a-4974-9912-4ff28c29fc21 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Pour dire à l’utilisateur qu’ils ont reçu un taco et de qui il vient. | Adresse e-mail (pour les tacos de migration d’une plate-forme à l’autre) Nom (pour saluer l’utilisateur) Image de profil (pour affichage au classement) Fuseau horaire (pour afficher correctement les tacos donnés sur la page d’activité) Id locataire (Pour l’agrégation des données par locataire) Id d’équipe (Pour l’agrégation des données par équipe)  |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>EUII et OII ne sont connectés à aucune exploitation forestière. Seuls les types d’erreurs et d’action.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>HeyTaco! bases de données et sauvegardes de données sont hébergées sur Amazon Web Services (AWS). 

Les opérations des centres de données d’Amazon ont été accréditées dans le cadre de l’ISO 27001 , soc 1 et SOC 2/SSAE 16/ISAE 3402 (précédemment SAS 70 Type II), PCI Niveau 1 , FISMA Modéré, et Sarbanes-Oxley (SOX).

Lorsque vous soumettez des informations via notre service, vos informations sont protégées et cryptées au repos et en transit par le biais de connexions sécurisées. Nous mettons en œuvre diverses mesures de sécurité pour assurer la sécurité de vos renseignements personnels.

Nous avons mis en place une gestion privilégiée de l’accès pour protéger les données sur nos serveurs.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

