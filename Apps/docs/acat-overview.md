---
title: Outil d’automatisation de la conformité des applications pour Microsoft 365
author: xu-hong
ms.author: hongxu6
manager: zhshang
description: Vue d’ensemble de l’outil d’automatisation de la conformité des applications pour Microsoft 365
keywords: Microsoft 365 d’automatisation de la certification des applications
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 5e3fbc062c1887a205a7b99a85a292ad9a64f8d0
ms.sourcegitcommit: 0865622c8abffc11115e56d966729e5318d67ab9
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/20/2022
ms.locfileid: "65608807"
---
# <a name="app-compliance-automation-tool-for-microsoft-365"></a>Outil d’automatisation de la conformité des applications pour Microsoft 365
Dans cet article, vous allez découvrir ce qu’est l’outil App Compliance Automation tool for Microsoft 365 (ACAT) et comment il simplifie la conformité et l’obtention de la certification Microsoft 365.

> [!IMPORTANT]
> ACAT est actuellement en préversion privée. Si vous souhaitez participer au programme de préversion privée, inscrivez-vous [ici](https://aka.ms/acat/private/signup).

> [!NOTE]
> Si vous souhaitez envoyer des commentaires à la préversion privée ACAT, vous pouvez commencer à partir de ce [formulaire](https://aka.ms/acat/feedback). L’équipe produit ACAT vous suivra dès que possible une fois que nous aurons vos messages. 

## <a name="what-is-app-compliance-automation-tool-for-microsoft-365"></a>Qu’est-ce que l’outil d’automatisation de la conformité des applications pour Microsoft 365
App Compliance Automation Tool for Microsoft 365 (ACAT) est un service dans le portail Azure qui permet de simplifier le parcours de conformité pour toute application qui consomme Microsoft 365 données client et qui est publiée via l’Espace partenaires. L’outil d’automatisation de la conformité des applications pour Microsoft 365 est un outil d’automatisation de conformité centré sur les applications qui vous permet d’achever Microsoft 365 certification avec plus de facilité et de commodité. En préversion privée, ACAT est disponible pour les applications s’exécutant sur Azure.

Avec cet outil, vous serez rapidement en mesure de définir la limite de conformité pour vos applications, de surveiller automatiquement les résultats de conformité et d’effectuer l’audit de conformité plus facilement. La limite de conformité est l’infrastructure cloud qui prend en charge la remise de l’application et tous les systèmes principaux avec lequel l’application peut communiquer.

En plus de fournir un suivi plus rapide vers Microsoft 365 certification, ACAT peut vous aider dans différents scénarios de conformité pour Microsoft 365 applications :

- Vue détaillée et étapes de correction pour les responsabilités de certification Microsoft 365.
- Rapports quotidiens automatiques pour vous aider à obtenir les résultats de conformité en continu.
- Meilleures pratiques de sécurité et de conformité qui peuvent être utilisées comme conseils dans la première phase du cycle de vie de votre application.

## <a name="benefits-of-acat"></a>Avantages de l’ACAT
Parcours de conformité centré sur l’application.
- ACAT signale quotidiennement l’état de conformité pour l’environnement cloud de vos applications, que vous pouvez intégrer à votre stratégie actuelle de conformité de l’infrastructure cloud.
- Les développeurs peuvent appeler ACAT même pendant la phase de développement de l’application.

Accélère le processus d’obtention de Microsoft 365 certifié.
- ACAT automatise entièrement certains contrôles de certification Microsoft 365.
- Une liste d’automatisation en constante croissance est en cours de développement par Microsoft.

Intégration native à Microsoft 365 workflow de certification.
- ACAT est entièrement intégré à l’Espace partenaires à des fins de certification Microsoft 365.

## <a name="concepts-of-acat"></a>Concepts de l’ACAT
### <a name="regulatory-compliance-report"></a>Rapport de conformité réglementaire 
Dans ACAT, vous pouvez auditer l’état de conformité de l’application en créant un rapport de conformité pour celle-ci. Vous pouvez définir la limite de conformité de votre application en spécifiant les ressources Azure qui génèrent l’application. Créez plusieurs rapports pour une application, en fonction de différents environnements de développement et étapes.

Une fois le rapport créé, ACAT commence à collecter les données de conformité au moment de votre déclencheur prédéfini, puis génère les résultats de conformité en tant que rapport pour vous. Pendant ce temps, ACAT continuera de surveiller les modifications de conformité de votre rapport de conformité en permanence, jusqu’à ce que vous choisissiez de supprimer le rapport.

### <a name="microsoft-365-certification-control-results"></a>Microsoft 365 résultats du contrôle de certification
Dans le rapport de conformité réglementaire, les résultats de conformité sont organisés par des contrôles avec leurs états correspondants marqués par ACAT :
- **Passé** : Il n’y a aucun échec pour les contrôles de certification Microsoft 365 entièrement automatisés.
- **Échec** : des responsabilités client ayant échoué sont détectées pour les contrôles de certification de Microsoft 365 entièrement automatisés.
- **Passé - Preuve supplémentaire nécessaire** : il n’existe aucun échec pour les contrôles de certification Microsoft 365 *partiellement automatisés*.
- **Échec - Preuve supplémentaire nécessaire** : des responsabilités client ayant échoué sont détectées pour les contrôles de certification Microsoft 365 *partiellement automatisés*.
- **Contrôle manuel** : ACAT n’automatise aucune responsabilité du client pour les contrôles de certification Microsoft 365.

### <a name="customer-responsibility"></a>Responsabilités du client
Il existe un ensemble de responsabilités client associées à chaque contrôle qui doivent être satisfaites. Ce sont des responsabilités que vous conservez dans les domaines suivants : données, points de terminaison, compte, gestion des accès, etc.

ACAT collecte des données pour chaque responsabilité du client et retourne un résultat d’évaluation pour celui-ci. Il vous fournit également une action de correction, qui est notre guide qui vous aide à vous aligner sur les normes de certification Microsoft 365.


## <a name="faq"></a>FAQ
### <a name="what-are-manual-controls-and-partially-automated-controls"></a>Que sont les contrôles manuels et les contrôles partiellement automatisés ?
Chaque contrôle de conformité est associé à un ensemble de responsabilités client pour lesquelles ACAT collecte des données de conformité. Toutefois, tous les contrôles pour la certification Microsoft 365 ne sont pas couverts par l’ACAT à ce stade (il existe un effort continu pour étendre la couverture). Pour le contrôle partiellement automatisé, ACAT automatise certaines parties des responsabilités des clients. Vous pouvez utiliser l’état de conformité de celui-ci pour référence, mais ne pouvez pas l’utiliser directement pour Microsoft 365 audit de certification. Pour les contrôles manuels, ACAT n’automatise actuellement aucune responsabilité du client.

### <a name="i-made-the-suggested-changes-base-on-the-remediation-suggestion-yet-the-control-is-still-failing"></a>J’ai apporté les modifications suggérées en fonction de la suggestion de correction, mais le contrôle échoue toujours
Après avoir pris des mesures pour résoudre l’échec, vous devez attendre qu’ACAT récupère les résultats d’évaluation actualisés pour mettre à jour l’état du contrôle. Les évaluations sont exécutées toutes les 24 heures à l’heure de déclenchement prédéfinie.

### <a name="how-is-the-compliance-report-used-in-the-certification-process"></a>Comment le rapport de conformité est-il utilisé dans le processus de certification ?
ACAT est intégré de manière transparente à [l’Espace partenaires](https://partner.microsoft.com/dashboard) pour terminer votre parcours de certification Microsoft 365. Lors de la création du rapport de conformité, vous pouvez modifier la configuration de certification Microsoft 365, à savoir le GUID de l’offre. Elle est facultative lors de la création, et vous pouvez la configurer ultérieurement lorsque vous commencerez à publier l’application.

## <a name="learn-more"></a>En savoir plus

* [Prise en main avec ACAT](https://aka.ms/acat/getstarted)
* [En savoir plus sur la certification Microsoft 365](https://aka.ms/acat/m365cert)
