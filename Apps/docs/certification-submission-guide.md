---
ms.author: oromalle
title: Guide de soumission de certification Microsoft 365
author: orionomalley
description: Vue granulaire du Guide de soumission de certification Microsoft 365
keywords: Équipes de certification des applications Microsoft 365 conformité de la sécurité m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 4d0f09b3a1dd6bde7022e93d08a491e2855d90a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/28/2021
ms.locfileid: "52071067"
---
# <a name="microsoft-365-certification-submission-guide"></a>Guide de soumission de certification Microsoft 365

**Dans cet article**
- [Introduction](#introduction)
- [Conditions préalables](#prerequisites) 
- [Mises à jour des spécifications de certification Microsoft 365](#microsoft-365-certification-specification-updates)
- [Étendue de certification](#certification-scope)
- [Processus de certification](#certification-process)
- [Preuve de conformité](#compliance-evidence) 
- [Envoi initial du document](#initial-document-submission) 
- [Activités de collecte et d'évaluation des preuves](#evidence-collection-and-assessment-activities)
- [Critères de certification](#app-certification-criteria)
- [Sécurité des applications](#application-security)
- [Sécurité opérationnelle](#operational-security) 
- [Sécurité et confidentialité de la gestion des données](#data-handling-security-and-privacy)
- [Révision facultative des frameworks de conformité externe](#optional-external-compliance-frameworks-review)
- [Annexe A](#appendix-a)
- [Annexe B](#appendix-b) 
- [Annexe C](#appendix-c) 
- [Annexe D](#appendix-d) 
- [Annexe E](#appendix-e) 
- [Annexe F](#appendix-f) 
- [Annexe G ](#appendix-g)
- [En savoir plus](#learn-more) 
- [Glossaire](#glossary) 


## <a name="introduction"></a>Introduction

Dans le cadre du programme de conformité des applications Microsoft 365, la certification Microsoft 365 garantit et garantit aux entreprises que les données et la confidentialité sont correctement sécurisées et protégées lors de l'intégration d'applications/de modules de développement tiers à la plateforme Microsoft 365. Les applications et les applications qui passent la validation sont désignées comme Certification **Microsoft 365** dans l'écosystème Microsoft 365. 

En participant au programme de certification Microsoft 365, vous acceptez ces conditions supplémentaires et vous respectez toute documentation qui s'applique à votre participation au programme de certification Microsoft 365 avec Microsoft Corporation ( « Microsoft », « nous », « nous » ou « notre »). Vous nous faites part de l'autorité qui vous permet d'accepter ces conditions supplémentaires de certification Microsoft 365 au nom de vous-même, d'une société et/ou d'une autre entité, le cas échéant. Nous pouvons modifier, modifier ou mettre fin à ces termes supplémentaires à tout moment. Votre participation continue au programme de certification Microsoft 365 après toute modification ou modification signifie que vous acceptez les nouvelles conditions supplémentaires. Si vous n'acceptez pas les nouvelles conditions supplémentaires ou si nous résilions ces termes supplémentaires, vous devez arrêter de participer au programme de certification Microsoft 365.

Ce document s'adresse aux éditeurs de logiciels indépendants pour fournir des informations sur le processus de certification Microsoft 365, les conditions préalables au démarrage du processus et les détails des contrôles de sécurité spécifiques que les éditeurs de logiciels indépendants doivent mettre en place.  Des informations générales sur le programme de conformité des applications Microsoft 365 sont disponibles dans la [page](https://docs.microsoft.com/microsoft-365-app-certification/overview)du programme conformité des applications Microsoft 365. 

> [!IMPORTANT]
> Actuellement, la certification Microsoft 365 est limitée :
>* Applications Microsoft Teams (onglets, bots, etc.) .
>* Applications/add-ins SharePoint
>* Office Add-ins (Word, Excel, PowerPoint, Outlook, Project, OneNote)

## <a name="prerequisites"></a>Prerequisites

### <a name="publisher-attestation"></a>Publisher Attestation

Avant d'obtenir le processus de certification Microsoft 365, vous devez avoir obtenu une attestation publisher. Toutefois, vous pouvez démarrer le processus de certification Microsoft 365 avant de terminer l'attestation publisher.  

### <a name="read-the-microsoft-365-certification-specification"></a>Lire la spécification de certification Microsoft 365

Microsoft recommande à tous les éditeurs de logiciels indépendants (éditeurs de logiciels indépendants) de lire entièrement cette spécification de certification Microsoft 365 afin de s'assurer que tous les contrôles applicables sont satisfaits par l'environnement dans l'étendue et l'application/le add-in. Cela permet de garantir un processus d'évaluation fluide.

## <a name="microsoft-365-certification-specification-updates"></a>Mises à jour des spécifications de certification Microsoft 365 

Les mises à jour de la spécification de certification Microsoft 365 sont prévues environ tous les six à douze mois. Ces mises à jour peuvent introduire de nouveaux domaines de sécurité cibles et/ou des contrôles de sécurité. Les mises à jour seront basées sur les commentaires des développeurs, les modifications apportées au paysage des menaces et pour augmenter la ligne de base de sécurité du programme au cours de sa maturité. 

Les isv qui ont déjà démarré l'évaluation de la certification Microsoft 365 peuvent poursuivre l'évaluation avec la version de la spécification de certification Microsoft 365 qui était valide au début de l'évaluation. Toutes les nouvelles soumissions, y compris la recertification annuelle, doivent être évaluées par rapport à la version publiée.

> [!NOTE]
> Vous n'êtes pas obligé de vous conformer à tous les contrôles de cette spécification de certification Microsoft 365 pour obtenir une certification. Toutefois, des seuils de passage (qui ne seront pas divulgués) sont en place pour chacun des domaines de sécurité abordés dans cette spécification de certification Microsoft 365. Certains contrôles seront classésen tant qu'échec en dur, ce qui signifie que l'absence de ces contrôles de sécurité entraîne l'échec de l'évaluation. 

## <a name="certification-scope"></a>Étendue de certification

L'environnement dans l'étendue est l'environnement qui prend en charge la livraison du code d'application/de add-in et prend en charge tous les systèmes **back-end** avec qui l'application/le module peut communiquer. Tous les environnements connectés supplémentaires seront également inclus dans l'étendue, sauf si une segmentation adéquate est en place ET que les environnements connectés ne peuvent pas avoir d'impact sur la sécurité de l'environnement dans l'étendue. Tous les environnements de récupération d'urgence doivent également être inclus dans l'étendue de l'évaluation, car ces environnements seraient requis pour accomplir le service en cas de problème dans l'environnement principal.  Le terme **composants système dans l'étendue** fait référence à TOUS les appareils et systèmes utilisés dans l'environnement   dans l'étendue.  Les composants dans l'étendue incluent, sans s'y limiter, les éléments suivants :
* Les applications web.
* Serveurs.
* Pare-feu (ou équivalent).
* Commutateurs.
* Équilibreurs de charge.
* Infrastructure virtuelle.
* Portails de gestion web des fournisseurs de cloud 

> [!IMPORTANT]
> L'environnement dans l'étendue doit avoir une DMZ et l'environnement de prise en charge de l'application/du add-in doit être segmenté des systèmes d'entreprise internes et des environnements d'entreprise, limitant ainsi l'étendue des activités d'évaluation aux systèmes dans l'étendue uniquement. Les analystes de certification valideront les techniques de segmentation lors de l'évaluation, ainsi que la révision des rapports de test de pénétration qui auraient dû inclure des tests pour valider l'efficacité de toutes les techniques de segmentation utilisées.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infrastructure as a Service (IaaS), Platform as a Service (PaaS) et Software as a Service (SaaS) 
Lorsque IaaS et/ou PaaS sont utilisés pour prendre en charge l'infrastructure de la remise de code d'application ou de module de module de prise en charge en révision, le fournisseur de plateforme Cloud sera responsable de certains des contrôles de sécurité évalués tout au long du processus de certification. Par conséquent, les analystes de certification doivent être assurés par une vérification externe indépendante des meilleures pratiques en matière de sécurité par le fournisseur de plateforme Cloud par le biais de rapports de conformité externes tels que les rapports [DSS](bookmark://pci-dss)attestation de conformité   (AOC), ISO27001 ou [SOC 2](bookmark://soc-2)   Type II. 

L'Annexe F fournit des détails sur les contrôles de sécurité qui seront probablement applicables en fonction des types de déploiement suivants et selon que l'application/le add-in exfiltre ou non les données M365 : 
* ISV hébergé 
* IaaS hébergé 
* PaaS/Serverless Hosted 
* Hybride hébergé 
* Shared Hosted 

Lorsque IaaS ou PaaS est déployé, vous devez fournir des preuves de l'environnement hébergé dans ces types de déploiement.

### <a name="sampling"></a>Échantillonnage

Les demandes de preuves à la prise en charge de l'évaluation de certification doivent être basées sur un échantillon des composants système dans l'étendue en considération des différents systèmes d'exploitation, de la fonction principale de l'appareil et des différents types d'appareils. Un exemple approprié est sélectionné au début du processus de certification. Le tableau suivant doit servir de guide sur la taille de l'échantillon :

|Taille de la population              | Échantillon                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4 |

> [!NOTE]
>Si des incohérences sont identifiées entre les appareils inclus dans l'exemple initial, la taille de l'échantillon peut être augmentée au cours de l'évaluation. 

## <a name="certification-process"></a>Processus de certification

Avant de commencer le processus de certification, vous devez avoir correctement démarré ou terminé votre attestation Publisher. Vos réponses d'attestation seront utilisées pour prendre en charge le processus de certification Microsoft 365 et se déroulent comme suit : 

1. Consulter la documentation de votre attestation d'éditeur pour vous assurer de l'alignement avec votre environnement actuel 
2. Demande de progression vers la certification Microsoft 365 par courrier électronique <AppCert@microsoft.com> 
3. Les analystes de certification ouvrent un dialogue avant de démarrer le processus de certification Microsoft 365.   
4. Envoyer votre [envoi de document initial](#initial-document-submission)
5. L'analyste de certification fournit une liste des contrôles pour lesquels des preuves sont requises, ce qui démarre officiellement le processus de certification Microsoft 365.
6. Soumettre des preuves qui montrent que tous les contrôles de certification Microsoft 365 ont été respectés dans un délai de 60 jours pour obtenir la certification Microsoft 365 

> [!IMPORTANT]
> **Délai de soumission :** En moyenne, le processus d'évaluation devrait prendre 15 jours, à condition que vous répondiez aux demandes de preuve dans un délai raisonnable. Microsoft vous recommande de vous assurer que ce guide de soumission de certification a été lu et de vous assurer que vous pouvez répondre aux contrôles qui y sont fournis et que vous pouvez fournir suffisamment de preuves avant de commencer le processus de certification. Au démarrage du processus de certification, un maximum de 60 jours est autorisé à effectuer l'évaluation, sinon les preuves déjà collectées deviennent obsolètes. Si, après la période de 60 jours, une évaluation réussie n'est pas atteinte, l'envoi échoue et le processus doit recommencer. Si un échec est émis en raison de l'échec de la spécification de certification Microsoft 365 ou parce que la période de 60 jours est atteinte et que suffisamment de preuves ne sont pas fournies, les résultats défaillants ne seront pas publiés par Microsoft. 

## <a name="compliance-evidence"></a>Preuve de conformité

Bien que cela ne soit pas obligatoire, si vous êtes actuellement en conformité avec d'autres frameworks de sécurité externes, vous pouvez utiliser ces certifications pour satisfaire certains contrôles de certification Microsoft 365. Les analystes de certification passeront en revue l'étendue et la couverture du contrôle de sécurité de toute infrastructure de sécurité externe prise en charge pour déterminer les contrôles qui peuvent être exclus de l'évaluation de certification Microsoft 365, en fournissant l'étendue des cadres de sécurité externes, notamment les environnements dans le cadre de l'évaluation de certification Microsoft 365. 

Les analystes de certification essaieront d'aligner les frameworks de sécurité externes existants sur la spécification de certification Microsoft 365. Toutefois, si la documentation de prise en charge ne peut pas garantir que les contrôles de certification Microsoft 365 ont été évalués dans le cadre de l'audit/l'évaluation des cadres de sécurité externes, vous devrez fournir des preuves supplémentaires des contrôles en place. 

Actuellement, les frameworks de sécurité externes qui peuvent être utilisés pour la prise en charge de l'évaluation de la certification Microsoft 365 sont les suivants :

*  [ISMS](#isms) / [IEC](#iec) - Spécification IS0/IEC 27001 
*  [PCI DSS](#pci-dss)
*  [SOC 2](#soc-2)

La documentation doit démontrer de manière adéquate que l'environnement dans l'étendue de la certification Microsoft 365 était inclus dans le cadre de ces cadres de sécurité externes. La validation de ces cadres de sécurité sera effectuée en acceptant les preuves de certifications valides effectuées par des sociétés tierces dignes de confiance. Ces sociétés fiables doivent être membres d'organismes d'accréditation internationaux pour les programmes de conformité pertinents.Voir [normes de certification iso](https://www.iso.org/certification.html) et de conformité pour ISO 27001 et évaluateurs de sécurité qualifiés (QSA) pour PCI DSS. [](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors) 

Le tableau suivant présente la documentation requise par les analystes de certification dans le cadre de ce processus de validation :

| **Standard** | **Configuration requise** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Une version publique de la déclaration **d'applicabilité** (SOA) et une copie du certificat ISO 27001 émis seront requises.  Le soa récapitule votre position sur chacun des 114 contrôles de sécurité des informations et sera utilisé pour identifier si une exclusion de contrôles qui ne sont pas détaillées de manière satisfaisante dans le certificat ISO 27001. Si cela ne peut pas être déterminé par la révision de la version publique de l'SOA, l'analyste peut avoir besoin d'accéder à l'intégralité de l'SOA si la norme ISO 27001 est utilisée pour valider certains contrôles de spécification de certification Microsoft 365.  Outre la validation de l'étendue des activités d'évaluation ISO 27001, les analystes confirmeront également la validité de la société d'audit comme décrit ci-dessus.|
|**[PCI DSS](#pci-dss)**| Un document AOC (Attestation de conformité de niveau **1)** valide doit être fourni pour identifier clairement l'application et les composants système dans l'étendue.  Un AOC d'auto-évaluation **ne sera** pas accepté comme preuve de la réunion des meilleures pratiques en matière de sécurité. L'AOC sera utilisé pour déterminer les contrôles de spécification de certification Microsoft 365 qui ont été évalués et confirmés dans le cadre de l'évaluation PCI DSS.|
|**[SOC 2](#soc-2)**|Le rapport **SOC 2 (Type I** ou Type II) doit être à jour (émis au cours des 15 derniers mois et la période déclarée démarrée au cours des 27 derniers mois) à utiliser comme preuve de conformité avec l'un des contrôles d'évaluation dans cette spécification de certification Microsoft 365.|


## <a name="microsoft-365-certification"></a>Microsoft 365 Certification

Les frameworks de sécurité externe pris en charge peuvent être utilisés comme preuves de la réunion de certains contrôles de certification Microsoft 365. Avant que les cadres de sécurité externes ne soient pris en compte, les analystes de certification examineront l'étendue et la couverture du contrôle de sécurité de l'infrastructure de sécurité externe à l'aide de la documentation envoyée ci-dessus. 

Les annexes suivantes peuvent être utilisées pour identifier les lacunes potentielles entre l'infrastructure de sécurité externe et la spécification de certification Microsoft 365 comme suit : 

|**Infrastructure** | **Considérations supplémentaires** |
|-------------- | --------------------|
|ISO 27001| [**Annexe C**](#appendix-c): Collecte de preuves – Deltas pour la norme ISO 27001.|
|PCI DSS | [**Annexe D**](#appendix-d): Collecte de preuves – Deltas pour PCI DSS.|
|SOC 2| [**Annexe E**](#appendix-e): Collecte de preuves – Deltas pour SOC 2.|

> [!NOTE]
> Bien que les normes/frameworks de sécurité externes mentionnés ci-dessus peuvent être soumis comme preuves pour répondre à certains contrôles de certification Microsoft 365, le fait de passer la certification Microsoft 365 ne signifie pas que vous réussirez à passer un audit de ces normes/frameworks. La spécification de certification Microsoft 365 n'est qu'un petit sous-ensemble de ces normes/frameworks de sécurité qui permet à Microsoft d'obtenir un niveau d'assurance en référence à votre posture de sécurité.

## <a name="initial-document-submission"></a>Envoi de document initial

La soumission de document initiale permet aux analystes de certification d'effectuer une étendue et de déterminer ce qui sera dans l'étendue de votre évaluation. Après quoi, vous serez tenu de soumettre la documentation de prise en charge et les preuves utilisées pour effectuer l'évaluation. Votre envoi initial doit inclure les informations spécifiées ci-dessous :

| **Vue d'ensemble de &nbsp; la documentation**     |   **Détails de la documentation**  |
| -------------------------| -----------------------------|
|**Description de l'application/du add-in** | Description de l'objectif et des fonctionnalités de l'application/du add-in. Cela doit fournir à l'analyste de certification une bonne compréhension du fonctionnement de l'application/du add-in et de son utilisation prévue.
|**Rapport de test de pénétration** |Un rapport de test de pénétration effectué au cours des 12 derniers mois. Ce rapport doit inclure l'environnement qui prend en charge le déploiement de l'application/de l'ajout, ainsi que tout environnement supplémentaire qui prend en charge le fonctionnement de l'application/du complément. **Remarque :** si vous ne testez pas de pénétration annuelle, vous pouvez les faire passer par le processus de certification.|
|**Diagrammes d'architecture**|Diagramme d'architecture logique représentant une vue d'ensemble de l'infrastructure de prise en charge de votre application/de votre application. Cela doit inclure tous **les environnements** d'hébergement et l'infrastructure de prise en charge de l'application/du add-in. Ce diagramme DOIT décrire tous les différents composants système de prise en charge dans l'environnement pour aider les analystes de certification à comprendre les systèmes dans l'étendue et à déterminer l'échantillonnage. Indiquez également le type d'environnement d'hébergement utilisé . IsV hébergé, IaaS, PaaS ou hybride. **Remarque :** Lorsque SaaS est utilisé, indiquez les différents services SaaS utilisés pour fournir les services de prise en charge dans l'environnement.|
|**Encombrement public** | Détails de **toutes les** adresses IP publiques et URL utilisées par l'infrastructure de prise en charge. Cela doit inclure la plage d'adresses IP routable complète allouée à l'environnement, sauf si une segmentation adéquate a été implémentée pour fractionner la plage en cours d'utilisation (une preuve adéquate de segmentation sera requise)|
|**Diagrammes de flux de données** |Diagrammes de flux détaillant les informations suivantes :
||&#x2713; données M365 circulent vers et depuis l'application/le add-in (y compris [EUII](#euii) et [OII](#oii) ).|
||&#x2713; flux de données M365 au sein de l'infrastructure de prise en charge (le cas échéant)|
||&#x2713; Diagrammes mettant en évidence où et quelles données sont stockées, comment les données sont transmises à des tiers externes (notamment des détails sur les tiers) et comment les données sont protégées en transit sur des réseaux ouverts/publics et au repos.|
|**Détails du point de terminaison de l'API**| Liste complète de tous les points de terminaison d'API utilisés par votre application. Pour mieux comprendre l'étendue de l'environnement, fournissez des emplacements de point de terminaison d'API dans votre environnement.                                
|**Autorisations de l'API Microsoft**| Fournir une documentation détaillant **TOUTES** les API Microsoft utilisées, ainsi que les autorisations demandées pour que l'application/le module fonctionne, ainsi qu'une justification des autorisations demandées|
|**Types de stockage de données** |Stockage de données et gestion des documents décrivant :|
||&#x2713; dans quelle mesure vos clients reçoivent et stockent les [euii](#euii) et [OII](#oii) de données M365|
||&#x2713; période de rétention des données.|
||&#x2713; pourquoi les données M365 du client sont capturées.|
||&#x2713; où les données M365 du client sont stockées (doivent être incluses dans les diagrammes de flux de données fournis ci-dessus).|
|**Confirmation de la conformité**|Documentation de prise en charge des frameworks de sécurité externes inclus dans la soumission de l'attestation publisher ou à prendre en compte lors de la révision des contrôles de certification Microsoft 365. Actuellement, les trois suivants sont pris en charge :|
||&#x2713; attestation [de conformité PCI DSS](#pci-dss) (AOC).|
||&#x2713; rapports [SOC 2](#soc-2) Type I/Type II.|
||&#x2713; [ISMS](#isms)  /  [IEC](#iec) - 1S0/IEC 27001 Déclaration d'applicabilité et de certification.|
|**Dépendances web**|Documentation répertoriant toutes les dépendances utilisées par l'application/le add-in avec les versions en cours d'exécution.|
|**Inventaire logiciel**|Inventaire logiciel à jour qui inclut tous les logiciels utilisés dans l'environnement dans l'étendue, ainsi que les versions.|
|**Inventaire matériel**| Inventaire matériel à jour utilisé par l'infrastructure de prise en charge. Cela sera utilisé pour faciliter l'échantillonnage lors de la phase d'évaluation. Si votre environnement inclut PaaS, fournissez des détails sur les services consommés.|

## <a name="evidence-collection-and-assessment-activities"></a>Activités de collecte et d'évaluation des preuves

Grâce à des activités robustes de collecte de preuves et d'évaluation, les analystes de certification pourront évaluer votre posture de sécurité pour obtenir un niveau adéquat d'assurance de la sécurité des données et le respect des contrôles de spécification de certification Microsoft 365. Les analystes de certification pourront y parvenir comme suit : 

**Collection de preuves**

* Documentation initiale, mise en évidence dans la section Soumission de [documentation](#initial-document-submission) initiale ci-dessus 
* Documents de stratégie 
* Traiter des documents 
* Paramètres de configuration du système 
* Modifier les tickets 
* Modifier les enregistrements de contrôle 
* Rapports système

Diverses méthodes seront utilisées pour collecter les preuves nécessaires à la fin du processus d'évaluation.  Cette collection de preuves peut prendre la forme des éléments ci-après : 
* Documents 
* Captures d’écran 
* Interviews 
* Partage d'écran 

Les techniques de collecte de preuves utilisées seront déterminées pendant le processus d'évaluation. 

**Activités d'évaluation**

Les analystes de certification examineront les preuves que vous fournissez pour déterminer si vous avez correctement satisfait aux contrôles au sein de cette spécification de certification Microsoft 365. 

Dans la mesure du possible et pour réduire le temps nécessaire pour effectuer l'évaluation, tout ou partie de la documentation détaillée dans la soumission de [documentation](#initial-document-submission)initiale doit être fournie   à l'avance.

Les analystes de certification examineront d'abord les preuves fournies à partir de la soumission initiale de la documentation et des informations d'attestation publisher pour identifier les lignes appropriées de la demande, la taille d'échantillonnage et la nécessité d'obtenir d'autres preuves, comme indiqué ci-dessus.  Les analystes de certification analyseront toutes les informations recueillies pour tirer des conclusions quant à la façon dont et si vous êtes en mesure de répondre aux contrôles de cette spécification de certification Microsoft 365. 

## <a name="app-certification-criteria"></a>Critères de certification des applications

Votre application, l'infrastructure de prise en charge et la documentation de prise en charge seront évaluées dans les domaines de sécurité suivants :

1. [**Sécurité des applications**](#application-security)
1. [**Sécurité opérationnelle /Déploiement sécurisé**](#operational-security)
1. [**Sécurité et confidentialité de la gestion des données**](#data-handling-security-and-privacy)
1. [**Révision facultative de l'infrastructure de conformité externe**](#optional-external-compliance-frameworks-review)

Chacun de ces domaines de sécurité inclut des contrôles clés spécifiques englobant une ou plusieurs exigences spécifiques qui seront évaluées dans le cadre du processus d'évaluation. Pour vous assurer que la certification Microsoft 365 est inclusive pour les développeurs de toutes tailles, chacun des quatre domaines de sécurité est évalué à l'aide d'un système de notation afin de déterminer un score global pour chacun des domaines. Les scores pour chacun des contrôles de certification Microsoft 365 sont alloués entre 1 (faible) et 3 (élevé) en fonction du risque perçu de ne pas être atteint. Chacun des quatre domaines de sécurité aura une marque de pourcentage minimale pour être considéré comme une passe. Certains éléments de cette spécification incluent certains critères d'échec automatique :

- Les autorisations d'API ne suivent pas le principe du moindre privilège (PoLP).  
- Aucun rapport de test de pénétration lorsqu'il est nécessaire.
- Aucune protection contre les programmes malveillants
- L'authentification multifacteur n'est pas utilisée pour protéger l'accès administratif.  
- Aucun processus de correction.  
- Aucune notification [de confidentialité R GDPR](#gdpr) appropriée.  

## <a name="application-security"></a>Sécurité des applications

Le domaine de sécurité des applications se concentre sur les trois domaines suivants : 
* Validation des autorisations GraphAPI 
* Vérifications de la connectivité externe
* Test de sécurité des applications 

**Validation des autorisations GraphAPI**

La validation des autorisations GraphAPI est effectuée pour valider l'application/le add-in ne demande pas d'autorisations trop permissives. Pour ce faire, vérifiez manuellement les autorisations demandées. Les analystes de certification référencent ces vérifications par rapport à la soumission d'attestation publisher et évaluent le niveau d'accès demandé pour s'assurer que les pratiques de « privilège minimum » sont respectées. Lorsque les analystes de certification pensent que ces pratiques de « moindre privilège » ne sont pas respectées, les analystes de certification auront une discussion ouverte avec vous pour valider la justification commerciale des autorisations demandées. Toute incohérence par rapport à votre soumission d'attestation publisher trouvée au cours de cette révision reçoit également des commentaires afin que votre attestation publisher puisse être mise à jour. 

**Vérifications de la connectivité externe**

Dans le cadre de l'évaluation, un analyste va passer en détail les fonctionnalités des applications pour identifier les connexions en dehors de M365.  Toutes les connexions qui ne sont pas identifiées comme étant Microsoft ou des connexions directes à votre service seront signalées et abordées au cours de l'évaluation.

**Test de sécurité des applications**

Un examen adéquat des risques associés à votre application/votre add-in et à votre environnement de prise en charge est essentiel pour fournir aux clients des garanties en matière de sécurité de l'application/du add-in. Les tests de sécurité des applications doivent être effectués si votre application dispose d'une connectivité à un service non publié par Microsoft. Si votre application fonctionne de façon autonome sans connectivité à un service ou un système back-end non-Microsoft, le test de pénétration n'est pas requis.


### <a name="penetration-testing-scope"></a>Étendue des tests de pénétration

Les activités  de test de pénétration DOIVENT inclure l'environnement qui prend en charge le déploiement de l'application/du complément (par exemple, l'endroit où le code de l'application/du complément est hébergé, qui sera généralement la ressource dans le fichier manifeste), ainsi que tout environnement supplémentaire qui prend en charge le fonctionnement de l'application/du complément (par exemple, si l'application/le complément discute avec d'autres applications web en dehors de Microsoft 365).  Lors de la définition de l'étendue, veillez à vous assurer que tous les systèmes ou environnements « connectés » qui peuvent avoir un impact sur la sécurité de l'environnement dans l'étendue sont également inclus dans toutes les activités de test de pénétration. 

Lorsque des techniques sont utilisées pour segmenter les environnements dans l'étendue d'autres environnements, les activités de test de pénétration DOIVENT valider l'efficacité de ces techniques de segmentation. Cela doit être détaillé dans le rapport de test de pénétration. 
 

### <a name="testspecification"></a>Spécification de test 

|Tester | Contrôles |
|-------|-----------|
|**Test de pénétration**| Les tests de pénétration des applications et **de** l'infrastructure DOIVENT avoir lieu chaque année (tous les 12 mois) et effectués par une société indépendante de confiance. La correction des vulnérabilités  critiques et à haut risque identifiées DOIT être effectuée dans un délai d'un mois après la fin du test de pénétration, ou plus tôt en fonction du processus de correction documenté.L'empreinte externe complète (adresses IP, URL, points de terminaison d'API, etc.) DOIT être inclus dans la portée du test de pénétration et doit être documenté dans le rapport de test de pénétration. L'encombrement externe complet (adresses IP, URL, points de terminaison d'API, etc.) **DOIT** être inclus dans la portée du test de pénétration et doit être documenté dans le rapport de test de pénétration.                                                                                                                                                                           Le test de pénétration d'application Web DOIT inclure toutes les classes de vulnérabilité ; par exemple, les plus récents OWASP Top 10 ou SANS Top 25 CWE.                                                                                                                                                                                Il n'est pas nécessaire de tester à nouveau les vulnérabilités identifiées par l'entreprise de test de pénétration . Toutefois, une correction et un auto-examen suffisent pour démontrer que des mesures correctives suffisantes doivent être fournies pendant l'évaluation. |

### <a name="application-security-testing-reportreview"></a>Examen du rapport de test de sécurité des applications

Les rapports de test de pénétration sont examinés pour s'assurer qu'aucune vulnérabilité ne répond aux critères d'échec **automatique suivants :**

* Présence d'un système d'exploitation non pris en charge. 

* Présence de comptes d'administration par défaut, éumables ou devinables.

* Présence de SQL d'injection.*

* Présence de scripts entre sites.*

* Présence de vulnérabilités de traversée d'annuaire (chemin d'accès au fichier).*

* Présence de vulnérabilités HTTP, par exemple, fractionnement de réponse d'en-tête, demandes de habilitation et attaques de desync.*

* Présence de la divulgation de code source (y compris [LFI](#lfi)).*

* Tout score critique ou élevé défini par les instructions de gestion des correctifs CVSS.

* Toute vulnérabilité technique importante qui peut être facilement exploitée pour compromettre une grande quantité d'EUII ou d'OUI.

*Quelles que soient les vulnérabilités CVSS Score

> [!IMPORTANT]
>Les rapports doivent être en mesure de fournir suffisamment d'assurance que tout ce qui est détaillé dans la section Spécification du test de sécurité des applications peut être démontré.


### <a name="penetration-testing-requirements-and-cost"></a>Exigences et coût des tests de pénétration

Pour les isv qui ne s'engagent actuellement pas dans les tests de pénétration, le test de pénétration est inclus dans la certification Microsoft 365. Microsoft organise et couvre le coût d'un test de pénétration pendant 12 jours de test manuel. Les coûts des tests de pénétration sont calculés en fonction du nombre de jours nécessaires pour tester l'environnement. Toute dépense dépassant 12 jours de test sera la responsabilité de l'isv. L'isv est également chargé de démontrer que les vulnérabilités identifiées dans le test de pénétration ont été corrigés avant l'octroi d'une certification, mais qu'il n'est pas nécessaire de produire un rapport propre.

Une fois qu'un test de pénétration est organisé, l'isv est responsable des frais associés à la planification et aux annulations comme suit :

| **Rescheduling Fee Timescale** | **Proportion Due** |
|------------------|------------------------|
| Re-planifier la demande reçue plus de 30 jours avant la date de début prévue. | 0 % due |
| Retentez la demande reçue 8 à 30 jours avant la date de début prévue. | 25 % Due |
| Re planning request received within 2 to 7 days prior to scheduled start date with a firm re-booking date.| 50 % Due |
| Re-planifier la demande reçue moins de 2 jours avant la date de début. | 100 % Due |

| **Échelle de temps des frais d'annulation** | **Proportion Due** |
|------------------|------------------------|
| La demande d'annulation a été reçue plus de 30 jours avant la date de début prévue. | 25 % Due |
| Demande d'annulation reçue 8 à 30 jours avant la date de début prévue. | 50 % Due |
| Demande d'annulation reçue dans les 7 jours avant la date de début prévue. | 90 % Due |

## <a name="operational-security"></a>Sécurité opérationnelle

Ce domaine mesure l'alignement des processus d'infrastructure et de déploiement de votre application avec les meilleures pratiques en matière de sécurité.

### <a name="test-specification"></a>Spécification de test

|Tester | Contrôles |
| ------------------------|------------------------------ |
| **Protection contre les programmes malveillants** | Vous devez déployer des mécanismes de protection contre les programmes malveillants sur tous les systèmes au niveau de l'étendue qui sont couramment affectés par les programmes malveillants. Ces mécanismes de protection peuvent inclure l'utilisation de logiciels antivirus ou de techniques de contrôle d'application qui protègent contre les programmes malveillants. Lorsque le logiciel antivirus ou le contrôle d'application est utilisé, il DOIT répondre aux critères suivants.                                                                                            L'antivirus (y compris les produits anti-programme malveillant) DOIT répondre aux exigences suivantes : |
||&#x2713; logiciel antivirus est en cours d'exécution sur tous les composants système dans l'étendue.|
||&#x2713; logiciel antivirus est tenu à jour (dans un délai de 30 jours).|
||&#x2713; signatures antivirus sont tenues à jour (dans un délai d'un jour).|
||&#x2713; l'analyse à l'accès et/ou les analyses périodiques avec notifications doivent être configurées.  Lorsque l'analyse sur accès est utilisée, les analyses **hebdomadaires** DOIVENT également être configurées. Toutefois, si l'analyse sur accès n'est pas configurée, l'analyse quotidienne doit être configurée.|
||&#x2713; logiciel antivirus **DOIT être** configuré comme suit.|
||&emsp;&#x25fc; bloquer les programmes malveillants suspects.|
||&emsp;&#x25fc; mettre en quarantaine les programmes malveillants suspects.|
||&emsp;&#x25fc; fournir une alerte sur les programmes malveillants suspects.|
||&#x2713; logiciel antivirus doit **être** configuré pour enregistrer toutes les activités.
||&#x2713; stratégies et procédures **doivent** être en place pour promouvoir des pratiques anti-programme malveillant fortes.|
||ou|
||Les contrôles d'application DOIVENT être configurés sur tout le système dans l'étendue pour répondre aux exigences suivantes :|
||&#x2713; toutes les applications autorisées à s'exécuter sur des composants système au niveau de l'étendue DOIVENT être approuvées officiellement par l'organisation.|
||&#x2713; L'organisation DOIT tenir à jour une liste complète des applications approuvées avec une justification professionnelle pour l'application.|
||&#x2713; des mécanismes de contrôle d'application spécifiques DOIVENT être entièrement documentés : emplacements de liste blanche ; signature de code, etc.|
||&#x2713; Contrôle d'application doit être configuré en tant que document.|
||&#x2713; documented process for application approvals must be in place and auditable.|
|**Gestion des correctifs**|Vous **DEVEZ avoir** documenté les stratégies et procédures de correction en place pour vous assurer que la mise à jour des correctifs est effectuée en temps voulu. Un processus  robuste DOIT être en place pour identifier, classer et mettre à jour les nouvelles vulnérabilités de sécurité en fonction des scores de classement des risques recommandés CVSS V3.1 ou d'une taxonomie de score équivalente : 
||**Scores de classement des risques** recommandés (plage de score de base CVSS v3.1)|
||&emsp;**Critique**: 9.0 - 10.0.|
||&emsp;**Élevé**: 7.0 - 8.9.|
||&emsp;**Moyenne**: 4,0 - 6,9.|
||&emsp;**Faible**: 0,1 - 3,9.|
||&emsp;**Aucun**: 0.0 |
|| **IMPORTANT**: le processus d'identification des nouvelles vulnérabilités doit être suffisamment robuste pour permettre l'identification et la correction des vulnérabilités en ligne avec la fenêtre de correction documentée que vous avez définie. |
|**Patching**|&#x2713; Les problèmes **critiques,** élevés ou à risque moyen DOIVENT être corrigés au cours d'une période pré-déterminée  et documentée décidée par l'isv, qui représente la période minimale avant que le problème ne soit résolu.  Bien que la fenêtre de correction soit définie par l'isv, elle doit être dans un délai raisonnable. Par exemple, trois mois pour mettre à jour une vulnérabilité critique ne seraient pas raisonnables et par conséquent rejetés dans votre évaluation de certification Microsoft 365.|
||&#x2713; stratégies et procédures détaillant le mode  de mise à  jour des correctifs doivent être en place et inclure tous les systèmes d'exploitation, applications et composants logiciels applicables utilisés dans l'environnement. Cela inclut toutes les dépendances web utilisées au sein de l'application/du add-in.|
||&#x2713; composants logiciels et systèmes d'exploitation ne sont plus pris en charge par le fournisseur NE **DOIVENT** pas être utilisés dans l'environnement. Des  stratégies de prise en charge DOIVENT être en place pour garantir que les composants logiciels/systèmes d'exploitation non pris en charge seront supprimés de l'environnement et qu'un processus permettant d'identifier la fin de vie des composants logiciels doit être en place.|
|**Analyse des vulnérabilités**|L'analyse des vulnérabilités doit inclure :|
||&#x2713;'analyse trimestrielle des vulnérabilités externes effectuée  sur l'empreinte publique complète de l'environnement dans l'étendue (URL ET adresses IP pour l'analyse de l'infrastructure et des applications Web).|
||&#x2713;'analyse trimestrielle des vulnérabilités internes authentifiées effectuées sur des composants système dans l'étendue (et non pour PaaS).|
||&#x2713; Une stratégie de correction  des vulnérabilités documentée DOIT être en place pour garantir que les composants système ne sont pas exempts de vulnérabilités connues en détaillant la chronologie de résolution des vulnérabilités en fonction de vos scores de classement des risques recommandés **CVSS** définis (voir ci-dessus).|
||&#x2713; des analyses en cours DOIVENT être effectuées jusqu'à ce que les **vulnérabilités** classées à risque identifié soient corrigés dans la chronologie requise, comme défini par la stratégie de correction de l'isv. Bien que la chronologie de correction soit définie par l'isv, la fenêtre doit être dans un délai raisonnable. Par exemple, trois mois pour corriger une vulnérabilité critique ne seraient pas raisonnables et par conséquent rejetés dans votre évaluation de certification Microsoft 365.|
|**Pare-feu**|Votre infrastructure de prise en charge doit avoir un pare-feu (ou un équivalent dans lequel les services Cloud sont en cours de consommation) configuré comme suit :|
||&#x2713; doit **être** installé sur toutes les connexions Internet exposant les environnements dans l'étendue.|
||&#x2713; doit **être** installé entre toutes les zones DMZ (zones démilitarisées) et tous les réseaux fiables.|
||&#x2713; tous les accès publics **DOIVENT** s'interrompre dans une zone DMZ (zone démilitarisée). |
||&#x2713; les informations d'identification administratives par défaut **DOIVENT être** modifiées avant l'installation dans les environnements de production.|
||&#x2713; tout le trafic autorisé par le biais de pare-feu dans l'étendue (dans les deux **sens)** DOIT passer par un processus d'approbation et tous les protocoles, services et ports doivent être documentés avec des justifications professionnelles.|
||&#x2713; règles de pare-feu doivent être configurées en ligne avec les règles autorisées documentées.|
||&#x2713; chiffrement fort, en ligne avec **l'Annexe B,** **DOIT** être activé sur toutes les interfaces d'administration non console de pare-feu.|
||&#x2713; l'authentification multifacteur (MFA) **DOIT** être activée pour l'accès administratif pare-feu.|
||&#x2713; examens du pare-feu **doivent** être effectués au moins tous les six mois.|
||L'analyse de certification examine la base des règles de pare-feu pour vérifier la présence de flux de trafic de sortie vers des tiers potentiels afin de valider le partage de données tierces externes.  |
||**Pare-feu d'application web (WAF).** Un crédit supplémentaire est accordé si un waf ou une mesure équivalente est déployé pour vous protéger contre les menaces et les vulnérabilités des applications web. S'il est présent, les stratégies et procédures de prise en charge **doivent** être en place avec les configurations WAF suivantes : |
||&#x2713; WAF doit fonctionner en mode de défense active (bloquant automatiquement les attaques identifiées) ou en mode de surveillance (surveillance/analyse active des alertes).|
||&#x2713; WAF configuré pour prendre en charge le déchargement [SSL.](#ssl)|
||&#x2713; WAF doit être configuré selon l'ensemble de règles principales [OWASP](#owasp) ****   (3.0 ou 3.1) pour se protéger contre la majorité des éléments suivants :|
||&emsp;&#x25fc; protocole et les problèmes de codage.|
||&emsp;&#x25fc; l'injection d'en-tête, la demande et le fractionnement de réponse.|
||&emsp;&#x25fc; attaques par traversée de fichier et de chemin d'accès.|
||&emsp;&#x25fc;'inclusion de fichiers distantes (RFI).|
||&emsp;&#x25fc; attaques d'exécution de code à distance.|
||&emsp;&#x25fc; attaques par injection php.|
||&emsp;&#x25fc; attaques par scripts entre sites.|
||&emsp;&#x25fc; SQL d'injection de matériel.|
||&emsp;&#x25fc; attaques par attachement de session.|
|**Contrôle des changements**|Les **stratégies** et procédures de contrôle des modifications DOIVENT être en place pour garantir que les modifications sont implémentées d'une manière visant à maintenir la sécurité, la stabilité et l'intégrité de l'environnement. Les critères de contrôle des changements **suivants sont** requis :|
||&#x2713; séparation des tâches : les environnements de développement et de test **DOIVENT** être séparés des environnements de production.|
||&#x2713; données sensibles des environnements de production **NE DOIVENT** pas être utilisées dans les environnements de développement/test.|
||&#x2713; toutes les modifications DOIVENT être testées dans un environnement de test/développement avant d'être introduites dans l'environnement de production.|
||&#x2713; demandes de **modification sont** élevées et autorisées **AVANT** de passer en production.|
||&#x2713; au minimum, les demandes de modification **DOIVENT** inclure :|
||&emsp;&#x25fc; documentation d'impact.|
||&emsp;&#x25fc; procédures de back-out documentées.|
||&#x2713; les demandes de **modification DOIVENT** être marquées comme étant terminées, uniquement **une** fois que le test des fonctionnalités a été effectué.|
|**Sécurisation du développement/déploiement de logiciels**|La sécurité doit être à l'avant-plan des pratiques de développement de logiciels pour minimiser le risque d'introduire des vulnérabilités de codage dans l'application/le add-in, ce qui permet de maintenir un environnement sécurisé et de sécuriser les données. Les pratiques de sécurité de développement logiciel **suivantes DOIVENT** être en place : |
||&#x2713; vous DEVEZ avoir un processus de développement de logiciels établi et documenté couvrant l'ensemble du cycle de vie du développement logiciel.|
||&#x2713; toutes les modifications de code DOIVENT être traitées par un processus de révision et d'autorisation par une personne autre que le développeur d'origine.|
||&#x2713; pratiques de codage sécurisé et les **techniques** de révision DOIVENT traiter les 10 premières classes de vulnérabilité [OWASP](https://owasp.org/www-project-top-ten) ou [SANS Top 25 CWE.](https://www.sans.org/top25-software-errors)|
||&#x2713; développeurs **DOIVENT suivre une** formation en programmation logicielle sécurisée au moins une fois par an.|
||&#x2713; référentiels de code **doivent** être sécurisés par l'mf.|
||&#x2713; des contrôles d'accès appropriés **DOIVENT** être en place pour protéger les référentiels de code contre les modifications de code malveillantes.|
||**Remarque**: Microsoft [](https://www.microsoft.com/en-us/securityengineering/sdl/) a publié le cycle de vie du développement de la sécurité (SDL) que Microsoft suit pour prendre en charge les exigences de sécurité et de conformité au sein de ses produits. Le SDL permet aux développeurs de créer des logiciels plus sécurisés en réduisant le nombre et la gravité des vulnérabilités dans les logiciels, tout en réduisant les coûts de développement.|
|**Gestion des comptes**| La gestion des comptes de composants système dans l'étendue, ainsi que les stratégies et procédures de prise en charge **DOIVENT** respecter les exigences suivantes : |
||&#x2713; les informations d'identification par défaut  (fournisseur ou éditeur de logiciels isv) sont désactivées ou supprimées dans tous les composants système dans l'étendue.|
||&#x2713; création, modification et suppression d'un compte **DOIT** passer par un processus d'approbation établi.|
||&#x2713; comptes qui n'ont pas été utilisés  depuis plus de 3 mois DOIVENT être désactivés ou supprimés, par conséquent, les isv doivent avoir un mécanisme pour y parvenir.|
||&#x2713;stratégies de mot de passe fortes ou toute autre atténuation **appropriée DOIT** être configurée pour protéger les informations d'identification de l'utilisateur. La stratégie de mot de passe suivante doit être utilisée à titre indicatif :|
||&emsp;&#x25fc; longueur minimale du mot de passe de huit caractères|
||&emsp;&#x25fc; seuil de verrouillage du compte de 10 tentatives au plus|
||&emsp;&#x25fc;'historique des mots de passe d'au moins cinq mots de passe|
||&emsp;&#x25fc; l'application de l'utilisation de mots de passe forts|
||&#x2713; comptes d'utilisateur uniques DOIVENT être émis à chaque utilisateur ; aucun compte partagé ne doit être utilisé.|
||&#x2713; principes des privilèges minimum **DOIVENT** s'appliquer à tous les utilisateurs, le mécanisme utilisé pour y parvenir doit être documenté (c'est-à-dire, l'utilisation de groupes). |
||&#x2713; le renforcement du  compte de service approprié DOIT être documenté et exécuté, par exemple, une connexion interactive désactivée, des connexions limitées à des hôtes spécifiques, etc. |
||&#x2713; solutions d'accès à distance **DOIVENT**: |
||&emsp;&#x25fc; utiliser l'authentification multifacteur (Multi Factor Authentication)|
||&emsp;&#x25fc; utiliser un profil de protection des données en transit qui répond ou dépasse le profil de configuration des données en transit, comme décrit dans l'Annexe A|
||&#x2713; Lorsque la gestion du DNS public se trouve en dehors de l'environnement dans l'étendue, tous les comptes d'utilisateurs en mesure d'apporter des modifications DNS DOIVENT être configurés pour utiliser l'mf.|
||**Remarque** : les portails de gestion cloud doivent également répondre aux exigences de gestion des comptes applicables, consultez l'Annexe F pour plus d'informations.|
|**Détection et prévention des intrusions (FACULTATIF)**| Un crédit supplémentaire est accordé lorsque le système de détection et de prévention des intrusions (IDPS) est utilisé dans le périmètre des environnements de prise en charge dans l'étendue.  Les contrôles recommandés suivants sont les suivants : |
||&#x2713; IDPS doit être déployé sur le périmètre de l'environnement de prise en charge |
||&#x2713; signatures IDPS doivent rester à jour au cours du dernier jour |
||&#x2713; IDPS doit être configuré pour l'inspection TLS |
||&#x2713; IDPS DOIT être configuré pour TOUT le trafic entrant et sortant |
||&#x2713; IDPS doit être configuré pour les alertes |
|**Journalisation des événements** |La couverture de **journalisation DOIT** inclure **TOUS** les composants et applications système dans l'étendue, y compris les mécanismes de protection contre les programmes malveillants. Les événements **suivants DOIVENT** être enregistrés :|
||&emsp;&#x25fc; aux utilisateurs d'accéder aux composants système et à l'application|
||&emsp;&#x25fc; toutes les actions entreprises par un utilisateur avec des privilèges élevés|
||&emsp;&#x25fc; tentatives d'accès logique non valides|
||&emsp;&#x25fc; création/modification de compte privilégié|
||&emsp;&#x25fc; journal des événements|
||&emsp;&#x25fc; désactivation des outils de sécurité ; par exemple, la journalisation des programmes malveillants ou des événements|
||&emsp;&#x25fc; journalisation anti-programme malveillant ; par exemple, mises à jour, détection de programmes malveillants, échecs d'analyse|
||&emsp;&#x25fc; événements IDPS/WAF (s'il est configuré)|
||Les journaux des **événements DOIVENT** inclure les informations suivantes :|
||&emsp;&#x25fc;'identification de l'utilisateur |
||&emsp;&#x25fc; type d'événement |
||&emsp;&#x25fc; date et heure |
||&emsp;&#x25fc; de réussite/d'échec|
||&emsp;&#x25fc; étiquette pour identifier le système concerné |
||La synchronisation de temps **DOIT être** utilisée dans tous les composants système dans l'étendue pour faciliter les enquêtes d'investigation.|
||La synchronisation de temps **DOIT être** configurée pour utiliser la même source de temps principale (et secondaire si nécessaire)|
||Les systèmes publics (systèmes au sein de la zone DMZ) **DOIVENT** écrire des journaux dans un référentiel de journalisation centralisée interne. Le référentiel de journalisation centralisée ne doit pas se trouver dans le DMZ.|
||Les pistes **d'audit** DOIVENT être sécurisées pour s'assurer que les données du journal ne peuvent pas être modifiées par un acteur de menace. L'accès au référentiel de journalisation centralisée doit être limité au personnel autorisé uniquement.|
||Les **journaux DOIVENT** être immédiatement disponibles pendant 30 jours. Les données **de journalisation** DOIVENT être conservées pendant au moins 90 jours.|
|**Révision** |Les processus de révision ainsi que les stratégies et procédures de prise en **charge DOIVENT** respecter les exigences suivantes :|
||&#x2713; effectuez des révisions quotidiennes des journaux ou utilisez l'analyse automatique des journaux et la technologie d'alerte pour passer en revue les événements de tous les composants système dans l'étendue afin d'identifier les événements de sécurité potentiels.|
||&#x2713; événements de sécurité **potentiels DOIVENT** être immédiatement suivis.|
|**Alerte** |Les processus d'alerte ainsi que les stratégies et procédures de prise en **charge DOIVENT** respecter les exigences suivantes : |
||&#x2713; événements de sécurité consignés qui représentent un risque pour la sécurité de vos systèmes, opérations ou données DOIVENT déclencher une alerte immédiate, par exemple (liste non exhaustive) :|
||&emsp;&#x25fc; création/modifications de compte Privilège|
||&emsp;&#x25fc; événements de programmes malveillants|
||&emsp;&#x25fc; désactivation des outils de sécurité|
||&emsp;&#x25fc; journal des événements|
||&emsp;&#x25fc; événements IDPS/WAF (s'il est configuré) |
||&#x2713; personnel doit toujours être disponible (24/24/7) pour réagir aux alertes déclenchées.|
|**Gestion des risques**|Une méthodologie d'évaluation des risques doit être développée et menée avec les méthodes suivantes :|
||&#x2713; processus formellement défini.|
||&#x2713; effectuée au moins une fois par an.|
||&#x2713; inclut tous les biens au sein de l'environnement dans l'étendue.|
||&#x2713; identifie les menaces et les vulnérabilités contre toutes les ressources incluses.|
||&#x2713; inclut l'utilisation de matrices d'impact et de probabilité définies.|
||&#x2713; entraîne la création d'un registre de risque et d'un plan de traitement des risques correspondant.|
|**Réponse aux incidents**|Un plan de réponse aux incidents approfondi **est requis** et **DOIT** inclure au minimum :|
||&#x2713; au minimum la couverture des composants et applications des systèmes au niveau de l'étendue.|
||&#x2713; procédures de réponse aux incidents spécifiques pour les modèles de menace attendus.|
||&#x2713; processus de communication documenté, garantissant la notification en temps voulu de toutes les parties prenantes clés et des organismes externes pertinents tels que ; marques/acquisitions de paiement, organismes de réglementation et autorités de surveillance[(R GDPR)](#gdpr)conformes aux exigences de rapport requises.|
||&#x2713; réponse aux incidents est mise à jour en fonction des leçons apprises, des modifications organisationnelles et de l'intégration des développements du secteur.|
||&#x2713; formation annuelle pour les membres de l'équipe de réponse aux incidents.|

## <a name="data-handling-security-and-privacy"></a>Sécurité et confidentialité de la gestion des données

Les données en transit entre l'utilisateur de l'application, les services intermédiaires et les systèmes isv doivent être protégées par chiffrement via une connexion TLS qui permet de prendre en charge un minimum de TLS v1.1. *Voir* [**l'annexe A**](#appendix-a).

Lorsque votre application récupère et stocke des données M365, vous devez implémenter un schéma de chiffrement de stockage de données qui suit la spécification définie dans [**l'Annexe B**](#appendix-a).

### <a name="test-specification"></a>Spécification de test

|Tester | Contrôles |
| -----------------------|-------------------------------- |
|**Données en transit**| La transmission de données sensibles DOIT utiliser un minimum de TLS 1.1 à quelques exceptions près décrites dans l'Annexe A.|
||La transmission des données sensibles **DOIT** être chiffrée de manière conforme aux profils de chiffrement décrits à l'Annexe B.|
||La compression TLS doit être désactivée.|
||HSTS (HTTP Strict Transport Security) **DOIT** être configuré pour >= 15552000|
|**Données au repos**| Le stockage  des données sensibles DOIT être protégé en fonction des profils de chiffrement décrits dans l'annexe B, qui couvrent les exigences minimales en matière de chiffrement, d'algorithmes, de tailles de clés, de hachage et d'authentification des messages.|
||Tous les types de données stockés DOIVENT être documentés.|
|**Conservation et suppression de données**|Le stockage des données sensibles **DOIT** être maintenu au minimum en implémentant des stratégies de rétention et de destruction des données, des procédures et des processus qui incluent au minimum :|
||&#x2713; documenter et limiter la quantité de stockage et la durée de rétention des données à celle requise pour les exigences légales, réglementaires et/ou professionnelles.|
||&#x2713; documentez et déployez des processus pour la suppression sécurisée des données sensibles lorsque cela n'est plus nécessaire, en ligne avec les stratégies documentées.|
||&#x2713; documentez et déployez un processus trimestrielle pour identifier et supprimer en toute sécurité les données sensibles stockées qui dépassent la période de rétention définie.|
|**Gestion de l'accès aux données**|Le fait de limiter l'accès aux données à ceux qui ont une raison professionnelle légitime permet aux organisations d'éviter toute mauvaise gestion des données sensibles par le biais d'une faute ou d'un malice. Les données sensibles reçues par l'application/le add-in et l'accès aux clés de chiffrement nécessitent une approbation documentée (électronique ou par écriture) pour que les parties autorisées à tous les niveaux d'accès y accèdent et doivent inclure une liste de privilèges approuvés et vérifiés montrant que la stratégie intègre les exigences spécifiées comme suit : |
||&#x2713; définition des besoins d'accès et des attributions de privilèges uniquement aux rôles qui nécessitent spécifiquement un accès privilégié de ce type. |
||&#x2713; l'accès aux privilèges minimum nécessaires pour effectuer les tâches.|
||&#x2713; vous assurer que des accords de partage de données sont en place avec tous les tiers qui consomment des données M365.|
|**RGPD**| Dans le cadre du processus de certification Microsoft 365, vous devez démontrer votre adhésion au R GDPR, soit par :|
||&#x2713; un examen indépendant de la conformité R GDPR par une société d'audit externe expérimentée. Vous devez soumettre le rapport pour révision ou autoriser l'analyste à afficher le rapport. Le rapport doit fournir suffisamment de détails pour non seulement valider l'évaluation de l'auditeur externe, mais aussi pour fournir suffisamment de confiance que l'examen externe a confirmé la conformité au R GDPR.|
||ou|
||&#x2713; la soumission de preuves supplémentaires pour fournir une garantie supplémentaire de votre engagement en matière de lois sur la confidentialité des données, comme suit :|
||&#x25fc; processus documenté de demande d'accès de l'objet (R.A.S.) conçu pour répondre aux demandes des clients et répondre à l'exigence de trente jours du R GDPR. Il est recommandé de mettre en place des outils de découverte de données appropriés pour s'assurer qu'une recherche de données sarmentée est remplie dans ces délais. **Remarque** : lorsque ces outils ne sont pas utilisés, vous devez montrer comment cela fonctionne et montrer comment les processus sont en mesure de garantir la découverte de toutes les informations de la sujet de données.|
||&#x25fc;confidentialité doivent être présentes sur le site web et contenir les informations suivantes :
||
||Lorsqu'un rapport R GDPR indépendant n'est pas disponible, les informations suivantes doivent être en place pour être examinées dans le cadre de l'évaluation de la certification M365 : |
||&#x2713; processus documenté de demande d'accès de l'objet (R.A.S.) conçu pour répondre aux demandes des clients et répondre à l'exigence de trente jours du R GDPR.  Il est recommandé de mettre en place des outils de découverte de données appropriés pour garantir la réalisation d'une recherche de données dans ces délais, où ces outils ne sont pas utilisés, vous devez montrer comment cela fonctionne et montrer comment les processus sont en mesure de garantir la découverte des informations de toutes les personnes qui sont soumises aux données.|
||&#x2713; confidentialité doivent être présentes sur le site web et contenir les informations suivantes :|
||&emsp;&emsp;&#x25a1; les coordonnées des organisations.|
||&emsp;&emsp;&#x25a1; type de données personnelles en cours de traitement.|
||&emsp;&emsp;&#x25a1; légale du traitement des données personnelles (*article 6*).|
||&emsp;&emsp;&#x25a1; détails des droits de la personne objet de données :|
||&emsp;&emsp;&#x25a1; droit d'être informé (*Articles 13 et 14*).
||&emsp;&emsp;&#x25a1; d'accès par la objet de données (*Article 15*).|
||&emsp;&emsp;&#x25a1; droit de rectification (*article 16*).|
||&emsp;&emsp;&#x25a1; droit à l'effacement (*article 17*).|
||&emsp;&emsp;&#x25a1; droit à la restriction du traitement (*Article 18*).|
||&emsp;&emsp;&#x25a1; droit à la portabilité des données (*Article 20*).|
||&emsp;&emsp;&#x25a1; droit à l'objet (*article 21*).|
||&emsp;&emsp;&#x25a1; droits en relation avec le marquage automatique des décisions, y compris le profilage (*article 22*).|
||&#x2713; partage d'informations avec des tiers doit avoir des accords en place pour garantir que le traitement des données de la personne concernée est conforme aux lois sur la confidentialité des données.|

## <a name="optional-external-compliance-frameworks-review"></a>Révision facultative des frameworks de conformité externe

Si des frameworks de sécurité externes ont été inclus dans l'attestation Publisher, les analystes de certification devront vérifier la validité de ces frameworks de conformité de sécurité dans le cadre de l'évaluation de la certification Microsoft 365.
Les preuves des frameworks de conformité de sécurité externe pris en charge suivants sont les suivantes :

* [ISMS](#isms) /  [IEC](#iec) - Spécification IS0/IEC 27001</h5>
* [PCI DSS](#pci-dss)
* [SOC 2](#soc-2)

La documentation identifiée dans la section [Preuve de](#compliance-evidence) conformité sera utilisée pour effectuer cette révision.

### <a name="test-specifications"></a>Spécifications de test

&#x2713; l'environnement de prise en  charge des  applications/des applications et des applications et tout processus d'entreprise de prise en charge DOIVENT être inclus dans l'étendue des frameworks de conformité de sécurité externe pris en charge et doivent être clairement indiqués dans la documentation fournie.

&#x2713; Les **frameworks** de conformité de sécurité externe pris en charge DOIVENT être à jour, c'est-à-dire au cours des 12 derniers mois (ou dans les 15 derniers mois si la réévaluation est en cours d'évaluation et que des preuves peuvent être fournies).

&#x2713; les cadres de conformité de sécurité externe pris en charge **DOIVENT** être exécutés par une société agréée indépendante.

## <a name="appendix-a"></a>Annexe A

### <a name="tls-profile-configuration-requirements"></a>Configuration requise pour le profil TLS

Tout le trafic réseau, qu'il s'agit d'un réseau virtuel, d'un service cloud ou d'un centre de données, doit être protégé avec un minimum de TLS v1.1 (TLS v1.2+ est recommandé) ou tout autre protocole applicable. Les exceptions à cette exigence sont :

* **Redirection HTTP vers HTTPS.** Votre application peut répondre sur HTTP pour rediriger les clients vers HTTPS, mais la réponse ne doit pas contenir de données sensibles (cookies, en-têtes, contenu). Aucune autre réponse HTTP autre que les redirections vers HTTPS et la réponse aux sondes d'état sont autorisées. Voir ci-dessous.
* **Sondes d'état d'santé.** Votre application peut répondre aux sondes d'état sur **HTTP** uniquement si les sondes d'état HTTPS ne sont pas pris en charge par la partie cochante.
* **Accès au certificat.** L'accès aux points de terminaison CRL, OCSP et AIA à des fins de validation de certificat et de vérification de révocation est autorisé sur HTTP.
* **Communications locales**. Votre application peut utiliser le protocole HTTP (ou d'autres protocoles non protégés) pour les communications qui ne quittent pas le système d'exploitation, e. g. connexion à un point de terminaison de serveur web exposé sur localhost.

La compression TLS **DOIT** être désactivée.

## <a name="appendix-b"></a>Annexe B

### <a name="encryption-profile-configuration-requirements"></a>Conditions requises pour la configuration du profil de chiffrement

Seuls les paramètres et primitives de chiffrement sont autorisés comme suit :

### <a name="symmetric-cryptography"></a>Chiffrement symétrique

**Chiffrement**

&emsp;&#x2713; seuls AES, BitLocker, Erdonne ou TDES sont autorisés. Toutes les longueurs de clé >=128 sont autorisées (128, 192 et 256 bits) et peuvent être utilisées (les clés 256 bits sont recommandées).

&emsp;&#x2713; seul le mode CBC est autorisé. Chaque opération de chiffrement doit utiliser un nouveau vecteur d'initialisation généré de manière aléatoire (IV).

&emsp;&#x2713;'utilisation de chiffrements de flux, tels que RC4, **N'est PAS** autorisée.

**Fonctions de hachage**

&emsp;&#x2713; tout nouveau code doit utiliser SHA-256, SHA-384 ou SHA-512 (collectivement appelé SHA-2). La sortie peut être tronquée sur au moins 128 bits

&emsp;&#x2713; SHA-1 ne peut être utilisé que pour des raisons de compatibilité.

&emsp;&#x2713;'utilisation de MD5, MD4, MD2 et autres fonctions de hachage n'est PAS autorisée, même pour les applications non cryptographiques.

**Authentification des messages**

&emsp;&#x2713; tout nouveau code DOIT utiliser HMAC avec l'une des fonctions de hachage approuvées. La sortie de HMAC peut être tronquée sur au moins 128 bits.

&emsp;&#x2713; HMAC-SHA1 ne peut être utilisé que pour des raisons de compatibilité.

&emsp;&#x2713; clé HMAC doit être d'au moins 128 bits. Les clés 256 bits sont recommandées.

### <a name="asymmetric-algorithms"></a>Algorithmes asymétriques

**Chiffrement**

&emsp;&#x2713; RSA est autorisé. La **clé DOIT** être d'au moins 2 048 bits et le remplissage OAEP doit être utilisé. L'utilisation du remplissage PKCS n'est autorisée que pour des raisons de compatibilité.

**Signatures**

&emsp;&#x2713; RSA est autorisé. La **clé DOIT** être d'au moins 2 048 bits et le remplissage PSS doit être utilisé. L'utilisation du remplissage PKCS n'est autorisée que pour des raisons de compatibilité.

&emsp;&#x2713;'ECDSA est autorisé. La **clé DOIT** être d'au moins 256 bits. La courbe NIST P-256, P-384 ou P-521 doit être utilisée.

**Échange de clés**

&emsp;&#x2713; ECDH est autorisé. La **clé DOIT** être d'au moins 256 bits. La courbe NIST P-256, P-384 ou P-521 doit être utilisée.

&emsp;&#x2713; l'ECDH est autorisé. La **clé DOIT** être d'au moins 256 bits. La courbe NIST P-256, P-384 ou P-521 doit être utilisée.

## <a name="appendix-c"></a>Annexe C

### <a name="evidence-collection--delta-for-iso-27001"></a>Collecte de preuves – Delta pour ISO 27001

Lorsque vous avez déjà atteint la conformité ISO27001, les deltas suivants (lacunes) non entièrement couverts par la norme ISO 27001 devront au minimum être examinés dans le cadre de cette certification Microsoft 365.

> [!NOTE]
> Dans le cadre de votre évaluation de certification Microsoft 365, l'analyste de certification déterminera si l'un des contrôles ISO 27001 mappés n'a pas été inclus dans le cadre de l'évaluation ISO 27001 et peut également décider d'exemples de contrôles qui ont été trouvés pour être inclus pour fournir une garantie supplémentaire. Toutes les exigences manquantes dans la norme ISO 27001 doivent être incluses dans vos activités d'évaluation de certification Microsoft 365.

**Protection contre les programmes malveillants – Antivirus**

Si la protection contre les programmes malveillants est en place à l'aide du contrôle d'application et est attestée dans le rapport ISO 27001, aucune investigation supplémentaire n'est nécessaire. Si aucun contrôle d'application n'est en place, les analystes de certification doivent identifier et évaluer les preuves des mécanismes de contrôle des applications pour empêcher la détonation de programmes malveillants dans l'environnement. Pour ce faire, vous devez :

* Démontrez que les logiciels antivirus s'exécutent sur tous les composants système échantillonés.

* Démontrez que l'antivirus est configuré sur tous les composants système échantillonés pour bloquer automatiquement les programmes malveillants, mettre en quarantaine & alerte ou pour alerter.

* Les logiciels antivirus **DOIVENT être** configurés pour enregistrer toutes les activités.

**Gestion des correctifs : correction**

Comme les audits ISO 27001 n'évaluent pas spécifiquement cette catégorie, vous devez :

* Les composants logiciels et les  systèmes d'exploitation ne sont plus pris en charge par le fournisseur. Des stratégies de prise en charge DOIVENT être en place pour garantir que les composants logiciels/systèmes d'exploitation non pris en charge seront supprimés de l'environnement et qu'un processus permettant d'identifier la fin de vie des composants logiciels doit être en place

**Analyse des vulnérabilités**  

Comme les audits ISO 27001 n'évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrer que l'analyse trimestrielle des vulnérabilités internes et externes est effectuée.

* Confirmez que la documentation de prise en charge est en place pour la correction des vulnérabilités en fonction du classement des risques et conforme aux spécifications suivantes :
 
 &#x2713; résoudre tous les problèmes critiques et à risque élevé en ligne avec le classement des risques pour l'analyse interne.
 
 &#x2713; résoudre tous les problèmes critiques, élevés et à risque moyen en ligne avec le classement des risques pour l'analyse externe.
 
 &#x2713; démontrer que la correction est effectuée en ligne avec la stratégie de correction des vulnérabilités documentée.

**Pare-feu : pare-feu (ou technologies équivalentes)**

Comme les audits ISO 27001 n'évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrez que les pare-feu sont installés à la limite de l'environnement dans l'étendue.

* Démontrez que les pare-feu sont installés entre le DMZ et les réseaux de confiance.

*   Démontrez que tous les accès publics se terminent dans la DMZ.

*   Démontrez que les informations d'identification administratives par défaut sont modifiées avant l'installation dans l'environnement en direct.

*   Démontrez que tout le trafic autorisé via le ou les pare-feu passe par un processus d'autorisation qui entraîne la documentation de tout le trafic avec une justification professionnelle.

*   Démontrez que tous les pare-feu sont configurés pour abandonner le trafic non explicitement défini.

*   Démontrez que les pare-feu ne supportent que le chiffrement fort sur toutes les interfaces d'administration non console.

*   Démontrez que les interfaces d'administration non-console du pare-feu exposées à Internet la prise en charge de l' mba.

*   Démontrer que les révisions des règles de pare-feu sont effectuées au moins tous les 6 mois

**Pare-feu – Pare-feu d'application web (WAF)**  

Un crédit supplémentaire est fourni si un waf est déployé pour vous protéger contre les menaces et les vulnérabilités des applications web qui peuvent être exposées à l'application. Lorsqu'un waf ou similaire est présent, vous devez :

* Démontrez que le waf est configuré en mode de défense active ou surveillez-le davantage avec des alertes.

* Démontrez que le waf est configuré pour prendre en charge le déchargement SSL.

* Est configuré selon l'ensemble de règles principales OWASP (3.0 ou 3.1) pour se protéger contre la plupart des types d'attaques suivants :

&#x2713; protocole et les problèmes de codage.

&#x2713; l'injection d'en-tête, la demande de séparation des demandes et le fractionnement de réponse.

&#x2713; attaques par traversée de fichier et de chemin d'accès.

&#x2713;'inclusion de fichiers distantes (RFI).

&#x2713;'exécution de code à distance.

&#x2713; attaques par injection php.

&#x2713; attaques par scripts entre sites.

&#x2713; SQL d'injection de matériel.

&#x2713; attaques par attachement de session.

**Contrôle des changements**

Comme les audits ISO 27001 n'évaluent pas spécifiquement certains éléments des processus de demande de modification, vous devez :

* Démontrez que les demandes de modification ont les détails suivants :

&#x2713; impact documenté.

&#x2713; détails sur les tests de fonctionnalités à effectuer.

&#x2713; détails des procédures de back-out.

* Démontrez que le test des fonctionnalités est effectué une fois les modifications terminées.

* Démontrez que les demandes de modification sont signées une fois les tests de fonctionnalités effectués.

**Gestion des comptes**

Comme les audits ISO 27001 n'évaluent pas spécifiquement certains éléments des processus de gestion des comptes, vous devez :

*   Montrer comment les &#x2713;sont implémentées pour atténuer les attaques par relecture (par exemple, MFA, Kerberos).
*   Expliquer comment les comptes qui n'ont pas été utilisés depuis 3 mois sont désactivés ou supprimés.
*   &#x2713; ou d'autres atténuations appropriées doivent être configurées pour protéger les informations d'identification de l'utilisateur. La stratégie de mot de passe minimale suivante doit être utilisée à titre indicatif :

&#x2713; longueur minimale du mot de passe de 8 caractères.

&#x2713; verrouillage du compte ne peut pas être supérieur à 10 tentatives.
 
&#x2713;'historique des mots de passe d'au moins cinq mots de passe.
 
&#x2713; l'application de l'utilisation de mots de passe forts.
 
*   Démontrez que l'mf est configuré pour toutes les solutions d'accès à distance.

*   Démontrez que le chiffrement fort est configuré sur toutes les solutions d'accès à distance.

*   Lorsque la gestion du DNS public se trouve en dehors de l'environnement dans l'étendue, tous les comptes d'utilisateurs en mesure d'apporter des modifications DNS DOIVENT être configurés pour utiliser l' usage de l' usage de l'mf.

**Détection et prévention des intrusions (FACULTATIF)**

Comme les audits ISO 27001 n'évaluent pas spécifiquement certains éléments des processus IDPS (Intrusion Detection and Prevention Services), vous devez :

*   Les IDPS **doivent** être déployés sur le périmètre de l'environnement de prise en charge.

*   Les signatures IDPS **doivent** être tenues à jour au cours du dernier jour.

*   IDPS **doit être** configuré pour l'inspection TLS.

*   IDPS **DOIT être** configuré pour TOUT le trafic entrant et sortant.

*   Les IDPS **doivent** être configurés pour les alertes.

**Journalisation des événements**

Comme les audits ISO 27001 n'évaluent pas spécifiquement certains éléments des processus de journalisation des événements de sécurité, vous devez :

* Démontrez que les systèmes publics se connectent à une solution de journalisation centralisée qui ne se trouve pas dans le DMZ.

* Démontrez comment un minimum de 30 jours de données de journalisation est immédiatement disponible, avec 90 jours conservés.

**Révision (journalisation des données)**

Comme les audits ISO 27001 n'évaluent pas spécifiquement certains éléments de cette catégorie, vous devez :

*   Démontrez comment les révisions quotidiennes des journaux sont effectuées et comment les exceptions et anomalies sont identifiées, montrant comment elles sont gérées.

**Alerte**

Comme les audits ISO 27001 n'évaluent pas spécifiquement certains éléments de cette catégorie, vous devez :

* Montrer comment les événements de sécurité sont configurés pour déclencher des alertes pour un tri immédiat.

* Montrer comment le personnel est disponible 24h/24 et 7 j/7 pour répondre aux alertes de sécurité.

**Gestion des risques**

Comme les audits ISO 27001 n'évaluent pas spécifiquement certains éléments des processus d'évaluation des risques, vous devez :

* Démontrer qu'un processus formel de gestion des risques est établi.

**Réponse aux incidents**

Comme les audits ISO 27001 n'évaluent pas spécifiquement certains éléments des stratégies et processus de réponse aux incidents, vous devez :

*   Démontrez que le plan/procédure de réponse aux incidents inclut :

&#x2713; procédures de réponse spécifiques pour les modèles de menace attendus.

&#x2713; fonctionnalités de gestion des incidents alignées sur NIST Cybersecurity Framework (Identifier, Protéger, Détecter, Répondre, Récupérer).
 
&#x2713; IRP couvre les systèmes dans l'étendue.
 
&#x2713; formation annuelle pour l'équipe de réponse aux incidents.

## <a name="appendix-d"></a>Annexe D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Collecte de preuves : deltas pour PCI DSS

Lorsque vous avez déjà atteint la conformité PCI DSS, les deltas suivants (lacunes) non entièrement couverts par PCI DSS devront au minimum être examinés dans le cadre de cette certification Microsoft 365.

> [!NOTE]
> Dans le cadre de l'évaluation de la certification Microsoft 365, l'analyste de certification détermine si l'un des contrôles PCI DSS mappés n'a pas été inclus dans le cadre de l'évaluation PCI DSS et peut également décider d'exemples de contrôles qui ont été trouvés pour être inclus pour fournir une garantie supplémentaire. Toutes les exigences manquantes dans le DSS PCI doivent être incluses dans les activités d'évaluation de la certification Microsoft 365.

**Protection contre les programmes malveillants : contrôle des applications**

Si la protection contre les programmes malveillants est en place par le biais de l'utilisation d'antivirus et est attestée dans le rapport PCI DSS, aucune investigation supplémentaire n'est nécessaire. Si aucun antivirus n'est en place, les analystes de certification doivent identifier et évaluer les preuves des mécanismes de contrôle des applications pour empêcher la détonation de programmes malveillants dans l'environnement. Pour ce faire, vous devez : 

*   Démontrez comment l'approbation de l'application est effectuée et confirmez que cette opération est terminée.

*   Démontrez qu'il existe une liste complète d'applications approuvées avec justification professionnelle.

*   Fournissez ou démontrez que la documentation de prise en charge est en place et détaille la configuration du logiciel de contrôle d'application pour répondre à des mécanismes de contrôle d'application spécifiques (mise en liste blanche, signature de code, etc.).

*   Démontrez que dans tous les composants système échantillonés, le contrôle d'application est configuré comme documenté.

**Gestion des correctifs : classement des risques**

Comme les audits PCI DSS n'évaluent pas spécifiquement cette catégorie, vous devez :

* Montrer comment le classement des vulnérabilités par risque est effectué.

**Analyse des vulnérabilités**

Comme les audits PCI DSS n'évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrer que la correction est effectuée en ligne avec la stratégie de correction des vulnérabilités documentée.

**Pare-feu : pare-feu (ou technologies équivalentes)**

Comme les audits PCI DSS n'évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrez que les pare-feu ne supportent que le chiffrement fort sur toutes les interfaces d'administration non console.

* Démontrez que les interfaces d'administration non-console du pare-feu exposées à Internet la prise en charge de l' mba.

Un crédit supplémentaire est fourni si un pare-feu d'application web (WAF) est déployé pour vous protéger contre les menaces et vulnérabilités des applications web qui peuvent être exposées à l'application. Lorsqu'un waf ou similaire est présent, vous devez :

* Démontrez que le waf est configuré en mode de défense active ou surveillez-le davantage avec des alertes.

* Démontrez que le waf est configuré pour prendre en charge le déchargement SSL.

* Est configuré selon l'ensemble de règles principales OWASP (3.0 ou 3.1) pour se protéger contre la plupart des types d'attaques suivants :

&#x2713; protocole et les problèmes de codage.

&#x2713; l'injection d'en-tête, la demande de séparation des demandes et le fractionnement de réponse.

&#x2713; attaques par traversée de fichier et de chemin d'accès.

&#x2713;'inclusion de fichiers distantes (RFI).

&#x2713;'exécution de code à distance.

&#x2713; attaques par injection php.

&#x2713; attaques par scripts entre sites.

&#x2713; SQL d'injection de matériel.

&#x2713; attaques par attachement de session.

**Contrôle des changements**

Comme les audits PCI DSS n'évaluent pas spécifiquement certains éléments des processus de demande de modification, vous devez :

* Démontrez que les demandes de modification sont formulées avant d'être réalisées dans des environnements de production.

* Démontrez que les modifications sont autorisées avant de passer en production.

* Démontrez que le test des fonctionnalités est effectué une fois les modifications terminées.

* Démontrez que les demandes de modification sont signées une fois les tests de fonctionnalités effectués.

**Sécurisation du développement/déploiement de logiciels**

Comme les audits PCI DSS n'accèdent pas spécifiquement à certains éléments de processus de déploiement et de développement logiciels sécurisés ; Cela vous sera nécessaire :

* Les référentiels de code DOIVENT être sécurisés par l'fa MFA.

*   Des contrôles d'accès appropriés DOIVENT être en place pour protéger les référentiels de code contre les modifications de code malveillantes.

**Gestion des comptes**

Comme les audits PCI DSS n'évaluent pas spécifiquement certains éléments des processus de gestion des comptes, vous devez :

* Montrer comment les mécanismes d'autorisation sont implémentés pour atténuer les attaques par relecture (par exemple, MFA, Kerberos).

* Des stratégies de mot de passe fortes ou d'autres atténuations appropriées doivent être configurées pour protéger les informations d'identification de l'utilisateur. La stratégie de mot de passe minimale suivante doit être utilisée à titre indicatif : 

&#x2713; longueur minimale du mot de passe de 8 caractères.

&#x2713; verrouillage du compte ne peut pas être supérieur à 10 tentatives.

&#x2713;'historique des mots de passe d'au moins cinq mots de passe.

&#x2713; l'application de l'utilisation de mots de passe forts.

* Démontrez que le chiffrement fort est configuré sur toutes les solutions d'accès à distance.

* Lorsque la gestion du DNS public se trouve en dehors de l'environnement dans l'étendue, tous les comptes d'utilisateurs en mesure d'apporter des modifications DNS DOIVENT être configurés pour utiliser l' usage de l' usage de l'mf.

**Détection et prévention des intrusions (FACULTATIF)**

Comme les audits PCI DSS n'évaluent pas spécifiquement certains éléments des processus IDPS (Intrusion Detection and Prevention Services), vous devez :

* IDPS doit être configuré pour l'inspection TLS.

*   IDPS DOIT être configuré pour TOUT le trafic entrant et sortant.

**Gestion des risques**

Comme les audits PCI DSS n'évaluent pas spécifiquement certains éléments des processus d'évaluation des risques, vous devez :

* Démontrer que l'évaluation des risques inclut des matrices d'impact et de probabilité.

**Réponse aux incidents**

Comme les audits PCI DSS n'évaluent pas spécifiquement certains éléments des stratégies et des processus de réponse aux incidents, le développeur devra :

* Faire la démonstration des fonctionnalités de gestion des incidents alignées sur NIST Cybersecurity Framework (identifier, protéger, détecter, répondre, récupérer).

## <a name="appendix-e"></a>Annexe E

### <a name="evidence-collection---deltas-for-soc-2"></a>Collecte de preuves - Deltas pour SOC 2

Lorsque vous avez déjà atteint la conformité SOC 2, les deltas suivants (lacunes) non entièrement couverts par SOC 2 devront être examinés dans le cadre de cette certification Microsoft 365.

> [!NOTE]
> Dans le cadre de l'évaluation de la certification Microsoft 365, l'analyste de certification détermine si l'un des contrôles SOC 2 mappés n'a pas été inclus dans le cadre de votre évaluation SOC 2 et peut également décider d'exemples de contrôles qui ont été trouvés pour être inclus pour fournir une garantie supplémentaire. Toutes les exigences manquantes dans votre évaluation SOC 2 doivent être incluses dans le cadre des activités d'évaluation de la certification Microsoft 365.

**Protection contre les programmes malveillants : contrôle des applications**

Si la protection contre les programmes malveillants est en place par le biais de l'utilisation d'antivirus et est attestée dans votre rapport SOC 2, aucune investigation supplémentaire n'est nécessaire. Si aucun antivirus n'est en place, les analystes de certification doivent identifier et évaluer les preuves des mécanismes de contrôle des applications pour empêcher la détonation de programmes malveillants dans l'environnement. Pour ce faire, vous devez :

* Fournissez ou démontrez que la documentation de prise en charge est en place et détaille la configuration du logiciel de contrôle d'application pour répondre à des mécanismes de contrôle d'application spécifiques (mise en liste blanche, signature de code, etc.).

* Démontrez comment l'approbation de l'application est effectuée et confirmez que cette opération est terminée.

*   Démontrez qu'il existe une liste complète d'applications approuvées avec justification professionnelle.

*   Démontrez que dans tous les composants système échantillonés, le contrôle d'application est configuré comme documenté.

**Gestion des correctifs : correction**

Comme les audits SOC 2 n'évaluent pas spécifiquement cette catégorie, vous devez :

*   Tout problème faible, moyen, élevé ou critique doit être corrigé dans les fenêtres d'activité de correction normales.

*   Les composants logiciels et les systèmes d'exploitation ne sont plus pris en charge par le fournisseur. Des stratégies de prise en charge DOIVENT être en place pour garantir que les composants logiciels/systèmes d'exploitation non pris en charge seront supprimés de l'environnement et qu'un processus permettant d'identifier la fin de vie des composants logiciels doit être en place.

**Pare-feu : pare-feu**

Comme les audits SOC 2 n'évaluent pas spécifiquement les contrôles de modification des listes de contrôle d'accès au pare-feu, vous devez :

* Démontrez que tout le trafic autorisé via le ou les pare-feu passe par un processus d'autorisation qui entraîne la documentation de tout le trafic avec une justification professionnelle.

* Démontrez que les révisions des règles de pare-feu sont effectuées au moins tous les six mois.

Un crédit supplémentaire est fourni si un pare-feu d'application web (WAF) ou similaire est déployé pour vous protéger contre les menaces et vulnérabilités des applications web qui peuvent être exposées à l'application. Lorsqu'un waf ou similaire est présent, vous devez :

* Démontrez que le waf est configuré en mode de défense active ou surveillez-le davantage avec des alertes.

* Démontrez que le waf est configuré pour prendre en charge le déchargement SSL.

* Est configuré selon l'ensemble de règles principales OWASP ((3.0 ou 3.1) pour se protéger contre la majorité des types d'attaques suivants :

&emsp;&#x2713; protocole et les problèmes de codage.

&emsp;&#x2713; l'injection d'en-tête, la demande et le fractionnement de réponse.

&emsp;&#x2713; attaques par traversée de fichier et de chemin d'accès.

&emsp;&#x2713;'inclusion de fichiers distantes (RFI).

&emsp;&#x2713; attaques d'exécution de code à distance.

&emsp;&#x2713; attaques par injection php.

&emsp;&#x2713; attaques par scripts entre sites.

&emsp;&#x2713; SQL d'injection de matériel.

&emsp;&#x2713; attaques par attachement de session.

**Contrôle des changements**

Comme les audits SOC 2 n'évaluent pas spécifiquement certains éléments des processus de demande de modification, le développeur devra :

* Montrer comment les environnements de développement/test sont distincts de l'environnement de production appliquant la séparation des tâches.

* Démontrez comment les données dynamiques ne sont pas utilisées dans les environnements de développement/test.

* Démontrez que le test des fonctionnalités est effectué une fois les modifications terminées.

* Démontrez que les demandes de modification sont signées une fois les tests de fonctionnalités effectués.

**Sécurisation du développement/déploiement de logiciels**

Comme les audits SOC 2 n'accèdent pas spécifiquement à certains éléments de processus de déploiement et de développement logiciels sécurisés ; Cela vous sera nécessaire :

*   Vous DEVEZ avoir un processus de développement de logiciels établi et documenté couvrant l'intégralité du cycle de vie du développement logiciel.

*   Les développeurs DOIVENT suivre une formation en programmation logicielle sécurisée au moins une fois par an.

*   Les référentiels de code DOIVENT être sécurisés par l'fa MFA.

*   Des contrôles d'accès appropriés DOIVENT être en place pour protéger les référentiels de code contre les modifications de code malveillantes.

**Gestion des comptes**

Comme les audits SOC2 n'évaluent pas spécifiquement certains éléments des processus de gestion des comptes, vous devez :

*   Montrer comment les mécanismes d'autorisation sont implémentés pour atténuer les attaques par relecture (par exemple, MFA, Kerberos).

*   Expliquer comment les comptes qui n'ont pas été utilisés depuis 3 mois sont désactivés ou supprimés.

*   Des stratégies de mot de passe fortes ou d'autres atténuations appropriées doivent être configurées pour protéger les informations d'identification de l'utilisateur. La stratégie de mot de passe minimale suivante doit être utilisée à titre indicatif :

&emsp;&#x2713; longueur minimale du mot de passe de 8 caractères.

&emsp;&#x2713; seuil de verrouillage du compte ne peut pas être supérieur à 10 tentatives.

&emsp;&#x2713;'historique des mots de passe d'au moins 5 mots de passe.

&emsp;&#x2713; l'application de l'utilisation de mots de passe forts

*   Démontrez que des comptes d'utilisateur uniques sont émis pour tous les utilisateurs.

*   Lorsque la gestion du DNS public se trouve en dehors de l'environnement dans l'étendue, tous les comptes d'utilisateurs en mesure d'apporter des modifications DNS DOIVENT être configurés pour utiliser l' usage de l' usage de l'mf.

**Détection et prévention des intrusions (FACULTATIF).**

Comme les audits SOC 2 n'évaluent pas spécifiquement certains éléments des processus IDPS (Intrusion Detection and Prevention Services), vous devez :

*   Les signatures IDPS doivent rester à jour au cours du dernier jour

*   IDPS DOIT être configuré pour l'inspection TLS

*   IDPS DOIT être configuré pour TOUT le trafic entrant et sortant

**Journalisation des événements**

Comme les audits SOC 2 n'évaluent pas spécifiquement certains éléments des processus de journalisation des événements de sécurité, vous devez :

* Démontrez comment, sur tous les composants système au sein de l'exemple de jeu, le système suivant est configuré pour enregistrer les événements suivants

&emsp;&#x2713; l'accès utilisateur aux composants système et aux applications.

&emsp;&#x2713; toutes les actions entreprises par un utilisateur avec des privilèges élevés.

&emsp;&#x2713; tentatives d'accès logique non valides.

Démontrer que les événements enregistrés contiennent ; Au minimum, les informations suivantes :

&emsp;&#x2713; utilisateur.

&emsp;&#x2713; type d'événement.

&emsp;&#x2713; date et heure.

&emsp;&#x2713; de réussite/d'échec.

&emsp;&#x2713; étiquette pour identifier le système concerné.

*   Démontrez que tous les composants système au sein de l'ensemble d'exemples sont configurés pour utiliser la synchronisation de temps et qu'ils sont identiques aux serveurs de temps principaux/secondaires.

* Démontrez que les systèmes publics se connectent à une solution de journalisation centralisée qui ne se trouve pas dans le DMZ.

*   Démontrez que les systèmes publics se connectent à une solution de journalisation centralisée qui ne se trouve pas dans le DMZ.

* Démontrez comment la solution de journalisation centralisée est protégée contre toute falsification non autorisée des données de journalisation.

* Démontrez comment un minimum de 30 jours de données de journalisation est immédiatement disponible, avec au moins 90 jours conservés.

**Gestion des risques**

Comme les audits SOC2 n'évaluent pas spécifiquement certains éléments des processus d'évaluation des risques, vous devez :

* Démontrer qu'une évaluation formelle des risques est effectuée au moins une fois par an.

*Réponse aux incidents.*

Comme les audits SOC2 n'évaluent pas spécifiquement certains éléments des stratégies et des processus de réponse aux incidents, vous devez :

* Démontrez que le plan/procédure de réponse aux incidents inclut :

&emsp;&#x2713; procédures de réponse spécifiques pour les modèles de menace attendus.

&emsp;&#x2713; processus de communication documenté pour assurer la notification en temps voulu des principales parties prenantes (marques de paiement/acquisition, organismes de réglementation, autorités de surveillance, directeurs, clients, etc.).

## <a name="appendix-f"></a>Annexe F

### <a name="hosting-deployment-types"></a>Types de déploiement d'hébergement

Microsoft reconnaît que vous allez déployer des applications et stocker du code d'application/de add-in dans différents environnements d'hébergement. Les responsabilités globales de certains contrôles de sécurité au sein de la certification Microsoft 365 dépendent de l'environnement d'hébergement utilisé. L'Annexe F examine les types de déploiement courants et les mapite avec les contrôles de sécurité évalués dans le cadre du processus d'évaluation. Les types de déploiement d'hébergement suivants ont été identifiés :

|  |  |
|-----|------|
|**ISV hébergé**|Les types hébergés par un isv peuvent être définis comme l'endroit où vous êtes responsable de l'infrastructure utilisée pour prendre en charge l'environnement d'application/de add-in. Il peut être physiquement situé dans vos propres centres de données ou centres de données tiers avec un service de colocalisation. En fin de compte, vous avez la propriété totale et le contrôle administratif sur l'infrastructure de prise en charge et l'environnement d'exploitation.|
|**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)|L'infrastructure en tant que service est un service fourni par le fournisseur de services cloud (CSP) qui gère et gère l'infrastructure de prise en charge physique en son nom. En règle générale, la mise en réseau, le stockage, les serveurs physiques et l'infrastructure de virtualisation incombent entièrement au CSP. Le système d'exploitation, l'intermédiaire, l'runtime, les données et les applications sont vos responsabilités. Les fonctionnalités de pare-feu sont également gérées et gérées par le tiers, mais la maintenance de la base de règles de pare-feu reste généralement la responsabilité des consommateurs.|
|**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)| La plateforme en tant que service vous permet de mettre en service une plateforme gérée présentant un service qui peut être consommé. Il n'est pas nécessaire d'effectuer des fonctions sysadmin, car le système d'exploitation et l'infrastructure de prise en charge sont gérés par le CSP. Cette fonction est généralement utilisée lorsque les organisations ne souhaitent pas se préoccuper de la présentation d'un service web et peuvent se concentrer sur la création du code source de l'application web et la publication de l'application web sur les services web gérés dans le cloud.  Un autre exemple peut être un service de base de données dans lequel la connectivité est donnée à une base de données, mais l'infrastructure de prise en charge et l'application de base de données sont abstraites du consommateur.   **Remarque : serverless et PaaS sont similaires afin que les valeurs Serverless et PasS du type d'hébergement de certification Microsoft 365 soient considérées comme identiques.**|
|**Hybride hébergé**|Avec le type hébergé hybride, vous pouvez utiliser plusieurs types hébergés pour prendre en charge différentes parties de l'environnement de prise en charge. C'est peut-être davantage le cas lorsque les applications/les modules sont utilisés dans plusieurs piles M365. Bien que la certification Microsoft 365 soit prise en charge lorsque des applications/modules sont développées dans plusieurs services M365, une évaluation de l'ensemble de l'environnement de prise en charge (entre applications/add-ins) doit être évaluée en ligne avec chacun des « mappages de types hébergés » applicables. Parfois, vous pouvez utiliser différents types hébergés pour un seul et même application, l'applicabilité des critères devra toujours suivre les critères « Mappages de types hébergés » sur les différents types hébergés.|
|**Hébergement partagé**|L'hébergement partagé est l'endroit où vous hébergez l'environnement au sein d'une plateforme partagée par plusieurs consommateurs individuels. La spécification de certification Microsoft 365 n'a pas été écrite pour tenir compte de ce problème en raison de l'adoption du cloud, l'hébergement partagé n'est pas courant. Si vous pensez que cela est utilisé, contactez Microsoft car des exigences supplémentaires devront être créées pour tenir compte des risques supplémentaires liés à ce type d'hébergement.|


## <a name="appendix-g"></a>Annexe G

### <a name="microsoft-365-certification-process-workflow"></a>Flux de travail du processus de certification Microsoft 365

![Flux de travail](ProcessFlow.jpg)

## <a name="learn-more"></a>Si vous souhaitez en savoir plus

[Présentation du programme de conformité des applications Microsoft 365](~/overview.md)  
[Qu'est-ce que l'attestation d'éditeur d'application Microsoft 365 ?](~/docs/attestation.md)  
[Qu'est-ce que la certification Microsoft 365 ?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossaire

### <a name="aia"></a>AIA

*L'accès aux informations d'autorité est un descripteur d'emplacement de service utilisé pour rechercher le certificat de l'autorité de certification émettrice.

### <a name="crl"></a>CRL

*La liste de révocation de certificats permet à un point de terminaison SSL (Secure Sockets Layer) de vérifier qu'un certificat reçu d'un hôte distant est valide et fiable.

### <a name="cvss-score"></a>Score CVSS

*Common Vulnerability Scoreing System est une norme publiée qui mesure la vulnérabilité et calcule un score numérique en fonction de sa gravité.

### <a name="cvss-patch-management-guidelines"></a>Recommandations en matière de gestion des correctifs CVSS

* Critique (9.0 - 10.0)
* Élevé (7,0 - 8,9)
* Moyenne (4,0 - 6,9)
* Faible (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*La zone démilitarisée est un réseau intermédiaire physique ou logique qui interagit directement avec des réseaux externes ou non propriétaires tout en maintenant le réseau interne, privé et isolé de l'hôte.

### <a name="euii"></a>EUII

*Informations d'identification de l'utilisateur final.*

### <a name="gdpr"></a>RGPD

*Le règlement général sur la protection des données est une réglementation de l'Union européenne sur la confidentialité et la protection des données pour toutes les données des citoyens de l'UE, quel que soit l'emplacement de votre site d'application.

### <a name="hsts"></a>HSTS

*Http Strict Transport Security utilise un en-tête de réponse HTTP qui demande au navigateur web d'accéder uniquement au contenu sur HTTPS.  Il est conçu pour se protéger contre les attaques de rétrogradation et les attaques par cookie.

### <a name="iec"></a>IEC

*Commissiontechnique internationale.

### <a name="isms"></a>ISMS

*Système de gestion de la sécurité des informations.

### <a name="isv"></a>ISV

Les fournisseurs de sécurité indépendants sont des individus et des organisations qui développent, vendent et vendent des logiciels qui s'exécutent sur des plateformes logicielles et matérielles tierces.

### <a name="iso-27001"></a>ISO 27001

Infrastructure de spécification du système de gestion de la sécurité des informations pour tous les contrôles techniques dans les processus de procédure et les stratégies de gestion des risques d'une organisation.

### <a name="lfi"></a>LFI

*L'inclusion de* fichiers locale permet à un attaquant d'inclure des fichiers sur un serveur via le navigateur web.

### <a name="nist"></a>NIST

Le *National Institute of Standards* (NIST), une agence non réglementaire du département du Commerce des États-Unis, fournit des conseils aux organisations du secteur privé aux États-Unis pour évaluer et approuver leur capacité à prévenir, détecter et répondre aux cyberattaques.

### <a name="non-significant-changes"></a>Modifications non significatives

* Résolutions de bogues mineures.
* Améliorations mineures en matière de performances.
* Systèmes d'exploitation/bibliothèques/correctifs d'application client et serveur.

### <a name="ocsp"></a>OCSP

*Le protocole d'état des* certificats en ligne permet de vérifier l'état de révocation des certificats numériques X.509.

### <a name="oii"></a>OII

*Informations d'identification organisationnelle*.

### <a name="owasp"></a>OWASP

*Ouvrez le projet de sécurité des applications web.*

### <a name="pci-dss"></a>PCI DSS

*Standard de sécurité des données de* l'industrie des cartes de paiement, une organisation qui maintient des normes pour la sécurité des données des titulaires de carte dans le monde entier.

### <a name="pen-testing"></a>Test du stylet

*Le test de* pénétration est une méthode de test d'une application web en simulant des attaques malveillantes pour rechercher les vulnérabilités de sécurité qu'une personne malveillante pourrait exploiter.

### <a name="saml"></a>SAML

*Security Assertion Markup Language* est une norme ouverte pour l'échange de données d'authentification et d'autorisation entre l'utilisateur, le fournisseur d'identité et le fournisseur de services.

### <a name="sensitive-data"></a>Données sensibles

* Données de contrôle d'accès.
* Contenu client.
* Informations d'identité de l'utilisateur final.
* Données de prise en charge.
* Données personnelles publiques.
* Informations pseudonymes de l'utilisateur final.

### <a name="significant-changes"></a>Modifications importantes

* Déplacement de l'environnement d'hébergement.
* Mises à niveau majeures de l'infrastructure de prise en charge ; par exemple, l'implémentation d'un nouveau pare-feu, les mises à niveau majeures vers les services frontaux, etc.
* Ajout de fonctionnalités et /ou d'extensions à votre application.
* Mises à jour de votre application qui capturent des données sensibles supplémentaires.
* Modifications apportées aux flux de données ou aux modèles d'autorisation de votre application
* Ajout de points de terminaison d'API ou de fonctions de point de terminaison d'API.

### <a name="soc-2"></a>SOC 2

*Service Organization Control 2*, une procédure d'audit technique constituée de cinq principes de service de confiance pour s'assurer que les fournisseurs de services gèrent en toute sécurité les données et la confidentialité des clients d'une organisation.

### <a name="ssl"></a>SSL

*Secure Sockets Layer*.

### <a name="tls"></a>TLS

*Transport Layer Security*.
