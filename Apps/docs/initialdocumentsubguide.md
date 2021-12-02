---
ms.author: oromalle
title: Microsoft 365 certification - Guide de soumission de document initial
author: orionomalley
description: Vue Microsoft 365 granulaire du Guide de soumission de certification
keywords: Équipes de certification des Microsoft 365 conformité de la sécurité m365 envoi initial de documents
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 0f879ce6b02fb469b0210500e4706d468ccb4011
ms.sourcegitcommit: 3e72bc447a90cd8b0313dab55f6a9374be8ae358
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/01/2021
ms.locfileid: "61261676"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 - Guide de soumission de document initial

La soumission initiale du document fait partie de la phase de pré-évaluation de la certification. Les informations fournies donnent aux analystes de certification l’arrière-plan nécessaire pour identifier les contrôles et les composants système qui seront dans l’étendue de votre évaluation. Ce document est destiné à servir uniquement d’exemple de ce qui est attendu de votre envoi initial de document. La documentation que vous fournissez varie en fonction de l’architecture, de l’implémenter et de la gestion de votre solution.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>Quel est l’environnement d’hébergement ou le modèle de service utilisé pour exécuter votre application ?
- L’infrastructure en tant que service (IaaS) est un modèle de service cloud dans lequel votre fournisseur de services cloud héberge vos composants d’infrastructure, mais les logiciels indépendants sont toujours chargés de déployer et de gérer les composants individuellement, tels que les machines virtuelles/systèmes d’exploitation, les magasins de données et les composants réseau. Azure Virtual Machine et Azure Disk Stockage en sont des exemples.
- La plateforme en tant que service (PaaS) est un modèle de service cloud dans lequel les composants d’infrastructure sont gérés par le fournisseur de services cloud. Les isv sont uniquement responsables du déploiement de leurs propres applications et services. Azure App Services, azure Functions et Azure CDN en sont des exemples.
- IsV hébergé dans ce contexte signifie qu’aucun fournisseur de services cloud n’est utilisé. L’isv gère physiquement ses propres serveurs, disques et réseau de manière indépendante sur site.
- Dans ce contexte, l’un des modèles ci-dessus est utilisé. Par exemple, certains fournisseurs de logiciels indépendants peuvent utiliser une combinaison de services IaaS et de services PaaS pour prendre en charge leur application, ou ils peuvent avoir des composants hébergés isv locaux et externaliser d’autres à un fournisseur de services cloud. Si vous utilisez l’un des autres modèles de service, sélectionnez hybride.

## <a name="penetration-test-report"></a>Rapport de test de pénétration

Veuillez inclure le rapport de test de pénétration complète avec les dates qui indiquent qu’il a été terminé au cours des 12 derniers mois. 
-   Ce rapport doit être produit à partir de tests de pénétration manuels, il ne peut pas être la sortie d’un outil d’analyse/test automatisé.
-   Ce rapport doit inclure l’environnement qui prend en charge le déploiement de l’application/de l’ajout, ainsi que tout environnement supplémentaire qui prend en charge le fonctionnement de l’application/des compléments.


## <a name="system-component-inventory"></a>Inventaire des composants système

Un inventroy à jour de tous les composants système utilisés par l’infrastructure de prise en charge. Cela sera utilisé pour faciliter l’échantillonnage lors de la phase d’évaluation. Si votre environnement inclut PaaS, il serait utile si vous pouvez fournir des détails sur tous les services PaaS consommés.

**Remarque :** IaaS/PaaS n’aurait aucun matériel qui serait sous le contrôle des fabricants de logiciels isv.  Dans ce cas, fournissez une liste ou une capture d’écran de toutes les ressources viruelles.

**Exemple :**

|Nom de l’actif|    Type d’actif| Description|    Fabricant|   Modèle|
|-|-|-|-|-|
|D212|  Windows Machine|   Virtual Machine|    N/A| N/A|
|LT101| Ordinateur portable| Station de travail|    Microsoft|  Surface 3|
|C2938| Commutateur| Commutateur|N/A|N/A|     
|LXM2|  Linux Machine|  Ordinateur de test|N/A|N/A|       


## <a name="software-inventory"></a>Inventaire logiciel

Un inventaire à jour de toutes les ressources logicielles, y compris tous les logiciels utilisés dans l’environnement dans l’étendue, ainsi que les versions.

**Exemple :**

|Logiciels|  Éditeur|  Version|     Objectif|
|-|-|-|-|
|Windows Server|    Microsoft 2016 | Build 14393| Système d’exploitation serveur pour l’environnement de production|.
|Linux Ubuntu|  S/O|    16.04 (Xenial)| Système d’exploitation serveur utilisé dans la DMZ.|
|ESXi|  VMWare| 6.5.0 (Build 13004031)| Utilisé pour prendre en charge les serveurs virtuels.|
|Mysql (Windows)|   S/O|    8.0.2.1|    Serveur de base de données pour stocker l’historique des conversation.|
|Tomcat|        Apache| 7.0.92| Portail client.|
|Services Internet (IIS)|   Microsoft|  10.0|   Prend en charge les API.|


## <a name="third-party-dependencies"></a>Dépendances tierces

Documentation répertoriant toutes les dépendances utilisées par l’application/le add-in avec les versions en cours d’exécution.

**Exemple :**

|Dépendances web|  Version actuelle en cours d’utilisation|
|-|-|
|JQuery|    3.5.1|
|React| 16.13.1|
|Bootstrap| 4.5.2|
|Express|   4.17.1|
|Angle|   10.0.14|
|AngularJS| 1.8.0|


## <a name="public-ip-addresses"></a>Adresses IP publiques

Détails de toutes les adresses IP publiques et URL utilisées par l’infrastructure de prise en charge. Cela doit inclure la plage d’adresses IP routable complète allouée à l’environnement, sauf si une segmentation adéquate a été implémentée pour fractionner la plage en cours d’utilisation (une preuve adéquate de segmentation sera requise).

**Exemple :**

|URL|  Adresse IP|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|  40.113.200.201|
|https://customerapi.contoso.com|   40.113.200.202|
|https://bot.contoso.com|   40.113.200.202|
|N/A (Jump Server)| 40.113.200.200|


## <a name="resource-endpoints"></a>Points de terminaison des ressources

API Nom du point de terminaison Adresse du client Contoso API    https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com Contoso Files API   https://filesapi.contoso.com

Liste complète de tous les points de terminaison d’API utilisés par votre application, y compris les points de terminaison de ressources externes et développés en interne. Pour mieux comprendre l’étendue de l’environnement, fournissez des emplacements de point de terminaison d’API dans votre environnement.

**Exemple :**

|Nom de l’API|  Adresse du point de terminaison|
|-|-|
|API client Contoso|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|API de fichiers Contoso| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Diagramme d’architecture

Diagramme d’architecture logique représentant une vue d’ensemble de l’infrastructure de prise en charge de votre application/de votre application. Cela doit inclure tous les environnements d’hébergement et l’infrastructure de prise en charge de l’application/du add-in. Ce diagramme DOIT décrire tous les différents composants système de prise en charge dans l’environnement pour aider les analystes de certification à comprendre les systèmes dans l’étendue et à déterminer l’échantillonnage. Indiquez également le type d’environnement d’hébergement utilisé . IsV hébergé, IaaS, PaaS ou hybride. Lorsque PaaS est utilisé, indiquez les différents services PaaS utilisés pour fournir les services de prise en charge dans l’environnement.

![Diagramme d’architecture](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Diagramme des Flow données

Flow diagrammes détaillés suivants :
-   Flux de données vers et à partir de l’application/du add-in (y compris les données client).
-   Flux de données dans l’infrastructure de prise en charge (le cas échéant)
-   Diagrammes mettant en évidence où et quelles données sont stockées, comment les données sont transmises à des tiers externes (notamment des détails sur les tiers) et comment les données sont protégées en transit sur des réseaux ouverts/publics et au repos.

![Diagramme des Flow données](../media/Dataflowdiagram.png)



