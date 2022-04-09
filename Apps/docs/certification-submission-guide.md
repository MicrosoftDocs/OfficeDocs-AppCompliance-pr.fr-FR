---
ms.author: oromalle
title: Guide de soumission de certification Microsoft 365
author: orionomalley
manager: tonybal
description: Microsoft 365 détails du guide de soumission de certification
keywords: équipes de certification des applications Microsoft 365 conformité de la sécurité m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 753b40f63b293fea83705ae8124f5f22cbebe394
ms.sourcegitcommit: 9cc3fe8502a6f21f3f6abb4dd23b99b116c51b8e
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/08/2022
ms.locfileid: "64720978"
---
# <a name="microsoft-365-certification-submission-guide"></a>Guide de soumission de certification Microsoft 365

**Dans cet article**
- [Introduction](#introduction)
- [Conditions préalables](#prerequisites) 
- [Microsoft 365 mises à jour des spécifications de certification](#microsoft-365-certification-specification-updates)
- [Étendue de certification](#certification-scope)
- [Processus de certification](#certification-process)
- [Envoi initial du document](#initial-document-submission) 
- [Collecte de preuves et activités d’évaluation](#evidence-collection-and-assessment-activities)
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

Dans le cadre du programme de conformité des applications Microsoft 365, la certification Microsoft 365 offre aux organisations d’entreprise l’assurance et la confiance que les données et la confidentialité sont correctement sécurisées et protégées lors de l’intégration d’applications/compléments de développeur tiers dans la plateforme Microsoft 365. Les applications et compléments qui réussissent la validation sont désignés **Microsoft 365 certifiés** dans l’ensemble de l’écosystème Microsoft 365. 

En participant au programme de certification Microsoft 365, vous acceptez ces conditions supplémentaires et vous vous conformez à toute documentation associée qui s’applique à votre participation au programme de certification Microsoft 365 avec Microsoft Corporation (« Microsoft », « nous », « nous » ou « notre »). Vous nous indiquez que vous avez le pouvoir d’accepter ces Microsoft 365 conditions supplémentaires de certification au nom de vous-même, d’une société et/ou d’une autre entité, le cas échéant. Nous pouvons modifier, modifier ou mettre fin à ces conditions supplémentaires à tout moment. Votre participation continue au programme de certification Microsoft 365 après toute modification ou modification signifie que vous acceptez les nouvelles conditions supplémentaires. Si vous n’acceptez pas les nouvelles conditions supplémentaires ou si nous mettons fin à ces conditions supplémentaires, vous devez cesser de participer au programme de certification Microsoft 365.

Ce document s’adresse aux éditeurs de logiciels indépendants afin de fournir des informations sur le processus de certification Microsoft 365, les conditions préalables au démarrage du processus et les détails des contrôles de sécurité spécifiques que les éditeurs de logiciels indépendants doivent avoir en place.  Vous trouverez des informations générales sur le programme de conformité des applications Microsoft 365 sous la [page](../overview.md) Microsoft 365 Programme de conformité des applications. 

> [!IMPORTANT]
> Actuellement, Microsoft 365 certification s’applique à tous :
>* Microsoft Teams applications (onglets, bots, etc.).
>* Applications/compléments Sharepoint
>* compléments Office (Word, Excel, PowerPoint, Outlook, Project, OneNote)
>* Webapps

## <a name="prerequisites"></a>Configuration requise

### <a name="publisher-attestation"></a>Attestation de l’éditeur

Avant de recevoir le processus de certification Microsoft 365, vous devez avoir terminé Publisher Attestation. Toutefois, vous pouvez démarrer le processus de certification Microsoft 365 avant de terminer Publisher Attestation.  

### <a name="read-the-microsoft-365-certification-specification"></a>Lire la spécification de certification Microsoft 365

Microsoft recommande à tous les éditeurs de logiciels indépendants de lire cette spécification de certification Microsoft 365 dans son intégralité pour s’assurer que tous les contrôles applicables sont respectés par l’environnement dans l’étendue et l’application/complément. Cela permet de garantir un processus d’évaluation sans heurts.

## <a name="microsoft-365-certification-specification-updates"></a>Microsoft 365 mises à jour des spécifications de certification 

Les mises à jour de la spécification de certification Microsoft 365 sont prévues environ tous les six à douze mois. Ces mises à jour peuvent introduire de nouveaux domaines de sécurité cibles et/ou des contrôles de sécurité. Les mises à jour seront basées sur les commentaires des développeurs, les modifications apportées au paysage des menaces et sur l’augmentation de la base de référence de sécurité du programme à mesure qu’il évoluera. 

Les éditeurs de logiciels indépendants qui ont déjà démarré l’évaluation de certification Microsoft 365 peuvent poursuivre l’évaluation avec la version de la spécification de certification Microsoft 365 qui était valide au démarrage de l’évaluation. Toutes les nouvelles soumissions, y compris la recertification annuelle, devront être évaluées par rapport à la version publiée.

> [!NOTE]
> Vous n’êtes pas tenu de vous conformer à tous les contrôles de cette spécification de certification Microsoft 365 pour obtenir une certification. Toutefois, le passage de seuils (qui ne seront pas divulgués) est en place pour chacun des domaines de sécurité abordés dans cette spécification de certification Microsoft 365. Certains contrôles sont classés comme un « **échec dur** », ce qui signifie que l’absence de ces contrôles de sécurité entraîne l’échec de l’évaluation. 

## <a name="certification-scope"></a>Étendue de certification

**L’environnement dans l’étendue** est l’environnement qui prend en charge la remise du code d’application/complément et prend en charge tous les systèmes principaux avec lequel l’application/le complément peut communiquer. Tous les environnements connectés supplémentaires seront également inclus dans l’étendue, sauf si une segmentation adéquate est en place et que les environnements connectés ne peuvent pas affecter la sécurité de l’environnement dans l’étendue. Tous les environnements de récupération d’urgence devront également être inclus dans l’étendue de l’évaluation, car ces environnements seraient nécessaires pour répondre au service en cas d’événements dans l’environnement principal.  Les composants   **système de portée termin** sont **tous les** appareils et systèmes utilisés dans l’environnement dans l’étendue. Les composants inclus dans l’étendue incluent, mais ne sont pas limités aux éléments suivants :
* Application(s) web(s).
* Serveurs.
* Pare-feu (ou équivalent).
* Commutateurs.
* Équilibreurs de charge.
* Infrastructure virtuelle.
* Portails de gestion web des fournisseurs de cloud 

> [!IMPORTANT]
> L’environnement dans l’étendue doit avoir une zone DMZ et l’environnement de prise en charge de l’application/complément doit être segmenté à partir des systèmes d’entreprise internes et des environnements d’entreprise, limitant ainsi l’étendue des activités d’évaluation aux systèmes inclus uniquement. Les analystes de certification valideront les techniques de segmentation pendant l’évaluation, ainsi que les rapports de test d’intrusion qui auraient dû inclure des tests pour valider l’efficacité de toutes les techniques de segmentation en cours d’utilisation.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infrastructure as a Service (IaaS), Platform as a Service (PaaS) et Software as a Service (SaaS) 
Lorsque IaaS et/ou PaaS sont utilisés pour prendre en charge l’infrastructure de la remise de code d’application ou de complément en cours d’examen, le fournisseur de plateforme cloud est responsable de certains des contrôles de sécurité évalués tout au long du processus de certification. Par conséquent, les analystes de certification devront disposer d’une vérification externe indépendante des bonnes pratiques de sécurité par le fournisseur de plateforme cloud par le biais de rapports de conformité externes tels que les rapports DSS PCI Attestation of Compliance (AOC), ISO27001 ou SOC 2 Type II. 

L’annexe F fournit des détails sur les contrôles de sécurité susceptibles d’être applicables en fonction des types de déploiement suivants et selon que l’application/complément exfiltre ou non les données M365 : 
* ISV hébergé 
* IaaS hébergé 
* PaaS/Serverless hébergé 
* Hébergé hybride 
* Hébergés partagés 

Lorsque IaaS ou PaaS est déployé, vous devez fournir des preuves de l’environnement hébergé dans ces types de déploiement.

### <a name="sampling"></a>Échantillonnage

Les demandes de preuves à l’appui de l’évaluation de certification doivent être basées sur un échantillon des composants système dans l’étendue en tenant compte des différents systèmes d’exploitation, de la fonction principale de l’appareil et des différents types d’appareils. Un exemple approprié sera sélectionné au début du processus de certification. Le tableau suivant doit être utilisé comme guide sur la taille de l’échantillon :

|Taille de la population              | Échantillon                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4|

> [!NOTE]
>Si des différences sont identifiées entre les appareils inclus dans l’échantillon initial, la taille de l’échantillon peut être augmentée pendant l’évaluation. 

## <a name="certification-process"></a>Processus de certification

Avant de commencer le processus de certification, vous devez avoir terminé correctement votre Publisher Attestation. Une fois l’opération terminée, votre processus de certification Microsoft 365 se déroule comme suit :

### <a name="preparation"></a>Préparation
1. Accédez à l’Espace partenaires et passez en revue la documentation [Publisher Attestation](../docs/attestation.md) terminée. Si nécessaire, vous pouvez modifier et mettre à jour vos réponses ; Toutefois, si vous le faites, vous devrez soumettre à nouveau votre documentation d’attestation pour approbation. Si votre soumission est antérieure à trois mois, nous vous demanderons de renvoyer Publisher Attestation à des fins de révision et de validation. 
1. Lisez attentivement le [guide de soumission de certification Microsoft 365](../docs/certification-submission-guide.md) pour comprendre ce qui vous sera demandé. Assurez-vous que vous serez en mesure de répondre aux [exigences de contrôle](../docs/certification-submission-guide.md#app-certification-criteria) spécifiées dans le guide de soumission de certification Microsoft 365.
1. Dans l’Espace partenaires, cliquez sur « Démarrer la certification ». Cela vous amènera à votre portail de soumission de document initial. Envoyez votre [soumission initiale de document](../docs/certification-submission-guide.md#initial-document-submission). Cela nous aidera à déterminer ce qui est dans l’étendue de votre évaluation en fonction de la façon dont votre application est conçue et gère les données client. Consultez fréquemment cette page pour voir si votre soumission a été acceptée.

>[!NOTE]
>Pour toutes les applications Office, vous pouvez référencer notre [guide d’utilisation des applications Office](../docs/userguide.md). Pour toutes les applications web, vous pouvez référencer notre [Guide de l’utilisateur de l’application SaaS](../docs/saasuserguide.md).

### <a name="assessment"></a>Évaluation
1. Une fois que votre soumission initiale de document a été acceptée, l’ensemble des contrôles de sécurité requis pour votre application s’affiche automatiquement dans le portail. Vous devrez ensuite soumettre des preuves pour chaque contrôle démontrant que le contrôle est en place. Gardez à l’esprit que vous disposerez de **60 jours** pour soumettre toutes les preuves. Un analyste examine vos preuves et approuve le contrôle ou demande des preuves nouvelles ou supplémentaires. Consultez fréquemment cette page pour voir si vos preuves ont été acceptées.
### <a name="certification"></a>Certification
1. Une fois votre soumission validée par un analyste, vous serez averti de votre décision de certification. Les applications qui reçoivent une certification recevront un badge sur leur application dans **Les pages AppSource** et **Microsoft Docs** . Vous pouvez en savoir plus sur les avantages complets de la certification [ici](../docs/enterprise-app-certification-guide.md#program-benefits).

## <a name="review-and-re-certification"></a>Révision et recertision
Si votre application subit des [modifications importantes](../docs/certification-submission-guide.md#significant-changes) à tout moment, vous devrez nous en informer.

Vous devrez également effectuer une recertification sur une base annuelle. Cela nécessite la revalidation des contrôles dans l’étendue par rapport à votre environnement actuel. Ce processus peut commencer jusqu’à 90 jours avant l’expiration de votre certification. Votre certification existante n’expirera pas pendant la période de re-certification. La re-certification de tous les programmes expire à l’anniversaire d’un an de votre certification Microsoft 365.

Si votre certification n’est pas renouvelée avant la date d’expiration, l’état de certification de vos applications est révoqué. Tous les badging, icônes et personnalisations de certification associées seront supprimés de votre application, et vous ne pourrez pas publier votre application en tant que Microsoft 365 Certifié.


> [!IMPORTANT]
> **Délai d’envoi :** En moyenne, le processus d’évaluation devrait prendre 30 jours, à condition que vous puissiez vérifier fréquemment l’état de votre soumission et répondre aux commentaires et aux demandes de preuve supplémentaires en temps voulu. Au démarrage du processus de certification, un maximum de 60 jours est autorisé pour terminer l’évaluation. Si toutes les soumissions n’ont pas été terminées au cours de la période de 60 jours, la soumission sera émise en échec et le processus doit recommencer. Ces résultats ne seront pas rendus publics.


## <a name="initial-document-submission"></a>Envoi initial du document


La soumission initiale du document aidera les analystes de certification à effectuer l’étendue et à déterminer ce qui sera dans l’étendue de votre évaluation. Après quoi vous devrez soumettre la documentation et les preuves à l’appui utilisées pour effectuer l’évaluation. Votre soumission initiale doit inclure les informations spécifiées ci-dessous. Pour plus d’informations, consultez le [Guide de sous-mission du document initital](../docs/initialdocumentsubguide.md).

| **DocumentationOverview&nbsp;**     |   **Détails de la documentation**  |
| -------------------------| -----------------------------|
|**Description de l’application/complément** | Description de l’objectif et des fonctionnalités de l’application/complément. Cela doit fournir à l’analyste de certification une bonne compréhension du fonctionnement de l’application/complément et de son utilisation prévue
|**Rapport de test de pénétration** |Rapport de test d’intrusion terminé au cours des 12 derniers mois. Ce rapport doit inclure l’environnement qui prend en charge le déploiement de l’application/de l’ajout, ainsi que tout autre environnement qui prend en charge le fonctionnement de l’application/complément. **Remarque :** si vous n’effectuez pas de tests d’intrusion annuels, vous pouvez choisir de les faire par le biais du processus de certification.|
|**Diagrammes d’architecture**|Diagramme d’architecture logique représentant une vue d’ensemble générale de l’infrastructure de prise en charge de votre application/complément. Cela doit inclure **tous les** environnements d’hébergement et l’infrastructure de prise en charge de l’application/complément. Ce diagramme DOIT représenter tous les différents composants système de prise en charge au sein de l’environnement pour aider les analystes de certification à comprendre les systèmes dans l’étendue et à déterminer l’échantillonnage. Indiquez également le type d’environnement d’hébergement utilisé ; ISV hébergé, IaaS, PaaS ou hybride. **Note:** Lorsque SaaS est utilisé, indiquez les différents services SaaS utilisés pour fournir les services de prise en charge au sein de l’environnement.|
|**Empreinte publique** | Détail de **toutes les** adresses IP et URL publiques utilisées par l’infrastructure de prise en charge. Cela doit inclure la plage d’adresses IP routables totale allouée à l’environnement, sauf si une segmentation adéquate a été implémentée pour fractionner la plage utilisée (une preuve adéquate de la segmentation sera nécessaire)|
|**Diagrammes de flux de données** |Flow diagrammes détaillant les éléments suivants :
||&#x2713; flux de données M365 vers et depuis l’application/complément (y compris [EUII](#euii) et [OII](#oii) ).|
||&#x2713; flux de données M365 au sein de l’infrastructure de prise en charge (le cas échéant)|
||&#x2713; Diagrammes mettant en évidence l’emplacement et les données stockées, la façon dont les données sont transmises à des tiers externes (y compris des détails sur les tiers) et la façon dont les données sont protégées en transit sur des réseaux ouverts/publics et au repos.|
|**Détails du point de terminaison d’API**| Liste complète de tous les points de terminaison d’API utilisés par votre application. Pour mieux comprendre l’étendue de l’environnement, fournissez des emplacements de point de terminaison d’API au sein de votre environnement.                                
|**Autorisations de l’API Microsoft**| Fournissez une documentation détaillant **TOUTES les** API Microsoft utilisées, ainsi que les autorisations demandées pour que l’application/complément fonctionne, ainsi qu’une justification pour les autorisations demandées|
|**Types de stockage de données** |Stockage de données et gestion des documents décrivant :|
||&#x2713; Dans quelle mesure vos clients M365 Data [EUII](#euii) et [OII](#oii) sont reçus et stockés|
||&#x2713; la période de rétention des données.|
||&#x2713; Pourquoi les données M365 client sont capturées.|
||&#x2713; Où les données client M365 sont stockées (doivent être incluses dans les diagrammes de flux de données fournis ci-dessus).|
|**Confirmation de conformité**|Documentation de prise en charge des infrastructures de sécurité externes incluses dans la soumission Publisher Attestation ou à prendre en compte lors de l’examen des contrôles de certification Microsoft 365. Actuellement, les trois éléments suivants sont pris en charge :|
||&#x2713; attestation de conformité [PCI DSS](#pci-dss) (AOC).|
||&#x2713; rapports [SOC 2](#soc-2) de type I/Type II.|
||&#x2713; [ISMSIEC](#isms) /  - 1S0/IEC 27001, instruction d’applicabilité (SoA) et de certification.[](#iec)|
|**Dépendances web**|Documentation répertoriant toutes les dépendances utilisées par l’application/complément avec les versions en cours d’exécution.|
|**Inventaire logiciel**|Inventaire logiciel à jour qui inclut tous les logiciels utilisés dans l’environnement dans l’étendue ainsi que les versions.|
|**Inventaire matériel**| Inventaire matériel à jour utilisé par l’infrastructure de prise en charge. Cela sera utilisé pour faciliter l’échantillonnage lors de l’exécution de la phase d’évaluation. Si votre environnement inclut PaaS, fournissez les détails des services consommés.|

## <a name="evidence-collection-and-assessment-activities"></a>Collecte de preuves et activités d’évaluation

Les analystes de certification devront examiner les preuves de tous les composants système dans l’exemple défini. Les types de preuves nécessaires pour appuyer le processus d’évaluation sont les suivants :

**Collecte de preuves**

* Documentation initiale, mise en évidence dans la section [Soumission de documentation initiale](#initial-document-submission) ci-dessus 
* Documents de stratégie 
* Traiter des documents 
* Paramètres de configuration système 
* Modifier les tickets 
* Modifier les enregistrements de contrôle 
* Rapports système

Diverses méthodes seront utilisées pour recueillir les preuves nécessaires pour terminer le processus d’évaluation.  Cette collection de preuves peut se présenter sous la forme des éléments suivants : 
* Documents 
* Captures d’écran 
* Entrevues 
* Partage d’écrans 

Les techniques de collecte de preuves utilisées seront déterminées pendant le processus d’évaluation. Pour obtenir des exemples concrets du type de preuve requis dans votre soumission, consultez le [Guide des exemples de preuves](../docs/certification-sample-evidence-guide.md).

**Activités d’évaluation**

Les analystes de certification examineront les preuves que vous fournissez pour déterminer si vous avez correctement respecté les contrôles dans cette spécification de certification Microsoft 365. 

Dans la mesure du possible et pour réduire le temps nécessaire à la réalisation de l’évaluation, toute la documentation détaillée dans la soumission  de  [la documentation initiale](#initial-document-submission) doit être fournie à l’avance.

Les analystes de certification examineront d’abord les preuves fournies par la soumission initiale de la documentation et les Publisher les informations d’attestation afin d’identifier les lignes d’interrogation appropriées, la taille de l’échantillonnage et la nécessité d’obtenir d’autres preuves, comme indiqué ci-dessus.  Les analystes de certification analysent toutes les informations collectées pour tirer des conclusions sur la façon dont et si vous respectez les contrôles de cette spécification de certification Microsoft 365. 

## <a name="app-certification-criteria"></a>Critères de certification des applications

Votre application, l’infrastructure de prise en charge et la documentation de prise en charge seront évaluées dans les domaines de sécurité suivants :

1. [**Sécurité des applications**](#application-security)
1. [**Sécurité opérationnelle / Déploiement sécurisé**](#operational-security)
1. [**Sécurité et confidentialité de la gestion des données**](#data-handling-security-and-privacy)

Chacun de ces domaines de sécurité comprend des contrôles clés spécifiques englobant une ou plusieurs exigences spécifiques qui seront évaluées dans le cadre du processus d’évaluation. Pour vous assurer que Microsoft 365 Certification est inclusive pour les développeurs de toutes tailles, chacun des domaines de sécurité est évalué à l’aide d’un système de scoring pour déterminer un score global à partir de chacun des domaines. Les scores pour chacun des contrôles de certification Microsoft 365 sont alloués entre 1 (faible) et 3 (élevé) en fonction du risque perçu que ce contrôle ne soit pas atteint. Chacun des domaines de sécurité aura une marque de pourcentage minimale à considérer comme une passe. Certains éléments de cette spécification incluent certains critères d’échec automatique :

- Les autorisations d’API ne respectent pas le principe des privilèges minimum (PoLP).  
- Aucun rapport de test d’intrusion s’il est nécessaire.
- Aucune défense anti-programme malveillant
- L’authentification multifacteur n’est pas utilisée pour protéger l’accès administratif.  
- Aucun processus de mise à jour corrective.  
- Aucun avis de confidentialité [RGPD](#gdpr) approprié.  

## <a name="application-security"></a>Sécurité des applications

Le domaine de sécurité des applications se concentre sur les trois domaines suivants : 
* Validation des autorisations GraphAPI 
* Vérifications de connectivité externe
* Test de sécurité des applications 

### <a name="graphapi-permission-validation"></a>Validation des autorisations GraphAPI

La validation des autorisations GraphAPI est effectuée pour valider que l’application/complément ne demande pas d’autorisations trop permissives. Pour ce faire, vérifiez manuellement les autorisations demandées. Les analystes de certification recoupent ces vérifications par rapport à la soumission d’attestation Publisher et évaluent le niveau d’accès demandé pour s’assurer que les pratiques de « privilège minimum » sont respectées. Lorsque les analystes de certification estiment que ces pratiques de « privilège minimum » ne sont pas respectées, les analystes de certification ont une discussion ouverte avec vous pour valider la justification métier des autorisations demandées. Toutes les différences par rapport à votre soumission Publisher Attestation trouvée lors de cette révision recevront également des commentaires afin que votre Publisher Attestation puisse être mise à jour. 

### <a name="external-connectivity-checks"></a>Vérifications de connectivité externe

Dans le cadre de l’évaluation, un analyste effectuera une petite présentation des fonctionnalités des applications pour identifier les connexions en dehors de M365.  Toutes les connexions qui ne sont pas identifiées comme étant Microsoft ou des connexions directes à votre service sont signalées et discutées lors de l’évaluation.

### <a name="application-security-testing"></a>Test de sécurité des applications

Un examen adéquat des risques associés à votre application/complément et à votre environnement de prise en charge est essentiel pour assurer aux clients la sécurité de l’application/complément. Les tests de sécurité des applications sous la forme de tests d’intrusion DOIVENT être effectués si votre application dispose d’une connectivité à un service non publié par Microsoft. Si votre application fonctionne de manière autonome sans connectivité à un service ou un backend non Microsoft, les tests d’intrusion ne sont pas nécessaires.


**Étendue des tests d’intrusion**

Les activités de test de pénétration **DOIVENT** être effectuées sur l’environnement de production en direct qui prend en charge le déploiement de l’application/complément (par exemple, où le code d’application/complément est hébergé, qui est généralement la ressource dans le fichier manifeste), ainsi que tout environnement supplémentaire qui prend en charge le fonctionnement de l’application/complément (par exemple, si l’application/complément communique avec d’autres applications web en dehors de Microsoft 365).  Lors de la définition de l’étendue, il faut veiller à ce que tous les systèmes ou environnements « connectés » qui peuvent avoir un impact sur la sécurité de l’environnement dans l’étendue soient également inclus dans TOUTES les activités de test d’intrusion. 

Lorsque des techniques sont utilisées pour segmenter les environnements dans l’étendue d’autres environnements, les activités de test d’intrusion DOIVENT valider l’efficacité de ces techniques de segmentation. Cela doit être détaillé dans le rapport de test d’intrusion. 

Les rapports de test d’intrusion seront examinés pour vous assurer qu’aucune vulnérabilité ne répond aux  **critères d’échec automatique suivants** décrits dans les contrôles ci-dessous.
 
**Exigences en matière de test d’intrusion**

|**Type de critère**|**Contrôles de test d’intrusion**|
| -------------------------|-----------------------------|
|**Critères généraux**| **Controls**|
|| Les tests d’intrusion d’applications et d’infrastructure **DOIVENT** avoir lieu chaque année (tous les 12 mois) et effectués par une entreprise indépendante reconnue. |
|| La correction des vulnérabilités critiques et à haut risque identifiées **doit** être effectuée dans un délai d’un mois après la fin du test de pénétration, ou plus tôt en fonction du processus de mise à jour corrective documenté. |
|| Empreinte externe complète (adresses IP, URL, points de terminaison d’API, etc.) DOIT être inclus dans le cadre des tests de pénétration et doit être documenté dans le rapport de test de pénétration. |
|| Les tests d’intrusion d’application web DOIVENT inclure toutes les classes de vulnérabilité ; par exemple, le plus actuel OWASP Top 10 ou SANS Top 25 CWE. |
|| Il n’est pas nécessaire de retester les vulnérabilités identifiées par l’entreprise de test d’intrusion ; la correction et l’auto-examen sont toutefois suffisants, des preuves suffisantes pour démontrer une correction suffisante **DOIVENT** être fournies pendant l’évaluation.|
|**Critères d’échec automatique :**|**Controls**|
|| Présence d’un système d’exploitation non pris en charge. |
|| Présence de comptes d’administration par défaut, énumérables ou devinables.|
|| Présence de SQL risques d’injection.|
|| Présence de scripts intersites.|
|| Présence de vulnérabilités de parcours d’annuaire (chemin d’accès au fichier).|
|| Présence de vulnérabilités HTTP, par exemple, fractionnement de la réponse d’en-tête, trafic de demandes et attaques desync.|
|| Présence de divulgation de code source (y compris  [LFI](#lfi)).|
|| Tout score critique ou élevé tel que défini par les instructions de gestion des correctifs CVSS.|
|| Toute vulnérabilité technique significative qui peut être facilement exploitée pour compromettre une grande quantité d’EUII ou OUI.|






> [!IMPORTANT]
>Les rapports doivent être en mesure de fournir suffisamment d’assurance que tout ce qui est détaillé dans la section Spécification des tests de sécurité des applications peut être démontré.


**Conditions et règles de test d’intrusion gratuits**

- Pour les éditeurs de logiciels indépendants qui n’effectuent actuellement pas de tests d’intrusion, les tests d’intrusion peuvent être effectués gratuitement avec la certification Microsoft 365. Microsoft organisera et couvrira le coût d’un test d’intrusion pendant jusqu’à 12 jours de tests manuels. Les coûts des tests d’intrusion sont calculés en fonction du nombre de jours nécessaires pour tester l’environnement. Toute dépense dépassant 12 jours de test sera de la responsabilité de l’ISV. 
- Les éditeurs de logiciels indépendants devront présenter des preuves et recevoir l’approbation de 50 % des contrôles dans l’étendue avant la réalisation du test d’intrusion. Pour commencer, remplissez simplement votre soumission initiale de document et choisissez d’inclure les tests d’intrusion dans le cadre de votre évaluation. Vous serez contacté pour définir l’étendue et planifier votre test d’intrusion une fois que vous aurez terminé 50 % des contrôles.
- Le rapport émis une fois la pentecôte terminée sera fourni à l’ISV une fois la certification terminée. Ce rapport ainsi que votre certification Microsoft 365 peuvent être utilisés pour montrer aux clients potentiels que votre environnement est sécurisé.
- Les éditeurs de logiciels indépendants seront également chargés de démontrer que les vulnérabilités identifiées dans le test d’intrusion ont été corrigées avant l’octroi d’une certification, mais n’ont pas besoin de produire un rapport propre.

Une fois qu’un test d’intrusion est organisé, l’éditeur de logiciels indépendants est responsable des frais associés au replanification et aux annulations comme suit :

| **Rééchelonnement de l’échelle de temps des frais** | **Proportion Payable** |
|------------------|------------------------|
| La demande de nouvelle planification a été reçue plus de 30 jours avant la date de début planifiée. | 0 % payable |
| Demande de nouvelle planification reçue 8 à 30 jours avant la date de début planifiée. | 25 % payable |
| Demande de nouvelle planification reçue dans les 2 à 7 jours précédant la date de début prévue avec une date de réservation ferme.| 50 % payable |
| Demande de nouvelle planification reçue moins de 2 jours avant la date de début. | 100 % payable |

| **Échelle de temps des frais d’annulation** | **Proportion Payable** |
|------------------|------------------------|
| La demande d’annulation a été reçue plus de 30 jours avant la date de début planifiée. | 25 % payable |
| La demande d’annulation a été reçue 8 à 30 jours avant la date de début planifiée. | 50 % payable |
| Demande d’annulation reçue dans les 7 jours précédant la date de début planifiée. | 90 % payable |

## <a name="operational-security"></a>Sécurité opérationnelle

Ce domaine mesure l’alignement des processus d’infrastructure et de déploiement de prise en charge de votre application avec les meilleures pratiques de sécurité.

### <a name="controls"></a>Contrôles

|**Famille de contrôles**| **Controls**|
| ------------------------|------------------------------ |
| **Protection contre les programmes malveillants - Antivirus**|Fournissez une documentation de stratégie qui régit les pratiques et procédures antivirus.|
||Fournissez des preuves démontrant que les logiciels antivirus s’exécutent sur tous les composants système échantillonnées.|
||Fournissez des preuves démontrant que les signatures antivirus sont à jour dans tous les environnements (dans un délai d’un jour).|
||Fournissez des preuves démontrant que l’antivirus est configuré pour effectuer une analyse d’accès ou une analyse périodique sur tous les composants système échantillonnées. Remarque : si l’analyse à l’accès n’est pas activée, vous devez activer au minimum l’analyse quotidienne et les alertes.|
||Fournissez des preuves démontrant que l’antivirus est configuré pour bloquer automatiquement les programmes malveillants ou la mise en quarantaine et les alertes sur tous les composants système échantillonné.|
|**Contrôles d’application** : obligatoire uniquement si les logiciels anti-programmes malveillants traditionnels ne sont pas utilisés|Fournissez des preuves démontrant que les applications sont approuvées avant d’être déployées.|
||Fournissez des preuves démontrant qu’une liste complète de demandes approuvées avec justification métier existe et qu’elle est conservée.|
||Fournissez la documentation de prise en charge détaillant que le logiciel de contrôle d’application est configuré pour répondre à des mécanismes de contrôle d’application spécifiques. (Exemple : Liste autorisée : sample1, sample3, signature de code)|
||Fournissez des preuves démontrant que le contrôle d’application est configuré comme documenté à partir de tous les composants système échantillonné.|
|**Gestion des correctifs - Classement des risques**| Fournissez la documentation de stratégie qui régit la façon dont les nouvelles vulnérabilités de sécurité sont identifiées et affectées à un score de risque.|
||Fournissez des preuves de la façon dont les nouvelles vulnérabilités de sécurité sont identifiées.|
||Fournissez des preuves montrant que toutes les vulnérabilités se voient attribuer un classement des risques une fois identifiées.|
|**Patch Managmeent - Mise à jour corrective**|Fournissez une documentation de stratégie pour la mise à jour corrective des composants système dans l’étendue, qui inclut une période de mise à jour corrective minimale appropriée pour les vulnérabilités critiques, élevées et à risque moyen; et la désaffectation de tous les systèmes d’exploitation et logiciels non pris en charge.|
||Fournissez des preuves démontrant que tous les composants système échantillonné sont corrigés.|
||Fournissez des preuves démontrant que tous les systèmes d’exploitation et composants logiciels non pris en charge ne sont pas utilisés dans l’environnement.|
|**Analyse des vulnérabilités**|Fournissez les rapports d’analyse des vulnérabilités des applications web et de l’infrastructure trimestrielle. L’analyse doit être effectuée sur l’intégralité de l’empreinte publique (adresses IP et URL) et des plages d’adresses IP internes.|
||Fournissez des preuves démontrant que la correction des vulnérabilités identifiées lors de l’analyse des vulnérabilités est corrigée conformément à la période de mise à jour corrective documentée.|
|**Pare-feu**|Fournissez une documentation de stratégie qui régit les procédures et les pratiques de gestion du pare-feu.|
||Fournissez des preuves vérifiables que toutes les informations d’identification d’administration par défaut sont modifiées avant l’installation dans des environnements de production.|
||Fournissez des preuves tangibles que les pare-feu sont installés à la limite de l’environnement dans l’étendue et installés entre le réseau de périmètre (également appelé DMZ, zone démilitarisée et sous-réseau filtré) et les réseaux approuvés internes.|
||Fournissez des preuves vérifiables que tous les accès publics se terminent dans la zone démilitarisée (DMZ).|
||Fournissez des preuves tangibles que tout le trafic autorisé via le pare-feu passe par un processus d’approbation.|
||Fournissez des preuves vérifiables que la base de règles de pare-feu est configurée pour supprimer le trafic non défini explicitement.|
||Fournissez des preuves vérifiables que le pare-feu prend en charge uniquement le chiffrement fort sur toutes les interfaces d’administration non console.|
||Fournissez des preuves démontrant que vous effectuez des révisions de règles de pare-feu au moins tous les 6 mois.|
|**Web Application Firewall (WAF) (FACULTATIF)** : un crédit supplémentaire sera récompensé pour satisfaire les contrôles suivants.|Fournissez des preuves démontrant que le Web Application Firewall (WAF) est configuré pour surveiller, alerter et bloquer activement le trafic malveillant.|
||Fournissez des preuves tangibles que le pare-feu d’applications web prend en charge le déchargement SSL.|
||Fournissez des preuves démontrant que le pare-feu d’applications web est protégé contre certaines classes ou toutes les classes de vulnérabilités suivantes conformément à l’ensemble de règles OWASP Core (3.0 ou 3.1) |
|**Modifier le contrôle**|Fournissez une documentation de stratégie qui régit les processus de contrôle des modifications.|
||Fournissez des preuves démontrant que les environnements de développement et de test appliquent la séparation des tâches de l’environnement de production.|
||Fournissez des preuves démontrant que les données de production sensibles ne sont pas utilisées dans les environnements de développement ou de test.|
||Fournissez des preuves démontrant que les demandes de modification documentées contiennent l’impact de la modification, des détails des procédures de sauvegarde et des tests à effectuer.|
||Fournissez des preuves démontrant que les demandes de modification sont soumises à un processus d’autorisation et d’approbation.|
|**Développement/déploiement de logiciels sécurisés**| Fournissez des stratégies et des procédures qui prennent en charge le développement et le déploiement de logiciels sécurisés, notamment des conseils sur les meilleures pratiques de codage sécurisé pour les classes de vulnérabilité courantes telles que OWASP Top 10 ou SANS Top 25 CWE.|
|| Fournissez des preuves démontrant que les modifications de code font l’objet d’un processus d’examen et d’autorisation par un deuxième réviseur.|
|| Fournissez des preuves démontrant que les développeurs suivent une formation de développement logiciel sécurisé chaque année.|
|| Fournissez des preuves démontrant que les référentiels de code sont sécurisés avec l’authentification multifacteur (MFA).|
|| Fournissez des preuves démontrant que des contrôles d’accès sont en place pour sécuriser les référentiels de code.
|**Gestion des comptes**| Fournissez une documentation de stratégie qui régit les pratiques et procédures de gestion des comptes.
||Fournissez des preuves démontrant que les informations d’identification par défaut sont désactivées, supprimées ou modifiées dans les composants système échantillonnées.|
||Fournissez des preuves démontrant que la création, la modification et la suppression d’un compte passent par un processus d’approbation établi.|
||Fournissez des preuves démontrant qu’un processus est en place pour désactiver ou supprimer des comptes non utilisés dans un délai de 3 mois.|
||Fournissez des preuves démontrant qu’une stratégie de mot de passe fort ou d’autres mesures d’atténuation appropriées pour protéger les informations d’identification de l’utilisateur sont en place.  Les éléments suivants doivent être utilisés comme instructions minimales : longueur minimale du mot de passe de 8 caractères, seuil de verrouillage de compte ne dépassant pas 10 tentatives, historique de mot de passe d’au moins 5 mots de passe, application de l’utilisation d’un mot de passe fort|
||Fournissez des preuves démontrant que des comptes d’utilisateur uniques sont émis pour tous les utilisateurs.|
||Fournissez des preuves démontrant que les principes de privilège minimum sont respectés dans l’environnement.|
||Fournissez des preuves démontrant qu’un processus est en place pour sécuriser ou renforcer les comptes de service et que le processus est suivi.|
||Fournissez des preuves démontrant que l’authentification multifacteur est configurée pour toutes les connexions d’accès à distance et toutes les interfaces d’administration non console.|
||Fournissez des preuves démontrant que le chiffrement fort est configuré pour toutes les connexions d’accès à distance et toutes les interfaces d’administration non console, y compris l’accès à tous les référentiels de code et aux interfaces de gestion cloud.|
||Fournissez des preuves démontrant que l’authentification multifacteur est utilisée pour protéger le portail d’administration que vous utilisez pour gérer et gérer tous les enregistrements DNS (Public Domain Name Service).|
|**Détection et prévention des intrusions (FACULTATIF) :** Un crédit supplémentaire sera récompensé pour la satisfaction des contrôles suivants|Fournissez des preuves démontrant que les systèmes de détection et de prévention des intrusions (IDPS) sont déployés dans le périmètre des environnements dans l’étendue.|
||Fournissez des preuves démontrant que les signatures IDPS sont conservées à jour (dans les 24 heures).|
||Fournissez des preuves démontrant que le protocole IDPS est configuré pour prendre en charge l’inspection TLS de tout le trafic web entrant.|
||Fournissez des preuves démontrant que le protocole IDPS est configuré pour surveiller tous les flux de trafic entrant.|
||Fournissez des preuves démontrant que le protocole IDPS est configuré pour surveiller tous les flux de trafic sortant.|
|**Journalisation des événements de sécurité** |Fournissez une documentation de stratégie pour les meilleures pratiques et procédures qui régissent la journalisation des événements de sécurité.|
|| Fournissez des preuves démontrant que la journalisation des événements de sécurité est configurée sur tous les composants système échantillonné pour consigner les événements suivants : accès utilisateur aux composants système et à l’application, Toutes les actions effectuées par un utilisateur à privilèges élevés, tentatives d’accès logique non valides création ou modification de compte privilégié, falsification du journal des événements, désactivation des outils de sécurité (par exemple, anti-programme malveillant ou journalisation des événements).  Journalisation des logiciels anti-programme malveillant (tels que les mises à jour, la détection des programmes malveillants et les échecs d’analyse)., événements IDPS et WAF, s’ils sont configurés|
||Fournissez des preuves démontrant que les événements de sécurité consignés contiennent les informations minimales suivantes : Utilisateur, Type d’événement, Date et heure, Indicateurs de réussite ou d’échec, Étiquette qui identifie le système affecté|
||Fournissez des preuves démontrant que tous les composants système échantillonné sont synchronisés dans le temps avec les mêmes serveurs principaux et secondaires.|
||Fournissez des preuves manifestes lorsque des systèmes publics sont en cours d’utilisation que les journaux des événements de sécurité sont envoyés à une solution de journalisation centralisée qui n’est pas dans le réseau de périmètre.|
||Fournissez des preuves vérifiables pour montrer que la solution de journalisation centralisée est protégée contre toute falsification non autorisée des données de journalisation.|
||Fournissez des preuves vérifiables qu’au moins 30 jours de données de journalisation des événements de sécurité sont immédiatement disponibles, avec 90 jours de journaux des événements de sécurité conservés.|
|**Révision (données de journal)** |Fournissez une documentation de stratégie qui régit les pratiques et procédures de révision des journaux.|
||Fournissez des preuves tangibles que les journaux d’activité sont examinés quotidiennement par un outil humain ou automatisé pour identifier les événements de sécurité potentiels.|
||Fournissez des preuves vérifiables que les événements et anomalies de sécurité potentiels sont examinés et corrigés.|
|**Alerte** | Fournissez une documentation de stratégie qui régit les procédures et les pratiques d’alerte d’événement de sécurité.|
|| Fournir des preuves tangibles que des alertes sont déclenchées pour le triage immédiat des types d’événements de sécurité suivants : création ou modifications de compte privilégiés, événements virus ou programmes malveillants, falsification du journal des événements, événements IDPS ou WAF|
||Fournissez des preuves tangibles montrant que le personnel est toujours disponible, toute la journée, tous les jours, pour répondre aux alertes de sécurité.|
|**Gestion des risques**|Fournir des preuves démontrant qu’un processus formel de gestion des risques liés à la sécurité de l’information est établi.|
||Fournir des preuves tangibles qu’une évaluation formelle des risques a lieu chaque année, au minimum.|
||Fournissez des preuves tangibles que l’évaluation des risques de sécurité des informations inclut des menaces, des vulnérabilités ou l’équivalent.|
||Fournissez des preuves vérifiables que l’évaluation des risques de sécurité des informations inclut l’impact, la matrice de risque de probabilité ou l’équivalent.|
||Fournir des preuves tangibles que l’évaluation des risques liés à la sécurité de l’information comprend un registre des risques et un plan de traitement.|
|**Réponse aux incidents**|Fournissez le plan de réponse aux incidents de sécurité (IRP).|
||Fournissez des preuves tangibles que l’IRP de sécurité comprend un processus de communication documenté pour assurer une notification en temps opportun aux parties prenantes clés, telles que les marques de paiement et les acheteurs, les organismes de réglementation, les autorités de surveillance, les administrateurs et les clients.|
||Fournissez des preuves tangibles que tous les membres de l’équipe de réponse aux incidents ont suivi une formation annuelle ou un exercice de table supérieure.|
||Fournissez des preuves démonstrables pour montrer que l’IRP de sécurité est mis à jour en fonction des leçons apprises ou des changements organisationnels.|

## <a name="data-handling-security-and-privacy"></a>Sécurité et confidentialité de la gestion des données

Les données en transit entre l’utilisateur de l’application, les services intermédiaires et les systèmes isv doivent être protégées par le chiffrement via une connexion TLS prenant en charge un minimum de TLS v1.1. *Voir* [**l’annexe A**](#appendix-a).

Lorsque votre application récupère et stocke des données M365, vous devez implémenter un schéma de chiffrement de stockage de données qui suit la spécification définie à [**l’Annexe B**](#appendix-a).

### <a name="controls"></a>Contrôles

|**Famille de contrôles**| **Controls** |
| -----------------------|-------------------------------- |
|**Données en transit**| Fournir des preuves démontrant que la configuration TLS répond ou dépasse les exigences de chiffrement dans les [exigences de configuration du profil TLS](../docs/certification-submission-guide.md#appendix-a)|
||Fournissez des preuves démontrant que la compression TLS est désactivée sur tous les services publics qui gèrent les requêtes web.|
||Fournissez des preuves démontrant que la sécurité de transport http stricte TLS est activée et configurée pour >= 15552000 sur tous les sites.|
|**Données au repos**| Fournissez des preuves démontrant que les données au repos sont chiffrées en ligne avec les exigences de profil de chiffrement, à l’aide d’algorithmes de chiffrement tels qu’AES, Blowfish, TDES et des tailles de clé de chiffrement de 128 bits et 256 bits.|
||Fournissez des preuves démontrant que la fonction de hachage ou l’authentification de message (HMAC-SHA1) est utilisée uniquement pour protéger les données au repos en ligne avec les exigences de profil de chiffrement.|
||Fournissez un inventaire montrant toutes les données stockées, y compris l’emplacement de stockage et le chiffrement utilisés pour protéger les données.|
|**Conservation et suppression de données**|Fournissez des preuves démontrant qu’une période de conservation des données approuvée et documentée est formellement établie.|
||Fournissez des preuves démontrant que les données conservées correspondent à une période de rétention définie.|
||Fournissez des preuves démontrant que des processus sont en place pour supprimer des données en toute sécurité après sa période de rétention.|
|**Gestion de l’accès aux données**|Fournissez une liste de toutes les personnes ayant accès aux données ou aux clés de chiffrement, y compris la justification métier.|
||Fournissez des preuves démontrant que les personnes échantillonnées qui ont accès aux données ou aux clés de chiffrement ont été officiellement approuvées, détaillant les privilèges requis pour leur fonction professionnelle.|
||Fournissez des preuves démontrant que les personnes échantillonnées qui ont accès aux données ou aux clés de chiffrement ont uniquement les privilèges inclus dans l’approbation.|
||Fournissez une liste de tous les tiers avec qui les données client sont partagées.|
||Fournissez des preuves démontrant que tous les tiers qui consomment des données client ont des accords de partage en place.|
|**RGPD** (le cas échéant)| Fournissez un processus documenté de demande d’accès aux sujets (SAR) et fournissez des preuves démontrant que les personnes concernées par les données sont en mesure de déclencher des DEMANDE.|
||Fournissez des preuves démontrant que vous êtes en mesure d’identifier tous les emplacements des données des personnes concernées lors de la réponse à un sar.|
||Vous conservez un avis de confidentialité qui doit contenir les détails de l’entreprise (nom, adresse, etc.).|
||Vous conservez un avis de confidentialité qui doit expliquer les types de données personnelles en cours de traitement.|
||Vous conservez un avis de confidentialité qui doit expliquer la légalité du traitement des données personnelles|
||Vous conservez un avis de confidentialité qui explique en détail les droits de la personne concernée : Droit d’être informé, Droit d’accès par la personne concernée, Droit à l’effacement, Droit à la restriction du traitement, Droit à la portabilité des données, Droit à l’objet, Droits relatifs à la prise de décision automatisée, y compris le profilage.|
|| Vous conservez un avis de confidentialité qui doit expliquer la durée pendant laquelle les données personnelles seront conservées.|

## <a name="optional-external-compliance-frameworks-review"></a>Révision facultative des frameworks de conformité externe

Bien qu’elle ne soit pas obligatoire, si vous êtes actuellement en conformité avec ISO 27001, PCI DSS ou SOC2, vous pouvez choisir d’utiliser ces certifications pour satisfaire certains des contrôles de certification Microsoft 365. Les analystes de certification tenteront d’aligner les infrastructures de sécurité externes existantes sur la spécification de certification Microsoft 365. Toutefois, si la documentation à l’appui ne peut pas fournir l’assurance que Microsoft 365 contrôles de certification ont été évalués dans le cadre de l’audit/évaluation des infrastructures de sécurité externes, vous devez fournir des preuves supplémentaires de la mise en place de ces contrôles.

La documentation doit démontrer de manière adéquate que l’environnement dans l’étendue de la certification Microsoft 365 a été inclus dans l’étendue de ces infrastructures de sécurité externes. La validation de ces infrastructures de sécurité sera effectuée en acceptant les preuves de certifications valides effectuées par des sociétés tierces externes réputées. Ces entreprises réputées doivent être membres d’organismes d’accréditation internationaux pour les programmes de conformité appropriés. Consultez les normes iso de certification et de conformité pour ISO 27001 et les évaluateurs de sécurité qualifiés (QSA) pour PCI DSS.

Le tableau suivant met en évidence les infrastructures externes et la documentation requises par les analystes de certification dans le cadre de ce processus de validation :

| **Standard** | **Configuration requise** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Une version publique **de l’instruction d’applicabilité** (SOA) et une copie du certificat ISO 27001 émis seront nécessaires.  Le SOA récapitule votre position sur chacun des 114 contrôles de sécurité des informations et sera utilisé pour déterminer si toute exclusion de contrôles qui ne sont pas détaillés de manière satisfaisante dans le certificat ISO 27001. Si cela ne peut pas être déterminé en examinant la version publique du SOA, l’analyste peut avoir besoin d’accéder à la soA complète si ISO 27001 est utilisé pour valider certains des contrôles de spécification de certification Microsoft 365.  En plus de valider l’étendue des activités d’évaluation ISO 27001, les analystes confirmeront également la validité de la société d’audit comme décrit ci-dessus.|
|**[PCI DSS](#pci-dss)**| Un document **d’attestation de conformité** (AOC) de niveau 1 valide doit être fourni identifiant clairement les composants de l’application et du système dans l’étendue.  Un AOC d’auto-évaluation **ne sera pas** accepté comme preuve des meilleures pratiques de sécurité de réunion. L’AOC sera utilisé pour déterminer lequel des contrôles de spécification de certification Microsoft 365 ont été évalués et confirmés dans le cadre de l’évaluation PCI DSS.|
|**[SOC 2](#soc-2)**|Le rapport **SOC 2 (type I ou II)** doit être à jour (émis au cours des 15 derniers mois et la période déclarée commencée au cours des 27 derniers mois) pour être utilisé comme preuve de conformité avec l’un des contrôles d’évaluation dans cette spécification de certification Microsoft 365.|

Si des infrastructures de sécurité externes ont été incluses dans l’attestation Publisher, les analystes de certification devront vérifier la validité de ces infrastructures de conformité de sécurité dans le cadre de l’évaluation de la certification Microsoft 365.

|**Infrastructure** | **Considérations supplémentaires** |
|-------------- | --------------------|
|ISO 27001| [**Annexe C**](#appendix-c) : Collection de preuves – Deltas pour ISO 27001.|
|PCI DSS | [**Annexe D**](#appendix-d) : Collecte de preuves – Deltas pour PCI DSS.|
|SOC 2| [**Annexe E**](#appendix-e) : Collection de preuves – Deltas pour SOC 2.|

> [!NOTE]
> Bien que les normes/frameworks de sécurité externes mentionnés ci-dessus puissent être présentés comme preuves pour répondre à certains des contrôles de certification Microsoft 365, le fait de transmettre la certification Microsoft 365 ne signifie pas que vous réussirez un audit par rapport à ces normes/frameworks. La spécification de certification Microsoft 365 n’est qu’un petit sous-ensemble de ces normes/frameworks de sécurité qui permet à Microsoft d’obtenir un niveau d’assurance en référence à votre posture de sécurité.


### <a name="requirements-to-use-external-compliance-frameworks"></a>Conditions requises pour utiliser des frameworks de conformité externes

&#x2713; L’environnement de prise en charge de l’application/complément **ET** tous les processus métier de prise en charge **DOIVENT** être inclus dans l’étendue de tout framework de conformité de sécurité externe pris en charge et doivent être clairement indiqués dans la documentation fournie.

&#x2713; les infrastructures de conformité de sécurité externe prises en charge **DOIVENT** être à jour, c’est-à-dire au cours des 12 derniers mois (ou dans un délai de 15 mois si la réévaluation est en cours d’exécution et que des preuves peuvent être fournies).

&#x2713; frameworks de conformité de sécurité externe pris en charge **DOIVENT** être exécutés par une société accréditée indépendante.

## <a name="appendix-a"></a>Annexe A

### <a name="tls-profile-configuration-requirements"></a>Configuration requise du profil TLS

Tout le trafic réseau, qu’il s’agisse d’un réseau virtuel, d’un service cloud ou d’un centre de données, doit être protégé avec un minimum de TLS v1.1 (TLS v1.2+ est recommandé) ou un autre protocole applicable. Les exceptions à cette exigence sont les suivantes :

* **Redirection HTTP vers HTTPS**. Votre application peut répondre via HTTP pour rediriger les clients vers HTTPS, mais la réponse ne doit pas contenir de données sensibles (cookies, en-têtes, contenu). Aucune autre réponse HTTP que les redirections vers HTTPS et la réponse aux sondes d’intégrité ne sont autorisées. Voir ci-dessous.
* **Sondes d’intégrité**. Votre application ne peut répondre aux sondes d’intégrité via HTTP **que si** les sondes d’intégrité HTTPS ne sont pas prises en charge par la partie de vérification.
* **Accès au certificat**. L’accès aux points de terminaison CRL, OCSP et AIA à des fins de validation et de révocation de certificat est autorisé via HTTP.
* **Communications locales**. Votre application peut utiliser HTTP (ou d’autres protocoles non protégés) pour les communications qui ne quittent pas le système d’exploitation, par exemple. g. connexion à un point de terminaison de serveur web exposé sur localhost.

La compression TLS **DOIT** être désactivée.

## <a name="appendix-b"></a>Annexe B

### <a name="encryption-profile-configuration-requirements"></a>Configuration requise du profil de chiffrement

Seules les primitives et paramètres de chiffrement sont autorisés comme suit :

### <a name="symmetric-cryptography"></a>Chiffrement symétrique

**Chiffrement**

&emsp;&#x2713; seuls AES, BitLocker, Blowfish ou TDES sont autorisés. Toutes les longueurs de clé prises en charge >=128 sont autorisées (128, 192 et 256 bits) et peuvent être utilisées (les clés 256 bits sont recommandées).

&emsp;&#x2713; seul le mode CBC est autorisé. Chaque opération de chiffrement doit utiliser un vecteur d’initialisation (IV) généré de manière aléatoire.

&emsp;&#x2713; L’utilisation de chiffrements de flux, tels que RC4, **n’est PAS** autorisée.

**Fonctions de hachage**

&emsp;&#x2713; Tout nouveau code doit utiliser SHA-256, SHA-384 ou SHA-512 (collectivement appelé SHA-2). La sortie peut être tronquée à pas moins de 128 bits

&emsp;&#x2713; SHA-1 ne peut être utilisé que pour des raisons de compatibilité.

&emsp;&#x2713; L’utilisation de MD5, MD4, MD2 et d’autres fonctions de hachage n’est PAS autorisée, même pour les applications non cryptographiques.

**Authentification des messages**

&emsp;&#x2713; Tout nouveau code DOIT utiliser HMAC avec l’une des fonctions de hachage approuvées. La sortie de HMAC peut être tronquée en pas moins de 128 bits.

&emsp;&#x2713; HMAC-SHA1 ne peut être utilisé que pour des raisons de compatibilité.

&emsp;&#x2713; clé HMAC DOIT être d’au moins 128 bits. Les clés 256 bits sont recommandées.

### <a name="asymmetric-algorithms"></a>Algorithmes asymétriques

**Chiffrement**

&emsp;&#x2713; RSA est autorisé. La clé **DOIT** être d’au moins 2 048 bits et le remplissage OAEP doit être utilisé. Utilisation du remplissage PKCS uniquement autorisé pour des raisons de compatibilité.

**Signatures**

&emsp;&#x2713; RSA est autorisé. La clé **DOIT** être d’au moins 2 048 bits et le remplissage PSS doit être utilisé. Utilisation du remplissage PKCS uniquement autorisé pour des raisons de compatibilité.

&emsp;&#x2713;ECDSA est autorisé. La clé **DOIT** être d’au moins 256 bits. La courbe NIST P-256, P-384 ou P-521 doit être utilisée.

**Clé Exchange**

&emsp;&#x2713; ECDH est autorisé. La clé **DOIT** être d’au moins 256 bits. La courbe NIST P-256, P-384 ou P-521 doit être utilisée.

&emsp;&#x2713; ECDH est autorisé. La clé **DOIT** être d’au moins 256 bits. La courbe NIST P-256, P-384 ou P-521 doit être utilisée.

## <a name="appendix-c"></a>Annexe C

### <a name="evidence-collection--delta-for-iso-27001"></a>Collection de preuves – Delta pour ISO 27001

Si vous avez déjà atteint la conformité ISO27001, les deltas suivants (lacunes) qui ne sont pas entièrement couverts par ISO 27001 devront, au minimum, être examinés dans le cadre de cette certification Microsoft 365.

> [!NOTE]
> Dans le cadre de votre évaluation de certification Microsoft 365, l’analyste de certification détermine si l’un des contrôles ISO 27001 mappés n’a pas été inclus dans l’évaluation ISO 27001 et peut également décider d’échantillonner les contrôles qui ont été détectés pour fournir une assurance supplémentaire. Toutes les exigences manquantes dans la norme ISO 27001 doivent être incluses dans vos activités d’évaluation de certification Microsoft 365.

**Protection contre les programmes malveillants – Antivirus**

Si la protection contre les programmes malveillants est en place à l’aide du contrôle d’application et est attestée dans le rapport ISO 27001, aucune investigation supplémentaire n’est nécessaire. Si aucun contrôle d’application n’est en place, les analystes de certification doivent identifier et évaluer les preuves des mécanismes de contrôle d’application pour empêcher la détonation de programmes malveillants dans l’environnement. Pour ce faire, vous devez :

* Démontrer que les logiciels antivirus s’exécutent sur tous les composants système échantillonnées.

* Démontrez que l’antivirus est configuré sur tous les composants système échantillonné pour bloquer automatiquement les programmes malveillants, mettre en quarantaine & alerte ou alerter.

* Les logiciels antivirus **DOIVENT** être configurés pour journaliser toutes les activités.

**Gestion des correctifs : mise à jour corrective**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement cette catégorie, vous devez :

* Les composants logiciels et les systèmes d’exploitation ne sont plus pris en charge par le fournisseur ne **doivent** pas être utilisés dans l’environnement. Les stratégies de prise en charge DOIVENT être mises en place pour garantir que les composants logiciels/systèmes d’exploitation non pris en charge seront supprimés de l’environnement et un processus permettant d’identifier le moment où les composants logiciels passent en fin de vie doit être en place

**Analyse des vulnérabilités**  

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrer que l’analyse trimestrielle des vulnérabilités internes et externes est effectuée.

* Vérifiez que la documentation de prise en charge est en place pour la correction des vulnérabilités en fonction du classement des risques et conformément à la spécification comme suit :
 
 &#x2713; résoudre tous les problèmes à risque critique et élevé conformément au classement des risques pour l’analyse interne.
 
 &#x2713; résoudre tous les problèmes à risque critique, élevé et moyen conformément au classement des risques pour l’analyse externe.
 
 &#x2713; Démontrer que la correction est effectuée conformément à la stratégie de correction des vulnérabilités documentée.

**Pare-feu : pare-feu (ou technologies équivalentes)**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrer que les pare-feu sont installés à la limite de l’environnement dans l’étendue.

* Démontrer que les pare-feu sont installés entre la zone DMZ et les réseaux approuvés.

*   Démontrer que tous les accès publics se terminent dans la DMZ.

*   Démontrer que les informations d’identification d’administration par défaut sont modifiées avant l’installation dans l’environnement actif.

*   Démontrer que tout le trafic autorisé via le ou les pare-feu passe par un processus d’autorisation qui aboutifie à la documentation de tout le trafic avec une justification métier.

*   Démontrer que tous les pare-feu sont configurés pour supprimer le trafic non défini explicitement.

*   Démontrez que les pare-feu prennent en charge uniquement le chiffrement fort sur toutes les interfaces d’administration non console.

*   Démontrer que les interfaces d’administration non console du pare-feu exposées à l’authentification multifacteur de prise en charge d’Internet.

*   Démontrer que les révisions des règles de pare-feu sont effectuées au moins tous les 6 mois

**Pare-feu – Pare-feu d’applications web (WAF)**  

Un crédit supplémentaire sera fourni si un pare-feu d’applications web est déployé pour vous protéger contre la multitude de menaces et de vulnérabilités d’application web auxquelles l’application peut être exposée. Lorsqu’un pare-feu d’applications web (WAF) ou similaire est présent, vous devez :

* Montrez que le pare-feu d’applications web est configuré en mode de défense actif ou surveillez davantage avec les alertes.

* Montrez que le pare-feu d’applications web est configuré pour prendre en charge le déchargement SSL.

* Est configuré conformément à l’ensemble de règles OWASP Core (3.0 ou 3.1) pour se protéger contre la plupart des types d’attaque suivants :

&#x2713; problèmes de protocole et d’encodage.

&#x2713; l’injection d’en-tête, la contrebande de demandes et le fractionnement des réponses.

&#x2713; attaques par parcours de fichiers et de chemins d’accès.

&#x2713; attaques RFI (Remote File Inclusion).

&#x2713; attaques d’exécution de code à distance.

&#x2713; attaques par injection PHP.

&#x2713; attaques de script intersites.

&#x2713; SQL attaques par injection.

&#x2713; attaques de fixation de session.

**Modifier le contrôle**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus de demande de modification, vous devez :

* Démontrez que les demandes de modification ont les détails suivants :

&#x2713; impact documenté.

&#x2713; Détails des tests de fonctionnalités à effectuer.

&#x2713; détails des procédures de sauvegarde.

* Démontrer que les tests de fonctionnalités sont effectués une fois les modifications terminées.

* Démontrez que les demandes de modification sont désactivées une fois les tests de fonctionnalités effectués.

**Gestion des comptes**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus de gestion des comptes, vous devez :

*   Montrez comment les &#x2713;sont implémentées pour atténuer les attaques par relecture (par exemple, MFA, Kerberos).
*   Montrez comment les comptes qui n’ont pas été utilisés depuis 3 mois sont désactivés ou supprimés.
*   &#x2713; ou d’autres atténuations appropriées doivent être configurées pour protéger les informations d’identification de l’utilisateur. La stratégie de mot de passe minimale suivante doit être utilisée comme indication :

&#x2713; longueur minimale du mot de passe de 8 caractères.

&#x2713; seuil de verrouillage de compte de 10 tentatives au plus.
 
&#x2713; l’historique des mots de passe d’au moins cinq mots de passe.
 
&#x2713; l’application de l’utilisation de mots de passe forts.
 
*   Démontrer que l’authentification multifacteur est configurée pour toutes les solutions d’accès à distance.

*   Démontrer que le chiffrement fort est configuré sur toutes les solutions d’accès à distance.

*   Lorsque la gestion du DNS public se trouve en dehors de l’environnement dans l’étendue, tous les comptes d’utilisateurs capables d’apporter des modifications DNS DOIVENT être configurés pour utiliser l’authentification multifacteur.

**Détection et prévention des intrusions (FACULTATIF)**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus IDPS (Intrusion Detection and Prevention Services), vous devez :

*   IDPS **DOIT** être déployé au périmètre de l’environnement de prise en charge.

*   Les signatures IDPS **DOIVENT** être conservées à jour au cours de la dernière journée.

*   IDPS **DOIT** être configuré pour l’inspection TLS.

*   IDPS **DOIT** être configuré pour TOUT le trafic entrant et sortant.

*   IDPS **DOIT** être configuré pour les alertes.

**Journalisation des événements**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus de journalisation des événements de sécurité, vous devez :

* Démontrer que les systèmes publics se connectent à une solution de journalisation centralisée qui n’est pas dans la DMZ.

* Montrez comment une valeur minimale de 30 jours de données de journalisation est immédiatement disponible, avec 90 jours conservés.

**Révision (données de journalisation)**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement certains éléments de cette catégorie, vous devez :

*   Montrez comment les examens quotidiens des journaux sont effectués et comment les exceptions et les anomalies sont identifiées, en montrant comment elles sont gérées.

**Alerte**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement certains éléments de cette catégorie, vous devez :

* Montrez comment les événements de sécurité sont configurés pour déclencher des alertes pour le triage immédiat.

* Montrez comment le personnel est disponible 24h/24 et 7 j/7 pour répondre aux alertes de sécurité.

**Gestion des risques**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des processus d’évaluation des risques, vous devez :

* Démontrer qu’un processus formel de gestion des risques est établi.

**Réponse aux incidents**

Étant donné que les audits ISO 27001 n’évaluent pas spécifiquement certains éléments des stratégies et processus de réponse aux incidents, vous devez :

*   Démontrez que le plan/la procédure de réponse aux incidents comprend :

&#x2713; procédures de réponse spécifiques pour les modèles de menace attendus.

&#x2713; fonctionnalités de gestion des incidents alignées sur NIST Cybersecurity Framework (Identifier, Protéger, Détecter, Répondre, Récupérer).
 
&#x2713; L’IRP couvre les systèmes dans l’étendue.
 
&#x2713; formation annuelle pour l’équipe chargée de la réponse aux incidents.

## <a name="appendix-d"></a>Annexe D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Collecte de preuves – Deltas pour PCI DSS

Si vous avez déjà atteint la conformité PCI DSS, les deltas suivants (lacunes) qui ne sont pas entièrement couverts par PCI DSS devront, au minimum, être examinés dans le cadre de cette certification Microsoft 365.

> [!NOTE]
> Dans le cadre de l’évaluation de la certification Microsoft 365, l’analyste de certification détermine si l’un des contrôles DSS PCI mappés n’a pas été inclus dans le cadre de l’évaluation PCI DSS et peut également décider d’échantillonner les contrôles qui ont été trouvés inclus pour fournir une assurance supplémentaire. Toutes les exigences manquantes dans le DSS PCI doivent être incluses dans les activités d’évaluation de la certification Microsoft 365.

**Protection contre les programmes malveillants - Contrôle d’application**

Si la protection contre les programmes malveillants est en place par le biais de l’utilisation de l’antivirus et qu’elle est attestée dans le rapport PCI DSS, aucune investigation supplémentaire n’est nécessaire. Si aucun antivirus n’est en place, les analystes de certification devront identifier et évaluer les preuves des mécanismes de contrôle d’application pour empêcher la détonation de programmes malveillants dans l’environnement. Pour ce faire, vous devez : 

*   Montrez comment l’approbation de l’application est effectuée et vérifiez que cette opération est terminée.

*   Démontrer qu’il existe une liste complète des applications approuvées avec justification métier.

*   Fournissez ou illustrez la documentation de prise en charge qui explique en détail comment le logiciel de contrôle d’application est configuré pour répondre à des mécanismes de contrôle d’application spécifiques (par exemple, autoriser la liste, signer du code, etc.).

*   Démontrez que sur tous les composants système échantillonné, le contrôle d’application est configuré comme documenté.

**Gestion des correctifs – Classement des risques**

Étant donné que les audits PCI DSS n’évaluent pas spécifiquement cette catégorie, vous devez :

* Montrez comment le classement des risques des vulnérabilités est effectué.

**Analyse des vulnérabilités**

Étant donné que les audits PCI DSS n’évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrez que la correction est effectuée conformément à la stratégie de correction des vulnérabilités documentée.

**Pare-feu : pare-feu (ou technologies équivalentes)**

Étant donné que les audits PCI DSS n’évaluent pas spécifiquement cette catégorie, vous devez :

* Démontrez que les pare-feu prennent en charge uniquement le chiffrement fort sur toutes les interfaces d’administration non console.

* Démontrer que les interfaces d’administration non console du pare-feu exposées à l’authentification multifacteur de prise en charge d’Internet.

Un crédit supplémentaire sera fourni si un Web Application Firewall (WAF) est déployé pour vous aider à vous protéger contre la multitude de menaces et de vulnérabilités d’application web auxquelles l’application peut être exposée. Lorsqu’un pare-feu d’applications web (WAF) ou similaire est présent, vous devez :

* Montrez que le pare-feu d’applications web est configuré en mode de défense actif ou surveillez davantage avec les alertes.

* Montrez que le pare-feu d’applications web est configuré pour prendre en charge le déchargement SSL.

* Est configuré conformément à l’ensemble de règles OWASP Core (3.0 ou 3.1) pour se protéger contre la plupart des types d’attaque suivants :

&#x2713; problèmes de protocole et d’encodage.

&#x2713; l’injection d’en-tête, la contrebande de demandes et le fractionnement des réponses.

&#x2713; attaques par parcours de fichiers et de chemins d’accès.

&#x2713; attaques RFI (Remote File Inclusion).

&#x2713; attaques d’exécution de code à distance.

&#x2713; attaques par injection PHP.

&#x2713; attaques de script intersites.

&#x2713; SQL attaques par injection.

&#x2713; attaques de fixation de session.

**Modifier le contrôle**

Étant donné que les audits PCI DSS n’évaluent pas spécifiquement certains éléments des processus de demande de modification, vous devez :

* Démontrer que les demandes de modification sont déclenchées avant d’être effectuées dans des environnements de production.

* Démontrer que les modifications sont autorisées avant de passer en production.

* Démontrer que les tests de fonctionnalités sont effectués une fois les modifications terminées.

* Démontrez que les demandes de modification sont désactivées une fois les tests de fonctionnalités effectués.

**Développement/déploiement de logiciels sécurisés**

Étant donné que les audits PCI DSS n’accèdent pas spécifiquement à certains éléments des processus de développement et de déploiement de logiciels sécurisés ; cela vous sera nécessaire :

* Les référentiels de code DOIVENT être sécurisés par l’authentification multifacteur.

*   Des contrôles d’accès adéquats DOIVENT être en place pour protéger les référentiels de code contre les modifications de code malveillantes.

**Gestion des comptes**

Étant donné que les audits PCI DSS n’évaluent pas spécifiquement certains éléments des processus de gestion des comptes, vous devez :

* Montrez comment les mécanismes d’autorisation sont implémentés pour atténuer les attaques par relecture (par exemple, MFA, Kerberos).

* Des stratégies de mot de passe forts ou d’autres atténuations appropriées doivent être configurées pour protéger les informations d’identification de l’utilisateur. La stratégie de mot de passe minimale suivante doit être utilisée comme indication : 

&#x2713; longueur minimale du mot de passe de 8 caractères.

&#x2713; seuil de verrouillage de compte de 10 tentatives au plus.

&#x2713; l’historique des mots de passe d’au moins cinq mots de passe.

&#x2713; l’application de l’utilisation de mots de passe forts.

* Démontrer que le chiffrement fort est configuré sur toutes les solutions d’accès à distance.

* Lorsque la gestion du DNS public se trouve en dehors de l’environnement dans l’étendue, tous les comptes d’utilisateurs capables d’apporter des modifications DNS DOIVENT être configurés pour utiliser l’authentification multifacteur.

**Détection et prévention des intrusions (FACULTATIF)**

Étant donné que les audits PCI DSS n’évaluent pas spécifiquement certains éléments des processus IDPS (Intrusion Detection and Prevention Services), vous devez :

* IDPS DOIT être configuré pour l’inspection TLS.

*   IDPS DOIT être configuré pour TOUT le trafic entrant et sortant.

**Gestion des risques**

Étant donné que les audits PCI DSS n’évaluent pas spécifiquement certains éléments des processus d’évaluation des risques, vous devez :

* Démontrer que l’évaluation des risques comprend des matrices d’impact et de probabilité.

**Réponse aux incidents**

Étant donné que les audits PCI DSS n’évaluent pas spécifiquement certains éléments des processus et des stratégies de réponse aux incidents, le développeur devra :

* Démontrer que les fonctionnalités de gestion des incidents s’alignent sur NIST Cybersecurity Framework (Identifier, Protéger, Détecter, Répondre, Récupérer).

## <a name="appendix-e"></a>Annexe E

### <a name="evidence-collection---deltas-for-soc-2"></a>Collecte de preuves - Deltas pour SOC 2

Si vous avez déjà atteint la conformité SOC 2, les deltas suivants (lacunes) qui ne sont pas entièrement couverts par SOC 2 devront être examinés dans le cadre de cette certification Microsoft 365.

> [!NOTE]
> Dans le cadre de l’évaluation de la certification Microsoft 365, l’analyste de certification détermine si l’un des contrôles SOC 2 mappés n’a pas été inclus dans le cadre de votre évaluation SOC 2 et peut également décider d’échantillonner les contrôles qui ont été trouvés inclus pour fournir une assurance supplémentaire. Toutes les exigences manquantes dans votre évaluation SOC 2 doivent être incluses dans le cadre des activités d’évaluation de la certification Microsoft 365.

**Protection contre les programmes malveillants - Contrôle d’application**

Si la protection contre les programmes malveillants est en place par le biais de l’utilisation de l’antivirus et est attestée dans votre rapport SOC 2, aucune investigation supplémentaire n’est nécessaire. Si aucun antivirus n’est en place, les analystes de certification devront identifier et évaluer les preuves des mécanismes de contrôle d’application pour empêcher la détonation de programmes malveillants dans l’environnement. Pour ce faire, vous devez :

* Fournissez ou illustrez la documentation de prise en charge qui explique en détail comment le logiciel de contrôle d’application est configuré pour répondre à des mécanismes de contrôle d’application spécifiques (par exemple, autoriser la liste, signer du code, etc.).

* Montrez comment l’approbation de l’application est effectuée et vérifiez que cette opération est terminée.

*   Démontrer qu’il existe une liste complète des applications approuvées avec justification métier.

*   Démontrez que sur tous les composants système échantillonné, le contrôle d’application est configuré comme documenté.

**Gestion des correctifs : mise à jour corrective**

Étant donné que les audits SOC 2 n’évaluent pas spécifiquement cette catégorie, vous devez :

*   Tout problème faible, moyen, élevé ou critique doit être corrigé dans les fenêtres d’activité de mise à jour corrective normale.

*   Les composants logiciels et les systèmes d’exploitation ne sont plus pris en charge par le fournisseur ne doivent pas être utilisés dans l’environnement. Les stratégies de prise en charge DOIVENT être en place pour garantir que les composants logiciels/systèmes d’exploitation non pris en charge seront supprimés de l’environnement et un processus permettant d’identifier le moment où les composants logiciels passent en fin de vie doit être en place.

**Pare-feu – Pare-feu**

Étant donné que les audits SOC 2 n’évaluent pas spécifiquement les contrôles de modification dans les listes de contrôle d’accès au pare-feu, vous devez :

* Démontrer que tout le trafic autorisé via le ou les pare-feu passe par un processus d’autorisation qui aboutifie à la documentation de tout le trafic avec une justification métier.

* Démontrer que les examens des règles de pare-feu sont effectués au moins tous les six mois.

Un crédit supplémentaire sera fourni si un Web Application Firewall (WAF) ou similaire est déployé pour vous aider à vous protéger contre la multitude de menaces et de vulnérabilités d’application web auxquelles l’application peut être exposée. Lorsqu’un pare-feu d’applications web (WAF) ou similaire est présent, vous devez :

* Montrez que le pare-feu d’applications web est configuré en mode de défense actif ou surveillez davantage avec les alertes.

* Montrez que le pare-feu d’applications web est configuré pour prendre en charge le déchargement SSL.

* Est configuré conformément à l’ensemble de règles OWASP Core ((3.0 ou 3.1) pour se protéger contre la majorité des types d’attaque suivants :

&emsp;&#x2713; problèmes de protocole et d’encodage.

&emsp;&#x2713; l’injection d’en-tête, la contrebande de demandes et le fractionnement des réponses.

&emsp;&#x2713; attaques par parcours de fichiers et de chemins d’accès.

&emsp;&#x2713; attaques RFI (Remote File Inclusion).

&emsp;&#x2713; attaques d’exécution de code à distance.

&emsp;&#x2713; attaques par injection PHP.

&emsp;&#x2713; attaques de script intersites.

&emsp;&#x2713; SQL attaques par injection.

&emsp;&#x2713; attaques de fixation de session.

**Modifier le contrôle**

Étant donné que les audits SOC 2 n’évaluent pas spécifiquement certains éléments des processus de demande de modification, le développeur doit :

* Montrez comment les environnements de développement/test sont distincts de l’environnement de production qui applique la séparation des tâches.

* Montrez comment les données dynamiques ne sont pas utilisées dans les environnements de développement/test.

* Démontrer que les tests de fonctionnalités sont effectués une fois les modifications terminées.

* Démontrez que les demandes de modification sont désactivées une fois les tests de fonctionnalités effectués.

**Développement/déploiement de logiciels sécurisés**

Étant donné que les audits SOC 2 n’accèdent pas spécifiquement à certains éléments des processus de développement et de déploiement de logiciels sécurisés ; cela vous sera nécessaire :

*   Vous DEVEZ disposer d’un processus de développement logiciel établi et documenté couvrant l’ensemble du cycle de vie du développement de logiciels.

*   Les développeurs DOIVENT suivre une formation de codage logiciel sécurisée au moins une fois par an.

*   Les référentiels de code DOIVENT être sécurisés par l’authentification multifacteur.

*   Des contrôles d’accès adéquats DOIVENT être en place pour protéger les référentiels de code contre les modifications de code malveillantes.

**Gestion des comptes**

Étant donné que les audits SOC2 n’évaluent pas spécifiquement certains éléments des processus de gestion de compte, vous devez :

*   Montrez comment les mécanismes d’autorisation sont implémentés pour atténuer les attaques par relecture (par exemple, MFA, Kerberos).

*   Montrez comment les comptes qui n’ont pas été utilisés depuis 3 mois sont désactivés ou supprimés.

*   Des stratégies de mot de passe forts ou d’autres atténuations appropriées doivent être configurées pour protéger les informations d’identification de l’utilisateur. La stratégie de mot de passe minimale suivante doit être utilisée comme indication :

&emsp;&#x2713; longueur minimale du mot de passe de 8 caractères.

&emsp;&#x2713; seuil de verrouillage de compte de 10 tentatives au plus.

&emsp;&#x2713; l’historique des mots de passe d’au moins 5 mots de passe.

&emsp;&#x2713; l’application de l’utilisation de mots de passe forts

*   Démontrer que des comptes d’utilisateur uniques sont émis pour tous les utilisateurs.

*   Lorsque la gestion du DNS public se trouve en dehors de l’environnement dans l’étendue, tous les comptes d’utilisateurs capables d’apporter des modifications DNS DOIVENT être configurés pour utiliser l’authentification multifacteur.

**Détection et prévention des intrusions (FACULTATIF).**

Étant donné que les audits SOC 2 n’évaluent pas spécifiquement certains éléments des processus IDPS (Intrusion Detection and Prevention Services), vous devez :

*   Les signatures IDPS DOIVENT être conservées à jour, au cours de la dernière journée

*   IDPS DOIT être configuré pour l’inspection TLS

*   IDPS DOIT être configuré pour TOUT le trafic entrant et sortant

**Journalisation des événements**

Étant donné que les audits SOC 2 n’évaluent pas spécifiquement certains éléments des processus de journalisation des événements de sécurité, vous devez :

* Montrez comment, sur tous les composants système de l’exemple de jeu, le système suivant est configuré pour journaliser les événements suivants

&emsp;&#x2713; l’accès utilisateur aux composants système et aux applications.

&emsp;&#x2713; Toutes les actions effectuées par un utilisateur à privilèges élevés.

&emsp;&#x2713; tentatives d’accès logique non valides.

Démontrer que les événements journalisés contiennent ; au minimum, les informations suivantes :

&emsp; utilisateur&#x2713;.

&emsp;&#x2713; type d’événement.

&emsp;&#x2713; date et heure.

&emsp;&#x2713; indicateur de réussite/d’échec.

&emsp;&#x2713; Étiquette pour identifier le système concerné.

*   Démontrer que tous les composants système de l’exemple de jeu sont configurés pour utiliser la synchronisation de l’heure et qu’ils sont identiques aux serveurs de temps principal/secondaire.

* Démontrer que les systèmes publics se connectent à une solution de journalisation centralisée qui n’est pas dans la DMZ.

*   Démontrer que les systèmes publics se connectent à une solution de journalisation centralisée qui n’est pas dans la DMZ.

* Montrez comment la solution de journalisation centralisée est protégée contre toute falsification non autorisée des données de journalisation.

* Montrez comment une valeur minimale de 30 jours de données de journalisation est immédiatement disponible, avec 90 jours ou plus conservés.

**Gestion des risques**

Étant donné que les audits SOC2 n’évaluent pas spécifiquement certains éléments des processus d’évaluation des risques, vous devez :

* Démontrer qu’une évaluation formelle des risques est effectuée au moins une fois par an.

*Réponse aux incidents.*

Étant donné que les audits SOC2 n’évaluent pas spécifiquement certains éléments des stratégies et processus de réponse aux incidents, vous devez :

* Démontrez que le plan/la procédure de réponse aux incidents comprend :

&emsp;&#x2713; procédures de réponse spécifiques pour les modèles de menace attendus.

&emsp;&#x2713; processus de communication documenté pour assurer la notification en temps opportun des principales parties prenantes (marques de paiement/acheteurs, organismes de réglementation, autorités de contrôle, administrateurs, clients, etc.).

## <a name="appendix-f"></a>Annexe F

### <a name="hosting-deployment-types"></a>Types de déploiement d’hébergement

Microsoft reconnaît que vous allez déployer des applications et stocker du code d’application/complément dans différents environnements d’hébergement. Les responsabilités globales de certains contrôles de sécurité au sein de la certification Microsoft 365 dépendent de l’environnement d’hébergement utilisé. L’annexe F examine les types de déploiement courants et les mappe aux contrôles de sécurité qui sont évalués dans le cadre du processus d’évaluation. Les types de déploiement d’hébergement suivants ont été identifiés :

|Types d’hébergement  |Description  |
|-----|------|
|**ISV hébergé**|Les types hébergés par un éditeur de logiciels indépendants peuvent être définis comme l’emplacement où vous êtes responsable de l’infrastructure utilisée pour prendre en charge l’environnement d’application/complément. Cela peut se trouver physiquement dans vos propres centres de données ou centres de données tiers avec un service de colocalisation. En fin de compte, vous disposez d’un contrôle administratif et d’une propriété totale sur l’infrastructure de prise en charge et l’environnement d’exploitation.|
|**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/overview/what-is-iaas/)|Infrastructure as a Service est un service fourni par lequel l’infrastructure de prise en charge physique est gérée et gérée en leur nom par le fournisseur de services cloud (CSP). En règle générale, la mise en réseau, le stockage, les serveurs physiques et l’infrastructure de virtualisation relèvent de la responsabilité du fournisseur de solutions Cloud. Le système d’exploitation, le middleware, le runtime, les données et les applications sont les responsabilités de vous. Les fonctionnalités de pare-feu seraient également gérées et gérées par le tiers, mais la maintenance de la base de règles de pare-feu serait généralement toujours la responsabilité des consommateurs.|
|**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/overview/what-is-paas/)| Avec Platform as a Service, vous êtes approvisionné avec une plateforme managée présentant un service qui peut être consommé. Vous n’avez pas besoin d’effectuer des fonctions sysadmin, car le système d’exploitation et l’infrastructure de prise en charge sont gérés par le fournisseur de solutions Cloud. Cela est généralement utilisé lorsque les organisations ne souhaitent pas être concernées par la présentation d’un service web et peuvent plutôt se concentrer sur la création du code source de l’application web et la publication de l’application web sur les services web gérés par le cloud.  Un autre exemple peut être un service de base de données où la connectivité est donnée à une base de données, mais l’infrastructure et l’application de base de données prises en charge sont abstraites du consommateur.   **Remarque : Serverless et PaaS sont similaires, de sorte que pour les besoins du type de déploiement Serverless et PasS de l’hébergement de certification Microsoft 365 sont considérés comme les mêmes**|
|**Hébergé hybride**|Avec le type hébergé hybride, vous pouvez utiliser plusieurs types hébergés pour prendre en charge différentes parties de l’environnement de prise en charge. Cela peut être plus le cas lorsque les applications/compléments sont utilisés sur plusieurs piles M365. Bien que la certification Microsoft 365 prenne en charge l’emplacement où les applications/modules complémentaires sur plusieurs services M365 sont développés, une évaluation de l’ensemble de l’environnement de prise en charge (entre applications/compléments) doit être évaluée conformément à chacun des « mappages de types hébergés » applicables. Parfois, vous pouvez utiliser différents types hébergés pour un seul complément, où cela est effectué, l’applicabilité des critères devra toujours suivre les critères « Mappages de types hébergés » entre les différents types hébergés.|
|**Hébergement partagé**|L’hébergement partagé est l’endroit où vous hébergez l’environnement au sein d’une plateforme partagée par plusieurs consommateurs individuels. La spécification de certification Microsoft 365 n’a pas été écrite pour en tenir compte en raison de l’adoption du cloud, l’hébergement partagé n’est pas courant. Si vous pensez qu’il est utilisé, contactez Microsoft car des exigences supplémentaires devront être créées pour prendre en compte les risques supplémentaires liés à ce type d’hébergement.|


## <a name="appendix-g"></a>Annexe G

## <a name="learn-more"></a>En savoir plus

[Vue d’ensemble du programme de conformité des applications Microsoft 365](~/overview.md)  
[Qu’est-ce que Microsoft 365 App Publisher Attestation ?](~/docs/attestation.md)  
[Qu’est-ce que la certification Microsoft 365 ?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossaire

### <a name="aia"></a>AIA

*Accès aux informations d’autorité est un descripteur d’emplacement de service utilisé pour rechercher le certificat de l’autorité de certification émettrice.

### <a name="crl"></a>LCR

*La liste de révocation de certificats fournit un moyen pour un point de terminaison SSL (Secure Sockets Layer) de vérifier qu’un certificat reçu d’un hôte distant est valide et digne de confiance.

### <a name="cvss-score"></a>Score CVSS

*Common Vulnerability Scoring System est une norme publiée qui mesure la vulnérabilité et calcule un score numérique en fonction de sa gravité.

### <a name="cvss-patch-management-guidelines"></a>Instructions de gestion des correctifs CVSS

* Critique (9.0 - 10.0)
* High (7.0 - 8.9)
* Moyen (4.0 - 6.9)
* Faible (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*La zone démilitarisée est un réseau intermédiaire physique ou logique qui interagit directement avec des réseaux externes ou non propriétaires tout en conservant le réseau privé interne de l’hôte séparé et isolé.

### <a name="euii"></a>EUII

*Informations d’identification de l’utilisateur final*.

### <a name="gdpr"></a>RGPD

*Le règlement général sur la protection des données est un règlement de l’Union européenne (UE) sur la confidentialité et la protection des données pour toutes les données des citoyens de l’UE, quel que soit l’emplacement de votre site d’application.

### <a name="hsts"></a>HSTS

*HTTP Strict Transport Security utilise un en-tête de réponse HTTP indiquant au navigateur web d’accéder uniquement au contenu via HTTPS.  Il est conçu pour vous protéger contre les attaques de rétrogradation et le détournement de cookies.

### <a name="iec"></a>CEI

*Commission électrotechnique internationale.

### <a name="isms"></a>DOCTRINES

*Système de gestion de la sécurité des informations.

### <a name="isv"></a>ISV

Les fournisseurs de sécurité indépendants sont des individus et des organisations qui développent, mettent en marché et vendent des logiciels qui s’exécutent sur des plateformes logicielles et matérielles tierces.

### <a name="iso-27001"></a>ISO 27001

Infrastructure de spécification du système de gestion de la sécurité des informations pour tous les contrôles techniques dans les processus et stratégies de gestion des risques d’une organisation.

### <a name="lfi"></a>LFI

*L’inclusion de fichiers local* permet à un attaquant d’inclure des fichiers sur un serveur via le navigateur web.

### <a name="nist"></a>NIST

Le *National Institute of Standards* (NIST), un organisme non réglementaire du département du Commerce des États-Unis, fournit des conseils aux organisations du secteur privé aux États-Unis afin d’évaluer et d’approuver leur capacité à prévenir, détecter et répondre aux cyberattaques.

### <a name="non-significant-changes"></a>Modifications non significatives

* Correctifs de bogues mineurs.
* Améliorations mineures des performances.
* Correctifs d’application de système d’exploitation/bibliothèques/client et serveur.

### <a name="ocsp"></a>OCSP

*Le protocole d’état des certificats en ligne* est utilisé pour vérifier l’état de révocation des certificats numériques X.509.

### <a name="oii"></a>OII

*Informations d’identification de l’organisation*.

### <a name="owasp"></a>OWASP

*Ouvrez le Project de sécurité des applications web*.

### <a name="pci-dss"></a>PCI DSS

*Payment Card Industry Data Security Standard*, une organisation qui maintient des normes pour la sécurité des données des titulaires de carte dans le monde entier.

### <a name="pen-testing"></a>Test de stylet

*Le test d’intrusion* est une méthode de test d’une application web en simulant des attaques malveillantes pour rechercher les vulnérabilités de sécurité qu’un attaquant peut exploiter.

### <a name="saml"></a>SAML

*Le langage de balisage d’assertion de sécurité* est une norme ouverte pour l’échange de données d’authentification et d’autorisation entre l’utilisateur, le fournisseur d’identité et le fournisseur de services.

### <a name="sensitive-data"></a>Données sensibles

* Données de contrôle d’accès.
* Contenu du client.
* Informations d’identité de l’utilisateur final.
* Données de prise en charge.
* Données personnelles publiques.
* Informations pseudonymes de l’utilisateur final.

### <a name="significant-changes"></a>Changements significatifs

* Réaffectation de l’environnement d’hébergement.
* Mises à niveau majeures de l’infrastructure de prise en charge ; par exemple, l’implémentation d’un nouveau pare-feu, les mises à niveau majeures vers les services frontaux, etc.
* Ajout de fonctionnalités et /ou d’extensions à votre application.
* Mises à jour de votre application qui capturent des données sensibles supplémentaires.
* Modifications apportées aux flux de données ou aux modèles d’autorisation de votre application
* Ajout de points de terminaison d’API ou de fonctions de point de terminaison d’API.

### <a name="soc-2"></a>SOC 2

*Service Organization Control 2*, une procédure d’audit technique composée de cinq principes de service d’approbation pour s’assurer que les fournisseurs de services gèrent en toute sécurité les données et la confidentialité des clients d’une organisation.

### <a name="ssl"></a>SSL

*Couche De sockets sécurisés*.

### <a name="tls"></a>TLS

*Sécurité de la couche de transport*.
