---
ms.author: oromalle
title: Certification Microsoft 365 - Guide initial de soumission de document
author: orionomalley
manager: tonybal
description: La soumission initiale du document fait partie de la phase de pré-évaluation de la certification.
keywords: les équipes de certification des applications Microsoft 365 la soumission initiale du document m365 de conformité à la sécurité
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 23c3cf7a64025bb7269adb35175e8d87bc64224e
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784503"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 Ceritification - Guide initial de soumission de document

La soumission initiale du document fait partie de la phase de pré-évaluation de la certification. Les informations fournies donneront aux analystes de certification l’arrière-plan nécessaire pour identifier les contrôles et les composants système qui seront inclus dans l’étendue de votre évaluation. Ce document est destiné à servir uniquement d’exemple de ce qui est attendu de votre soumission initiale de document. La documentation que vous fournissez varie en fonction de la façon dont votre solution est conçue, implémentée et gérée.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>Quel est l’environnement d’hébergement ou le modèle de service utilisé pour exécuter votre application ?
- L’infrastructure en tant que service (IaaS) est un modèle de service cloud dans lequel votre fournisseur de services cloud héberge vos composants d’infrastructure, mais les éditeurs de logiciels indépendants sont toujours responsables du déploiement et de la gestion des composants individuellement, tels que Machines Virtuelles/systèmes d’exploitation, magasins de données et composants réseau. Les machines virtuelles Azure et les Stockage de disque Azure en sont des exemples.
- Platform as a Service (PaaS) est un modèle de service cloud où les composants d’infrastructure sont gérés par le fournisseur de services cloud. Les éditeurs de logiciels indépendants sont uniquement responsables du déploiement de leurs propres applications et services. Les services Azure App, les Azure Functions et les Azure CDN en sont des exemples.
- L’isv hébergé dans ce contexte signifie qu’aucun fournisseur de services cloud n’est utilisé. L’éditeur de logiciels indépendant gère physiquement ses propres serveurs, disques et réseau local.
- Hybride dans ce contexte signifie qu’un des modèles ci-dessus est utilisé. Par exemple, certains éditeurs de logiciels indépendants peuvent choisir d’utiliser un mélange de services IaaS et de services PaaS pour prendre en charge leur application, ou ils peuvent avoir des composants hébergés par un éditeur de logiciels indépendants locaux et externaliser d’autres services à un fournisseur de services cloud. Si vous utilisez un autre modèle de service, sélectionnez hybride.

## <a name="penetration-test-report"></a>Rapport de test d’intrusion

Veuillez inclure le rapport de test d’intrusion complet avec des dates indiquant qu’il a été terminé au cours des 12 derniers mois. 
-   Ce rapport doit être produit à partir de tests d’intrusion manuels. Il ne peut pas s’agir de la sortie d’un outil d’analyse/test automatisé.
-   Ce rapport doit inclure l’environnement qui prend en charge le déploiement de l’application/de l’ajout, ainsi que tout autre environnement qui prend en charge le fonctionnement de l’application/des compléments.


## <a name="system-component-inventory"></a>Inventaire des composants système

Inventroy à jour de tous les composants système utilisés par l’infrastructure de prise en charge. Cela sera utilisé pour faciliter l’échantillonnage lors de l’exécution de la phase d’évaluation. Si votre environnement inclut PaaS, il serait utile de pouvoir fournir des détails sur tous les services PaaS consommés.

**Note:** IaaS/PaaS n’aurait pas de matériel qui serait sous le contrôle ISV.  Dans ce cas, fournissez une liste ou une capture d’écran de toutes les ressources virtuelles.

**Exemple :**

|Nom de la ressource|Type de ressource|Description|Fabricant|Modèle|
|---|---|---|---|---|
|D212|machine Windows|Virtual Machine|N/A|S/O|
|LT101|Ordinateur portable|Station de travail|Microsoft|Surface 3|
|C2938|Commutateur|Commutateur|N/A|S/O|
|LXM2|Linux Machine|Test Machine|N/A|S/O|


## <a name="software-inventory"></a>Inventaire logiciel

Inventaire à jour de toutes les ressources logicielles, y compris tous les logiciels utilisés dans l’environnement dans l’étendue, ainsi que les versions.

**Exemple :**

|Logiciels|Éditeur|Version|Objectif|
|---|---|---|---|
|Windows Server|Microsoft 2016 |Build 14393|Système d’exploitation serveur pour l’environnement de production|
|Linux Ubuntu|S/O|16.04 (Xenial)|Système d’exploitation serveur en cours d’utilisation dans la DMZ.|
|Esxi|Vmware|6.5.0 (Build 13004031)|Utilisé pour prendre en charge les serveurs virtuels.|
|Mysql (Windows)|S/O|8.0.2.1|Serveur de base de données pour stocker l’historique des conversations.|
|Tomcat|Apache|7.0.92|Portail du client.|
|Services Internet (IIS)|Microsoft|10.0|Prend en charge les API.|


## <a name="third-party-dependencies"></a>Dépendances tierces

Documentation répertoriant toutes les dépendances utilisées par l’application/complément avec les versions en cours d’exécution.

**Exemple :**

|Dépendances web|Version actuelle en cours d’utilisation|
|----|----|
|Jquery|3.5.1|
|React|16.13.1|
|Bootstrap|4.5.2|
|Express|4.17.1|
|Angle|10.0.14|
|AngularJS|1.8.0|


## <a name="public-ip-addresses"></a>Adresses IP publiques

Détail de toutes les adresses IP et URL publiques utilisées par l’infrastructure de prise en charge. Cela doit inclure la plage d’adresses IP routables totale allouée à l’environnement, sauf si une segmentation adéquate a été implémentée pour fractionner la plage utilisée (une preuve adéquate de la segmentation sera nécessaire).

**Exemple :**

|URL|Adresse IP|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|40.113.200.201|
|https://customerapi.contoso.com|40.113.200.202|
|https://bot.contoso.com|40.113.200.202|
|N/A (Serveur de saut)|40.113.200.200|


## <a name="resource-endpoints"></a>Points de terminaison de ressource

Adresse du point de terminaison du nom de l’API Contoso Api client https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com API Contoso Fileshttps://filesapi.contoso.com

Liste complète de tous les points de terminaison d’API utilisés par votre application, y compris les points de terminaison de ressources externes et développés en interne. Pour mieux comprendre l’étendue de l’environnement, fournissez des emplacements de point de terminaison d’API au sein de votre environnement.

**Exemple :**

|Nom de l’API|  Adresse du point de terminaison|
|-|-|
|API client Contoso|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso Files API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Diagramme architectural

Diagramme d’architecture logique représentant une vue d’ensemble générale de l’infrastructure de prise en charge de votre application/complément. Cela doit inclure tous les environnements d’hébergement et l’infrastructure de prise en charge de l’application/complément. Ce diagramme DOIT représenter tous les différents composants système de prise en charge au sein de l’environnement pour aider les analystes de certification à comprendre les systèmes dans l’étendue et à déterminer l’échantillonnage. Indiquez également le type d’environnement d’hébergement utilisé ; ISV hébergé, IaaS, PaaS ou hybride. Là où PaaS est utilisé, indiquez les différents services PaaS utilisés pour fournir les services de prise en charge dans l’environnement.

![Diagramme architectural](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>diagramme Data Flow

Flow diagrammes détaillant les éléments suivants :
-   Les données circulent vers et depuis l’application/complément (y compris les données client).
-   Flux de données au sein de l’infrastructure de prise en charge (le cas échéant)
-   Diagrammes mettant en évidence l’emplacement et les données stockées, la façon dont les données sont transmises à des tiers externes (y compris les détails des tiers) et la façon dont les données sont protégées en transit sur des réseaux ouverts/publics et au repos.

![diagramme Data Flow](../media/Dataflowdiagram.png)



