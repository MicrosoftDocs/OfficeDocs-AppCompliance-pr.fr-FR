---
title: Programme de conformité de l’application Microsoft 365
author: LGerrard
ms.author: Legerrar
description: Introduction et vue d’ensemble du programme
keywords: Certification ou Attestation d’éditeur de l’application m365 Microsoft 365
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: c644414281f46696ff49f3b9eb1341f02e96f0ba
ms.sourcegitcommit: 78dbace87a9b5027ea5aa23a6be9b8c613bd06ce
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/07/2021
ms.locfileid: "53315114"
---
# <a name="microsoft-365-app-compliance-program"></a>Programme de conformité de l’application Microsoft 365

Le programme de conformité de l’application Microsoft 365 est une approche sur trois niveaux sur la conformité et la sécurité de l’application. Chaque niveau se crée sur le suivant, offrant un programme en couche pour offrir aux utilisateurs la confiance dont ils ont besoin lors de l’utilisation des applications de l’écosystème Microsoft 365. Tous les niveaux actuellement dans le programme sont volontaires et sont effectués à la discrétion des développeurs de l’application. 

Notre déclaration de mission : les clients de Microsoft ont une confiance totale dans les applications qui font fonctionner leur organisation.

  ![Approche à trois niveaux vers la conformité de l’application](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a>Vérification de l’éditeur

La [Vérification de l’éditeur](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) permet aux administrateurs et aux utilisateurs de comprendre l’authenticité de l’application que les développeurs intègrent avec la plateforme d’identité Microsoft. Lorsqu’une application est marquée comme vérifiée par l’éditeur, cela signifie que celui-ci a vérifié son identité à l’aide d’un compte Microsoft Partner Network qui a effectué un processus de vérification et a associé ce compte Microsoft Partner Network à son inscription d’application.
La vérification de l’éditeur s’applique aux applications répondant aux conditions suivantes :  
- Utilisation d’OAuth 2.0 et d’OpenID Connect pour connecter les utilisateurs et demander un accès aux données à l’aide des API côté service telles que Microsoft Graph. 
- Inscription dans Azure AD en tant que multi-locataire.  

> [!IMPORTANT]
> La vérification de l’éditeur n’empêche pas un développeur d’applications de commencer ou achever une Attestation d’éditeur ou une Certification Microsoft 365. Si cela ne s’applique pas à l’application, la vérification peut être ignorée et l’attestation peut démarrer.

## <a name="publisher-attestation"></a>Attestation de l’éditeur

L’[Attestation de l’éditeur](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide) est l’emplacement dans lequel les développeurs partagent des données générales, de traitement des données, de sécurité et de conformité relatives à leur service d’application. Ceci réduit le besoin pour les administrateurs informatiques de travailler directement avec les éditeurs de l’application. Toutes les informations nécessaires à la prise de décision informée peuvent être trouvées pour toutes les applications ayant terminé l’attestation de l’éditeur au même endroit et dans un format cohérent. L’objectif est de faciliter et d’accélérer le processus d’adoption de l’application tout en assurant les clients que les applications utilisées chez leurs locataires répondent aux normes de l’organisation.

Publisher Attestation s’applique à WebApps et à toutes les applications qui s’intègrent aux produits Microsoft suivants :
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

> [!IMPORTANT]
> Microsoft ne valide pas les informations fournies. Le développeur atteste uniquement de l’authenticité, de l’exactitude et de l’intégrité de la documentation de l’attestation et des données de performances de l’application correspondantes. 

## <a name="microsoft-365-certification"></a>Certification Microsoft 365
La [Certification Microsoft 365](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide) offre la confiance et l’assurance aux organisations que les données et la confidentialité sont sécurisées et protégées de manière adéquate lors de l’utilisation des applications Microsoft Teams. La certification confirme que la solution d’application est compatible avec les technologies Microsoft, conforme aux meilleurs pratiques de sécurité de l’application cloud et prise en charge par Microsoft.Au cours de ce processus, les développeurs de l’application collaborent avec un expert tiers pour valider les normes de conformité et de sécurité de l’organisation. La Certification Microsoft 365 s’applique aux mêmes applications que celle qui se qualifient pour l’Attestation de l’éditeur. 


