---
title: Informations d’application pour le signal dynamique par signal dynamique
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations disponibles sur la sécurité et la conformité pour Dynamic Signal, ses politiques de traitement des données, ses informations sur le catalogue d’applications Microsoft Cloud App Security et les informations de sécurité et de conformité dans le registre STAR de l’ASC.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0d3c59f6809bafe16eec2a1d709f40a980576b1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552225"
---
# <a name="dynamic-signal"></a>Signal dynamique

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur le: Décembre 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Vue dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Voir dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Dynamic Signal à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Signal dynamique |
| ID | WA200000102 WA20000102 |
| Office 365 clients soutenus | Microsoft Teams |
| Nom de l’entreprise partenaire | Signal dynamique |
| URL du site web partenaire | [https://dynamicsignal.com](https://dynamicsignal.com) |
| URL de la page Teams’informations d’application | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL de la politique de confidentialité | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL des conditions d’utilisation | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Dynamic Signal sur la façon dont cette application recueille et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Énumérez [toutes les autorisations microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) cette application nécessite.

>| **Permission**  | **Type d’autorisation (Délégué/Demande)** | **Les données sont-elles collectées? Justification pour le recueillir?** | **Les données sont-elles stockées ? Justification pour le stocker?** | **Id d’application AD Azure** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Délégué | Dynamic Signal synchronise l’utilisateur d’Azure AD à sa plate-forme pour permettre une activation et une désactivation simplifiées des utilisateurs en temps réel. Les données sont stockées dans Dynamic Signal pour permettre aux utilisateurs d’utiliser cette application pendant la synchronisation. | Lisez les autorisations d’un utilisateur spécifique pour synchroniser les utilisateurs de la plate-forme Dynamic Signal avec Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | Délégué | Dynamic Signal synchronise l’utilisateur d’Azure AD à sa plate-forme pour permettre une activation et une désactivation simplifiées des utilisateurs en temps réel. Les données sont stockées dans Dynamic Signal pour permettre aux utilisateurs d’utiliser cette application pendant la synchronisation. | Lisez les autorisations d’un utilisateur spécifique pour synchroniser les utilisateurs de la plate-forme Dynamic Signal avec Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | Délégué | Dynamic Signal synchronise l’utilisateur d’Azure AD à sa plate-forme pour permettre une activation et une désactivation simplifiées des utilisateurs en temps réel. Les données sont stockées dans Dynamic Signal pour permettre aux utilisateurs d’utiliser cette application pendant la synchronisation. | Conserver l’accès aux groupes et aux équipes du locataire. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | Délégué | Dynamic Signal synchronise l’utilisateur d’Azure AD à sa plate-forme pour permettre une activation et une désactivation simplifiées des utilisateurs en temps réel. Les données sont stockées dans Dynamic Signal pour permettre aux utilisateurs d’utiliser cette application pendant la synchronisation. | Authentifiez les utilisateurs avec l’application Dynamic Signal. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données organisationnelles avec un service non Microsoft, énumérez le service non Microsoft utilisé par l’application, quelles données sont transférées et justifiez pourquoi l’application doit transférer ces informations.

>Les produits non services Microsoft ne sont pas utilisés.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations identifiables de l’utilisateur final (EUII) : la liste (prénom, nom de famille, nom d’affichage, adresse e-mail) de n’importe quel membre de l’équipe ou chat à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à l’EUII?**  | **L’EUII est-il stocké dans la base de données?** | **Justification du stockage de l’EUII ?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| openid se connecte à l’aide d’openid directory.readwrite.all accès au domaine et aux groupes du locataire, ajouter une application à un offline_access de conserver l’accès aux groupes et équipes du locataire | openid Permettre l’authentification indépendante. directory.readwrite.all accès au domaine et aux groupes du locataire, ajouter une application à une offline_access conserver l’accès aux groupes et équipes du locataire Note: L’application Dynamic Signal utilise le bot équipes pour appliquer les groupes et les autorisations créées dans Dynamic Signal à Teams de sorte qu’un utilisateur actif dans Dynamic Signal aura accès aux mêmes groupes et utilisateurs qu’au sein de Teams. |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations organisationnelles identifiables (OII) ou des informations identifiables de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de conservation et de suppression ?

>L’application et la plate-forme dynamic signal utilisent les informations utilisateur pour faciliter l’intégration Microsoft Teams. Ces informations sont disponibles pour les utilisateurs avec les autorisations appropriées au sein de la plate-forme Dynamic Signal. Les informations pertinentes sont le nom, le nom d’affichage et l’e-mail. Ces informations sont stockées dans les journaux de plate-forme Dynamic Signal conformément à la stratégie de l’organisation respective avec la licence Signal Dynamique.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels des données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple la suppression, la conservation, la vérification, l’archivage, la politique de l’utilisateur final, etc.

>Les données PII collectées lors de l’enregistrement et stockées dans la plate-forme Dynamic Signal incluent : Prénom, Nom de famille, E-mail/Identificateur et tous les champs personnalisés qui sont mis en place par la marque et/ou les partenaires de l’agence. Lorsque les membres utilisent Facebook ou Twitter à l’aide d’oAuth Registration, certaines des données utilisateur exposées sont présentées à la plate-forme Dynamic Signal pour pré-remplir les données. Ces données incluent le nom, l’emplacement et la photo. Les utilisateurs ont le contrôle sur les informations et les données présentées aux utilisateurs sur les pages bio de la communauté. Les membres peuvent choisir de charger des photos personnelles ou de marque, de connecter des comptes/canaux sociaux et d’utiliser/points du programme qui seront présentés dans la page bio.

#### <a name="human-review-of-organizational-information"></a>Examen humain de l’information organisationnelle

Les humains participent-ils à l’examen ou à l’analyse des données d’information organisationnelle identifiables (OII) qui sont recueillies ou stockées par cette application?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security apparaissent](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security information' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

