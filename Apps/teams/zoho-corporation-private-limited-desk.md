---
title: Informations sur l’application pour Zoho Desk par Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toutes les informations de sécurité et de conformité disponibles pour Zoho Desk, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 6386c25acea352558965af02c99a49cd79baff6b
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65227988"
---
# <a name="zoho-desk"></a>Zoho Desk

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Dernière mise à jour par le développeur : 20 octobre 2021</p>

* [Afficher dans Teams magasin](https://teams.microsoft.com/l/app/091ec948-c0ee-4d56-aa9e-51c3d8316a9c)
* [Afficher dans AppSource](https://appsource.microsoft.com/product/office/WA104382044)

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par Zoho Corporation Private Limited à Microsoft :

| **Information** | **Response** |
|:----------------|:-------------|
| Nom de l'application | Zoho Desk |
| ID | WA104382044 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | Zoho Corporation Private Limited |
| Site web de la société | [https://www.zoho.com](https://www.zoho.com) |
| Conditions d’utilisation de l’application | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |
| Fonctionnalités principales de l’application | Zoho Desk est un logiciel de support technique web qui vous permet de gérer efficacement vos activités de support client. Zoho Desk vous permet d’attribuer, de suivre et de configurer facilement des alertes sur les tickets du support technique. Vous pouvez personnaliser Zoho Desk pour votre entreprise et garantir la satisfaction de votre expérience de support client. |
| Emplacement du siège social de la société | États-Unis d’Amérique |
| Page d’informations sur l’application | [https://www.zoho.com/desk/help/](https://www.zoho.com/desk/help/) |
| Quel est l’environnement d’hébergement ou le modèle de service utilisé pour exécuter votre application ? | IsvHosted |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par Zoho Corporation Private Limited sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

Répertoriez les [autorisations Microsoft Graph](/graph/permissions-reference) requises par cette application.

>| **Permission**  | **Type d’autorisation (Délégué/Application)** | **Les données sont-elles collectées ? Justification de la collecte ?** | **Les données sont-ils stockées ? Justification du stockage ?** | **ID d’application Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.Read | Délégué |  | Lire les fichiers utilisateur. |  |
>| Files.Read.All | Délégué |  | Lire tous les fichiers auxquels l’utilisateur peut accéder. |  |
>| User.Read | Délégué |  | Connectez-vous et lisez le profil utilisateur. |  |
>| User.ReadBasic.All | Délégué |  | Lisez les profils de base de tous les utilisateurs. |  |
>| email | Délégué |  | Affichez l’adresse e-mail de l’utilisateur. |  |
>| offline_access | Délégué |  | Conservez l’accès aux données aux laquelle vous lui avez donné accès. |  |
>| profil | Délégué |  | Affichez le profil de base de l’utilisateur. |  |


#### <a name="non-microsoft-services-used"></a>Non-services Microsoft utilisé

Si l’application transfère ou partage des données d’organisation avec un service non-Microsoft, répertoriez le service non-Microsoft utilisé par l’application, les données transférées et incluez une justification pour laquelle l’application doit transférer ces informations.

>Les non-services Microsoft ne sont pas utilisées.

#### <a name="data-access-via-bots"></a>Accès aux données via des bots

Si cette application contient un bot ou une extension de messagerie, elle peut accéder aux informations d’identification de l’utilisateur final (EUII) : la liste (prénom, nom, nom d’affichage, adresse e-mail) d’un membre de l’équipe d’une équipe ou d’une conversation à laquelle elle est ajoutée. Cette application utilise-t-elle cette fonctionnalité ?

>Aucun EUII n’est accessible.


#### <a name="telemetry-data"></a>Données de télémétrie

Des informations d’identification organisationnelle (OII) ou des informations d’identification de l’utilisateur final (EUII) apparaissent-elles dans les journaux ou les données de télémétrie de cette application ? Si c’est le cas, décrivez quelles données sont stockées et quelles sont les stratégies de rétention et de suppression ?

>Non

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Contrôles organisationnels pour les données stockées par partenaire

Décrire comment les administrateurs de l’organisation peuvent contrôler leurs informations dans les systèmes partenaires ? Par exemple, suppression, rétention, audit, archivage, stratégie de l’utilisateur final, etc.

>1) Il existe une option dans l’interface utilisateur pour supprimer les entités, les administrateurs et les agents à l’intérieur du bureau Zoho qui disposent d’options de suppression peuvent effectuer cette opération. 2) Nous avons également des options d’exportation à l’aide desquelles l’administrateur peut exporter et réaliser à leurs fins.  3) Nous maintenons l’audit sur le serveur principal, à la demande du client ces informations peuvent être fournies.

| **Information** | **Response** |
|:----------------|:-------------|
| L’application ou l’infrastructure sous-jacente traite-t-elle les données relatives à un client Microsoft ou à son appareil ? | Oui |
| Quelles données sont traitées par votre application ? | Données de profil, Webhook conversation personnelle. |
| L’application prend-elle en charge TLS 1.1 ou version ultérieure ? | Oui |
| L’application ou l’infrastructure sous-jacente stocke-t-elle des données client Microsoft ? | Oui |
| Quelles données sont stockées dans vos bases de données ? | ID d’utilisateur, nom d’utilisateur, adresse e-mail |
| Si l’infastructure sous-jacente traite ou stocke les données client Microsoft, où ces données sont-elles stockées géographiquement ? | États-Unis d’Amérique, d’Irlande, des Pays-Bas (the), de Chine, du Japon, d’Inde, d’Australie |
| Disposez-vous d’un processus de location et d’élimination des données établi ? | Oui |
| Combien de temps les données sont-ils conservées après la résiliation du compte ? | Moins de 90 jours |
| Disposez-vous d’un processus de gestion de l’accès aux données établi ? | Oui |
| Transférez-vous des données client ou du contenu client vers des tiers ou des sous-processeurs ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

<iframe height='1020' title='informations de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308" target="_blank">Afficher dans une nouvelle réponse</a>| **** |
|:----------------|:-------------|
|
| **tabInformation** Effectuez-vous des tests d’intrusion annuels sur l’application ? | Oui |
| L’application a-t-elle un plan de récupération d’urgence documenté, y compris une stratégie de sauvegarde et de restauration ? | Oui Votre |
| environnement utilise-t-il des contrôles d’application ou de protection anti-programme malveillant traditionnels ? | TraditionalAntiMalware, ApplicationControls |
| Disposez-vous d’un processus établi pour mettre en retrait et classer les vulnérabilités de sécurité ? | Oui |
| Avez-vous une stratégie qui régit votre contrat de niveau de service (SLA) pour l’application de correctifs ? | Oui |
| Effectuez-vous des activités de gestion des correctifs en fonction de vos contrats SLA de stratégie de mise à jour corrective ? | Oui |
| Votre environnement a-t-il des systèmes d’exploitation ou logiciels non pris en charge ? | Non |
| Effectuez-vous une analyse trimestrielle des vulnérabilités sur votre application et l’infastructure qui la prend en charge ? | Oui |
| Un pare-feu est-il installé sur votre limite de réseau externe ? | Oui |
| Avez-vous un processus de gestion des modifications établi pour examiner et approuver les demandes de modification avant qu’elles ne soient déployées en production ? | Oui |
| Une personne supplémentaire examine-t-elle et approuve toutes les demandes de modification de code soumises à la production par le développeur d’origine ? | Oui |
| Les pratiques de codage sécurisé prennent-elles en compte les classes de vulnérabilité courantes telles que OWASP Top 10 ? | Oui |
| Authentification multifacteur (MFA) activée pour : | CodeRepositories, DNSManagement, Credential |
| Avez-vous un processus établi pour l’approvisionnement, la modification et la suppression de comptes d’employés ? | Oui |
| Avez-vous déployé un logiciel de détection et de prévention des intrusions (IDPS) au périmètre de la limite réseau qui prend en charge votre application ? | Oui |
| La journalisation des événements est-elle configurée sur tous les composants système qui prennent en charge votre application ? | Oui |
| Tous les journaux d’activité sont-ils examinés régulièrement par des outils humains ou automatisés pour détecter les événements de sécurité potentiels ? | Oui |
| Lorsqu’un événement de sécurité est détecté, les alertes sont-ils automatiquement envoyées à un employé pour le triage ? | Oui |
| Avez-vous établi un processus officiel de gestion des risques liés à la sécurité des informations ? | Oui |
| Un processus formel de réponse aux incidents de sécurité est-il documenté et établi ? | Oui |
| Signalez-vous les violations de données d’application ou de service aux autorités de surveillance et aux personnes concernées par la violation dans les 72 heures suivant la détection ? | Oui |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| L’application est-elle conforme à la Loi hipaa (Health Insurance Portability and Accounting Act) ? | Oui |
| L’application est-elle conforme à Health Information Trust Alliance, Common Security Framework (HITRUST CSF) ? | Non |
| L’application est-elle conforme aux contrôles d’organisation de service (SOC 1) ? | Non |
| L’application est-elle conforme aux contrôles d’organisation de service (SOC 2) ? | Oui |
| Quelle certification SOC 2 avez-vous obtenue ? | type2 |
| Date de certification SOC2 la plus récente | 2021-11-30 |
| L’application est-elle conforme aux contrôles d’organisation de service (SOC 3) ? | Non |
| Effectuez-vous des évaluations PCI DSS annuelles par rapport à l’application et à son environnement de prise en charge ? | Non |
| L’application Organisation internationale pour la normalisation (ISO 27001) est-elle certifiée ? | Oui |
| L’application est-elle conforme à l’Organisation internationale pour la normalisation (ISO 27018) ? | Oui |
| L’application est-elle conforme à l’Organisation internationale pour la normalisation (ISO 27017) ? | Oui |
| L’application est-elle conforme à l’Organisation internationale pour la normalisation (ISO 27002) ? | Non |
| L’application Federal Risk and Authorization Management Program (FedRAMP) est-elle conforme ? | Non |
| L’application est-elle conforme à la Loi sur les droits à l’éducation et la vie privée de la famille (FERPA) ? | Non |
| L’application est-elle conforme à la Loi coppa (Children’s Online Privacy Protection Act) ? | Non |
| L’application est-elle conforme à Sarbanes-Oxley Act (SOX) ? | Non |
| L’application est-elle conforme à NIST 800-171 ? | Non |
| L’application a-t-elle été certifiée Cloud Security Alliance (CSA Star) ? | Oui |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| Avez-vous un RGPD ou d’autres exigences ou obligations en matière de confidentialité ou de protection des données (comme le CCPA) ? | Oui |
| L’application a-t-elle un avis de confidentialité externe qui décrit comment elle collecte, utilise, partage et stocke les données client ? | Oui |
| URL de la politique de confidentialité | https://www.zoho.com/terms.html |
| L’application effectue-t-elle une prise de décision automatisée, y compris le profilage qui pourrait avoir un effet juridique ou un impact similaire ? | Non |
| L’application traite-t-elle les données client à des fins secondaires qui ne sont pas décrites dans l’avis de confidentialité (c’est-à-dire marketing, analytique) ? | Non |
| Traitez-vous des catégories spéciales de données sensibles (origines raciales ou ethniques, opinions politiques, croyances religieuses ou philosophiques, données génétiques ou biométriques, données de santé) ou catégories de données soumises à des lois de notification de violation ? | Non |
| L’application collecte-t-elle ou traite-t-elle des données auprès de mineurs (c’est-à-dire des personnes de moins de 16 ans) ? | Non |
| L’application dispose-t-elle de fonctionnalités permettant de supprimer les données personnelles d’une personne sur demande ? | Oui |
| L’application dispose-t-elle de fonctionnalités permettant de restreindre ou de limiter le traitement des données personnelles d’une personne sur demande ? | Oui |
| L’application offre-t-elle aux utilisateurs la possibilité de corriger ou de mettre à jour leurs données personnelles ? | Oui |
| Des examens réguliers de la sécurité et de la confidentialité des données sont-ils effectués (par exemple, des évaluations d’impact sur la protection des données ou des évaluations des risques de confidentialité) pour identifier les risques liés au traitement des données personnelles pour l’application ? | Oui |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| Votre application s’intègre-t-elle à Microsoft Identity Platform (Azure AD) pour l’authentification unique, l’accès à l’API, etc. ? | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle d’intégration Plateforme d'identités Microsoft ? | Oui |
| Votre application utilise-t-elle la dernière version de MSAL (Bibliothèque d’authentification Microsoft) ou Microsoft Identity Web pour l’authentification ? | Oui |
| Si votre application n’utilise pas l’une des bibliothèques ci-dessus, quelle bibliothèque ou bibliothèque d’authentification utilise-t-elle ? |  |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Oui |
| Répertorier les types de stratégies prises en charge | Multi-Factor Authentication, Exiger des appareils gérés par l’organisation pour des applications spécifiques, blocage des comportements de connexion à risque, limitation de l’accès accordé à d’autres personnes que les rôles d’administration  |
| Votre application prend-elle en charge l’évaluation continue de l’accès (CAE) | Oui |
| Votre application stocke-t-elle des informations d’identification dans le code ? | Non |
| Les applications et compléments pour Microsoft 365 peuvent utiliser des API Microsoft supplémentaires en dehors de Microsoft Graph. Votre application ou complément utilise-t-il des API Microsoft supplémentaires ? | Non |

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

>|   **autorisation Graph**  | **Type d’autorisation** |          **Justification**          | **ID d’application Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Contacts.Read | Délégué | Accéder en lecture aux contacts utilisateur | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read | Délégué | Lire les fichiers utilisateur | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read.All | Délégué | Accéder en lecture à tous les fichiers auxquels cet utilisateur peut accéder | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read.Selected | Délégué | Lire des fichiers sélectionnés par l’utilisateur | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| User.Read | Délégué | Activer la connexion et lire le profil utilisateur | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| User.ReadBasic.All | Délégué | Lire les profils de base de tous les utilisateurs | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| email | Délégué | Afficher l’adresse de messagerie des utilisateurs | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| offline_access | Délégué | Gérer l’accès aux données auxquelles vous avez accordé l’accès | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| profil | Délégué | Afficher le profil de base des utilisateurs | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |

>Cette application n’a pas d’API supplémentaires.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

