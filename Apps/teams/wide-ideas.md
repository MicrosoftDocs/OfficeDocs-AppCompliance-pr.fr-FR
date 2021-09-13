---
title: Informations sur les applications pour les idées larges par idées larges
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour les idées larges, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le Registre CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1e73a7aebbaaffa12572717f7a4a9968fd5667f7
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282022"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Afficher dans Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Les idées larges à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | Wide Ideas |
| ID | WA200000819 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Wide Ideas |
| URL du site web partenaire | [https://getwideideas.com](https://getwideideas.com) |
| URL de la politique de confidentialité | [https://getwideideas.com/privacy-policy/](https://getwideideas.com/privacy-policy/) |
| URL des conditions d’utilisation | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474849364/Product_42949683744/Asset_0831a14b-e5df-4f0b-8385-3c06edaeceeb/GENERALTERMSANDCONDITIONSWideI.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Gestion des données par l’application

Ces informations ont été fournies par Wide Ideas sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/graph/permissions-reference) this app requires.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-elles stockées ? Justification de son stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | application | Nous allons enregistrer l’ID de groupe et les utilisateurs appartenant à quels groupes | Permet à l’application de lire les données dans l’annuaire de notre organisation Clients, telles que les utilisateurs et les groupes.  | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |
>| Group.ReadWrite.All | application | Nous allons enregistrer l’ID de canal associé au groupe. | Permet aux utilisateurs de créer des équipes, des canaux et des onglets à l’Microsoft Teams à partir du portail client. Cela permet également aux utilisateurs de synchroniser des équipes existantes dans Microsoft Teams dans le portail client. | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |
>| User.Read | délégué | Nous enregistreons le message &amp; électronique de nom | Permet aux utilisateurs de se connecter et de donner accès à Microsoft Graph en leur nom | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |


#### <a name="non-microsoft-services-used"></a>Non utilisé services Microsoft

Si l’application transfère ou partage des données organisationnelles avec un service non-Microsoft, indiquez le service non-Microsoft utilisé par l’application, quelles données sont transférées et incluez une justification pour la raison pour laquelle l’application doit transférer ces informations.

>| **Toutes les OII non services Microsoft sont transférées vers** |  **Quels OII sont transférés ?** | **Justification du transfert d’OII ?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailjet Email utilisé pour les notifications par courrier électronique. |  | N/A |

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre d’une équipe ou d’une conversation à qui elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>| **Justification de l’accès à EUII ?**  | **L’EUII est-il stocké dans des bases de données ?** | **Justification du stockage de l’EUII ?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Pour créer des utilisateurs dans notre système back-end et accorder des autorisations pour accéder au contenu lié à l’équipe. | We store: Name - To shown the name of the user, Email address - To identify the user |  |


#### <a name="telemetry-data"></a>Données de télémétrie

Les informations d’identification organisationnelle (OII) ou d’identification de l’utilisateur final (EUII) apparaissent-elles dans la télémétrie ou les journaux de cette application ? Si oui, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Nous stockons uniquement le numéro IP dans nos journaux. 

L’organisation peut nous envoyer une demande en tant que fournisseur s’il souhaite que des données soient supprimées.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par le partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? par exemple, la suppression, la rétention, l’audit, l’archivage, la stratégie de l’utilisateur final, etc.

>Stockage des données : toutes les données client sont stockées dans Microsoft Azure services. Les utilisateurs doivent être authentifiés à 2 facteurs via Azure AD. L’accès basé sur un rôle (RBAC) est en place. Tout accès aux Microsoft Azure est strictement effectué par le biais de connexions chiffrées. Toutes les données sont chiffrées au repos. Tous les services sont protégés par le Centre de sécurité Azure. 

Nous avons également une stratégie d’accès en place conformément au principe du moindre privilège. 


#### <a name="human-review-of-organizational-information"></a>Examen humain des informations organisationnelles

Les humains sont-ils impliqués dans la révision ou l’analyse de données d’informations d’identification organisationnelle (OII) collectées ou stockées par cette application ?

>Non

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Les informations du catalogue [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) apparaissent ci-dessous.

<iframe height='1020' title='Microsoft Cloud App Security Informations' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">Afficher dans un nouvel onglet</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

