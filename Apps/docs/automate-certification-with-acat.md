---
title: Automatiser la certification Microsoft 365 avec l’outil d’automatisation de la conformité des applications pour Microsoft 365
description: Utilisation de l’outil d’automatisation de la conformité des applications pour Microsoft 365 (ACAT) pour automatiser la certification Microsoft 365.
author: yjin81
ms.author: yajin1
manager: zhshang
ms.service: certification
ms.topic: how-to
ms.date: 04/13/2022
ms.custom: template-how-to
ms.openlocfilehash: c81ccf3626d6039333f52a487e98233364f7174e
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433434"
---
# <a name="automate-microsoft-365-certification-with-app-compliance-automation-tool-for-microsoft-365"></a>Automatiser la certification Microsoft 365 avec l’outil d’automatisation de la conformité des applications pour Microsoft 365

L’Outil d’automatisation de la conformité des applications pour Microsoft 365 (ACAT) collabore avec le programme de conformité des applications Microsoft 365 pour répondre à certains des contrôles requis pour la certification Microsoft 365. Cet article vous aidera à bien démarrer avec ACAT et à utiliser les évaluations de conformité avec la certification Microsoft 365.

> [!IMPORTANT]
> ACAT est actuellement en préversion privée. Si vous souhaitez participer au programme de préversion privée, inscrivez-vous [ici](https://aka.ms/acat/private/signup).

## <a name="create-your-first-compliance-report-to-onboard-acat"></a>Créer votre premier rapport de conformité pour intégrer ACAT

ACAT vous permet de vous concentrer sur la conformité de votre application ou d’un environnement spécifique d’une application (par exemple, production, préproduction, etc.). Il vous permet de créer un **rapport de conformité** dans lequel vous pouvez définir la limite de conformité en fonction de l’infrastructure cloud de votre application ou de l’environnement spécifique d’une application.

> [!IMPORTANT]
> Étant donné qu’ACAT est en préversion privée, vous ne pouvez pas la *https://portal.azure.com* rechercher directement. Utilisez les options ci-dessous pour lancer ACAT.

- Recherchez et lancez ***l’outil d’automatisation de la conformité des applications pour Microsoft 365*** dans [Portail Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D&microsoft_azure_marketplace_ItemHideKey=Microsoft_Azure_AppComplianceAutomationHidden), ou lancez [directement avec le lien profond d’ACAT](https://portal.azure.com/#blade/Microsoft_Azure_AppComplianceAutomation/AcatMenuBlade/overview).
- Accédez à ***Rapports*** à partir de la gauche.

:::image type="complex" source="../media/ACAT/getstarted-create-report-inline.png" lightbox="../media/ACAT/getstarted-create-report.png" alt-text="Créer un rapport de conformité":::
   Accédez à Rapports pour créer un rapport de conformité :::image-end:::

- Sélectionnez ***Créer un rapport*** pour commencer à créer votre premier rapport de conformité avec une configuration appropriée. 
    - **Concepts de base**
        - **Nom du rapport** : le nom du rapport de conformité est requis et ne peut pas être dupliqué dans le locataire. Il peut s’agir de la combinaison de nombres, d’alphabets et de traits de soulignement. Il est recommandé d’utiliser un nom explicite avec le rapport de conformité, par exemple, indiquant l’application ou l’environnement spécifique.
        - **Temps** de déclenchement : ACAT génère quotidiennement les évaluations de conformité pour le rapport de conformité. Cette configuration est utilisée pour spécifier quand la génération doit être déclenchée. 
        - **Sélectionner un abonnement** : en préversion privée, ACAT vous permet de définir l’étendue du rapport de conformité en choisissant les ressources Azure dans un abonnement spécifique. Vous pouvez choisir l’abonnement approprié en fonction de votre infrastructure cloud. Si l’abonnement de votre application ne figure pas dans la liste, vous devez demander l’autorisation à votre administrateur. 
        - **Sélectionner des ressources** : une fois l’abonnement spécifié, sélectionnez les ressources appropriées en fonction de votre infrastructure cloud. Par défaut, toutes les ressources sont sélectionnées automatiquement. Vous pouvez également rechercher les ressources par filtres (par exemple, groupe de ressources, balise, etc.), puis sélectionner les ressources. 
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-basic-inline.png" lightbox="../media/ACAT/getstarted-report-config-basic.png" alt-text="Configuration de base":::
       Configuration de base pour le rapport de conformité :::image-end:::

    - **certification Microsoft 365** : la configuration de la certification Microsoft 365 est facultative lors de la création.  Elle peut être configurée ultérieurement une fois que vous aurez commencé à publier votre application.
        - **GUID de** l’offre : le GUID de l’offre est l’identificateur unique de l’offre de la Place de marché dans [Microsoft Partner Network](https://partner.microsoft.com/dashboard). Sélectionnez *En savoir plus* pour obtenir une instruction pas à pas sur l’obtention de l’identificateur unique.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-m365-inline.png" lightbox="../media/ACAT/getstarted-report-config-m365.png" alt-text="configuration de la certification Microsoft 365":::
       Configuration de la certification Microsoft 365:::image-end:::

Une fois que vous avez confirmé la configuration et créé le rapport de conformité, ACAT collecte automatiquement les données liées à la conformité à partir des sources ci-dessous. 

- Activez le [Microsoft Defender pour le cloud](https://azure.microsoft.com/services/defender-for-cloud/) (niveau gratuit) pour votre abonnement. 
- Activez certaines stratégies personnalisées pour votre abonnement. 

> [!NOTE]
> Si la création réussit, ACAT commence à collecter et à générer les évaluations de conformité pour votre rapport de conformité à compter du lendemain. 

## <a name="audit-the-compliance-assessments-with-your-compliance-report"></a>Auditer les évaluations de conformité avec votre rapport de conformité

Avec ACAT, vous pouvez découvrir l’état d’exécution du rapport de conformité et auditer facilement les évaluations de conformité. 

- Accédez à ***Rapports*** à partir de la gauche. Vous pouvez obtenir un bref résumé des rapports de conformité existants.
    - **État de l’exécution** : l’état d’exécution indique si ACAT gère toujours correctement le rapport de conformité dans la dernière génération. Il existe trois états pour l’état d’exécution. 
        - **Actif** : le rapport de conformité s’exécute en continu et avec succès. 
        - **Échec** : L’ACAT n’a pas pu générer les évaluations de conformité pour ce rapport de conformité pour la dernière génération. Cet état peut se produire pour plusieurs raisons, par exemple, il existe une configuration incorrecte dans votre abonnement pour bloquer les données de conformité routées vers ACAT, une défaillance ou une panne du système s’est produite avec ACAT, etc. 
        - **Désactivé** : ce rapport de conformité est désactivé (suspendu) manuellement. Cette fonctionnalité n’est pas activée en préversion privée. 
    - **Heure du dernier déclencheur** et **heure de déclenchement suivante** : ACAT génère quotidiennement les évaluations de conformité pour le rapport de conformité. *L’heure du dernier déclencheur* indique le moment où la dernière génération s’est déclenchée, et *l’heure du déclencheur Suivant* indique l’heure du déclencheur pour la génération à venir. 
    - **Microsoft 365 certification** : comprendre l’état de votre rapport de conformité pour Microsoft 365 contrôles de certification. Les trois états pour l’état de conformité de la certification Microsoft 365 sont les suivants :
        - **Passé** : Il n’y a aucun échec pour les contrôles de certification Microsoft 365 entièrement automatisés.
        - **Échec** : des responsabilités client ayant échoué sont détectées pour les contrôles de certification de Microsoft 365 entièrement automatisés.
        - **Manuel** : cet état inclut deux types de contrôles : le *contrôle manuel automatisé partiel* , partiellement automatisé par l’ACAT et nécessitant toujours un effort manuel pour collecter des preuves de conformité, et le *contrôle manuel* qui nécessite un effort manuel complet pour collecter des preuves de conformité. ACAT automatise certaines parties des responsabilités des clients pour le contrôle partiellement automatisé. Vous pouvez utiliser l’état de conformité de celui-ci pour référence, mais ne pouvez pas l’utiliser directement pour Microsoft 365 audit de certification.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-list-inline.png" lightbox="../media/ACAT/getstarted-report-list.png" alt-text="Liste des rapports de conformité":::
       Liste des rapports de conformité existants.
    :::image-end:::

En plus d’apprendre le résumé général des rapports de conformité existants, vous pouvez également auditer les détails de l’évaluation de la conformité auprès de votre équipe dans ACAT. Obtenez les détails de l’évaluation de la conformité pour le rapport de conformité spécifique en cliquant sur le nom du rapport. ACAT affiche les détails ci-dessous.

- **Paramètres** : Vous pouvez modifier la configuration du rapport de conformité avec *Paramètres*. En préversion privée, vous pouvez modifier la configuration liée à la certification Microsoft 365. 
- **Télécharger le rapport** : ACAT vous permet de télécharger les évaluations du rapport de conformité sous forme de fichiers csv dans un format qui peut être partagé avec des partenaires pour la collaboration.
    - **Inventaire de l’infrastructure cloud** : ce fichier contient les détails des ressources de ce rapport de conformité. Il peut être utilisé pour décrire l’inventaire cloud de votre application. 
    - **Microsoft 365 l’évaluation de la conformité de certification** : ce fichier inclut les évaluations de conformité de votre rapport de conformité à partir de la vue de Microsoft 365 contrôle de certification. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-toolbar-inline.png" lightbox="../media/ACAT/getstarted-report-detail-toolbar.png" alt-text="Barre d’outils rapport de conformité":::
    Barre d’outils pour le rapport de conformité.
:::image-end:::

- **Éléments essentiels** : cette section indique l’état et la configuration du rapport de conformité. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-essential-inline.png" lightbox="../media/ACAT/getstarted-report-detail-essential.png" alt-text="Éléments essentiels du rapport de conformité":::
    Éléments essentiels du rapport de conformité.
:::image-end:::

- **Résultats de l’évaluation**
    - L’état de conformité du contrôle de certification Microsoft 365 est classé en cinq catégories. 
        - **Passé** : Il n’y a aucun échec pour les contrôles de certification Microsoft 365 entièrement automatisés.
        - **Échec** : des responsabilités client ayant échoué sont détectées pour les contrôles de certification de Microsoft 365 entièrement automatisés.
        - **Passé - Preuve supplémentaire nécessaire** : il n’y a pas d’échecs pour les contrôles de certification Microsoft 365 partiellement automatisés. Vous devez toujours collecter des preuves supplémentaires pour les contrôles manuellement.
        - **Échec - Preuves supplémentaires nécessaires** : des responsabilités client ayant échoué sont détectées pour les contrôles de certification Microsoft 365 partiellement automatisés.
        - **Contrôle manuel** : ACAT n’automatise aucune responsabilité du client pour les contrôles de certification Microsoft 365. 
    - Les évaluations de conformité sont organisées par Microsoft 365 famille et contrôle de contrôle de certification. 
        - Pour en savoir plus sur les détails du contrôle de conformité et sur la collecte des preuves de conformité pour le contrôle manuel, cliquez sur le nom du contrôle. 
        - Lorsque vous développez le contrôle entièrement automatisé et le contrôle partiellement automatisé, vous pouvez en savoir plus sur la conformité de la responsabilité des clients de ce contrôle. 
        - Pour chaque responsabilité du client, vous pouvez également découvrir l’état de conformité des ressources associées et les étapes de correction pour les ressources ayant échoué en cliquant sur le bouton d’action. 
            - **Ressources non saines** : vous devez suivre les étapes de correction pour corriger les ressources non saines. 
            - **Ressources non applicables** : vous devez suivre la raison N/A pour configurer les ressources, puis ACAT peut collecter les évaluations de conformité pour les ressources.

:::image type="complex" source="../media/ACAT/getstarted-report-detail-assessment-inline.png" lightbox="../media/ACAT/getstarted-report-detail-assessment.png" alt-text="Évaluations des rapports de conformité":::
    Évaluations de conformité pour le rapport de conformité.
:::image-end:::

## <a name="use-your-first-compliance-report-with-microsoft-r365-certification-audit"></a>Utiliser votre premier rapport de conformité avec l’audit de certification Microsoft r365

Avant d’utiliser le rapport de conformité avec Microsoft 365 certification, vous devez configurer le GUID de l’offre pour associer le rapport de conformité à votre offre de la Place de marché. Il existe deux options : 

- Pendant le processus de création du rapport de conformité, configurez le GUID de l’offre dans *Microsoft 365 onglet Certification*. 
- Si le rapport de conformité est déjà créé, accédez à la *Paramètres* de ce rapport de conformité pour configurer le GUID de l’offre.

Une fois le GUID de l’offre configuré, accédez à [Microsoft Partner Network](https://partner.microsoft.com/dashboard) pour démarrer la conformité de l’application. La *documentation initiale* est la première phase de la certification Microsoft 365. Dans cette phase, si vous choisissez *Oui* pour déterminer si vous utilisez ACAT, vous pouvez choisir le rapport de conformité approprié pour cet audit. La certification Microsoft 365 soumettra automatiquement les évaluations de conformité des contrôles entièrement automatisés au vérificateur, ce qui vous fera gagner du temps et des efforts. 

## <a name="get-high-level-overview-of-your-compliance-reports"></a>Obtenir une vue d’ensemble générale de vos rapports de conformité 

La ***vue d’ensemble*** vous permet de mieux comprendre l’état de haut niveau de vos rapports de conformité. 

- **État** d’exécution du rapport de conformité : cette vue d’ensemble vous donne la statistique de l’état d’exécution de vos rapports de conformité.
    - **Actif** : le rapport de conformité s’exécute en continu et avec succès. 
    - **Échec** : L’ACAT n’a pas pu générer les évaluations de conformité pour ce rapport de conformité au cours de la dernière génération. Cet état peut se produire pour plusieurs raisons, par exemple, il existe une configuration incorrecte dans votre abonnement pour bloquer les données de conformité routées vers ACAT, une défaillance ou une panne du système s’est produite avec ACAT, etc. 
    - **Désactivé** : ce rapport de conformité est désactivé (suspendu) manuellement. Cette fonctionnalité n’est pas activée en préversion privée. 

:::image type="complex" source="../media/ACAT/getstarted-overview-runtime-inline.png" lightbox="../media/ACAT/getstarted-overview-runtime.png" alt-text="Vue d’ensemble de l’état de l’exécution":::
    Vue d’ensemble de l’état d’exécution du rapport de conformité.
:::image-end:::

- **Rapports de conformité réglementaire actifs** : cette vue d’ensemble vous donne les statistiques des résultats de conformité pour chaque rapport de conformité *actif* .
    - **Passé** : Il n’y a aucun échec pour les contrôles de certification Microsoft 365 entièrement automatisés.
    - **Échec** : des responsabilités client ayant échoué sont détectées pour les contrôles de certification de Microsoft 365 entièrement automatisés.
    - **Manuel** : cet état inclut deux types de contrôles : le *contrôle manuel automatisé partiel* , partiellement automatisé par l’ACAT et nécessitant toujours un effort manuel pour collecter des preuves de conformité, et le *contrôle manuel* qui nécessite un effort manuel complet pour collecter des preuves de conformité. ACAT automatise certaines parties des responsabilités des clients pour le contrôle partiellement automatisé. Vous pouvez utiliser l’état de conformité de celui-ci pour référence, mais ne pouvez pas l’utiliser directement pour Microsoft 365 audit de certification.

:::image type="complex" source="../media/ACAT/getstarted-overview-compliance-inline.png" lightbox="../media/ACAT/getstarted-overview-compliance.png" alt-text="Vue d’ensemble de l’état de conformité":::
    Vue d’ensemble de l’état de conformité pour les rapports de conformité actifs.
:::image-end:::

## <a name="troubleshooting"></a>Résolution des problèmes 

### <a name="why-is-the-compliance-report-created-failed-due-to-authorization-error"></a>Pourquoi le rapport de conformité créé a-t-il échoué en raison d’une erreur d’autorisation ? 

Lors de la création d’un rapport de conformité, ACAT configure l’environnement avec votre abonnement pour collecter automatiquement les données de conformité, et cette action nécessite une autorisation spécifique de l’abonnement. Vous pouvez vérifier l’autorisation de votre abonnement comme ci-dessous. 

- Recherchez et lancez les **abonnements** dans [Portail Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
- Accédez à l’abonnement que vous souhaitez utiliser pour créer le rapport de conformité. 
- Accédez au **contrôle d’accès (IAM)** à gauche. 
- Sélectionnez **Afficher mon accès** pour vérifier votre autorisation.
    - Si votre organisation utilise des [rôles intégrés Azure](/azure/role-based-access-control/built-in-roles), vos attributions de rôles doivent inclure au moins l’un des rôles suivants :
        - [Contributeur de stratégie de ressources](/azure/role-based-access-control/built-in-roles#resource-policy-contributor) et [administrateur de sécurité](/azure/role-based-access-control/built-in-roles#security-admin)
        - Autre attribution de rôle disposant d’autorisations plus élevées (par exemple, [Propriétaire](/azure/role-based-access-control/built-in-roles#owner), etc.)

### <a name="how-to-report-an-acat-issue-or-warning"></a>Comment signaler un problème ou un avertissement ACAT ? 

Lorsque vous rencontrez un problème dans ACAT et que vous souhaitez contacter le [programme de préversion privée ACAT](mailto:acatprivatepreview@microsoft.com) pour obtenir de l’aide, nous avons besoin de votre aide pour collecter les preuves afin de mieux comprendre votre scénario.

- Obtenir les détails de l’erreur ou de l’avertissement ACAT
    - Accédez aux **notifications** en plus de [Portail Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Sélectionner **d’autres événements dans le journal d’activité** 
    
    :::image type="complex" source="../media/ACAT/getstarted-troubleshoot-activitylog.png" alt-text="Notifications ACAT":::
        Accédez au journal d’activité pour vérifier les notifications ACAT.
    :::image-end:::
    
    - Modifiez **l’intervalle de temps** correctement pour filtrer votre erreur ou avertissement ACAT dans le journal d’activité. 
    - Recherchez votre erreur ou avertissement ACAT, sélectionnez pour obtenir les détails et enregistrez les détails sous forme de fichier.
    
- Vérifiez si votre abonnement est correctement configuré par ACAT. 
    - Recherchez et lancez les **abonnements** dans [Portail Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Accédez à l’abonnement que vous souhaitez utiliser pour créer le rapport de conformité. 
    - Sélectionnez **Fournisseur de** ressources pour vérifier si l’état de ces fournisseurs est *inscrit*.
        - Microsoft.Security
        - Microsoft.ResourceGraph
    - Retour pour [Portail Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D) et lancer **Resource Graph Explorer**.
    - Sélectionner **une nouvelle requête**
    - Exécutez cette requête pour vérifier l’attribution de stratégie et télécharger le résultat en tant que CSV. 

    ```kusto
    resourcecontainers
    | where type == "microsoft.resources/subscriptions/resourcegroups"
    | where name contains "acat"
    ```

    - Exécutez cette requête pour vérifier l’automatisation et télécharger le résultat en tant que CSV.

    ```kusto
    resources
    | where type == "microsoft.security/automations"
    | where name contains "acat"
    ```

    - Exécutez cette requête pour vérifier l’évaluation et télécharger le résultat en tant que CSV. Vous devez remplacer l’espace réservé ***your-subscriptionId*** par l’abonnement spécifique que vous souhaitez interroger.

    ```kusto
    SecurityResources
      | where type == 'microsoft.security/assessments'
      | where subscriptionId == "your-subscriptionId"
      | extend metadata=properties.metadata,
      status=properties.status,
      links=properties.links,
      displayName=properties.displayName,
      resourceDetails=properties.resourceDetails,
      description=properties.metadata.description
      | project type, id, name, description, metadata, status, resourceDetails, links, displayName
    ```