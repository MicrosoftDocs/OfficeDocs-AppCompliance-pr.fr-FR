---
ms.author: oromalle
title: Guide Microsoft 365 soumission de certification
author: orionomalley
manager: tonybal
description: Vue Microsoft 365 granulaire du Guide de soumission de certification
keywords: équipes de certification des Microsoft 365 de sécurité m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 7cd345151494175e77398ba02371639e82b5b349
ms.sourcegitcommit: b7ef94cf5fb12f6730a8688834ceee4f8fe8e0da
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/25/2022
ms.locfileid: "64461727"
---
# <a name="microsoft-365-certification-submission-guide"></a>Guide Microsoft 365 soumission de certification

**Dans cet article**
- [Introduction](#introduction)
- [Conditions préalables](#prerequisites) 
- [Microsoft 365 des spécifications de certification](#microsoft-365-certification-specification-updates)
- [Étendue de certification](#certification-scope)
- [Processus de certification](#certification-process)
- [Envoi initial du document](#initial-document-submission) 
- [Activités de collecte et d’évaluation des preuves](#evidence-collection-and-assessment-activities)
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

Dans le cadre du programme de conformité des applications Microsoft 365, la certification Microsoft 365 offre aux organisations d’entreprise la garantie et la confiance que les données et la confidentialité sont correctement sécurisées et protégées lors de l’intégration d’applications/de modules de développement tiers à la plateforme Microsoft 365. Les applications et les applications qui passent la validation seront désignées Microsoft 365 **certifiées** dans l’écosystème Microsoft 365' 

En participant au programme de certification Microsoft 365, vous acceptez ces conditions supplémentaires et respectez toute documentation qui s’applique à votre participation au programme de certification Microsoft 365 avec Microsoft Corporation ( « Microsoft », « nous », « nous » ou « notre »). Vous nous faites part de l’autorité qui vous permet d’accepter ces conditions supplémentaires de certification Microsoft 365 au nom de vous-même, d’une société et/ou d’une autre entité, le cas échéant. Nous pouvons modifier, modifier ou mettre fin à ces termes supplémentaires à tout moment. Votre participation continue au programme Microsoft 365 certification après toute modification ou modification signifie que vous acceptez les nouvelles conditions supplémentaires. Si vous n’acceptez pas les nouvelles conditions supplémentaires ou si nous résilions ces termes supplémentaires, vous devez arrêter de participer au programme Microsoft 365 certification.

Ce document s’adresse aux éditeurs de logiciels indépendants pour fournir des informations sur le processus de certification Microsoft 365, les conditions préalables au démarrage du processus et les détails des contrôles de sécurité spécifiques que les éditeurs de logiciels indépendants doivent mettre en place.  Des informations générales sur le Microsoft 365 conformité des applications sont disponibles dans la page Microsoft 365 conformité des [applications](../overview.md). 

> [!IMPORTANT]
> Actuellement, Microsoft 365 certification est applicable à tous :
>* Microsoft Teams applications (onglets, bots, etc.) .
>* Applications/add-ins SharePoint
>* Office(Word, Excel, PowerPoint, Outlook, Project, OneNote)
>* WebApps

## <a name="prerequisites"></a>Conditions préalables

### <a name="publisher-attestation"></a>Attestation de l’éditeur

Avant d’obtenir le processus Microsoft 365 certification, vous devez avoir obtenu Publisher attestation. Toutefois, vous pouvez démarrer le processus Microsoft 365 certification avant de terminer l Publisher attestation.  

### <a name="read-the-microsoft-365-certification-specification"></a>Lire les spécifications Microsoft 365 certification

Microsoft recommande à tous les éditeurs de logiciels indépendants (éditeurs de logiciels indépendants) de lire entièrement cette spécification de certification Microsoft 365 pour s’assurer que tous les contrôles applicables sont satisfaits par l’environnement dans l’étendue et l’application/le add-in. Cela permet de garantir un processus d’évaluation fluide.

## <a name="microsoft-365-certification-specification-updates"></a>Microsoft 365 des spécifications de certification 

Les mises à jour de la spécification Microsoft 365 certification sont prévues environ tous les six à douze mois. Ces mises à jour peuvent introduire de nouveaux domaines de sécurité cibles et/ou des contrôles de sécurité. Les mises à jour seront basées sur les commentaires des développeurs, les modifications apportées au paysage des menaces et pour augmenter la ligne de base de sécurité du programme au cours de sa maturité. 

Les isvs qui ont déjà démarré l’évaluation Microsoft 365 Certification peuvent poursuivre l’évaluation avec la version de la spécification de certification Microsoft 365 qui était valide au début de l’évaluation. Toutes les nouvelles soumissions, y compris la recertification annuelle, doivent être évaluées par rapport à la version publiée.

> [!NOTE]
> Vous n’êtes pas obligé de vous conformer à tous les contrôles au sein de cette Microsoft 365 certification pour obtenir une certification. Toutefois, des seuils de passage (qui ne seront pas divulgués) sont en place pour chacun des domaines de sécurité abordés dans cette Microsoft 365 de certification. Certains contrôles seront classés en tant qu’échec en dur, ce qui signifie que l’absence de ces contrôles de sécurité entraîne l’échec de l’évaluation. 

## <a name="certification-scope"></a>Étendue de certification

**L’environnement dans l’étendue** est l’environnement qui prend en charge la livraison du code d’application/de add-in et prend en charge tous les systèmes back-end avec qui l’application/le module peut communiquer. Tous les environnements connectés supplémentaires seront également inclus dans l’étendue, sauf si une segmentation adéquate est en place ET que les environnements connectés ne peuvent pas avoir d’impact sur la sécurité de l’environnement dans l’étendue. Tous les environnements de récupération d’urgence doivent également être inclus dans l’étendue de l’évaluation, car ces environnements seraient requis pour accomplir le service en cas de problème dans l’environnement principal.  Les  **composants**  système d’étendue termin sont  tous les appareils et systèmes utilisés dans l’environnement dans l’étendue. Les composants dans l’étendue incluent, sans s’y limiter, les éléments suivants :
* Les applications web.
* Serveurs.
* Pare-feu (ou équivalent).
* Commutateurs.
* Équilibreurs de charge.
* Infrastructure virtuelle.
* Portails de gestion web des fournisseurs de cloud 

> [!IMPORTANT]
> L’environnement dans l’étendue doit avoir une DMZ et l’environnement de prise en charge de l’application/du add-in doit être segmenté des systèmes d’entreprise internes et des environnements d’entreprise, limitant ainsi l’étendue des activités d’évaluation aux systèmes dans l’étendue uniquement. Les analystes de certification valideront les techniques de segmentation lors de l’évaluation, ainsi que la révision des rapports de test de pénétration qui auraient dû inclure des tests pour valider l’efficacité de toutes les techniques de segmentation utilisées.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infrastructure as a Service (IaaS), Platform as a Service (PaaS) et Software as a Service (SaaS) 
Lorsque IaaS et/ou PaaS sont utilisés pour prendre en charge l’infrastructure de la remise de code d’application ou de module de module de prise en charge en révision, le fournisseur de plateforme Cloud sera responsable de certains des contrôles de sécurité évalués tout au long du processus de certification. Par conséquent, les analystes de certification doivent être fournis avec une vérification externe indépendante des meilleures pratiques de sécurité par le fournisseur de plateforme Cloud via des rapports de conformité externes tels que les rapports  [DSSAttestation](bookmark://pci-dss)  of Compliance (AOC), ISO27001  [ouSOC 2Type](bookmark://soc-2)  II. 

L’Annexe F fournit des détails sur les contrôles de sécurité qui seront probablement applicables en fonction des types de déploiement suivants et selon que l’application/le add-in exfiltre ou non les données M365 : 
* ISV hébergé 
* IaaS hébergé 
* PaaS/Serverless Hosted 
* Hybride hébergé 
* Shared Hosted 

Lorsque IaaS ou PaaS est déployé, vous devez fournir des preuves de l’environnement hébergé dans ces types de déploiement.

### <a name="sampling"></a>Échantillonnage

Les demandes de preuves à la prise en charge de l’évaluation de certification doivent être basées sur un échantillon des composants système dans l’étendue en considération des différents systèmes d’exploitation, de la fonction principale de l’appareil et des différents types d’appareils. Un exemple approprié est sélectionné au début du processus de certification. Le tableau suivant doit servir de guide sur la taille de l’échantillon :

|Taille de la population              | Échantillon                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4|

> [!NOTE]
>Si des incohérences sont identifiées entre les appareils inclus dans l’exemple initial, la taille de l’échantillon peut être augmentée au cours de l’évaluation. 

## <a name="certification-process"></a>Processus de certification

Avant de commencer le processus de certification, vous devez avoir effectué correctement votre attestation Publisher certificat. Une fois le processus de certification Microsoft 365 terminé, procédez comme suit :

### <a name="preparation"></a>Préparation
1. Accédez à l’Centre partenaires et examinez votre documentation [d’attestation Publisher complète](../docs/attestation.md). Si nécessaire, vous pouvez modifier et mettre à jour vos réponses . Toutefois, si vous le faites, vous devrez resoumettre votre documentation d’attestation pour approbation. Si votre envoi a plus de trois mois, nous vous demanderons de soumettre à nouveau une attestation Publisher pour révision et validation. 
1. Lisez attentivement le Guide [Microsoft 365 soumission de certification](../docs/certification-submission-guide.md) pour comprendre ce qui vous sera nécessaire. Assurez-vous que vous serez en mesure de répondre [aux exigences de](../docs/certification-submission-guide.md#app-certification-criteria) contrôle spécifiées dans le Guide Microsoft 365 soumission de certification.
1. Dans l’Espace partenaires, cliquez sur « Démarrer la certification ». Cela vous permet d’être en communication avec votre portail de soumission de documents initial. Envoyez votre [envoi de document initial](../docs/certification-submission-guide.md#initial-document-submission). Cela nous aidera à déterminer ce qui est dans l’étendue de votre évaluation en fonction de la façon dont votre application est conçu et gère les données client. Consultez cette page fréquemment pour voir si votre soumission a été acceptée.

>[!NOTE]
>Pour toutes les applications Office, vous pouvez référencer [notre Guide Office utilisateur des applications](../docs/userguide.md). Pour tous les WebApps, vous pouvez référencer notre Guide de l’utilisateur [de l’application SaaS](../docs/saasuserguide.md).

### <a name="assessment"></a>Évaluation
1. Une fois votre envoi de document initial accepté, l’ensemble des contrôles de sécurité requis pour votre application s’affiche automatiquement sur le portail. Vous devez ensuite soumettre des preuves pour chaque contrôle montrant que le contrôle est en place. Gardez à l’esprit que vous aurez **60 jours** pour soumettre toutes les preuves. Un analyste examine vos preuves et approuve le contrôle ou demande une preuve nouvelle ou supplémentaire. Consultez cette page fréquemment pour voir si vos preuves ont été acceptées.
### <a name="certification"></a>Certification
1. Une fois votre soumission validée par un analyste, vous serez informé de votre décision de certification. Les applications qui reçoivent une certification recevront un badge sur leur application dans **AppSource** et les pages **de documents Microsoft** . Vous pouvez en savoir plus sur les avantages complets de la certification [ici](../docs/enterprise-app-certification-guide.md#program-benefits).

## <a name="review-and-re-certification"></a>Révision et re-certification
Si votre application subit des modifications [importantes à](../docs/certification-submission-guide.md#significant-changes) tout moment, vous devez nous en informer.

Vous devez également passer par une recertification annuelle. Cela nécessitera la revalidation des contrôles dans l’étendue par rapport à votre environnement actuel. Ce processus peut commencer jusqu’à 90 jours avant l’expiration de votre certification. Votre certification existante n’expirera pas pendant la période de certification. La nouvelle certification dans tous les programmes expire à l’anniversaire d’un an de votre Microsoft 365 certification.

Si votre certification n’est pas renouvelé avant la date d’expiration, le statut de certification de vos applications est révoqué. Tous les problèmes, icônes et marque de certification associée seront supprimés de votre application, et il vous sera interdit de la publicité de votre application comme Microsoft 365 certifié.


> [!IMPORTANT]
> **Délai de soumission :** En moyenne, le processus d’évaluation devrait prendre 30 jours, à condition de pouvoir vérifier fréquemment l’état de votre soumission et de répondre aux commentaires et aux demandes de preuve supplémentaires dans un délai raisonnable. Au démarrage du processus de certification, un maximum de 60 jours est autorisé à effectuer l’évaluation. Si toutes les soumissions n’ont pas été terminées au cours de la période de 60 jours, la soumission est émise en cas d’échec et le processus doit recommencer. Ces résultats ne seront pas publics.


## <a name="initial-document-submission"></a>Envoi initial de documents


La soumission initiale de documents permettra aux analystes de certification d’effectuer l’étendue et de déterminer ce qui sera dans l’étendue de votre évaluation. Après quoi, vous serez tenu de soumettre la documentation de prise en charge et les preuves utilisées pour effectuer l’évaluation. Votre envoi initial doit inclure les informations spécifiées ci-dessous. Pour obtenir des conseils supplémentaires, consultez le [Guide de sous-mission de document initital](../docs/initialdocumentsubguide.md).

| **DocumentationOverview&nbsp;**     |   **Détails de la documentation**  |
| -------------------------| -----------------------------|
|**Description de l’application/du add-in** | Description de l’objectif et des fonctionnalités de l’application/du add-in. Cela doit fournir à l’analyste de certification une bonne compréhension du fonctionnement de l’application/du add-in et de son utilisation prévue.
|**Rapport de test de pénétration** |Un rapport de test de pénétration effectué au cours des 12 derniers mois. Ce rapport doit inclure l’environnement qui prend en charge le déploiement de l’application/de l’ajout, ainsi que tout environnement supplémentaire qui prend en charge le fonctionnement de l’application/du complément. **Remarque :** si vous ne testez pas de pénétration annuelle, vous pouvez les faire passer par le processus de certification.|
|**Diagrammes d’architecture**|Diagramme d’architecture logique représentant une vue d’ensemble de l’infrastructure de prise en charge de votre application/de votre application. Cela doit inclure tous **les environnements** d’hébergement et l’infrastructure de prise en charge de l’application/du add-in. Ce diagramme DOIT décrire tous les différents composants système de prise en charge dans l’environnement pour aider les analystes de certification à comprendre les systèmes dans l’étendue et à déterminer l’échantillonnage. Indiquez également le type d’environnement d’hébergement utilisé . IsV hébergé, IaaS, PaaS ou hybride. **Remarque :** Lorsque SaaS est utilisé, indiquez les différents services SaaS utilisés pour fournir les services de prise en charge dans l’environnement.|
|**Encombrement public** | Détails de **toutes les** adresses IP publiques et URL utilisées par l’infrastructure de prise en charge. Cela doit inclure la plage d’adresses IP routable complète allouée à l’environnement, sauf si une segmentation adéquate a été implémentée pour fractionner la plage en cours d’utilisation (une preuve adéquate de segmentation sera requise)|
|**Diagrammes de flux de données** |Flow diagrammes détaillés suivants :
||&#x2713; données M365 circulent vers et depuis l’application/le add-in (y compris [EUII](#euii) et [OII](#oii) ).|
||&#x2713; flux de données M365 au sein de l’infrastructure de prise en charge (le cas échéant)|
||&#x2713; Diagrammes mettant en évidence où et quelles données sont stockées, comment les données sont transmises à des tiers externes (notamment des détails sur les tiers) et comment les données sont protégées en transit sur des réseaux ouverts/publics et au repos.|
|**Détails du point de terminaison de l’API**| Liste complète de tous les points de terminaison d’API utilisés par votre application. Pour mieux comprendre l’étendue de l’environnement, fournissez des emplacements de point de terminaison d’API dans votre environnement.                                
|**Autorisations de l’API Microsoft**| Fournir une documentation détaillée de **TOUTES** les API Microsoft utilisées, ainsi que les autorisations demandées pour que l’application/le add-in fonctionne, ainsi qu’une justification des autorisations demandées|
|**Types de stockage de données** |Stockage de données et gestion des documents décrivant :|
||&#x2713; dans quelle mesure vos clients M365 Data [EUII](#euii) et [OII](#oii) sont reçus et stockés|
||&#x2713; période de rétention des données.|
||&#x2713; pourquoi les données M365 du client sont capturées.|
||&#x2713; l’endroit où sont stockées les données M365 du client (doit être inclus dans les diagrammes de flux de données fournis ci-dessus).|
|**Confirmation de la conformité**|Documentation de prise en charge pour les cadres de sécurité externes inclus dans la soumission Publisher attestation ou à prendre en compte lors de l’examen Microsoft 365 contrôles de certification. Actuellement, les trois suivants sont pris en charge :|
||&#x2713; [attestation de conformité PCI DSS](#pci-dss) (AOC).|
||&#x2713; [rapports SOC 2](#soc-2) Type I/Type II.|
||&#x2713; [ISMSIEC](#isms) /  - 1S0/IEC 27001 Déclaration d’applicabilité et de certification.[](#iec)|
|**Dépendances web**|Documentation répertoriant toutes les dépendances utilisées par l’application/le add-in avec les versions en cours d’exécution.|
|**Inventaire logiciel**|Inventaire logiciel à jour qui inclut tous les logiciels utilisés dans l’environnement dans l’étendue, ainsi que les versions.|
|**Inventaire matériel**| Inventaire matériel à jour utilisé par l’infrastructure de prise en charge. Cela sera utilisé pour faciliter l’échantillonnage lors de la phase d’évaluation. Si votre environnement inclut PaaS, fournissez des détails sur les services consommés.|

## <a name="evidence-collection-and-assessment-activities"></a>Activités de collecte et d’évaluation des preuves

Les analystes de certification devront examiner les preuves sur tous les composants système au sein de l’ensemble d’exemples défini. Les types de preuve requis pour prendre en charge le processus d’évaluation sont les suivants :

**Collection de preuves**

* Documentation initiale, mise en évidence dans la section [Soumission de documentation](#initial-document-submission) initiale ci-dessus 
* Documents de stratégie 
* Traiter des documents 
* Paramètres de configuration du système 
* Modifier les tickets 
* Modifier les enregistrements de contrôle 
* Rapports système

Diverses méthodes seront utilisées pour collecter les preuves nécessaires à la fin du processus d’évaluation.  Cette collection de preuves peut prendre la forme des éléments ci-après : 
* Documents 
* Captures d’écran 
* Interviews 
* Partage d’écran 

Les techniques de collecte de preuves utilisées seront déterminées pendant le processus d’évaluation. Pour obtenir des exemples concrets du type de preuve requis dans votre soumission, voir le [Guide des exemples de preuves](../docs/certification-sample-evidence-guide.md).

**Activités d’évaluation**

Les analystes de certification examineront les preuves que vous fournissez pour déterminer si vous avez correctement satisfait aux contrôles au sein de cette Microsoft 365 de certification. 

Dans la mesure du possible et pour réduire le temps nécessaire pour effectuer l’évaluation, tout ou partie de la documentation détaillée dans la soumission de  [documentation](#initial-document-submission)  initiale doit être fournie à l’avance.

Les analystes de certification examineront d’abord les preuves fournies à partir de la soumission initiale de la documentation et des informations d’attestation Publisher pour identifier les lignes de procédure appropriées, la taille d’échantillonnage et la nécessité d’obtenir des preuves supplémentaires, comme indiqué ci-dessus.  Les analystes de certification analyseront toutes les informations recueillies pour tirer des conclusions quant à la façon dont et si vous êtes en mesure de répondre aux contrôles au sein de cette Microsoft 365 de certification. 

## <a name="app-certification-criteria"></a>Critères de certification des applications

Votre application, l’infrastructure de prise en charge et la documentation de prise en charge seront évaluées dans les domaines de sécurité suivants :

1. [**Sécurité des applications**](#application-security)
1. [**Sécurité opérationnelle /Déploiement sécurisé**](#operational-security)
1. [**Sécurité et confidentialité de la gestion des données**](#data-handling-security-and-privacy)

Chacun de ces domaines de sécurité inclut des contrôles clés spécifiques englobant une ou plusieurs exigences spécifiques qui seront évaluées dans le cadre du processus d’évaluation. Pour s’assurer que la certification Microsoft 365 est inclusive pour les développeurs de toutes tailles, chacun des domaines de sécurité est évalué à l’aide d’un système de notation afin de déterminer un score global pour chacun des domaines. Les scores pour chacun des contrôles de certification Microsoft 365 sont alloués entre 1 (faible) et 3 (élevé) en fonction du risque perçu que ce contrôle ne soit pas atteint. Chacun des domaines de sécurité aura une marque de pourcentage minimale pour être considéré comme une passe. Certains éléments de cette spécification incluent certains critères d’échec automatique :

- Les autorisations d’API ne suivent pas le principe du moindre privilège (PoLP).  
- Aucun rapport de test d’intrusion lorsqu’il est nécessaire.
- Aucune protection contre les programmes malveillants
- L’authentification multifacteur n’est pas utilisée pour protéger l’accès administratif.  
- Aucun processus de correction.  
- Aucune notification [de confidentialité R GDPR](#gdpr) appropriée.  

## <a name="application-security"></a>Sécurité des applications

Le domaine de sécurité des applications se concentre sur les trois domaines suivants : 
* Validation des autorisations GraphAPI 
* Vérifications de la connectivité externe
* Test de sécurité des applications 

### <a name="graphapi-permission-validation"></a>Validation des autorisations GraphAPI

La validation des autorisations GraphAPI est effectuée pour valider l’application/le add-in ne demande pas d’autorisations trop permissives. Pour ce faire, vérifiez manuellement les autorisations demandées. Les analystes de certification font référence à ces vérifications par rapport à la soumission d’attestation Publisher et évaluent le niveau d’accès demandé pour s’assurer que les pratiques de « privilège minimum » sont respectées. Lorsque les analystes de certification pensent que ces pratiques de « moindre privilège » ne sont pas respectées, les analystes de certification auront une discussion ouverte avec vous pour valider la justification commerciale des autorisations demandées. Toute incohérence par rapport à votre envoi Publisher attestation d’attestation de données trouvée au cours de cette révision reçoit également des commentaires afin que votre attestation Publisher puisse être mise à jour. 

### <a name="external-connectivity-checks"></a>Vérifications de la connectivité externe

Dans le cadre de l’évaluation, un analyste va passer en détail les fonctionnalités des applications pour identifier les connexions en dehors de M365.  Toutes les connexions qui ne sont pas identifiées comme étant Microsoft ou des connexions directes à votre service seront signalées et abordées au cours de l’évaluation.

### <a name="application-security-testing"></a>Test de sécurité des applications

Un examen adéquat des risques associés à votre application/votre add-in et à votre environnement de prise en charge est essentiel pour fournir aux clients des garanties en matière de sécurité de l’application/du add-in. Les tests de sécurité des applications doivent être effectués sous la forme de tests de pénétration si votre application dispose d’une connectivité à un service non publié par Microsoft. Si votre application fonctionne de façon autonome sans connectivité à un service ou un système back-end non-Microsoft, le test de pénétration n’est pas requis.


**Étendue des tests de pénétration**

Les activités de test  de pénétration DOIVENT être effectuées sur l’environnement de production en direct qui prend en charge le déploiement de l’application/du complément (par exemple, l’endroit où le code de l’application/du complément est hébergé, qui sera généralement la ressource dans le fichier manifeste), ainsi que tout environnement supplémentaire qui prend en charge le fonctionnement de l’application/du complément (par exemple, si l’application/le complément discute avec d’autres applications web en dehors de Microsoft 365).  Lors de la définition de l’étendue, veillez à vous assurer que tous les systèmes ou environnements « connectés » qui peuvent avoir un impact sur la sécurité de l’environnement dans l’étendue sont également inclus dans TOUTES les activités de test de pénétration. 

Lorsque des techniques sont utilisées pour segmenter les environnements dans l’étendue d’autres environnements, les activités de test de pénétration DOIVENT valider l’efficacité de ces techniques de segmentation. Cela doit être détaillé dans le rapport de test de pénétration. 

Les rapports de test de pénétration sont examinés pour s’assurer qu’aucune **** vulnérabilité ne répond aux critères d’échec automatique suivants décrits dans les contrôles ci-dessous.
 
**Exigences en matière de test de pénétration**

||**Contrôles de test de pénétration**|
| -------------------------|-----------------------------|
|**Critères généraux**| **Controls**|
|| Les tests de pénétration des applications **et de** l’infrastructure DOIVENT avoir lieu chaque année (tous les 12 mois) et effectués par une société indépendante de confiance. |
|| La correction des vulnérabilités critiques et à  haut risque identifiées DOIT être effectuée dans un délai d’un mois après la fin du test de pénétration, ou plus tôt en fonction du processus de correction documenté. |
|| L’encombrement externe complet (adresses IP, URL, points de terminaison d’API, etc.) DOIT être inclus dans la portée du test de pénétration et doit être documenté dans le rapport de test de pénétration. |
|| Le test de pénétration d’application Web DOIT inclure toutes les classes de vulnérabilité ; par exemple, les plus récents OWASP Top 10 ou SANS Top 25 CWE. |
|| Il n’est pas nécessaire de tester à nouveau les vulnérabilités identifiées par l’entreprise de test de pénétration. Toutefois, la correction et  l’auto-examen suffisent pour démontrer que des mesures correctives suffisantes doivent être fournies pendant l’évaluation.|
|**Critères d’échec automatique :**|**Controls**|
|| Présence d’un système d’exploitation non pris en charge. |
|| Présence de comptes d’administration par défaut, éumables ou devinables.|
|| Présence de risques SQL d’injection.|
|| Présence de scripts entre sites.|
|| Présence de vulnérabilités de traversée d’annuaire (chemin d’accès au fichier).|
|| Présence de vulnérabilités HTTP, par exemple, fractionnement de réponse d’en-tête, demandes de habilitation et attaques de desync.|
|| Présence de la divulgation de code source ( [includingLFI](#lfi)).|
|| Tout score critique ou élevé défini par les instructions de gestion des correctifs CVSS.|
|| Toute vulnérabilité technique importante qui peut être facilement exploitée pour compromettre une grande quantité d’EUII ou d’OUI.|






> [!IMPORTANT]
>Les rapports doivent être en mesure de fournir suffisamment d’assurance que tout ce qui est détaillé dans la section Spécification du test de sécurité des applications peut être démontré.


**Exigences et règles de test de pénétration complémentaires**

- Pour les isv qui n’effectuent actuellement pas de test de pénétration, les tests de pénétration peuvent être effectués gratuitement par Microsoft 365 certification. Microsoft organise et couvre le coût d’un test de pénétration pendant 12 jours de test manuel. Les coûts des tests de pénétration sont calculés en fonction du nombre de jours requis pour tester l’environnement. Toute dépense dépassant 12 jours de test sera la responsabilité de l’isv. 
- Les isv doivent soumettre des preuves et recevoir l’approbation de 50 % des contrôles dans l’étendue avant que le test de pénétration ne soit effectué. Pour commencer, il vous suffit de remplir votre envoi initial de documents et de faire en sorte que le test d’intrusion soit inclus dans le cadre de votre évaluation. Vous serez contacté pour étendue et planifier votre test de pénétration lorsque vous aurez terminé 50 % des contrôles.
- Le rapport émis une fois la pentest terminée est fourni à l’isv une fois qu’il a obtenu la certification. Ce rapport, ainsi que votre certification Microsoft 365, peuvent être utilisés pour montrer aux clients potentiels que votre environnement est sécurisé.
- Les isoeurs seront également chargés de démontrer que les vulnérabilités identifiées dans le test de pénétration ont été corrigés avant l’octroi d’une certification, mais n’ont pas besoin de produire un rapport propre.

Une fois qu’un test de pénétration est organisé, l’isv est responsable des frais associés à la planification et aux annulations comme suit :

| **Rescheduling Fee Timescale** | **Proportion Due** |
|------------------|------------------------|
| Re planning request received more than 30 days prior to scheduled start date. | 0 % Due |
| Re-planifier la demande reçue 8 à 30 jours avant la date de début prévue. | 25 % Due |
| Re planning request received within 2 to 7 days prior to scheduled start date with a firm re-booking date.| 50 % Due |
| Re-planifier la demande reçue moins de 2 jours avant la date de début. | 100 % Due |

| **Échelle de temps des frais d’annulation** | **Proportion Due** |
|------------------|------------------------|
| La demande d’annulation a été reçue plus de 30 jours avant la date de début prévue. | 25 % Due |
| Demande d’annulation reçue 8 à 30 jours avant la date de début prévue. | 50 % Due |
| Demande d’annulation reçue dans les 7 jours avant la date de début prévue. | 90 % Due |

## <a name="operational-security"></a>Sécurité opérationnelle

Ce domaine mesure l’alignement des processus d’infrastructure et de déploiement de votre application avec les meilleures pratiques en matière de sécurité.

### <a name="controls"></a>Contrôles

|**Famille de contrôles**| **Controls**|
| ------------------------|------------------------------ |
| **Protection contre les programmes malveillants : antivirus**|Fournir une documentation de stratégie qui régit les pratiques et procédures anti-virus.|
||Fournissez des preuves montrant que des logiciels antivirus sont en cours d’exécution sur tous les composants système échantillonés.|
||Fournir des preuves montrant que les signatures antivirus sont à jour dans tous les environnements (dans un délai d’un jour).|
||Fournir des preuves montrant que l’antivirus est configuré pour effectuer une analyse à l’accès ou une analyse périodique sur tous les composants système échantillonné. Remarque : si l’analyse sur accès n’est pas activée, un minimum d’analyse et d’alerte quotidiennes doit être activé.|
||Fournir des preuves montrant que l’antivirus est configuré pour bloquer automatiquement les programmes malveillants ou la mise en quarantaine et les alertes sur tous les composants système échantillonés.|
|**Contrôles d’application** : requis uniquement si la protection anti-programme malveillant classique n’est pas utilisée|Fournir des preuves montrant que les applications sont approuvées avant d’être déployées.|
||Fournir des preuves montrant qu’une liste complète d’applications approuvées avec justification professionnelle existe et est conservée.|
||Fournir une documentation de prise en charge détaillant la configuration du logiciel de contrôle d’application pour répondre à des mécanismes de contrôle d’application spécifiques. (Exemple : Liste autorisée : exemple1, exemple3, signature de code)|
||Fournissez des preuves montrant que le contrôle d’application est configuré comme documenté à partir de tous les composants système échantillonés.|
|**Gestion des correctifs : classement des risques**| Documentation sur la stratégie d’approvisionnement qui régit la façon dont les nouvelles vulnérabilités de sécurité sont identifiées et affectées à un score de risque.|
||Fournir des preuves de la façon dont les nouvelles vulnérabilités de sécurité sont identifiées.|
||Fournir des preuves montrant que toutes les vulnérabilités se voit attribuer un classement des risques une fois identifiées.|
|**Patch Managmeent - Patching**|Fournir une documentation de stratégie pour la correction des composants système au niveau de l’étendue qui inclut une période de correction minimale appropriée pour les vulnérabilités critiques, élevées et à risque moyen ; et la désaffectation de tous les systèmes d’exploitation et logiciels non pris en charge.|
||Fournissez des preuves montrant que tous les composants système échantillonés sont corrigés.|
||Fournir des preuves montrant que les systèmes d’exploitation et composants logiciels non pris en charge ne sont pas utilisés dans l’environnement.|
|**Analyse des vulnérabilités**|Fournissez les rapports d’analyse des vulnérabilités des applications web et de l’infrastructure trimestrielle. L’analyse doit être effectuée sur l’intégralité de l’empreinte publique (adresses IP et URL) et des plages d’adresses IP internes.|
||Fournissez des preuves montrant que la correction des vulnérabilités identifiées au cours de l’analyse des vulnérabilités est mise à jour en ligne avec votre période de correction documentée.|
|**Pare-feu**|Fournir une documentation de stratégie qui régit les pratiques et procédures de gestion des pare-feu.|
||Fournissez la preuve que les informations d’identification administratives par défaut sont modifiées avant l’installation dans les environnements de production.|
||Fournissez la preuve que les pare-feu sont installés à la limite de l’environnement dans l’étendue et installés entre le réseau de périmètre (également appelé DMZ, zone démilitarisée et sous-réseau filtré) et les réseaux de confiance internes.|
||Fournissez la preuve que tous les accès publics se terminent dans la zone démilitarisée (DMZ).|
||Fournissez la preuve que tout le trafic autorisé par le pare-feu passe par un processus d’approbation.|
||Fournissez la preuve que la base de règles de pare-feu est configurée pour abandonner le trafic non explicitement défini.|
||Fournissez la preuve que le pare-feu prend uniquement en charge le chiffrement fort sur toutes les interfaces d’administration non console.|
||Fournissez des preuves montrant que vous effectuez des révisions de règles de pare-feu au moins tous les 6 mois.|
|**Pare-feu d’application web (WAF) (FACULTATIF)** : un crédit supplémentaire sera crédité pour satisfaire les contrôles suivants.|Fournissez des preuves montrant que le pare-feu de l’application Web (WAF) est configuré pour surveiller, alerter et bloquer activement le trafic malveillant.|
||Fournissez des preuves que le waf prend en charge le déchargement SSL.|
||Fournir des preuves montrant que le waf est protégé contre une partie ou l’ensemble des classes de vulnérabilités suivantes, selon l’ensemble de règles principales OWASP (3.0 ou 3.1) |
|**Contrôle des changements**|Fournir une documentation de stratégie qui régit les processus de contrôle des changements.|
||Fournissez des preuves montrant que les environnements de développement et de test appliquent la séparation des tâches de l’environnement de production.|
||Fournir des preuves montrant que les données de production sensibles ne sont pas utilisées dans les environnements de développement ou de test.|
||Fournissez des preuves montrant que les demandes de modification documentées contiennent l’impact de la modification, des détails des procédures de sortie et des tests à mettre en place.|
||Fournir des preuves montrant que les demandes de modification font l’objet d’un processus d’autorisation et d’approbation.|
|**Sécurisation du développement/déploiement de logiciels**| Fournir des stratégies et des procédures qui permettent de sécuriser le développement et le déploiement de logiciels, notamment des conseils sur les meilleures pratiques de codage sécurisé par rapport aux classes de vulnérabilité courantes telles que OWASP Top 10 ou SANS Top 25 CWE.|
|| Fournir des preuves montrant que les modifications de code font l’objet d’un processus de révision et d’autorisation par un deuxième réviseur.|
|| Fournissez des preuves montrant que les développeurs suivent une formation de développement logiciel sécurisée annuellement.|
|| Fournir des preuves montrant que les référentiels de code sont sécurisés à l’aide de l’authentification multifacteur (MFA).|
|| Fournir des preuves montrant que des contrôles d’accès sont en place pour sécuriser les référentiels de code.
|**Gestion des comptes**| Fournir une documentation de stratégie qui régit les pratiques et procédures de gestion des comptes.
||Fournissez des preuves montrant que les informations d’identification par défaut sont désactivées, supprimées ou modifiées dans les composants système échantillonés.|
||Fournir une preuve montrant que la création, la modification et la suppression de compte passe par un processus d’approbation établi.|
||Fournir des preuves montrant qu’un processus est en place pour désactiver ou supprimer des comptes non utilisés dans les 3 mois.|
||Fournissez des preuves montrant qu’une stratégie de mot de passe forte ou d’autres atténuations appropriées pour protéger les informations d’identification de l’utilisateur sont en place.  Les valeurs suivantes doivent être utilisées comme consigne minimale : longueur minimale du mot de passe de 8 caractères, seuil de verrouillage du compte de 10 tentatives maximum, historique des mots de passe d’un minimum de 5 mots de passe, application de l’utilisation d’un mot de passe fort|
||Fournir des preuves montrant que des comptes d’utilisateur uniques sont émis à tous les utilisateurs.|
||Fournissez des preuves montrant que les principes des privilèges minimum sont respectés au sein de l’environnement.|
||Fournissez des preuves montrant qu’un processus est en place pour sécuriser ou sécuriser les comptes de service et que le processus est suivi.|
||Fournissez des preuves montrant que l’mf est configurée pour toutes les connexions d’accès à distance et toutes les interfaces d’administration non console.|
||Fournissez des preuves montrant que le chiffrement fort est configuré pour toutes les connexions d’accès à distance et toutes les interfaces d’administration non console, y compris l’accès aux référentiels de code et aux interfaces de gestion cloud.|
||Fournissez des preuves montrant que l’ment MFA est utilisé pour protéger le portail d’administration que vous utilisez pour gérer et gérer tous les enregistrements DNS (Public Domain Name Service).|
|**Détection et prévention des intrusions (FACULTATIF) :** Un crédit supplémentaire sera crédité pour satisfaire les contrôles suivants|Fournissez des preuves montrant que les systèmes de détection et de prévention des intrusions (IDPS) sont déployés sur le périmètre des environnements dans l’étendue.|
||Fournir des preuves montrant que les signatures IDPS sont conservées à jour (dans les 24 heures).|
||Fournissez des preuves montrant que le service IDPS est configuré pour prendre en charge l’inspection TLS de tout le trafic web entrant.|
||Fournissez des preuves montrant que les services IDPS sont configurés pour surveiller tous les flux de trafic entrant.|
||Fournissez des preuves montrant que les services IDPS sont configurés pour surveiller tous les flux de trafic sortant.|
|**Journalisation des événements de sécurité** |Fournir une documentation de stratégie pour les meilleures pratiques et procédures qui régissent la journalisation des événements de sécurité.|
|| Fournir des preuves montrant que la journalisation des événements de sécurité est définie dans tous les composants système échantillonés pour consigner les événements suivants : accès utilisateur aux composants système et à l’application, toutes les actions entreprises par un utilisateur à privilèges élevés, accès logique non valide tente de créer ou de modifier un compte privilégié, falsification du journal des événements, Désactivation des outils de sécurité (par exemple, logiciel anti-programme malveillant ou journalisation des événements),  Journalisation des logiciels anti-programme malveillant (telles que les mises à jour, la détection des programmes malveillants et les échecs d’analyse)., événements IDPS et WAF, s’ils sont configurés|
||Fournir des preuves montrant que les événements de sécurité consignés contiennent les informations minimales suivantes : Utilisateur, Type d’événement, Date et heure, Indicateurs de réussite ou d’échec, Étiquette qui identifie le système concerné|
||Fournissez des preuves montrant que tous les composants système échantillonés sont synchronisés dans le temps sur les mêmes serveurs principaux et secondaires.|
||Fournissez des preuves manifestes lorsque des systèmes publics sont en cours d’utilisation que les journaux des événements de sécurité sont envoyés à une solution de journalisation centralisée qui ne se trouve pas dans le réseau de périmètre.|
||Fournissez des preuves crédibles pour montrer que la solution de journalisation centralisée est protégée contre toute falsification non autorisée des données de journalisation.|
||Fournissez la preuve qu’un minimum de 30 jours de données de journalisation des événements de sécurité sont immédiatement disponibles, avec 90 jours de journaux des événements de sécurité conservés.|
|**Révision (données du journal)** |Fournir une documentation de stratégie qui régit les pratiques et procédures de révision des journaux.|
||Fournissez des preuves crédibles que les journaux sont examinés quotidiennement par un outil humain ou automatisé pour identifier les événements de sécurité potentiels.|
||Fournir des preuves crédibles que des événements de sécurité potentiels et des anomalies sont examinés et corrigés.|
|**Alertes** | Fournir une documentation de stratégie qui régit les procédures et les pratiques d’alerte des événements de sécurité.|
|| Fournir des preuves crédibles que des alertes sont déclenchées pour un tri immédiat pour les types d’événements de sécurité suivants : création ou modification de compte privilégié, événements de virus ou de programmes malveillants, falsification du journal des événements, événements IDPS ou WAF|
||Fournissez des preuves montrant que le personnel est toujours disponible, toute la journée, tous les jours, pour répondre aux alertes de sécurité.|
|**Gestion des risques**|Fournir des preuves montrant qu’un processus formel de gestion des risques de sécurité des informations est établi.|
||Fournissez des preuves qu’une évaluation formelle des risques se produit annuellement, au minimum.|
||Fournissez des preuves crédibles que l’évaluation des risques de sécurité des informations inclut des menaces, des vulnérabilités ou l’équivalent.|
||Fournissez des preuves crédibles que l’évaluation des risques de sécurité des informations inclut l’impact, la matrice de risque de probabilité ou l’équivalent.|
||Fournir des preuves crédibles que l’évaluation des risques de sécurité des informations inclut un registre de risque et un plan de traitement.|
|**Réponse aux incidents**|Fournir le plan de réponse aux incidents de sécurité (IRP).|
||Fournir des preuves crédibles que l’IRP de sécurité inclut un processus de communication documenté pour assurer une notification opportune aux principales parties prenantes, telles que les marques de paiement et les acquisitions, les organismes de réglementation, les autorités de surveillance, les directeurs et les clients.|
||Fournissez la preuve que tous les membres de l’équipe de réponse aux incidents ont suivi une formation annuelle ou un exercice de tableau.|
||Fournissez des preuves crédibles pour montrer que l’IRP de sécurité est mis à jour en fonction des leçons apprises ou des modifications organisationnelles.|

## <a name="data-handling-security-and-privacy"></a>Sécurité et confidentialité de la gestion des données

Les données en transit entre l’utilisateur de l’application, les services intermédiaires et les systèmes isv doivent être protégées par chiffrement via une connexion TLS qui permet de prendre en charge un minimum de TLS v1.1. *Voir* [**l’annexe A**](#appendix-a).

Lorsque votre application récupère et stocke des données M365, vous devez implémenter un schéma de chiffrement de stockage de données qui suit la spécification définie dans [**l’Annexe B**](#appendix-a).

### <a name="controls"></a>Contrôles

|**Famille de contrôles**| **Controls** |
| -----------------------|-------------------------------- |
|**Données en transit**| Fournir des preuves montrant que la configuration TLS répond ou dépasse les exigences de chiffrement dans les exigences de [configuration de profil TLS](../docs/certification-submission-guide.md#appendix-a)|
||Fournir des preuves montrant que la compression TLS est désactivée dans tous les services publics qui gèrent les demandes web.|
||Fournissez des preuves montrant que la sécurité de transport http TLS stricte est activée et configurée pour >= 15552000 sur tous les sites.|
|**Données au repos**| Fournissez des preuves montrant que les données au repos sont chiffrées en ligne avec les exigences de profil de chiffrement, à l’aide d’algorithmes de chiffrement tels qu’AES, Latérienne, TDES et les tailles de clés de chiffrement 128 bits et 256 bits.|
||Fournissez des preuves montrant que la fonction de hachage ou l’authentification de message (HMAC-SHA1) est utilisée uniquement pour protéger les données au repos en ligne avec les exigences de profil de chiffrement.|
||Fournissez un inventaire montrant toutes les données stockées, y compris l’emplacement de stockage et le chiffrement utilisés pour protéger les données.|
|**Conservation et suppression de données**|Fournir des preuves montrant qu’une période de rétention des données approuvée et documentée est officiellement établie.|
||Fournir des preuves montrant que les données conservées correspond à la période de rétention définie.|
||Fournir des preuves montrant que des processus sont en place pour supprimer en toute sécurité des données après sa période de rétention.|
|**Gestion de l’accès aux données**|Fournissez une liste de toutes les personnes ayant accès aux données ou aux clés de chiffrement, y compris la justification professionnelle.|
||Fournissez des preuves montrant que les personnes échantillonnables qui ont accès aux données ou aux clés de chiffrement ont été officiellement approuvées, en détaillant les privilèges requis pour leur fonction.|
||Fournissez des preuves montrant que les personnes échantillonnables qui ont accès aux données ou aux clés de chiffrement ont uniquement les privilèges inclus dans l’approbation.|
||Fournissez la liste de tous les tiers avec qui les données client sont partagées.|
||Fournir des preuves montrant que tous les tiers qui consomment des données client ont des accords de partage en place.|
|**R GDPR** (le cas échéant)| Fournir un processus documenté de demande d’accès de l’objet (R.A.S.) et fournir des preuves montrant que les sujets de données sont en mesure de lever des demandes d’accès client.|
||Fournissez des preuves montrant que vous êtes en mesure d’identifier tous les emplacements des données des personnes qui répondent à une recherche de détail.|
||Vous conservez une notification de confidentialité qui doit contenir les détails de la société (nom, adresse, etc.).|
||Vous conservez une notification de confidentialité qui doit expliquer les types de données personnelles en cours de traitement.|
||Vous conservez une notification de confidentialité qui doit expliquer la loi du traitement des données personnelles|
||Vous conservez une notification de confidentialité qui explique en détail les droits de la personne objet de données : Droit d’être informé, Droit d’accès par la personne objet de données, Droit à l’effacement, Droit à la restriction du traitement, Droit à la portabilité des données, Droit à l’objet, Droits en relation avec la prise de décision automatisée, y compris le profilage.|
|| Vous conservez une notification de confidentialité qui doit expliquer la durée pendant laquelle les données personnelles seront conservées.|

## <a name="optional-external-compliance-frameworks-review"></a>Révision facultative des frameworks de conformité externe

Bien que cela ne soit pas obligatoire, si vous êtes actuellement en conformité avec la norme ISO 27001, PCI DSS ou SOC2, vous pouvez utiliser ces certifications pour satisfaire certains contrôles de certification Microsoft 365. Les analystes de certification essaieront d’aligner les infrastructure de sécurité externes existantes sur la Microsoft 365 certification. Toutefois, si la documentation de prise en charge ne peut pas garantir que les contrôles de certification Microsoft 365 ont été évalués dans le cadre de l’audit/l’évaluation des cadres de sécurité externes, vous devrez fournir des preuves supplémentaires des contrôles en place.

La documentation doit démontrer de manière adéquate que l’environnement dans l’étendue de la certification Microsoft 365 a été inclus dans l’étendue de ces cadres de sécurité externes. La validation de ces cadres de sécurité sera effectuée en acceptant les preuves de certifications valides effectuées par des sociétés tierces dignes de confiance. Ces sociétés fiables doivent être membres d’organismes d’accréditation internationaux pour les programmes de conformité pertinents. Voir normes de certification iso et de conformité pour ISO 27001 et évaluateurs de sécurité qualifiés (QSA) pour PCI DSS.

Le tableau suivant met en évidence les cadres externes et la documentation requises par les analystes de certification dans le cadre de ce processus de validation :

| **Standard** | **Configuration requise** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Une version publique de la déclaration **d’applicabilité** (SOA) et une copie du certificat ISO 27001 émis seront requises.  Le soa récapitule votre position sur chacun des 114 contrôles de sécurité des informations et sera utilisé pour identifier si une exclusion de contrôles qui ne sont pas détaillées de manière satisfaisante dans le certificat ISO 27001. Si cela ne peut pas être déterminé par la révision de la version publique de l’SOA, l’analyste peut avoir besoin d’accéder à l’intégralité de l’SOA si la norme ISO 27001 est utilisée pour valider certains contrôles de spécification de certification Microsoft 365.  Outre la validation de l’étendue des activités d’évaluation ISO 27001, les analystes confirmeront également la validité de la société d’audit comme décrit ci-dessus.|
|**[PCI DSS](#pci-dss)**| Un document AOC ( **Attestation de** conformité de niveau 1) valide doit être fourni pour identifier clairement l’application et les composants système dans l’étendue.  Un AOC d’auto-évaluation **ne** sera pas accepté comme preuve de la réunion des meilleures pratiques en matière de sécurité. L’AOC sera utilisé pour déterminer quels contrôles des spécifications de certification Microsoft 365 ont été évalués et confirmés dans le cadre de l’évaluation PCI DSS.|
|**[SOC 2](#soc-2)**|Le rapport **SOC 2 (Type I ou Type II)** doit être à jour (émis au cours des 15 derniers mois et la période déclarée démarrée au cours des 27 derniers mois) à utiliser comme preuve de conformité avec l’un des contrôles d’évaluation au sein de cette spécification de certification Microsoft 365.|

Si des frameworks de sécurité externes ont été inclus dans l’attestation Publisher, les analystes de certification devront vérifier la validité de ces frameworks de conformité de sécurité dans le cadre de l’évaluation de la certification Microsoft 365.

|**Infrastructure** | **Considérations supplémentaires** |
|-------------- | --------------------|
|ISO 27001| [**Annexe C**](#appendix-c) : Collecte de preuves – Deltas pour ISO 27001.|
|PCI DSS | [**Annexe D**](#appendix-d) : Collecte de preuves – Deltas pour PCI DSS.|
|SOC 2| [**Annexe E**](#appendix-e) : Collecte de preuves – Deltas pour SOC 2.|

> [!NOTE]
> Bien que les normes/frameworks de sécurité externes mentionnés ci-dessus peuvent être soumis comme preuves pour répondre à certains contrôles de certification Microsoft 365, le fait de passer la certification Microsoft 365 ne signifie pas que vous réussirez à passer un audit de ces normes/frameworks. La Microsoft 365 certification de l’entreprise n’est qu’un petit sous-ensemble de ces normes/frameworks de sécurité qui permet à Microsoft d’obtenir un niveau d’assurance en référence à votre posture de sécurité.


### <a name="requirements-to-use-external-compliance-frameworks"></a>Conditions requises pour utiliser des cadres de conformité externes

&#x2713; l’environnement de prise en charge des applications/des  applications et des applications et  tout processus d’entreprise de prise en charge DOIVENT être inclus dans l’étendue des frameworks de conformité de sécurité externe pris en charge et doivent être clairement indiqués dans la documentation fournie.

&#x2713; Les **frameworks de** conformité de sécurité externe pris en charge DOIVENT être à jour, c’est-à-dire au cours des 12 derniers mois (ou dans les 15 mois si la réévaluation est en cours d’évaluation et que des preuves peuvent être fournies).

&#x2713; les cadres de conformité de sécurité externe pris en charge **DOIVENT** être exécutés par une société agréée indépendante.

## <a name="appendix-a"></a>Annexe A

### <a name="tls-profile-configuration-requirements"></a>Configuration requise pour le profil TLS

Tout le trafic réseau, qu’il s’agit d’un réseau virtuel, d’un service cloud ou d’un centre de données, doit être protégé avec un minimum de TLS v1.1 (TLS v1.2+ est recommandé) ou tout autre protocole applicable. Les exceptions à cette exigence sont :

* **Redirection HTTP vers HTTPS**. Votre application peut répondre sur HTTP pour rediriger les clients vers HTTPS, mais la réponse ne doit pas contenir de données sensibles (cookies, en-têtes, contenu). Aucune autre réponse HTTP autre que les redirections vers HTTPS et la réponse aux sondes d’état sont autorisées. Voir ci-dessous.
* **Sondes d’état**. Votre application peut répondre aux sondes d’état **sur HTTP uniquement** si les sondes d’état HTTPS ne sont pas pris en charge par la partie cochante.
* **Accès au certificat**. L’accès aux points de terminaison CRL, OCSP et AIA à des fins de validation de certificat et de vérification de révocation est autorisé sur HTTP.
* **Communications locales**. Votre application peut utiliser le protocole HTTP (ou d’autres protocoles non protégés) pour les communications qui ne quittent pas le système d’exploitation, e. g. connexion à un point de terminaison de serveur web exposé sur localhost.

La compression TLS **DOIT** être désactivée.

## <a name="appendix-b"></a>Annexe B

### <a name="encryption-profile-configuration-requirements"></a>Conditions requises pour la configuration du profil de chiffrement

Seuls les paramètres et primitives de chiffrement sont autorisés comme suit :

### <a name="symmetric-cryptography"></a>Chiffrement symétrique

**Chiffrement**

&emsp;&#x2713; seuls AES, BitLocker,Térouille ou TDES sont autorisés. Toutes les longueurs de clé >=128 sont autorisées (128, 192 et 256 bits) et peuvent être utilisées (les touches 256 bits sont recommandées).

&emsp;&#x2713; seul le mode CBC est autorisé. Chaque opération de chiffrement doit utiliser un nouveau vecteur d’initialisation généré de manière aléatoire (IV).

&emsp;&#x2713;'utilisation de chiffrements de flux, tels que RC4, **N’est PAS** autorisée.

**Fonctions de hachage**

&emsp;&#x2713; tout nouveau code doit utiliser SHA-256, SHA-384 ou SHA-512 (collectivement appelé SHA-2). La sortie peut être tronquée sur au moins 128 bits

&emsp;&#x2713; SHA-1 ne peut être utilisé que pour des raisons de compatibilité.

&emsp;&#x2713;'utilisation de MD5, MD4, MD2 et autres fonctions de hachage n’est PAS autorisée, même pour les applications non cryptographiques.

**Authentification des messages**

&emsp;&#x2713; tout nouveau code DOIT utiliser HMAC avec l’une des fonctions de hachage approuvées. La sortie de HMAC peut être tronquée sur au moins 128 bits.

&emsp;&#x2713; HMAC-SHA1 ne peut être utilisé que pour des raisons de compatibilité.

&emsp;&#x2713; clé HMAC DOIT être d’au moins 128 bits. Les clés 256 bits sont recommandées.

### <a name="asymmetric-algorithms"></a>Algorithmes asymétriques

**Chiffrement**

&emsp;&#x2713; RSA est autorisé. La **clé DOIT** être d’au moins 2 048 bits et le remplissage OAEP doit être utilisé. L’utilisation du remplissage PKCS n’est autorisée que pour des raisons de compatibilité.

**Signatures**

&emsp;&#x2713; RSA est autorisé. La **clé DOIT** être d’au moins 2 048 bits et le remplissage PSS doit être utilisé. L’utilisation du remplissage PKCS n’est autorisée que pour des raisons de compatibilité.

&emsp;&#x2713;'ECDSA est autorisé. La **clé DOIT** être d’au moins 256 bits. La courbe NIST P-256, P-384 ou P-521 doit être utilisée.

**Clé Exchange**

&emsp;&#x2713; ECDH est autorisé. La **clé DOIT** être d’au moins 256 bits. La courbe NIST P-256, P-384 ou P-521 doit être utilisée.

&emsp;&#x2713; ECDH est autorisé. La **clé DOIT** être d’au moins 256 bits. La courbe NIST P-256, P-384 ou P-521 doit être utilisée.

## <a name="appendix-c"></a>Annexe C

### <a name="evidence-collection--delta-for-iso-27001"></a>Collecte de preuves – Delta pour ISO 27001

Lorsque vous avez déjà atteint la conformité ISO27001, les deltas suivants (lacunes) non entièrement couverts par la norme ISO 27001 devront au minimum être examinés dans le cadre de cette certification Microsoft 365.

> [!NOTE]
> Dans le cadre de votre évaluation de certification Microsoft 365, l’analyste de certification détermine si l’un des contrôles ISO 27001 mappés n’a pas été inclus dans le cadre de l’évaluation ISO 27001 et peut également décider d’échantilloner des contrôles qui ont été trouvés pour être inclus pour fournir une garantie supplémentaire. Toutes les exigences manquantes dans la norme ISO 27001 doivent être incluses dans vos activités d’évaluation Microsoft 365 certification.

**Protection contre les programmes malveillants – Antivirus**

Si la protection contre les programmes malveillants est en place à l’aide du contrôle d’application et est attestée dans le rapport ISO 27001, aucune investigation supplémentaire n’est nécessaire. Si aucun contrôle d’application n’est en place, les analystes de certification doivent identifier et évaluer les preuves des mécanismes de contrôle d’application pour empêcher la détonation de programmes malveillants dans l’environnement. Pour ce faire, vous devez :

* Démontrez que les logiciels antivirus s’exécutent sur tous les composants système échantillonés.

* Démontrez que l’antivirus est configuré sur tous les composants système échantillonés pour bloquer automatiquement les programmes malveillants, mettre en quarantaine & alerte ou pour alerter.

* Les logiciels antivirus **DOIVENT être** configurés pour enregistrer toutes les activités.

**Gestion des correctifs : correction**

Comme les audits ISO 27001 n’évaluent pas spécifiquement cette catégorie, vous devez :

* Les composants logiciels et les systèmes d’exploitation ne  sont plus pris en charge par le fournisseur. Des stratégies de prise en charge DOIVENT être en place pour garantir que les composants logiciels/systèmes d’exploitation non pris en charge seront supprimés de l’environnement et qu’un processus permettant d’identifier la fin de vie des composants logiciels doit être en place

**Analyse des vulnérabilités**  

Comme les audits ISO 27001 n’évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrer que l’analyse trimestrielle des vulnérabilités internes et externes est effectuée.

* Confirmez que la documentation de prise en charge est en place pour la correction des vulnérabilités en fonction du classement des risques et conforme aux spécifications suivantes :
 
 &#x2713; résoudre tous les problèmes critiques et à risque élevé en ligne avec le classement des risques pour l’analyse interne.
 
 &#x2713; résoudre tous les problèmes critiques, élevés et à risque moyen en ligne avec le classement des risques pour l’analyse externe.
 
 &#x2713; démontrer que la correction est effectuée en ligne avec la stratégie de correction des vulnérabilités documentée.

**Pare-feu : pare-feu (ou technologies équivalentes)**

Comme les audits ISO 27001 n’évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrez que les pare-feu sont installés à la limite de l’environnement dans l’étendue.

* Démontrez que les pare-feu sont installés entre le DMZ et les réseaux de confiance.

*   Démontrez que tous les accès publics se terminent dans la DMZ.

*   Démontrez que les informations d’identification administratives par défaut sont modifiées avant l’installation dans l’environnement en direct.

*   Démontrez que tout le trafic autorisé via le ou les pare-feu passe par un processus d’autorisation qui entraîne la documentation de tout le trafic avec une justification professionnelle.

*   Démontrez que tous les pare-feu sont configurés pour abandonner le trafic non explicitement défini.

*   Démontrez que les pare-feu ne supportent que le chiffrement fort sur toutes les interfaces d’administration non console.

*   Démontrez que les interfaces d’administration non-console du pare-feu exposées à Internet supportent l’mfmf.

*   Démontrer que les révisions des règles de pare-feu sont effectuées au moins tous les 6 mois

**Pare-feu – Pare-feu d’application web (WAF)**  

Un crédit supplémentaire est fourni si un waf est déployé pour vous protéger contre les menaces et les vulnérabilités des applications web qui peuvent être exposées à l’application. Lorsqu’un waf ou similaire est présent, vous devez :

* Démontrez que le waf est configuré en mode de défense active ou surveillez-le davantage avec des alertes.

* Démontrez que le waf est configuré pour prendre en charge le déchargement SSL.

* Est configuré selon l’ensemble de règles principales OWASP (3.0 ou 3.1) pour se protéger contre la plupart des types d’attaques suivants :

&#x2713; protocole et les problèmes de codage.

&#x2713; l’injection d’en-tête, la demande et le fractionnement de réponse.

&#x2713; attaques par traversée de fichier et de chemin d’accès.

&#x2713; les attaques d’inclusion de fichier distante (RFI).

&#x2713; attaques d’exécution de code à distance.

&#x2713; attaques par injection php.

&#x2713; attaques par scripts entre sites.

&#x2713; SQL d’injection.

&#x2713; attaques par attachement de session.

**Contrôle des changements**

Comme les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus de demande de modification, vous devez :

* Démontrez que les demandes de modification ont les détails suivants :

&#x2713; impact documenté.

&#x2713; détails sur les tests de fonctionnalités à effectuer.

&#x2713; détails des procédures de back-out.

* Démontrez que le test des fonctionnalités est effectué une fois les modifications terminées.

* Démontrer que les demandes de modification sont signées après le test des fonctionnalités.

**Gestion des comptes**

Comme les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus de gestion des comptes, vous devez :

*   Montrer comment les &#x2713;sont implémentées pour atténuer les attaques par relecture (par exemple, MFA, Kerberos).
*   Expliquer comment les comptes qui n’ont pas été utilisés depuis 3 mois sont désactivés ou supprimés.
*   &#x2713; ou d’autres atténuations appropriées doivent être configurées pour protéger les informations d’identification de l’utilisateur. La stratégie de mot de passe minimale suivante doit être utilisée à titre indicatif :

&#x2713; longueur minimale du mot de passe de 8 caractères.

&#x2713; le seuil de verrouillage du compte ne peut pas être supérieur à 10 tentatives.
 
&#x2713;'historique des mots de passe d’au moins cinq mots de passe.
 
&#x2713; l’application de l’utilisation de mots de passe forts.
 
*   Démontrez que l’mf est configuré pour toutes les solutions d’accès à distance.

*   Démontrez que le chiffrement fort est configuré sur toutes les solutions d’accès à distance.

*   Lorsque la gestion du DNS public se trouve en dehors de l’environnement dans l’étendue, tous les comptes d’utilisateurs en mesure d’apporter des modifications DNS DOIVENT être configurés pour utiliser l’usage de l’mf.

**Détection et prévention des intrusions (FACULTATIF)**

Comme les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus IDPS (Intrusion Detection and Prevention Services), vous devez :

*   Les IDPS **doivent** être déployés sur le périmètre de l’environnement de prise en charge.

*   Les signatures IDPS **doivent** rester à jour au cours du dernier jour.

*   IDPS **doit être** configuré pour l’inspection TLS.

*   IDPS **DOIT être** configuré pour TOUT le trafic entrant et sortant.

*   Les IDPS **doivent** être configurés pour les alertes.

**Journalisation des événements**

Comme les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus de journalisation des événements de sécurité, vous devez :

* Démontrez que les systèmes publics se connectent à une solution de journalisation centralisée qui ne se trouve pas dans le DMZ.

* Démontrez comment un minimum de 30 jours de données de journalisation est immédiatement disponible, avec 90 jours conservés.

**Reviewing (Logging Data)**

Comme les audits ISO 27001 n’évaluent pas spécifiquement certains éléments de cette catégorie, vous devez :

*   Démontrez comment les révisions quotidiennes des journaux sont effectuées et comment les exceptions et anomalies sont identifiées, montrant comment elles sont gérées.

**Alertes**

Comme les audits ISO 27001 n’évaluent pas spécifiquement certains éléments de cette catégorie, vous devez :

* Montrer comment les événements de sécurité sont configurés pour déclencher des alertes pour un tri immédiat.

* Montrer comment le personnel est disponible 24 h/24 et 7 jours sur 7 pour répondre aux alertes de sécurité.

**Gestion des risques**

Comme les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus d’évaluation des risques, vous devez :

* Démontrer qu’un processus formel de gestion des risques est établi.

**Réponse aux incidents**

Comme les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des stratégies et processus de réponse aux incidents, vous devez :

*   Démontrez que le plan/procédure de réponse aux incidents inclut :

&#x2713; procédures de réponse spécifiques pour les modèles de menace attendus.

&#x2713; fonctionnalités de gestion des incidents alignées sur NIST Cybersecurity Framework (identifier, protéger, détecter, répondre, récupérer).
 
&#x2713; IRP couvre les systèmes dans l’étendue.
 
&#x2713; formation annuelle pour l’équipe de réponse aux incidents.

## <a name="appendix-d"></a>Annexe D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Collecte de preuves : deltas pour PCI DSS

Lorsque vous avez déjà atteint la conformité PCI DSS, les deltas suivants (lacunes) non entièrement couverts par PCI DSS devront au minimum être examinés dans le cadre de cette certification Microsoft 365.

> [!NOTE]
> Dans le cadre de l’évaluation de la certification Microsoft 365, l’analyste de certification détermine si l’un des contrôles PCI DSS mappés n’a pas été inclus dans le cadre de l’évaluation PCI DSS et peut également décider d’exemples de contrôles qui ont été trouvés pour être inclus pour fournir une garantie supplémentaire. Toutes les exigences manquantes dans le DSS PCI doivent être incluses dans les activités d’évaluation Microsoft 365 certification.

**Protection contre les programmes malveillants : contrôle des applications**

Si la protection contre les programmes malveillants est en place par le biais de l’utilisation d’antivirus et est attestée dans le rapport PCI DSS, aucune investigation supplémentaire n’est nécessaire. Si aucun antivirus n’est en place, les analystes de certification doivent identifier et évaluer les preuves des mécanismes de contrôle des applications pour empêcher la détonation de programmes malveillants dans l’environnement. Pour ce faire, vous devez : 

*   Démontrez comment l’approbation de l’application est effectuée et confirmez que cette opération est terminée.

*   Démontrez qu’il existe une liste complète des applications approuvées avec justification professionnelle.

*   Fournissez ou démontrez que la documentation de prise en charge est en place et détaille la configuration du logiciel de contrôle d’application pour répondre à des mécanismes de contrôle d’application spécifiques (mise en liste blanche, signature de code, etc.).

*   Démontrez que dans tous les composants système échantillonés, le contrôle d’application est configuré comme documenté.

**Gestion des correctifs : classement des risques**

Comme les audits PCI DSS n’évaluent pas spécifiquement cette catégorie, vous devez :

* Montrer comment le classement des vulnérabilités par risque est effectué.

**Analyse des vulnérabilités**

Comme les audits PCI DSS n’évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrer que la correction est effectuée en ligne avec la stratégie de correction des vulnérabilités documentée.

**Pare-feu : pare-feu (ou technologies équivalentes)**

Comme les audits PCI DSS n’évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrez que les pare-feu ne supportent que le chiffrement fort sur toutes les interfaces d’administration non console.

* Démontrez que les interfaces d’administration non-console du pare-feu exposées à Internet supportent l’mfmf.

Un crédit supplémentaire est fourni si un pare-feu d’application web (WAF) est déployé pour vous protéger contre les menaces et vulnérabilités des applications web qui peuvent être exposées à l’application. Lorsqu’un waf ou similaire est présent, vous devez :

* Démontrez que le waf est configuré en mode de défense active ou surveillez-le davantage avec des alertes.

* Démontrez que le waf est configuré pour prendre en charge le déchargement SSL.

* Est configuré selon l’ensemble de règles principales OWASP (3.0 ou 3.1) pour se protéger contre la plupart des types d’attaques suivants :

&#x2713; protocole et les problèmes de codage.

&#x2713; l’injection d’en-tête, la demande et le fractionnement de réponse.

&#x2713; attaques par traversée de fichier et de chemin d’accès.

&#x2713; les attaques d’inclusion de fichier distante (RFI).

&#x2713; attaques d’exécution de code à distance.

&#x2713; attaques par injection php.

&#x2713; attaques par scripts entre sites.

&#x2713; SQL d’injection.

&#x2713; attaques par attachement de session.

**Contrôle des changements**

Comme les audits PCI DSS n’évaluent pas spécifiquement certains éléments des processus de demande de modification, vous devez :

* Démontrez que les demandes de modification sont formulées avant d’être faites dans les environnements de production.

* Démontrez que les modifications sont autorisées avant de passer en production.

* Démontrez que le test des fonctionnalités est effectué une fois les modifications terminées.

* Démontrer que les demandes de modification sont signées après le test des fonctionnalités.

**Sécurisation du développement/déploiement de logiciels**

Comme les audits PCI DSS n’accèdent pas spécifiquement à certains éléments de processus de déploiement et de développement logiciels sécurisés ; Cela vous sera nécessaire :

* Les référentiels de code DOIVENT être sécurisés par l’mf.

*   Des contrôles d’accès appropriés DOIVENT être en place pour protéger les référentiels de code contre les modifications de code malveillantes.

**Gestion des comptes**

Comme les audits PCI DSS n’évaluent pas spécifiquement certains éléments des processus de gestion des comptes, vous devez :

* Montrer comment les mécanismes d’autorisation sont implémentés pour atténuer les attaques par relecture (par exemple, MFA, Kerberos).

* Des stratégies de mot de passe fortes ou d’autres atténuations appropriées doivent être configurées pour protéger les informations d’identification de l’utilisateur. La stratégie de mot de passe minimale suivante doit être utilisée à titre indicatif : 

&#x2713; longueur minimale du mot de passe de 8 caractères.

&#x2713; le seuil de verrouillage du compte ne peut pas être supérieur à 10 tentatives.

&#x2713;'historique des mots de passe d’au moins cinq mots de passe.

&#x2713; l’application de l’utilisation de mots de passe forts.

* Démontrez que le chiffrement fort est configuré sur toutes les solutions d’accès à distance.

* Lorsque la gestion du DNS public se trouve en dehors de l’environnement dans l’étendue, tous les comptes d’utilisateurs en mesure d’apporter des modifications DNS DOIVENT être configurés pour utiliser l’usage de l’mf.

**Détection et prévention des intrusions (FACULTATIF)**

Comme les audits PCI DSS n’évaluent pas spécifiquement certains éléments des processus IDPS (Intrusion Detection and Prevention Services), vous devez :

* IDPS doit être configuré pour l’inspection TLS.

*   IDPS DOIT être configuré pour TOUT le trafic entrant et sortant.

**Gestion des risques**

Comme les audits PCI DSS n’évaluent pas spécifiquement certains éléments des processus d’évaluation des risques, vous devez :

* Démontrer que l’évaluation des risques inclut des matrices d’impact et de probabilité.

**Réponse aux incidents**

Comme les audits PCI DSS n’évaluent pas spécifiquement certains éléments des stratégies et processus de réponse aux incidents, le développeur devra :

* Faire la démonstration des fonctionnalités de gestion des incidents alignées sur NIST Cybersecurity Framework (identifier, protéger, détecter, répondre, récupérer).

## <a name="appendix-e"></a>Annexe E

### <a name="evidence-collection---deltas-for-soc-2"></a>Collecte de preuves - Deltas pour SOC 2

Lorsque vous avez déjà atteint la conformité SOC 2, les deltas suivants (lacunes) non entièrement couverts par SOC 2 devront être examinés dans le cadre de cette certification Microsoft 365.

> [!NOTE]
> Dans le cadre de l’évaluation de la certification Microsoft 365, l’analyste de certification détermine si l’un des contrôles SOC 2 mappés n’a pas été inclus dans le cadre de votre évaluation SOC 2 et peut également décider d’exemples de contrôles qui ont été trouvés pour être inclus pour fournir une garantie supplémentaire. Toutes les exigences manquantes dans votre évaluation SOC 2 doivent être incluses dans le cadre des activités d’évaluation Microsoft 365 certification.

**Protection contre les programmes malveillants : contrôle des applications**

Si la protection contre les programmes malveillants est en place par le biais de l’utilisation d’antivirus et est attestée dans votre rapport SOC 2, aucune investigation supplémentaire n’est nécessaire. Si aucun antivirus n’est en place, les analystes de certification doivent identifier et évaluer les preuves des mécanismes de contrôle des applications pour empêcher la détonation de programmes malveillants dans l’environnement. Pour ce faire, vous devez :

* Fournissez ou démontrez que la documentation de prise en charge est en place et détaille la configuration du logiciel de contrôle d’application pour répondre à des mécanismes de contrôle d’application spécifiques (mise en liste blanche, signature de code, etc.).

* Démontrez comment l’approbation de l’application est effectuée et confirmez que cette opération est terminée.

*   Démontrez qu’il existe une liste complète des applications approuvées avec justification professionnelle.

*   Démontrez que dans tous les composants système échantillonés, le contrôle d’application est configuré comme documenté.

**Gestion des correctifs : correction**

Comme les audits SOC 2 n’évaluent pas spécifiquement cette catégorie, vous devez :

*   Tout problème faible, moyen, élevé ou critique doit être corrigé dans les fenêtres d’activité de correction normales.

*   Les composants logiciels et les systèmes d’exploitation ne sont plus pris en charge par le fournisseur. Des stratégies de prise en charge DOIVENT être en place pour garantir que les composants logiciels/systèmes d’exploitation non pris en charge seront supprimés de l’environnement et qu’un processus permettant d’identifier la fin de vie des composants logiciels doit être en place.

**Pare-feu : pare-feu**

Comme les audits SOC 2 n’évaluent pas spécifiquement les contrôles de modification des listes de contrôle d’accès au pare-feu, vous devez :

* Démontrez que tout le trafic autorisé via le ou les pare-feu passe par un processus d’autorisation qui entraîne la documentation de tout le trafic avec une justification professionnelle.

* Démontrez que les examens des règles de pare-feu sont effectués au moins tous les six mois.

Un crédit supplémentaire est fourni si un pare-feu d’application web (WAF) ou similaire est déployé pour vous protéger contre les menaces et vulnérabilités des applications web qui peuvent être exposées à l’application. Lorsqu’un waf ou similaire est présent, vous devez :

* Démontrez que le waf est configuré en mode de défense active ou surveillez-le davantage avec des alertes.

* Démontrez que le waf est configuré pour prendre en charge le déchargement SSL.

* Est configuré selon l’ensemble de règles principales OWASP ((3.0 ou 3.1) pour se protéger contre la majorité des types d’attaques suivants :

&emsp;&#x2713; protocole et les problèmes d’encodage.

&emsp;&#x2713; l’injection d’en-tête, la demande de séparation des demandes et le fractionnement de réponse.

&emsp;&#x2713; attaques par traversée de fichier et de chemin d’accès.

&emsp;&#x2713;'inclusion de fichiers distantes (RFI).

&emsp;&#x2713;'exécution de code à distance.

&emsp;&#x2713; attaques par injection php.

&emsp;&#x2713; attaques par scripts entre sites.

&emsp;&#x2713; SQL d’injection.

&emsp;&#x2713; attaques par attachement de session.

**Contrôle des changements**

Comme les audits SOC 2 n’évaluent pas spécifiquement certains éléments des processus de demande de modification, le développeur devra :

* Montrer comment les environnements de développement/test sont distincts de l’environnement de production appliquant la séparation des tâches.

* Démontrez comment les données dynamiques ne sont pas utilisées dans les environnements de développement/test.

* Démontrez que le test des fonctionnalités est effectué une fois les modifications terminées.

* Démontrer que les demandes de modification sont signées après le test des fonctionnalités.

**Sécurisation du développement/déploiement de logiciels**

Comme les audits SOC 2 n’accèdent pas spécifiquement à certains éléments de processus de déploiement et de développement logiciels sécurisés ; Cela vous sera nécessaire :

*   Vous DEVEZ avoir un processus de développement de logiciels établi et documenté couvrant l’ensemble du cycle de vie du développement logiciel.

*   Les développeurs DOIVENT suivre une formation en programmation logicielle sécurisée au moins une fois par an.

*   Les référentiels de code DOIVENT être sécurisés par l’mf.

*   Des contrôles d’accès appropriés DOIVENT être en place pour protéger les référentiels de code contre les modifications de code malveillantes.

**Gestion des comptes**

Comme les audits SOC2 n’évaluent pas spécifiquement certains éléments des processus de gestion des comptes, vous devez :

*   Montrer comment les mécanismes d’autorisation sont implémentés pour atténuer les attaques par relecture (par exemple, MFA, Kerberos).

*   Expliquer comment les comptes qui n’ont pas été utilisés depuis 3 mois sont désactivés ou supprimés.

*   Des stratégies de mot de passe fortes ou d’autres atténuations appropriées doivent être configurées pour protéger les informations d’identification de l’utilisateur. La stratégie de mot de passe minimale suivante doit être utilisée à titre indicatif :

&emsp;&#x2713; mot de passe minimal de 8 caractères.

&emsp;&#x2713; le seuil de verrouillage du compte ne peut pas être supérieur à 10 tentatives.

&emsp;&#x2713;'historique des mots de passe d’au moins 5 mots de passe.

&emsp;&#x2713; l’application de l’utilisation de mots de passe forts

*   Démontrez que des comptes d’utilisateur uniques sont émis pour tous les utilisateurs.

*   Lorsque la gestion du DNS public se trouve en dehors de l’environnement dans l’étendue, tous les comptes d’utilisateurs en mesure d’apporter des modifications DNS DOIVENT être configurés pour utiliser l’usage de l’mf.

**Détection et prévention des intrusions (FACULTATIF).**

Comme les audits SOC 2 n’évaluent pas spécifiquement certains éléments des processus IDPS (Intrusion Detection and Prevention Services), vous devez :

*   Les signatures IDPS doivent rester à jour au cours du dernier jour

*   IDPS DOIT être configuré pour l’inspection TLS

*   IDPS DOIT être configuré pour TOUT le trafic entrant et sortant

**Journalisation des événements**

Comme les audits SOC 2 n’évaluent pas spécifiquement certains éléments des processus de journalisation des événements de sécurité, vous devez :

* Démontrez comment, sur tous les composants système au sein de l’exemple de jeu, le système suivant est configuré pour enregistrer les événements suivants

&emsp;&#x2713; utilisateur aux composants système et aux applications.

&emsp;&#x2713; toutes les actions entreprises par un utilisateur avec des privilèges élevés.

&emsp;&#x2713; tentatives d’accès logique non valides.

Démontrer que les événements enregistrés contiennent ; Au minimum, les informations suivantes :

&emsp;&#x2713; utilisateur.

&emsp;&#x2713; type d’événement.

&emsp;&#x2713; date et heure.

&emsp;&#x2713; de réussite/d’échec.

&emsp;&#x2713; étiquette pour identifier le système concerné.

*   Démontrez que tous les composants système de l’exemple sont configurés pour utiliser la synchronisation heure et qu’ils sont identiques aux serveurs de temps principaux/secondaires.

* Démontrez que les systèmes publics se connectent à une solution de journalisation centralisée qui ne se trouve pas dans le DMZ.

*   Démontrez que les systèmes publics se connectent à une solution de journalisation centralisée qui ne se trouve pas dans le DMZ.

* Démontrez comment la solution de journalisation centralisée est protégée contre toute falsification non autorisée des données de journalisation.

* Démontrez comment un minimum de 30 jours de données de journalisation est immédiatement disponible, avec au moins 90 jours conservés.

**Gestion des risques**

Comme les audits SOC2 n’évaluent pas spécifiquement certains éléments des processus d’évaluation des risques, vous devez :

* Démontrer qu’une évaluation formelle des risques est effectuée au moins une fois par an.

*Réponse aux incidents.*

Comme les audits SOC2 n’évaluent pas spécifiquement certains éléments des stratégies et processus de réponse aux incidents, vous devez :

* Démontrez que le plan/procédure de réponse aux incidents inclut :

&emsp;&#x2713; procédures de réponse spécifiques pour les modèles de menace attendus.

&emsp;&#x2713; processus de communication documenté pour assurer la notification en temps voulu des principales parties prenantes (marques de paiement/acquisition, organismes de réglementation, autorités de surveillance, directeurs, clients, etc.).

## <a name="appendix-f"></a>Annexe F

### <a name="hosting-deployment-types"></a>Types de déploiement d’hébergement

Microsoft reconnaît que vous allez déployer des applications et stocker du code d’application/de add-in dans différents environnements d’hébergement. Les responsabilités globales de certains contrôles de sécurité au sein de la certification Microsoft 365 dépendent de l’environnement d’hébergement utilisé. L’Annexe F examine les types de déploiement courants et les mapite avec les contrôles de sécurité évalués dans le cadre du processus d’évaluation. Les types de déploiement d’hébergement suivants ont été identifiés :

|Types d’hébergement  |Description  |
|-----|------|
|**ISV hébergé**|Les types hébergés par un isv peuvent être définis comme l’endroit où vous êtes responsable de l’infrastructure utilisée pour prendre en charge l’environnement d’application/de add-in. Il peut être physiquement situé dans vos propres centres de données ou centres de données tiers avec un service de colocalisation. En fin de compte, vous avez la propriété totale et le contrôle administratif sur l’infrastructure de prise en charge et l’environnement d’exploitation.|
|**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/overview/what-is-iaas/)|L’infrastructure en tant que service est un service fourni par le fournisseur de services cloud (CSP) qui gère et gère l’infrastructure de prise en charge physique en son nom. En règle générale, la mise en réseau, le stockage, les serveurs physiques et l’infrastructure de virtualisation incombent entièrement au CSP. Le système d’exploitation, l’intermédiaire, l’runtime, les données et les applications sont vos responsabilités. Les fonctionnalités de pare-feu sont également gérées et gérées par le tiers, mais la maintenance de la base de règles de pare-feu reste généralement la responsabilité des consommateurs.|
|**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/overview/what-is-paas/)| La plateforme en tant que service vous permet de mettre en service une plateforme gérée présentant un service qui peut être consommé. Il n’est pas nécessaire d’effectuer des fonctions sysadmin, car le système d’exploitation et l’infrastructure de prise en charge sont gérés par le CSP. Cette fonction est généralement utilisée lorsque les organisations ne souhaitent pas se préoccuper de la présentation d’un service web et peuvent se concentrer sur la création du code source de l’application web et la publication de l’application web sur les services web gérés dans le cloud.  Un autre exemple peut être un service de base de données dans lequel la connectivité est donnée à une base de données, mais l’infrastructure de prise en charge et l’application de base de données sont abstraites du consommateur.   **Remarque : les services Serverless et PaaS sont similaires de sorte que les valeurs Serverless et PasS du type de déploiement d’hébergement de certification Microsoft 365 soient considérées comme identiques.**|
|**Hybride hébergé**|Avec le type hébergé hybride, vous pouvez utiliser plusieurs types hébergés pour prendre en charge différentes parties de l’environnement de prise en charge. C’est peut-être davantage le cas lorsque les applications/les modules sont utilisés dans plusieurs piles M365. Bien que la certification Microsoft 365 soit prise en charge lorsque des applications/modules sont développées dans plusieurs services M365, une évaluation de l’ensemble de l’environnement de prise en charge (entre applications/add-ins) doit être évaluée en fonction de chacun des « mappages de types hébergés » applicables. Parfois, vous pouvez utiliser différents types hébergés pour un seul et même application, l’applicabilité des critères devra toujours suivre les critères « Mappages de types hébergés » sur les différents types hébergés.|
|**Hébergement partagé**|L’hébergement partagé est l’endroit où vous hébergez l’environnement au sein d’une plateforme partagée par plusieurs consommateurs individuels. La spécification Microsoft 365 certification n’a pas été écrite pour tenir compte de ce problème en raison de l’adoption du cloud, l’hébergement partagé n’est pas courant. Si vous pensez que cela est utilisé, contactez Microsoft car des exigences supplémentaires devront être créées pour tenir compte des risques supplémentaires liés à ce type d’hébergement.|


## <a name="appendix-g"></a>Annexe G

## <a name="learn-more"></a>En savoir plus

[Vue d Microsoft 365 du programme de conformité des applications](~/overview.md)  
[Qu’est-ce Microsoft 365 attestation d’Publisher’application ?](~/docs/attestation.md)  
[Qu’est-ce Microsoft 365 certification ?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossaire

### <a name="aia"></a>AIA

*L’accès aux informations d’autorité est un descripteur d’emplacement de service utilisé pour rechercher le certificat de l’autorité de certification émettrice.

### <a name="crl"></a>CRL

*La liste de révocation de certificats permet à un point de terminaison SSL (Secure Sockets Layer) de vérifier qu’un certificat reçu d’un hôte distant est valide et fiable.

### <a name="cvss-score"></a>Score CVSS

*Common Vulnerability Scoreing System est une norme publiée qui mesure la vulnérabilité et calcule un score numérique en fonction de sa gravité.

### <a name="cvss-patch-management-guidelines"></a>Recommandations en matière de gestion des correctifs CVSS

* Critique (9.0 - 10.0)
* Élevé (7,0 - 8,9)
* Moyenne (4,0 - 6,9)
* Faible (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*La zone démilitarisée est un réseau intermédiaire physique ou logique qui interagit directement avec des réseaux externes ou non propriétaires tout en conservant le réseau interne, privé et isolé de l’hôte.

### <a name="euii"></a>EUII

*Informations d’identification de l’utilisateur final*.

### <a name="gdpr"></a>RGPD

*Le règlement général sur la protection des données est une réglementation de l’Union européenne sur la confidentialité et la protection des données pour toutes les données des citoyens de l’UE, quel que soit l’emplacement de votre site d’application.

### <a name="hsts"></a>HSTS

*Http Strict Transport Security utilise un en-tête de réponse HTTP qui demande au navigateur web d’accéder uniquement au contenu sur HTTPS.  Il est conçu pour se protéger contre les attaques de rétrogradation et les piratages de cookies.

### <a name="iec"></a>IEC

*Commissiontechnique internationale.

### <a name="isms"></a>ISMS

*Système de gestion de la sécurité des informations.

### <a name="isv"></a>ISV

Les fournisseurs de sécurité indépendants sont des individus et des organisations qui développent, vendent et vendent des logiciels qui s’exécutent sur des plateformes logicielles et matérielles tierces.

### <a name="iso-27001"></a>ISO 27001

Infrastructure de spécification du système de gestion de la sécurité des informations pour tous les contrôles techniques dans les processus de procédure et les stratégies de gestion des risques d’une organisation.

### <a name="lfi"></a>LFI

*L’inclusion de* fichiers locale permet à un attaquant d’inclure des fichiers sur un serveur via le navigateur web.

### <a name="nist"></a>NIST

Le *National Institute of Standards* (NIST), une agence non réglementaire du département du Commerce des États-Unis, fournit des conseils aux organisations du secteur privé aux États-Unis pour évaluer et approuver leur capacité à prévenir, détecter et répondre aux cyberattaques.

### <a name="non-significant-changes"></a>Modifications non significatives

* Résolutions de bogues mineures.
* Améliorations mineures en matière de performances.
* Systèmes d’exploitation/bibliothèques/correctifs d’application client et serveur.

### <a name="ocsp"></a>OCSP

*Le protocole d’état des* certificats en ligne permet de vérifier l’état de révocation des certificats numériques X.509.

### <a name="oii"></a>OII

*Informations d’identification organisationnelle*.

### <a name="owasp"></a>OWASP

*Ouvrez le Project de sécurité des applications web*.

### <a name="pci-dss"></a>PCI DSS

*Standard de sécurité des données du* secteur des cartes de paiement, une organisation qui maintient des normes pour la sécurité des données des titulaires de carte dans le monde entier.

### <a name="pen-testing"></a>Test du stylet

*Le test de* pénétration est une méthode de test d’une application web en simulant des attaques malveillantes pour rechercher les vulnérabilités de sécurité qu’une personne malveillante pourrait exploiter.

### <a name="saml"></a>SAML

*Security Assertion Markup Language* est une norme ouverte pour l’échange de données d’authentification et d’autorisation entre l’utilisateur, le fournisseur d’identité et le fournisseur de services.

### <a name="sensitive-data"></a>Données sensibles

* Données de contrôle d’accès.
* Contenu client.
* Informations d’identité de l’utilisateur final.
* Données de prise en charge.
* Données personnelles publiques.
* Informations pseudonymes de l’utilisateur final.

### <a name="significant-changes"></a>Modifications importantes

* Déplacement de l’environnement d’hébergement.
* Mises à niveau majeures de l’infrastructure de prise en charge ; par exemple, l’implémentation d’un nouveau pare-feu, les mises à niveau majeures vers les services frontaux, etc.
* Ajout de fonctionnalités et /ou d’extensions à votre application.
* Mises à jour de votre application qui capturent des données sensibles supplémentaires.
* Modifications apportées aux flux de données ou aux modèles d’autorisation de votre application
* Ajout de points de terminaison d’API ou de fonctions de point de terminaison d’API.

### <a name="soc-2"></a>SOC 2

*Service Organization Control 2*, une procédure d’audit technique constituée de cinq principes de service de confiance pour s’assurer que les fournisseurs de services gèrent en toute sécurité les données et la confidentialité des clients d’une organisation.

### <a name="ssl"></a>SSL

*Secure Sockets Layer*.

### <a name="tls"></a>TLS

*Transport Layer Security*.
