---
title: Informations d’application pour lucidchart diagrams for PowerPoint par Lucid Software Inc
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour lucidchart Diagrams for PowerPoint, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 024b2e925ba84967bf40754908a8d98baa1d705f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553605"
---
# <a name="lucidchart-diagrams-for-powerpoint"></a>Diagrammes de Lucidchart pour PowerPoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380117" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Lucid Software Inc à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Diagrammes de Lucidchart pour PowerPoint |
| ID | WA104380117 |
| Office 365 clients soutenus | PowerPoint 2016 ou plus tard sur Mac, PowerPoint sur le web, PowerPoint 2013 ou plus tard sur Windows |
| Nom de l’entreprise partenaire | Lucid Software Inc |
| URL du site web partenaire | [https://www.lucidchart.com/](https://www.lucidchart.com/) |
| URL de la politique de confidentialité | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL des conditions d’utilisation | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Lucid Software Inc sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Délégué | Nom et adresse e-mail. | Les autorisations d’e-mail, d’openid et de profil permettent à Lucidchart de générer un jeton openid pour un utilisateur et d’obtenir suffisamment d’informations de base sur l’utilisateur pour enregistrer un compte Lucidchart pour eux si nécessaire. Afin de vérifier les données qui reviennent de Microsoft, nous faisons une demande pour obtenir la clé publique avec laquelle leur réponse est signée. Aucune autre donnée n’est reçue ou envoyée à Microsoft dans le cadre de notre flux SSO. |  |
>| openid | Délégué | Nom et adresse e-mail. | Les autorisations d’e-mail, d’openid et de profil permettent à Lucidchart de générer un jeton openid pour un utilisateur et d’obtenir suffisamment d’informations de base sur l’utilisateur pour enregistrer un compte Lucidchart pour eux si nécessaire. Afin de vérifier les données qui reviennent de Microsoft, nous faisons une demande pour obtenir la clé publique avec laquelle leur réponse est signée. Aucune autre donnée n’est reçue ou envoyée à Microsoft dans le cadre de notre flux SSO. |  |
>| profil | Délégué | Nom et adresse e-mail. | Les autorisations d’e-mail, d’openid et de profil permettent à Lucidchart de générer un jeton openid pour un utilisateur et d’obtenir suffisamment d’informations de base sur l’utilisateur pour enregistrer un compte Lucidchart pour eux si nécessaire. Afin de vérifier les données qui reviennent de Microsoft, nous faisons une demande pour obtenir la clé publique avec laquelle leur réponse est signée. Aucune autre donnée n’est reçue ou envoyée à Microsoft dans le cadre de notre flux SSO. |  |

#### <a name="data-access-using-other-microsoft-apis"></a>Accès aux données à l’aide d’autres API Microsoft

Les applications et les modules complémentaires intégrés à Microsoft 365 peuvent utiliser d’autres API Microsoft que Microsoft Graph pour recueillir ou traiter des informations organisationnelles identifiables (OII). Énumérez toutes les API Microsoft autres que Microsoft Graph utilisations de cette application.

>| **API** |  **L’ŒIL est-il recueilli?** |  **Quel OII est recueilli?** | **Justification de la collecte de l’ŒII?** | **OII est-il stocké ?** | **Justification pour stocker OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Interface API JavaScript pour Office | Oui | Nous utilisons le Office OneDrive javascript SDK à partir d’ouvrir le OneDrive de fichiers à l’aide OneDrive.open(). Nous ne générons aucun jeton d’accès et nous ne faisons aucune demande OneDrive’API de notre pays; le OneDrive choix de fichiers SDK le fait pour nous. Nous ne voyons que les noms de fichiers que l’utilisateur choisit. |  | Si l’utilisateur sélectionne un fichier à l’aide OneDrive de fichier, nous stockons le nom du fichier. |  |

#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>| **Tous les services Microsoft OII non services Microsoft sont transférés à** |  **Quel OII est transféré?** | **Justification du transfert d’OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Les données lucidchart sont stockées dans AWS. |  | Nous n’utilisons pas d’API Microsoft. Nous utilisons openID pour obtenir des données utilisateur de base pour effectuer SSO. Nous utilisons leur API de sélection de fichiers, mais cela ne nous donne pas accès aux fichiers de l’utilisateur autres que ceux qu’ils nous soumettent par l’intermédiaire du cueilleur. |



#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>Nous connectons des adresses e-mail et IP pour des raisons de sécurité et de support. Tous les journaux d’accès aux &amp; journaux enregistrés sont en fait immuables dans un système tiers. L’accès aux journaux nécessite l’AMF.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données lucidchart sont stockées dans AWS. Il est crypté au repos et en transit. Lucidchart utilise les règles du moindre privilège et de l’AMF.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

