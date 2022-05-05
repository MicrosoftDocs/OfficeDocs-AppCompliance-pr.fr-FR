---
title: Informations sur l’application pour Guru par Guru Technologies
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Guru, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b623d0d92400219e5ad31d58ade4d98409aced98
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226558"
---
# <a name="guru"></a>Guru

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur : 1er mars 2021</p>

* <a href="https://teams.microsoft.com/l/app/094bf90e-e413-4740-b2dc-68d624d0e40e" target="_blank">Afficher dans Teams magasin</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001719" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Guru Technologies à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Guru |
| ID | WA200001719 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Guru Technologies |
| URL du site web du partenaire | [https://www.getguru.com](https://www.getguru.com) |
| URL de Teams page d’informations sur l’application | [https://www.getguru.com/integrations/microsoft-teams](https://www.getguru.com/integrations/microsoft-teams) |
| URL de la politique de confidentialité | [https://www.getguru.com/privacy/](https://www.getguru.com/privacy/) |
| URL des conditions d’utilisation | [https://www.getguru.com/terms-of-service](https://www.getguru.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Guru Technologies sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>Cette application n’utilise pas Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quel OII est transféré ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Application de l’utilisateur final et bases de données internes de Guru | lorsqu’un utilisateur ou une entreprise configure l’application Guru pour Teams, les informations courantes telles que le nom d’utilisateur, l’e-mail et le nom d’entreprise associés à leur profil utilisateur sont enregistrées et accessibles par Guru. | Étant donné qu’un utilisateur doit disposer à la fois d’un compte Teams et d’un compte Guru pour utiliser l’intégration, nous suivons et suivons les utilisateurs qui activent l’intégration pour aider à fournir un support et une gestion à ces utilisateurs. |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre de l’équipe d’une équipe ou d’une conversation à laquelle elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Lorsqu’un utilisateur ou une entreprise configure l’application Guru pour Teams, les informations courantes telles que le nom d’utilisateur, l’e-mail et le nom d’entreprise associés à leur profil utilisateur sont enregistrées et accessibles par Guru. Lors d’un arrêt de compte, les données sont conservées pendant 90 jours, puis supprimées. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>L’équipe de Guru Paramètres permettre aux administrateurs d’une équipe de déterminer les contrôles de groupe et d’accès/rôle à approvisionner par collection, avec la possibilité d’ajouter, de supprimer et de réaffecter des cartes à d’autres personnes. Enterprise clients qui ont déployé l’authentification unique bénéficient également de la console du fournisseur d’authentification unique pour intégrer/déconnecter et établir des groupes via SCIM

#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans l’examen ou l’analyse des données d’information d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informations d’identité

Ces informations ont été fournies par Guru Technologies sur la façon dont cette application gère l’authentification, l’autorisation, les meilleures pratiques d’inscription d’application et d’autres critères d’identité.

| **Information** | **Response** |
|:----------------|:-------------|
| Intégrez-vous à La plateforme d’identification Microsoft (Azure AD) ?  | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
