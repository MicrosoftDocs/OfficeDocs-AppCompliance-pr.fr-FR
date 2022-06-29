---
title: Informations sur l’application pour EasyLife 365 par EasyLife 365 AG
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/27/2022
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toutes les informations de sécurité et de conformité disponibles pour EasyLife 365, ses stratégies de gestion des données, ses informations de catalogue d’applications Microsoft Cloud App Security et les informations de sécurité/conformité dans le registre CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust-certification
ms.openlocfilehash: a50f566f963504e4c87d5b7a261373446afe6432
ms.sourcegitcommit: c06f3d478e1b4f66c02e2855ffac6de2f350208a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/29/2022
ms.locfileid: "66249327"
---
# <a name="easylife-365"></a>EasyLife 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Dernière mise à jour par le développeur : 23 mars 2022</p>

* <a href="https://teams.microsoft.com/l/app/93731bac-4d43-480f-9e40-9fc567dfb817" target="_blank">Afficher dans le magasin Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003697" target="_blank">Afficher dans AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informations générales

Informations fournies par EasyLife 365 AG à Microsoft :

| **Information** | **Réponse** |
|:----------------|:-------------|
| Nom de l'application | EasyLife 365 |
| ID | WA200003697 |
| Office 365 clients pris en charge | Microsoft Teams |
| Nom de la société partenaire | EasyLife 365 AG |
| Site web de la société | [https://www.easylife365.cloud](https://www.easylife365.cloud) |
| Conditions d’utilisation de l’application | [https://www.easylife365.cloud/terms](https://www.easylife365.cloud/terms) |
| Fonctionnalités principales de l’application | Facilitez la gouvernance ! |
| Emplacement du siège social de la société | Suisse |
| Page d’informations sur l’application | [https://www.easylife365.cloud/governance/features](https://www.easylife365.cloud/governance/features) |
| Quel est l’environnement d’hébergement ou le modèle de service utilisé pour exécuter votre application ? | Paas |
| Quels fournisseurs de cloud d’hébergement l’application utilise-t-elle ? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Comment l’application gère les données

Ces informations ont été fournies par EasyLife 365 AG sur la façon dont cette application collecte et stocke les données organisationnelles et le contrôle que votre organisation aura sur les données collectées par l’application.

| **Information** | **Réponse** |
|:----------------|:-------------|
| L’application ou l’infrastructure sous-jacente traite-t-elle les données relatives à un client Microsoft ou à son appareil ? | Oui |
| Quelles données sont traitées par votre application ? | Métadonnées de groupe (ID, nom, nombre de propriétaires, informations d’expiration); Informations utilisateur (id, userprincipalname, mail, preferredlanguage, userType) |
| L’application prend-elle en charge TLS 1.1 ou version ultérieure ? | Oui |
| L’application ou l’infrastructure sous-jacente stocke-t-elle des données client Microsoft ? | Oui |
| Quelles données sont stockées dans vos bases de données ? | Regrouper les métadonnées (ID, nom) et les informations utilisateur (ID, courrier) dans notre journalisation pendant 90 jours |
| Si l’infastructure sous-jacente traite ou stocke les données client Microsoft, où ces données sont-elles stockées géographiquement ? | Pays-Bas (le) |
| Disposez-vous d’un processus de location et d’élimination des données établi ? | Oui |
| Combien de temps les données sont-ils conservées après la résiliation du compte ? | Moins de 90 jours |
| Disposez-vous d’un processus de gestion de l’accès aux données établi ? | Oui |
| Transférez-vous des données client ou du contenu client vers des tiers ou des sous-processeurs ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Les informations du catalogue [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) s’affichent ci-dessous.

| **Information** | **Réponse** |
|:----------------|:-------------|
| Effectuez-vous des tests d’intrusion annuels sur l’application ? | Oui |
| L’application dispose-t-elle d’un plan de récupération d’urgence documenté, y compris une stratégie de sauvegarde et de restauration ? | Oui |
| Votre environnement utilise-t-il une protection anti-programme malveillant traditionnelle ou des contrôles d’application ? | TraditionalAntiMalware, ApplicationControls |
| Avez-vous mis en place un processus de mise en retrait et de classement des risques des vulnérabilités de sécurité ? | Oui |
| Avez-vous une stratégie qui régit votre contrat de niveau de service (SLA) pour l’application de correctifs ? | Oui |
| Effectuez-vous des activités de gestion des correctifs en fonction de vos contrats SLA de stratégie de mise à jour corrective ? | Oui |
| Votre environnement a-t-il des systèmes d’exploitation ou logiciels non pris en charge ? | Non |
| Effectuez-vous une analyse trimestrielle des vulnérabilités sur votre application et l’infastructure qui la prend en charge ? | Non |
| Un pare-feu est-il installé sur votre limite de réseau externe ? | Non |
| Avez-vous un processus de gestion des modifications établi pour examiner et approuver les demandes de modification avant qu’elles ne soient déployées en production ? | Oui |
| Une personne supplémentaire examine-t-elle et approuve-t-elle toutes les demandes de modification de code soumises à la production par le développeur d’origine ? | Oui |
| Les pratiques de codage sécurisées prennent-elles en compte les classes de vulnérabilité courantes telles que OWASP Top 10 ? | Oui |
| Authentification multifacteur (MFA) activée pour : | DNSManagement, Credential, CodeRepositories |
| Disposez-vous d’un processus établi pour l’approvisionnement, la modification et la suppression de comptes d’employés ? | Oui |
| Disposez-vous d’un logiciel de détection et de prévention des intrusions (IDPS) déployé au périmètre de la limite réseau qui prend en charge votre application ? | S/O |
| La journalisation des événements est-elle configurée sur tous les composants système qui prennent en charge votre application ? | Oui |
| Tous les journaux sont-ils examinés régulièrement par des outils humains ou automatisés pour détecter les événements de sécurité potentiels ? | Oui |
| Lorsqu’un événement de sécurité est détecté, les alertes sont-ils automatiquement envoyées à un employé pour le triage ? | Oui |
| Avez-vous établi un processus officiel de gestion des risques liés à la sécurité des informations ? | Oui |
| Avez-vous un processus formel de réponse aux incidents de sécurité documenté et établi ? | Oui |
| Signalez-vous les violations de données d’application ou de service aux autorités de surveillance et aux personnes concernées par la violation dans les 72 heures suivant la détection ? | Oui |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Réponse** |
|:----------------|:-------------|
| L’application est-elle conforme à la Loi hipaa (Health Insurance Portability and Accounting Act) ? | Non |
| L’application est-elle conforme à Health Information Trust Alliance, Common Security Framework (HITRUST CSF) ? | Non |
| L’application est-elle conforme aux contrôles d’organisation de service (SOC 1) ? | Non |
| L’application est-elle conforme aux contrôles d’organisation de service (SOC 2) ? | Non |
| L’application est-elle conforme aux contrôles d’organisation de service (SOC 3) ? | Non |
| Effectuez-vous des évaluations PCI DSS annuelles par rapport à l’application et à son environnement de prise en charge ? | Non |
| L’application Organisation internationale pour la normalisation (ISO 27001) est-elle certifiée ? | Non |
| L’application est-elle conforme à l’Organisation internationale pour la normalisation (ISO 27018) ? | Non |
| L’application est-elle conforme à l’Organisation internationale pour la normalisation (ISO 27017) ? | Non |
| L’application est-elle conforme à l’Organisation internationale pour la normalisation (ISO 27002) ? | Non |
| L’application Federal Risk and Authorization Management Program (FedRAMP) est-elle conforme ? | Non |
| L’application est-elle conforme à la Loi sur les droits à l’éducation et la vie privée de la famille (FERPA) ? | Non |
| L’application est-elle conforme à la Loi coppa (Children’s Online Privacy Protection Act) ? | Non |
| L’application est-elle conforme à Sarbanes-Oxley Act (SOX) ? | Non |
| L’application est-elle conforme à NIST 800-171 ? | Non |
| L’application a-t-elle été certifiée Cloud Security Alliance (CSA Star) ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Réponse** |
|:----------------|:-------------|
| Avez-vous un RGPD ou d’autres exigences ou obligations en matière de confidentialité ou de protection des données (comme le CCPA) ? | Oui |
| L’application a-t-elle un avis de confidentialité externe qui décrit comment elle collecte, utilise, partage et stocke les données client ? | Oui |
| URL de la politique de confidentialité | https://www.easylife365.cloud/web/privacy |
| L’application effectue-t-elle une prise de décision automatisée, y compris le profilage qui pourrait avoir un effet juridique ou un impact similaire ? | Non |
| L’application traite-t-elle les données client à des fins secondaires qui ne sont pas décrites dans l’avis de confidentialité (c’est-à-dire marketing, analytique) ? | Non |
| Traitez-vous des catégories spéciales de données sensibles (origines raciales ou ethniques, opinions politiques, croyances religieuses ou philosophiques, données génétiques ou biométriques, données de santé) ou catégories de données soumises à des lois de notification de violation ? | Non |
| L’application collecte-t-elle ou traite-t-elle des données auprès de mineurs (c’est-à-dire des personnes de moins de 16 ans) ? | Non |
| L’application dispose-t-elle de fonctionnalités permettant de supprimer les données personnelles d’une personne sur demande ? | Non |
| L’application dispose-t-elle de fonctionnalités permettant de restreindre ou de limiter le traitement des données personnelles d’une personne sur demande ? | Non |
| L’application offre-t-elle aux utilisateurs la possibilité de corriger ou de mettre à jour leurs données personnelles ? | Non |
| Des examens réguliers de la sécurité et de la confidentialité des données sont-ils effectués (par exemple, des évaluations d’impact sur la protection des données ou des évaluations des risques de confidentialité) pour identifier les risques liés au traitement des données personnelles pour l’application ? | Non |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Réponse** |
|:----------------|:-------------|
| Votre application s’intègre-t-elle à Microsoft Identity Platform (Azure AD) pour l’authentification unique, l’accès aux API, etc. ? | Oui |
| Avez-vous examiné et respecté toutes les meilleures pratiques applicables décrites dans la liste de contrôle d’intégration Plateforme d'identités Microsoft ? | Oui |
| Votre application utilise-t-elle la dernière version de MSAL (Bibliothèque d’authentification Microsoft) ou Microsoft Identity Web pour l’authentification ? | Oui |
| Votre application prend-elle en charge les stratégies d’accès conditionnel ? | Non |
| Votre application prend-elle en charge l’évaluation continue de l’accès (CAE) | Non |
| Votre application stocke-t-elle des informations d’identification dans le code ? | Non |
| Les applications et compléments pour Microsoft 365 peuvent utiliser des API Microsoft supplémentaires en dehors de Microsoft Graph. Votre application ou complément utilise-t-il des API Microsoft supplémentaires ? | Oui |

#### <a name="data-access-using-microsoft-graph"></a>Accès aux données à l’aide de Microsoft Graph

>|   **Autorisation Graph**  | **Type d’autorisation** |          **Justification**          | **ID d’application Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Group.Read.All | Délégué | Permet de lire des groupes ou des équipes | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Group.ReadWrite.All | Délégué | Permet de manipualiser les métadonnées des groupes ou teams | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| GroupMember.Read.All | Délégué | Lit les membres d’un groupe | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.Read.All | Délégué | Permet de récupérer les métadonnées du compte invité | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.ReadBasic.All | Délégué | Permet de rechercher des membres ou des comptes invités dans une organisation | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Channel.Create | application | Crée des canaux pour une équipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Channel.ReadBasic.All | application | Lit les canaux d’une équipe existante | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.Read.All | application | Obtenir les modèles actuels de paramètres de compte de groupe et d’invité | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.ReadWrite.All | application | Appliquer les paramètres de compte invité pour le groupe ou l’équipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Create | application | Crée un groupe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | les deux | Lit les informations de groupe et récupère les alias de groupe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.ReadWrite.All | application | Manipule les métadonnées de groupe dans le back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.Read.All | application | Récupère les appartenances au groupe ou à l’équipe dans le serveur principal | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.ReadWrite.All | application | Permet d’ajouter ou de supprimer des membres d’un groupe ou d’une équipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| IdentityRiskyUser.ReadWrite.All | application | Permet de manipuler les comptes invités et leurs métadonnées | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Mail.Send | application | Envoie des messages à l’aide d’une boîte aux lettres partagée | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| MailboxSettings.Read | application | Récupère les paramètres de langue préférés d’un utilisateur | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Reports.Read.All | application | Récupère les données d’utilisation des groupes et teams | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Team.ReadBasic.All | application | Récupérer les informations d’équipe de base | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamSettings.ReadWrite.All | application | Permet d’archiver et d’annuler l’archivage d’une équipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Teams.Create | application | Crée une équipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.Read.All | application | Récupère les onglets d’une équipe créée | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.ReadWrite.All | application | Permet de créer ou de manipualiser des onglets d’une équipe créée | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Invite.All | application | Invite un utilisateur au locataire | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read | Délégué | Obtient les informations utilisateur et les informations d’organisation | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read.All | les deux | Récupère les informations sur les invités et les utilisateurs | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | Délégué | Lire tous les groupes d’utilisateurs | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| Group.ReadWrite.All | Délégué | Modifier les métadonnées de groupe de l’utilisateur et manipuler les groupes et Teams | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.Read.All | Délégué | Permet à un propriétaire de groupe de lire l’appartenance à un groupe ou à une équipe | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.ReadWrite.All | Délégué | Permet au propriétaire du groupe de manipuler l’appartenance à un groupe ou à une équipe | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamSettings.ReadWrite.All | Délégué | Permet d’archiver ou d’annuler l’archivage d’une équipe | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsActivity.Send | application | Utilisé pour envoyer des notifications Teams dans le serveur principal | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsAppInstallation.ReadForUser.All | application | Vérifiez si l’application EasyLife est installée pour l’utilisateur avant d’envoyer des notifications via Teams. | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read | Délégué | Lit les données de l’organisation et les informations utilisateur | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read.All | Délégué | Permet de rechercher d’autres membres ou comptes invités dans un répertoire | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.ReadBasic.All | Délégué | Affiche les photos de l’utilisateur | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| email | Délégué | Utilisé par l’authentification unique | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| offline_access | Délégué | Utilisé par l’authentification unique | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| openid | Délégué | Utilisé par l’authentification unique | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| profil | Délégué | Utilisé par l’authentification unique | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |

>Cette application n’a pas d’API supplémentaires.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="certification"

### <a name="certification-information"></a>Informations de certification

| **Contrôle** | **Résultat de la certification Microsoft 365** |
|:------------|:---------------------------------------|
| [**SÉCURITÉ DES APPLICATIONS**](../docs/certification-submission-guide.md#application-security) | **PASSER** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Test de pénétration | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Évaluation des vulnérabilités (DAST/SAST/Test d’intrusion) | Dans l’étendue |
| [**SÉCURITÉ OPÉRATIONNELLE**](../docs/certification-submission-guide.md#operational-security) | **PASSER** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Protection contre les programmes malveillants - Antivirus | S/O |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Protection contre les programmes malveillants - Contrôle d’application | S/O |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestion des correctifs - Classement des risques | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestion des correctifs - Mise à jour corrective | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Analyse des vulnérabilités | S/O |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pare-feu - Pare-feu (ou technologies équivalentes) | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pare-feu - Pare-feu d’applications web (WAF) (facultatif) | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Modifier le contrôle | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Développement/déploiement de logiciels sécurisés | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestion des comptes | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Détection et prévention des intrusions (facultatif) | S/O |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Journalisation des événements de sécurité | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Révision (données de journalisation) | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Alertes d’événements de sécurité | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestion des risques liés à la sécurité des informations | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Réponse aux incidents | Dans l’étendue |
| [**CONFIDENTIALITÉ DE LA SÉCURITÉ DE GESTION &amp; DES DONNÉES**](../docs/certification-submission-guide.md#data-handling-security-and-privacy) | **PASSER** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Données en transit | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Données au repos | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Conservation et élimination des données | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestion de l’accès aux données | Dans l’étendue |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RGPD | Dans l’étendue |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
