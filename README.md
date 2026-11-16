# Catalogue VMware Hands-on Labs : VMware Cloud Foundation (VCF) 9.1

Ce document présente les labs disponibles dans la plateforme VMware Hands-on Labs (HOL) pour VMware Cloud Foundation 9.1. Chaque lab est un environnement complet, préconfiguré et accessible depuis un navigateur, sans aucune infrastructure à déployer.

L'objectif de ce guide est de faciliter le partage et la planification des parcours de formation : il regroupe les labs par domaine et précise, pour chacun, son contenu, son objectif et son lien d'accès.

## Sommaire

1. [Tableau récapitulatif des labs](#tableau-récapitulatif-des-labs)
2. [Présentation](#présentation)
3. [Comment accéder aux labs](#comment-accéder-aux-labs)
4. [Parcours recommandés](#parcours-recommandés)
5. [VCF Operations : supervision et optimisation](#vcf-operations--supervision-et-optimisation)
6. [VCF Automation : libre-service et applications](#vcf-automation--libre-service-et-applications)
7. [Plateforme VCF : cycle de vie, réseau et performance](#plateforme-vcf--cycle-de-vie-réseau-et-performance)
8. [vSphere dans VCF](#vsphere-dans-vcf)
9. [Stockage, résilience et protection des données](#stockage-résilience-et-protection-des-données)
10. [Mobilité, services de données et IA privée](#mobilité-services-de-données-et-ia-privée)
11. [Sécurité avec vDefend](#sécurité-avec-vdefend)
12. [Équilibrage de charge avec Avi](#équilibrage-de-charge-avec-avi)
13. [Évolutions par rapport à la version précédente](#évolutions-par-rapport-à-la-version-précédente)

## Tableau récapitulatif des labs

| N° | Domaine | Lab | Référence | Lien |
|---|---|---|---|---|
| 1 | VCF Operations | Prise en main et supervision de VCF Operations | HOL-2711-01-VCF-L | ... |
| 2 | VCF Operations | Dépannage du cloud privé, journaux, métriques et flux réseau | HOL-2711-02-VCF-L | ... |
| 3 | VCF Operations | Santé et diagnostics de l'infrastructure | HOL-2711-03-VCF-L | ... |
| 4 | VCF Operations | Tableaux de bord, vues et rapports | HOL-2711-12-VCF-L | ... |
| 5 | VCF Operations | Optimisation de la capacité et Green Score | HOL-2711-08-VCF-L | ... |
| 6 | VCF Operations | Optimisation des coûts, showback et chargeback | HOL-2711-09-VCF-L | ... |
| 7 | VCF Automation | Nouveautés de VCF Automation | HOL-2711-20-VCF-L | ... |
| 8 | VCF Automation | Prise en main de VCF Automation | HOL-2711-21-VCF-L | ... |
| 9 | VCF Automation | Gestion et administration côté fournisseur | HOL-2711-22-VCF-L | ... |
| 10 | VCF Automation | Applications modernes et cloud native avec VCF Automation | HOL-2711-24-VCF-L | ... |
| 11 | Plateforme VCF | Maintenir son cloud privé, nouveautés plateforme et authentification unique | HOL-2704-01-VCF-L | ... |
| 12 | Plateforme VCF | Réseau VCF avec NSX et VPC | HOL-2704-02-VCF-L | ... |
| 13 | Plateforme VCF | Introduction à la performance vSphere et sous-systèmes ESXi | HOL-2704-03-VCF-L | ... |
| 14 | Plateforme VCF | Performance des charges de travail avec VMmark | HOL-2704-04-VCF-L | ... |
| 15 | Plateforme VCF | Mise à niveau depuis vSphere 8 | HOL-2704-05-VCF-S | ... |
| 16 | Plateforme VCF | Opérations avancées et outils VCF | HOL-2704-06-VCF-L | ... |
| 17 | Plateforme VCF | Gestion unifiée des machines virtuelles et de Kubernetes avec vSphere Supervisor | HOL-2704-07-VCF-L | ... |
| 18 | vSphere | Nouveautés de vSphere dans VCF | HOL-2706-01-VCF-L | ... |
| 19 | vSphere | vSphere : sujets avancés et automatisation avec PowerCLI | HOL-2706-02-VCF-L | ... |
| 20 | Stockage et résilience | vSAN et NVMe Memory Tiering | HOL-2734-01-VCF-L | ... |
| 21 | Stockage et résilience | Réplication vSphere améliorée | HOL-2734-02-VCF-S | ... |
| 22 | Stockage et résilience | VMware Live Recovery : reprise après sinistre | HOL-2734-03-VCF-L | ... |
| 23 | Stockage et résilience | VMware Live Recovery : reprise après ransomware | HOL-2734-04-VCF-S | ... |
| 24 | Mobilité, données et IA | HCX : prise en main, planification et migration avancée | HOL-2705-03-VCF-L | ... |
| 25 | Mobilité, données et IA | VMware Data Services Manager : prise en main | HOL-2705-04-VCF-L | ... |
| 26 | Mobilité, données et IA | VMware Private AI Foundation avec NVIDIA : prise en main | HOL-2705-12-VCF-L | ... |
| 27 | Sécurité vDefend | Parcours sécurité du pare-feu vDefend | HOL-2770-01-ANS-L | ... |
| 28 | Sécurité vDefend | Pare-feu vDefend avec protection avancée contre les menaces | HOL-2770-02-ANS-L | ... |
| 29 | Sécurité vDefend | Pare-feu distribué vDefend : prise en main et sécurité avancée | HOL-2770-03-ANS-L | ... |
| 30 | Équilibrage de charge Avi | Équilibrage de charge des applications VCF avec Avi | HOL-2740-01-ANS-L | ... |
| 31 | Équilibrage de charge Avi | Prise en main de l'équilibrage de charge Avi | HOL-2740-02-ANS-L | ... |
| 32 | Équilibrage de charge Avi | Migration d'un équilibrage de charge existant avec l'outil de conversion Avi | HOL-2740-05-ANS-L | ... |

Le détail de chaque lab (description, objectif) figure dans les sections thématiques ci-dessous.

## Présentation

Le catalogue VCF 9.1 met à jour l'ensemble des labs du catalogue précédent. Plusieurs labs ont été regroupés afin d'offrir des parcours plus complets et moins redondants. Les labs s'adressent aux administrateurs, architectes et ingénieurs plateforme qui souhaitent découvrir ou approfondir le modèle d'exploitation unifié du cloud privé VMware.

### Public concerné

Ces labs sont destinés en priorité aux étudiants de E5 CCSN, dans le cadre du cours Virtual Data Center Automation (VCF Automation). Ils sont également ouverts à toutes les personnes intéressées par VMware Cloud Foundation, quel que soit leur niveau, qui souhaitent se former ou approfondir leurs connaissances de manière pratique et gratuite.

## Comment accéder aux labs

1. Créer ou utiliser un compte Hands-on Labs (gratuit).
2. Ouvrir le catalogue VCF 9.1 : https://labs.hol.vmware.com/HOL/catalog
3. Rechercher le lab par sa référence ou par son thème, puis cliquer sur « Lancer ».
4. L'environnement est provisionné et accessible directement dans le navigateur.

Les liens individuels des labs sont à renseigner à l'emplacement prévu dans chaque fiche (champ « Lien »).

## Parcours recommandés

| Profil | Parcours suggéré |
|---|---|
| Découverte de la plateforme | Maintenir son cloud privé, puis réseau VPC, puis vSphere nouveautés |
| Exploitation et supervision | Prise en main de VCF Operations, dépannage, tableaux de bord, capacité, coûts |
| Automatisation et libre-service | Prise en main de VCF Automation, administration fournisseur, applications modernes |
| Sécurité | Parcours sécurité vDefend, pare-feu distribué, protection avancée contre les menaces |
| Résilience | Réplication vSphere, reprise après sinistre, reprise après ransomware |
| Performance | Introduction à la performance, sous-systèmes ESXi, VMmark |

---

## VCF Operations : supervision et optimisation

### Prise en main et supervision de VCF Operations

- **Référence** : HOL-2711-01-VCF-L
- **Description** : Lab d'entrée dans VCF Operations. Il présente la nouvelle interface et les fonctions de supervision transverses du cloud privé : infrastructure, réseau, stockage, applications, services et sécurité. Il regroupe les anciens labs de prise en main, de supervision réseau et stockage, de supervision des applications, de supervision de la sécurité et des nouveautés Operations.
- **Objectif** : Acquérir une vision d'ensemble de VCF Operations et savoir surveiller l'état et les performances de l'ensemble du cloud privé depuis une console unique.
- **Lien** : ...

### Dépannage du cloud privé, journaux, métriques et flux réseau

- **Référence** : HOL-2711-02-VCF-L
- **Description** : Lab consacré au diagnostic et à la résolution d'incidents. Il couvre l'analyse des journaux, des métriques et des flux réseau, ainsi que la corrélation entre ces sources pour identifier la cause d'un problème.
- **Objectif** : Apprendre à localiser rapidement l'origine d'un incident et à réduire le temps de résolution grâce aux outils d'analyse de VCF Operations.
- **Lien** : ...

### Santé et diagnostics de l'infrastructure

- **Référence** : HOL-2711-03-VCF-L
- **Description** : Lab centré sur le suivi de la santé de l'infrastructure du cloud privé et sur les outils de diagnostic associés : alertes, recommandations et vérifications de l'état des composants.
- **Objectif** : Savoir anticiper les dégradations, interpréter les alertes et maintenir un niveau de service stable.
- **Lien** : ...

### Tableaux de bord, vues et rapports

- **Référence** : HOL-2711-12-VCF-L
- **Description** : Lab de création de visualisations personnalisées dans VCF Operations : tableaux de bord, vues et rapports adaptés aux besoins des équipes d'exploitation et de la direction.
- **Objectif** : Maîtriser la construction de tableaux de bord et de rapports exploitables pour suivre l'activité du cloud privé et en rendre compte.
- **Lien** : ...

### Optimisation de la capacité et Green Score

- **Référence** : HOL-2711-08-VCF-L
- **Description** : Lab sur la planification de capacité et l'optimisation des ressources, incluant le suivi de l'indicateur Green Score lié à l'efficacité énergétique de l'infrastructure.
- **Objectif** : Dimensionner correctement l'infrastructure, identifier les ressources sous-utilisées ou surdimensionnées et réduire l'impact énergétique.
- **Lien** : ...

### Optimisation des coûts, showback et chargeback

- **Référence** : HOL-2711-09-VCF-L
- **Description** : Lab consacré à la gestion financière du cloud privé : calcul des coûts, refacturation interne (chargeback) et affichage des coûts aux équipes consommatrices (showback).
- **Objectif** : Mettre en place la transparence des coûts et responsabiliser les équipes sur leur consommation de ressources.
- **Lien** : ...

---

## VCF Automation : libre-service et applications

### Nouveautés de VCF Automation

- **Référence** : HOL-2711-20-VCF-L
- **Description** : Lab de découverte des nouvelles fonctions d'automatisation introduites avec VCF 9.1, en particulier le libre-service et la gouvernance des environnements.
- **Objectif** : Comprendre les évolutions d'automatisation de la version 9.1 et leur apport pour les équipes plateforme et les consommateurs.
- **Lien** : ...

### Prise en main de VCF Automation

- **Référence** : HOL-2711-21-VCF-L
- **Description** : Lab d'introduction à VCF Automation : navigation dans l'interface, concepts clés et premiers déploiements de ressources.
- **Objectif** : Prendre en main la solution et comprendre le modèle de consommation du cloud privé en libre-service.
- **Lien** : ...

### Gestion et administration côté fournisseur

- **Référence** : HOL-2711-22-VCF-L
- **Description** : Lab destiné aux administrateurs du fournisseur de service : configuration de la plateforme, gestion des organisations, des ressources et des accès.
- **Objectif** : Savoir administrer VCF Automation en tant que fournisseur et préparer l'environnement pour les différentes équipes.
- **Lien** : ...

### Applications modernes et cloud native avec VCF Automation

- **Référence** : HOL-2711-24-VCF-L
- **Description** : Lab de construction et de déploiement d'applications modernes à l'aide des organisations de VCF Automation. Il regroupe les anciens labs sur la création d'applications modernes et le déploiement d'applications cloud native.
- **Objectif** : Déployer des applications cloud native sur le cloud privé et valoriser le modèle de libre-service pour les équipes de développement.
- **Lien** : ...

---

## Plateforme VCF : cycle de vie, réseau et performance

### Maintenir son cloud privé, nouveautés plateforme et authentification unique

- **Référence** : HOL-2704-01-VCF-L
- **Description** : Lab central sur la plateforme VCF : opérations de maintenance et de cycle de vie, nouveautés de la plateforme et configuration de l'authentification unique (SSO).
- **Objectif** : Connaître les opérations d'exploitation courantes de la plateforme et savoir centraliser l'authentification des utilisateurs.
- **Lien** : ...

### Réseau VCF avec NSX et VPC

- **Référence** : HOL-2704-02-VCF-L
- **Description** : Lab sur la mise en réseau du cloud privé avec NSX et les VPC (Virtual Private Cloud). Il couvre le réseau applicatif simplifié, la résilience réseau et le multi-tenant.
- **Objectif** : Concevoir et exploiter un réseau souple, résilient et adapté aux environnements multi-locataires.
- **Lien** : ...

### Introduction à la performance vSphere et sous-systèmes ESXi

- **Référence** : HOL-2704-03-VCF-L
- **Description** : Lab d'initiation à la performance dans VCF : compréhension des indicateurs et tests des sous-systèmes d'un hôte ESXi (processeur, mémoire, disque et réseau).
- **Objectif** : Apprendre à mesurer, interpréter et diagnostiquer la performance de l'infrastructure de virtualisation.
- **Lien** : ...

### Performance des charges de travail avec VMmark

- **Référence** : HOL-2704-04-VCF-L
- **Description** : Lab d'évaluation de la performance à l'aide de VMmark, un banc d'essai conçu pour mesurer le comportement de charges de travail virtualisées.
- **Objectif** : Savoir exécuter et analyser un test de performance représentatif pour valider un dimensionnement.
- **Lien** : ...

### Mise à niveau depuis vSphere 8

- **Référence** : HOL-2704-05-VCF-S
- **Description** : Lab court consacré au parcours de mise à niveau d'un environnement vSphere 8 vers VMware Cloud Foundation.
- **Objectif** : Comprendre les étapes, les prérequis et les points d'attention d'une migration vers VCF.
- **Lien** : ...

### Opérations avancées et outils VCF

- **Référence** : HOL-2704-06-VCF-L
- **Description** : Lab destiné aux utilisateurs expérimentés, présentant les outils et opérations avancés de la plateforme.
- **Objectif** : Approfondir l'exploitation de VCF et gagner en autonomie sur les tâches complexes d'administration.
- **Lien** : ...

### Gestion unifiée des machines virtuelles et de Kubernetes avec vSphere Supervisor

- **Référence** : HOL-2704-07-VCF-L
- **Description** : Lab montrant comment gérer à la fois des machines virtuelles et des conteneurs Kubernetes sur une même plateforme grâce à vSphere Supervisor.
- **Objectif** : Unifier l'exploitation des charges de travail traditionnelles et conteneurisées.
- **Lien** : ...

---

## vSphere dans VCF

### Nouveautés de vSphere dans VCF

- **Référence** : HOL-2706-01-VCF-L
- **Description** : Lab présentant les nouvelles fonctions de vSphere au sein de VMware Cloud Foundation.
- **Objectif** : Identifier les évolutions utiles à votre environnement et planifier leur adoption.
- **Lien** : ...

### vSphere : sujets avancés et automatisation avec PowerCLI

- **Référence** : HOL-2706-02-VCF-L
- **Description** : Lab d'approfondissement sur des sujets avancés de vSphere, incluant l'automatisation des tâches d'administration avec PowerCLI.
- **Objectif** : Maîtriser des fonctions avancées et automatiser les opérations répétitives par script.
- **Lien** : ...

---

## Stockage, résilience et protection des données

### vSAN et NVMe Memory Tiering

- **Référence** : HOL-2734-01-VCF-L
- **Description** : Lab couvrant VMware vSAN, de la prise en main aux sujets avancés, ainsi que la configuration de bout en bout du Memory Tiering NVMe.
- **Objectif** : Maîtriser le stockage défini par logiciel et optimiser l'usage de la mémoire pour augmenter la densité de machines virtuelles.
- **Lien** : ...

### Réplication vSphere améliorée

- **Référence** : HOL-2734-02-VCF-S
- **Description** : Lab court sur la réplication vSphere améliorée, destiné à protéger les machines virtuelles en les répliquant vers un autre site.
- **Objectif** : Configurer la réplication et comprendre ses paramètres et ses objectifs de point de reprise.
- **Lien** : ...

### VMware Live Recovery : reprise après sinistre

- **Référence** : HOL-2734-03-VCF-L
- **Description** : Lab illustrant un scénario de reprise après sinistre avec VMware Live Recovery : planification, orchestration et bascule.
- **Objectif** : Construire et tester un plan de reprise d'activité pour assurer la continuité de service.
- **Lien** : ...

### VMware Live Recovery : reprise après ransomware

- **Référence** : HOL-2734-04-VCF-S
- **Description** : Lab court portant sur la récupération après une attaque par ransomware, avec restauration vers un environnement sain.
- **Objectif** : Savoir restaurer des charges de travail de manière sûre après une cyberattaque.
- **Lien** : ...

---

## Mobilité, services de données et IA privée

### VMware Cloud Foundation Operations HCX : prise en main, planification et migration avancée

- **Référence** : HOL-2705-03-VCF-L
- **Description** : Lab consacré à HCX pour la planification et la réalisation de migrations de charges de travail, des premiers pas aux scénarios avancés.
- **Objectif** : Planifier et exécuter des migrations vers ou entre environnements avec un minimum d'interruption.
- **Lien** : ...

### VMware Data Services Manager : prise en main

- **Référence** : HOL-2705-04-VCF-L
- **Description** : Lab d'introduction à Data Services Manager pour provisionner et gérer des bases de données en libre-service sur le cloud privé.
- **Objectif** : Offrir des services de données gérés, standardisés et rapides à déployer.
- **Lien** : ...

### VMware Private AI Foundation avec NVIDIA : prise en main

- **Référence** : HOL-2705-12-VCF-L
- **Description** : Lab de découverte de VMware Private AI Foundation avec NVIDIA, pour exécuter des charges d'intelligence artificielle sur une infrastructure privée.
- **Objectif** : Comprendre comment déployer des charges d'IA tout en conservant la maîtrise des données et de l'infrastructure.
- **Lien** : ...

---

## Sécurité avec vDefend

### Parcours sécurité du pare-feu vDefend

- **Référence** : HOL-2770-01-ANS-L
- **Description** : Lab présentant le parcours de sécurisation d'un environnement avec le pare-feu vDefend, de la visibilité à l'application des politiques.
- **Objectif** : Comprendre la démarche progressive de mise en place de la segmentation et de la sécurité réseau.
- **Lien** : ...

### Pare-feu vDefend avec protection avancée contre les menaces

- **Référence** : HOL-2770-02-ANS-L
- **Description** : Lab sur la détection et la prévention des menaces avancées en complément du pare-feu vDefend.
- **Objectif** : Renforcer la posture de sécurité en identifiant et en bloquant les comportements malveillants.
- **Lien** : ...

### Pare-feu distribué vDefend : prise en main et sécurité avancée

- **Référence** : HOL-2770-03-ANS-L
- **Description** : Lab couvrant le pare-feu distribué vDefend, depuis la prise en main jusqu'aux fonctions de sécurité avancées.
- **Objectif** : Mettre en œuvre la micro-segmentation et appliquer des politiques de sécurité au plus près des charges de travail.
- **Lien** : ...

---

## Équilibrage de charge avec Avi

### Équilibrage de charge des applications VCF avec Avi

- **Référence** : HOL-2740-01-ANS-L
- **Description** : Lab sur l'utilisation d'Avi Load Balancer pour répartir le trafic des applications déployées sur VMware Cloud Foundation.
- **Objectif** : Garantir la disponibilité et les performances des applications grâce à un équilibrage de charge adapté.
- **Lien** : ...

### Prise en main de l'équilibrage de charge Avi

- **Référence** : HOL-2740-02-ANS-L
- **Description** : Lab d'introduction aux concepts et à la configuration de base d'Avi Application Load Balancing.
- **Objectif** : Créer ses premiers services virtuels et comprendre l'architecture d'Avi.
- **Lien** : ...

### Migration d'un équilibrage de charge existant avec l'outil de conversion Avi

- **Référence** : HOL-2740-05-ANS-L
- **Description** : Lab consacré à la migration de configurations d'équilibrage de charge héritées vers Avi à l'aide de l'outil de conversion.
- **Objectif** : Moderniser un équilibrage de charge existant en limitant les erreurs et le travail manuel.
- **Lien** : ...

---

## Évolutions par rapport à la version précédente

- Plusieurs labs de la version précédente ont été regroupés dans un même lab VCF 9.1, notamment pour VCF Operations, le réseau NSX et les performances vSphere.
- Un lab a été retiré sans remplaçant : « Gestion des organisations pour toutes les applications avec VCF Automation ».
- Les labs portant le suffixe « S » sont des formats courts, ceux portant le suffixe « L » sont des labs complets.

## Ressources

- Catalogue Hands-on Labs : https://labs.hol.vmware.com/HOL/catalog
- Blog VMware Cloud Foundation : https://blogs.vmware.com/cloud-foundation/
