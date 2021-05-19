---
title: Informations d’application pour SIGNL4 par Derdack SIGNL4
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour SIGNL4, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a619327000c93e3292e266c8b025034370a8b623
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553205"
---
# <a name="signl4"></a>SIGNL4

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: 6 août 2020</p>

* <a href="https://teams.microsoft.com/l/app/bd19c878-00b7-47cd-9b65-74a2def84427" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001239" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Derdack SIGNL4 à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | SIGNL4 |
| ID | WA200001239 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Derdack SIGNL4 |
| URL du site web partenaire | [https://www.signl4.com](https://www.signl4.com) |
| URL de la politique de confidentialité | [https://www.signl4.com/privacy-policy/](https://www.signl4.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://www.signl4.com/terms_of_use/](https://www.signl4.com/terms_of_use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Derdack SIGNL4 sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>Cette application n’utilise pas microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| En conséquence, l’adresse e-mail, l’adresse e-mail est nécessaire pour envoyer des notifications de facturation au client lorsqu’il utilise l’application. Twilio, numéros de téléphone, contenu d’alerte pour l’envoi d’alertes via SMS messages texte |  | Azure Management API, Azure Monitor Alerts sont collectés, Collection se produit parce que les systèmes envoie des notifications pour ces alertes |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Les informations d’adresse e-mail sont contenues dans les journaux. Des données supplémentaires sur le contenu d’alerte, soumises par l’organisation, peuvent également être incluses dans les journaux. Pour éviter cela, l’organisation peut résilier le compte dans l’application.
Les données dans les journaux sont nécessaires pour le support et les problèmes de dépannage que le client ma a avec l’application.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données sont stockées dans le centre de données Azure en Europe. L’accès à ce système est possible pour les administrateurs. 2FA en utilisant l’authentification AAD. Les clés d’accès aux comptes de stockage sont également utilisées pour gérer l’accès.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Oui

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

