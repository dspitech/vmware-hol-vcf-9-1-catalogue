# Catalogue VMware Hands-on Labs : VMware Cloud Foundation (VCF) 9.1

Ce document présente les labs disponibles dans la plateforme VMware Hands-on Labs (HOL) pour VMware Cloud Foundation 9.1. Chaque lab est un environnement complet, préconfiguré et accessible depuis un navigateur, sans aucune infrastructure à déployer.

L'objectif de ce guide est de faciliter le partage et la planification des parcours de formation : il regroupe les labs par domaine et précise, pour chacun, son contenu, son objectif et son lien d'accès.

## Sommaire

1. [Tableau récapitulatif des labs](#tableau-récapitulatif-des-labs)
2. [Ordre de suivi recommandé](#ordre-de-suivi-recommandé)
3. [Présentation](#présentation)
4. [Comment accéder aux labs](#comment-accéder-aux-labs)
5. [Prérequis et préparation](#prérequis-et-préparation)
6. [Conseils pour réussir un lab](#conseils-pour-réussir-un-lab)
7. [Parcours recommandés](#parcours-recommandés)
8. [VCF Operations : supervision et optimisation](#vcf-operations--supervision-et-optimisation)
9. [VCF Automation : libre-service et applications](#vcf-automation--libre-service-et-applications)
10. [Plateforme VCF : cycle de vie, réseau et performance](#plateforme-vcf--cycle-de-vie-réseau-et-performance)
11. [vSphere dans VCF](#vsphere-dans-vcf)
12. [Stockage, résilience et protection des données](#stockage-résilience-et-protection-des-données)
13. [Mobilité, services de données et IA privée](#mobilité-services-de-données-et-ia-privée)
14. [Sécurité avec vDefend](#sécurité-avec-vdefend)
15. [Équilibrage de charge avec Avi](#équilibrage-de-charge-avec-avi)
16. [Évolutions par rapport à la version précédente](#évolutions-par-rapport-à-la-version-précédente)

## Tableau récapitulatif des labs

| N° | Domaine | Lab | Référence | Lien |
|---|---|---|---|---|
| 1 | VCF Operations | Prise en main et supervision de VCF Operations | HOL-2711-01-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27715) |
| 2 | VCF Operations | Dépannage du cloud privé, journaux, métriques et flux réseau | HOL-2711-02-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27679) |
| 3 | VCF Operations | Santé et diagnostics de l'infrastructure | HOL-2711-03-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27635) |
| 4 | VCF Operations | Tableaux de bord, vues et rapports | HOL-2711-12-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27685) |
| 5 | VCF Operations | Optimisation de la capacité et Green Score | HOL-2711-08-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27699) |
| 6 | VCF Operations | Optimisation des coûts, showback et chargeback | HOL-2711-09-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27700) |
| 7 | VCF Automation | Nouveautés de VCF Automation | HOL-2711-20-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27713) |
| 8 | VCF Automation | Prise en main de VCF Automation | HOL-2711-21-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27677) |
| 9 | VCF Automation | Gestion et administration côté fournisseur | HOL-2711-22-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27695) |
| 10 | VCF Automation | Applications modernes et cloud native avec VCF Automation | HOL-2711-24-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27672) |
| 11 | Plateforme VCF | Maintenir son cloud privé, nouveautés plateforme et authentification unique | HOL-2704-01-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27687) |
| 12 | Plateforme VCF | Réseau VCF avec NSX et VPC | HOL-2704-02-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27667) |
| 13 | Plateforme VCF | Introduction à la performance vSphere et sous-systèmes ESXi | HOL-2704-03-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27694) |
| 14 | Plateforme VCF | Performance des charges de travail avec VMmark | HOL-2704-04-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27693) |
| 15 | Plateforme VCF | Mise à niveau depuis vSphere 8 | HOL-2704-05-VCF-S | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27706) |
| 16 | Plateforme VCF | Opérations avancées et outils VCF | HOL-2704-06-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27704) |
| 17 | Plateforme VCF | Gestion unifiée des machines virtuelles et de Kubernetes avec vSphere Supervisor | HOL-2704-07-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27680) |
| 18 | vSphere | Nouveautés de vSphere dans VCF | HOL-2706-01-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27714) |
| 19 | vSphere | vSphere : sujets avancés et automatisation avec PowerCLI | HOL-2706-02-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27670) |
| 20 | Stockage et résilience | vSAN et NVMe Memory Tiering | HOL-2734-01-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27712) |
| 21 | Stockage et résilience | Réplication vSphere améliorée | HOL-2734-02-VCF-S | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27675) |
| 22 | Stockage et résilience | VMware Live Recovery : reprise après sinistre | HOL-2734-03-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27709) |
| 23 | Stockage et résilience | VMware Live Recovery : reprise après ransomware | HOL-2734-04-VCF-S | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27710) |
| 24 | Mobilité, données et IA | HCX : prise en main, planification et migration avancée | HOL-2705-03-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27707) |
| 25 | Mobilité, données et IA | VMware Data Services Manager : prise en main | HOL-2705-04-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27671) |
| 26 | Mobilité, données et IA | VMware Private AI Foundation avec NVIDIA : prise en main | HOL-2705-12-VCF-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27644) |
| 27 | Sécurité vDefend | Parcours sécurité du pare-feu vDefend | HOL-2770-01-ANS-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27651) |
| 28 | Sécurité vDefend | Pare-feu vDefend avec protection avancée contre les menaces | HOL-2770-02-ANS-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27638) |
| 29 | Sécurité vDefend | Pare-feu distribué vDefend : prise en main et sécurité avancée | HOL-2770-03-ANS-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27652) |
| 30 | Équilibrage de charge Avi | Équilibrage de charge des applications VCF avec Avi | HOL-2740-01-ANS-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27697) |
| 31 | Équilibrage de charge Avi | Prise en main de l'équilibrage de charge Avi | HOL-2740-02-ANS-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27678) |
| 32 | Équilibrage de charge Avi | Migration d'un équilibrage de charge existant avec l'outil de conversion Avi | HOL-2740-05-ANS-L | [Ouvrir le lab](https://labs.hol.vmware.com/HOL/catalog/lab/27689) |

Le détail de chaque lab (description, objectif) figure dans les sections thématiques ci-dessous.

## Ordre de suivi recommandé

Ce tableau propose un ordre pour suivre l'ensemble des 32 labs, des fondations jusqu'aux sujets avancés. Les étudiants du cours Virtual Data Center Automation peuvent suivre en priorité les étapes 1 et 2, puis poursuivre avec les suivantes. Les niveaux indiqués sont des suggestions et la colonne « Fait » permet de suivre sa progression.

| Ordre | Étape | Lab | Référence | Niveau | Pourquoi à cette place | Fait |
|---|---|---|---|---|---|---|
| 1 | 1. Fondations de la plateforme | [Maintenir son cloud privé, nouveautés plateforme et authentification unique](https://labs.hol.vmware.com/HOL/catalog/lab/27687) | HOL-2704-01-VCF-L | Débutant | Point de départ : cycle de vie, nouveautés et authentification unique | [ ] |
| 2 | 1. Fondations de la plateforme | [Nouveautés de vSphere dans VCF](https://labs.hol.vmware.com/HOL/catalog/lab/27714) | HOL-2706-01-VCF-L | Débutant | Découvrir les nouveautés vSphere avant d'aller plus loin | [ ] |
| 3 | 1. Fondations de la plateforme | [Réseau VCF avec NSX et VPC](https://labs.hol.vmware.com/HOL/catalog/lab/27667) | HOL-2704-02-VCF-L | Débutant | Comprendre le réseau NSX et les VPC, utile pour la suite | [ ] |
| 4 | 1. Fondations de la plateforme | [vSAN et NVMe Memory Tiering](https://labs.hol.vmware.com/HOL/catalog/lab/27712) | HOL-2734-01-VCF-L | Intermédiaire | Stockage vSAN et optimisation de la mémoire | [ ] |
| 5 | 1. Fondations de la plateforme | [vSphere : sujets avancés et automatisation avec PowerCLI](https://labs.hol.vmware.com/HOL/catalog/lab/27670) | HOL-2706-02-VCF-L | Intermédiaire | Sujets avancés et premiers scripts PowerCLI | [ ] |
| 6 | 1. Fondations de la plateforme | [Gestion unifiée des machines virtuelles et de Kubernetes avec vSphere Supervisor](https://labs.hol.vmware.com/HOL/catalog/lab/27680) | HOL-2704-07-VCF-L | Intermédiaire | Introduction à Kubernetes sur la plateforme, utile avant les applications cloud native | [ ] |
| 7 | 2. VCF Automation (coeur du cours) | [Prise en main de VCF Automation](https://labs.hol.vmware.com/HOL/catalog/lab/27677) | HOL-2711-21-VCF-L | Débutant | Première prise en main de VCF Automation | [ ] |
| 8 | 2. VCF Automation (coeur du cours) | [Nouveautés de VCF Automation](https://labs.hol.vmware.com/HOL/catalog/lab/27713) | HOL-2711-20-VCF-L | Débutant | Nouveautés de la version 9.1 | [ ] |
| 9 | 2. VCF Automation (coeur du cours) | [Gestion et administration côté fournisseur](https://labs.hol.vmware.com/HOL/catalog/lab/27695) | HOL-2711-22-VCF-L | Intermédiaire | Administration côté fournisseur : organisations, ressources, accès | [ ] |
| 10 | 2. VCF Automation (coeur du cours) | [Applications modernes et cloud native avec VCF Automation](https://labs.hol.vmware.com/HOL/catalog/lab/27672) | HOL-2711-24-VCF-L | Intermédiaire | Déploiement d'applications modernes en libre-service | [ ] |
| 11 | 3. Supervision et optimisation avec VCF Operations | [Prise en main et supervision de VCF Operations](https://labs.hol.vmware.com/HOL/catalog/lab/27715) | HOL-2711-01-VCF-L | Débutant | Prise en main de la supervision | [ ] |
| 12 | 3. Supervision et optimisation avec VCF Operations | [Dépannage du cloud privé, journaux, métriques et flux réseau](https://labs.hol.vmware.com/HOL/catalog/lab/27679) | HOL-2711-02-VCF-L | Intermédiaire | Dépannage par les journaux, métriques et flux | [ ] |
| 13 | 3. Supervision et optimisation avec VCF Operations | [Santé et diagnostics de l'infrastructure](https://labs.hol.vmware.com/HOL/catalog/lab/27635) | HOL-2711-03-VCF-L | Intermédiaire | Santé et diagnostics de l'infrastructure | [ ] |
| 14 | 3. Supervision et optimisation avec VCF Operations | [Tableaux de bord, vues et rapports](https://labs.hol.vmware.com/HOL/catalog/lab/27685) | HOL-2711-12-VCF-L | Intermédiaire | Tableaux de bord et rapports | [ ] |
| 15 | 3. Supervision et optimisation avec VCF Operations | [Optimisation de la capacité et Green Score](https://labs.hol.vmware.com/HOL/catalog/lab/27699) | HOL-2711-08-VCF-L | Intermédiaire | Capacité et efficacité énergétique | [ ] |
| 16 | 3. Supervision et optimisation avec VCF Operations | [Optimisation des coûts, showback et chargeback](https://labs.hol.vmware.com/HOL/catalog/lab/27700) | HOL-2711-09-VCF-L | Intermédiaire | Gestion des coûts, showback et chargeback | [ ] |
| 17 | 4. Sécurité et équilibrage de charge | [Parcours sécurité du pare-feu vDefend](https://labs.hol.vmware.com/HOL/catalog/lab/27651) | HOL-2770-01-ANS-L | Débutant | Parcours sécurité du pare-feu vDefend | [ ] |
| 18 | 4. Sécurité et équilibrage de charge | [Pare-feu distribué vDefend : prise en main et sécurité avancée](https://labs.hol.vmware.com/HOL/catalog/lab/27652) | HOL-2770-03-ANS-L | Intermédiaire | Pare-feu distribué et micro-segmentation | [ ] |
| 19 | 4. Sécurité et équilibrage de charge | [Pare-feu vDefend avec protection avancée contre les menaces](https://labs.hol.vmware.com/HOL/catalog/lab/27638) | HOL-2770-02-ANS-L | Avancé | Protection avancée contre les menaces | [ ] |
| 20 | 4. Sécurité et équilibrage de charge | [Prise en main de l'équilibrage de charge Avi](https://labs.hol.vmware.com/HOL/catalog/lab/27678) | HOL-2740-02-ANS-L | Débutant | Bases de l'équilibrage de charge Avi | [ ] |
| 21 | 4. Sécurité et équilibrage de charge | [Équilibrage de charge des applications VCF avec Avi](https://labs.hol.vmware.com/HOL/catalog/lab/27697) | HOL-2740-01-ANS-L | Intermédiaire | Équilibrage de charge des applications VCF | [ ] |
| 22 | 4. Sécurité et équilibrage de charge | [Migration d'un équilibrage de charge existant avec l'outil de conversion Avi](https://labs.hol.vmware.com/HOL/catalog/lab/27689) | HOL-2740-05-ANS-L | Avancé | Migration d'un équilibrage de charge existant | [ ] |
| 23 | 5. Résilience et protection des données | [Réplication vSphere améliorée](https://labs.hol.vmware.com/HOL/catalog/lab/27675) | HOL-2734-02-VCF-S | Intermédiaire | Réplication des machines virtuelles | [ ] |
| 24 | 5. Résilience et protection des données | [VMware Live Recovery : reprise après sinistre](https://labs.hol.vmware.com/HOL/catalog/lab/27709) | HOL-2734-03-VCF-L | Intermédiaire | Reprise après sinistre | [ ] |
| 25 | 5. Résilience et protection des données | [VMware Live Recovery : reprise après ransomware](https://labs.hol.vmware.com/HOL/catalog/lab/27710) | HOL-2734-04-VCF-S | Avancé | Reprise après ransomware | [ ] |
| 26 | 6. Performance | [Introduction à la performance vSphere et sous-systèmes ESXi](https://labs.hol.vmware.com/HOL/catalog/lab/27694) | HOL-2704-03-VCF-L | Intermédiaire | Indicateurs de performance et sous-systèmes ESXi | [ ] |
| 27 | 6. Performance | [Performance des charges de travail avec VMmark](https://labs.hol.vmware.com/HOL/catalog/lab/27693) | HOL-2704-04-VCF-L | Avancé | Mesure de performance avec VMmark | [ ] |
| 28 | 7. Sujets avancés, migration et services | [Mise à niveau depuis vSphere 8](https://labs.hol.vmware.com/HOL/catalog/lab/27706) | HOL-2704-05-VCF-S | Intermédiaire | Mise à niveau depuis vSphere 8 | [ ] |
| 29 | 7. Sujets avancés, migration et services | [Opérations avancées et outils VCF](https://labs.hol.vmware.com/HOL/catalog/lab/27704) | HOL-2704-06-VCF-L | Avancé | Opérations avancées et outils | [ ] |
| 30 | 7. Sujets avancés, migration et services | [HCX : prise en main, planification et migration avancée](https://labs.hol.vmware.com/HOL/catalog/lab/27707) | HOL-2705-03-VCF-L | Intermédiaire | Migration de charges avec HCX | [ ] |
| 31 | 7. Sujets avancés, migration et services | [VMware Data Services Manager : prise en main](https://labs.hol.vmware.com/HOL/catalog/lab/27671) | HOL-2705-04-VCF-L | Intermédiaire | Bases de données en libre-service | [ ] |
| 32 | 7. Sujets avancés, migration et services | [VMware Private AI Foundation avec NVIDIA : prise en main](https://labs.hol.vmware.com/HOL/catalog/lab/27644) | HOL-2705-12-VCF-L | Avancé | IA privée avec NVIDIA | [ ] |

## Présentation

Le catalogue VCF 9.1 met à jour l'ensemble des labs du catalogue précédent. Plusieurs labs ont été regroupés afin d'offrir des parcours plus complets et moins redondants. Les labs s'adressent aux administrateurs, architectes et ingénieurs plateforme qui souhaitent découvrir ou approfondir le modèle d'exploitation unifié du cloud privé VMware.

### Public concerné

Ces labs sont destinés en priorité aux étudiants de E5 CCSN, dans le cadre du cours Virtual Data Center Automation (VCF Automation). Ils sont également ouverts à toutes les personnes intéressées par VMware Cloud Foundation, quel que soit leur niveau, qui souhaitent se former ou approfondir leurs connaissances de manière pratique et gratuite.

## Comment accéder aux labs

1. Créer ou utiliser un compte Hands-on Labs (gratuit).
2. Ouvrir le catalogue VCF 9.1 : https://labs.hol.vmware.com/HOL/catalog?search=HOL-27
3. Rechercher le lab par sa référence ou par son thème, puis cliquer sur « Lancer ».
4. L'environnement est provisionné et accessible directement dans le navigateur.

Chaque fiche et le tableau récapitulatif donnent le lien direct vers le lab dans le catalogue.

## Prérequis et préparation

Avant de lancer votre premier lab, prenez quelques minutes pour préparer votre environnement de travail.

### Créer son compte Hands-on Labs

Un compte est nécessaire pour lancer les labs. Pour vous aider dans la création et la configuration de votre compte, consultez la fiche d'aide publiée par l'équipe Hands-on Labs : [guide de création de compte HOL](https://ent.box.com/s/ftdwoeoeahdejb5iv0ymjxxc2dbumjqd).

### Matériel et navigateur

- Utilisez un navigateur récent et à jour (Chrome, Edge ou Firefox, par exemple).
- Privilégiez un ordinateur avec un écran de taille confortable : les labs affichent à la fois un manuel et une console, ce qui demande de la place.
- Désactivez les extensions qui peuvent gêner l'affichage ou bloquer des fenêtres (bloqueurs de publicité, par exemple) si vous rencontrez des problèmes.

### Connexion

- Utilisez une connexion internet stable, de préférence filaire ou en Wi-Fi de bonne qualité.
- Évitez les réseaux restrictifs qui filtrent certains flux. Si le lab ne s'affiche pas depuis le réseau de votre établissement, essayez depuis un autre réseau.

### Temps à prévoir

- Chaque lab dispose d'une durée de session limitée, indiquée au lancement. Consultez la fiche du lab dans le catalogue pour connaître sa durée estimée avant de démarrer.
- Réservez une plage de temps sans interruption, avec une marge supplémentaire pour la prise en main de l'environnement.
- Les labs au format court (suffixe « S ») demandent généralement moins de temps que les labs complets (suffixe « L »).

## Conseils pour réussir un lab

1. **Lire le manuel en entier avant de lancer l'environnement.** Cela permet de comprendre l'objectif, les étapes et les points délicats, et d'éviter de consommer le temps de session à découvrir les consignes.
2. **Prendre des notes et des captures d'écran.** Notez les paramètres utilisés, les commandes exécutées et les résultats obtenus. Ces éléments sont précieux pour réviser et pour rédiger un éventuel compte rendu.
3. **Ne pas perdre le temps de session.** Préparez vos notes et vos questions à l'avance, évitez de laisser l'environnement ouvert sans l'utiliser et suivez les étapes dans l'ordre indiqué par le manuel.
4. **Relancer le lab en cas de blocage.** Si une étape échoue de manière répétée ou si l'environnement se comporte de façon anormale, terminez la session et lancez-en une nouvelle plutôt que de perdre du temps à insister.
5. **Avancer étape par étape.** Vérifiez le résultat de chaque étape avant de passer à la suivante : une erreur non détectée peut bloquer la suite.
6. **Respecter l'ordre de suivi recommandé.** Les premiers labs apportent les notions utiles pour les suivants.

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
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27715

### Dépannage du cloud privé, journaux, métriques et flux réseau

- **Référence** : HOL-2711-02-VCF-L
- **Description** : Lab consacré au diagnostic et à la résolution d'incidents. Il couvre l'analyse des journaux, des métriques et des flux réseau, ainsi que la corrélation entre ces sources pour identifier la cause d'un problème.
- **Objectif** : Apprendre à localiser rapidement l'origine d'un incident et à réduire le temps de résolution grâce aux outils d'analyse de VCF Operations.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27679

### Santé et diagnostics de l'infrastructure

- **Référence** : HOL-2711-03-VCF-L
- **Description** : Lab centré sur le suivi de la santé de l'infrastructure du cloud privé et sur les outils de diagnostic associés : alertes, recommandations et vérifications de l'état des composants.
- **Objectif** : Savoir anticiper les dégradations, interpréter les alertes et maintenir un niveau de service stable.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27635

### Tableaux de bord, vues et rapports

- **Référence** : HOL-2711-12-VCF-L
- **Description** : Lab de création de visualisations personnalisées dans VCF Operations : tableaux de bord, vues et rapports adaptés aux besoins des équipes d'exploitation et de la direction.
- **Objectif** : Maîtriser la construction de tableaux de bord et de rapports exploitables pour suivre l'activité du cloud privé et en rendre compte.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27685

### Optimisation de la capacité et Green Score

- **Référence** : HOL-2711-08-VCF-L
- **Description** : Lab sur la planification de capacité et l'optimisation des ressources, incluant le suivi de l'indicateur Green Score lié à l'efficacité énergétique de l'infrastructure.
- **Objectif** : Dimensionner correctement l'infrastructure, identifier les ressources sous-utilisées ou surdimensionnées et réduire l'impact énergétique.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27699

### Optimisation des coûts, showback et chargeback

- **Référence** : HOL-2711-09-VCF-L
- **Description** : Lab consacré à la gestion financière du cloud privé : calcul des coûts, refacturation interne (chargeback) et affichage des coûts aux équipes consommatrices (showback).
- **Objectif** : Mettre en place la transparence des coûts et responsabiliser les équipes sur leur consommation de ressources.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27700

---

## VCF Automation : libre-service et applications

### Nouveautés de VCF Automation

- **Référence** : HOL-2711-20-VCF-L
- **Description** : Lab de découverte des nouvelles fonctions d'automatisation introduites avec VCF 9.1, en particulier le libre-service et la gouvernance des environnements.
- **Objectif** : Comprendre les évolutions d'automatisation de la version 9.1 et leur apport pour les équipes plateforme et les consommateurs.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27713

### Prise en main de VCF Automation

- **Référence** : HOL-2711-21-VCF-L
- **Description** : Lab d'introduction à VCF Automation : navigation dans l'interface, concepts clés et premiers déploiements de ressources.
- **Objectif** : Prendre en main la solution et comprendre le modèle de consommation du cloud privé en libre-service.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27677

### Gestion et administration côté fournisseur

- **Référence** : HOL-2711-22-VCF-L
- **Description** : Lab destiné aux administrateurs du fournisseur de service : configuration de la plateforme, gestion des organisations, des ressources et des accès.
- **Objectif** : Savoir administrer VCF Automation en tant que fournisseur et préparer l'environnement pour les différentes équipes.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27695

### Applications modernes et cloud native avec VCF Automation

- **Référence** : HOL-2711-24-VCF-L
- **Description** : Lab de construction et de déploiement d'applications modernes à l'aide des organisations de VCF Automation. Il regroupe les anciens labs sur la création d'applications modernes et le déploiement d'applications cloud native.
- **Objectif** : Déployer des applications cloud native sur le cloud privé et valoriser le modèle de libre-service pour les équipes de développement.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27672

---

## Plateforme VCF : cycle de vie, réseau et performance

### Maintenir son cloud privé, nouveautés plateforme et authentification unique

- **Référence** : HOL-2704-01-VCF-L
- **Description** : Lab central sur la plateforme VCF : opérations de maintenance et de cycle de vie, nouveautés de la plateforme et configuration de l'authentification unique (SSO).
- **Objectif** : Connaître les opérations d'exploitation courantes de la plateforme et savoir centraliser l'authentification des utilisateurs.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27687

### Réseau VCF avec NSX et VPC

- **Référence** : HOL-2704-02-VCF-L
- **Description** : Lab sur la mise en réseau du cloud privé avec NSX et les VPC (Virtual Private Cloud). Il couvre le réseau applicatif simplifié, la résilience réseau et le multi-tenant.
- **Objectif** : Concevoir et exploiter un réseau souple, résilient et adapté aux environnements multi-locataires.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27667

### Introduction à la performance vSphere et sous-systèmes ESXi

- **Référence** : HOL-2704-03-VCF-L
- **Description** : Lab d'initiation à la performance dans VCF : compréhension des indicateurs et tests des sous-systèmes d'un hôte ESXi (processeur, mémoire, disque et réseau).
- **Objectif** : Apprendre à mesurer, interpréter et diagnostiquer la performance de l'infrastructure de virtualisation.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27694

### Performance des charges de travail avec VMmark

- **Référence** : HOL-2704-04-VCF-L
- **Description** : Lab d'évaluation de la performance à l'aide de VMmark, un banc d'essai conçu pour mesurer le comportement de charges de travail virtualisées.
- **Objectif** : Savoir exécuter et analyser un test de performance représentatif pour valider un dimensionnement.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27693

### Mise à niveau depuis vSphere 8

- **Référence** : HOL-2704-05-VCF-S
- **Description** : Lab court consacré au parcours de mise à niveau d'un environnement vSphere 8 vers VMware Cloud Foundation.
- **Objectif** : Comprendre les étapes, les prérequis et les points d'attention d'une migration vers VCF.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27706

### Opérations avancées et outils VCF

- **Référence** : HOL-2704-06-VCF-L
- **Description** : Lab destiné aux utilisateurs expérimentés, présentant les outils et opérations avancés de la plateforme.
- **Objectif** : Approfondir l'exploitation de VCF et gagner en autonomie sur les tâches complexes d'administration.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27704

### Gestion unifiée des machines virtuelles et de Kubernetes avec vSphere Supervisor

- **Référence** : HOL-2704-07-VCF-L
- **Description** : Lab montrant comment gérer à la fois des machines virtuelles et des conteneurs Kubernetes sur une même plateforme grâce à vSphere Supervisor.
- **Objectif** : Unifier l'exploitation des charges de travail traditionnelles et conteneurisées.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27680

---

## vSphere dans VCF

### Nouveautés de vSphere dans VCF

- **Référence** : HOL-2706-01-VCF-L
- **Description** : Lab présentant les nouvelles fonctions de vSphere au sein de VMware Cloud Foundation.
- **Objectif** : Identifier les évolutions utiles à votre environnement et planifier leur adoption.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27714

### vSphere : sujets avancés et automatisation avec PowerCLI

- **Référence** : HOL-2706-02-VCF-L
- **Description** : Lab d'approfondissement sur des sujets avancés de vSphere, incluant l'automatisation des tâches d'administration avec PowerCLI.
- **Objectif** : Maîtriser des fonctions avancées et automatiser les opérations répétitives par script.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27670

---

## Stockage, résilience et protection des données

### vSAN et NVMe Memory Tiering

- **Référence** : HOL-2734-01-VCF-L
- **Description** : Lab couvrant VMware vSAN, de la prise en main aux sujets avancés, ainsi que la configuration de bout en bout du Memory Tiering NVMe.
- **Objectif** : Maîtriser le stockage défini par logiciel et optimiser l'usage de la mémoire pour augmenter la densité de machines virtuelles.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27712

### Réplication vSphere améliorée

- **Référence** : HOL-2734-02-VCF-S
- **Description** : Lab court sur la réplication vSphere améliorée, destiné à protéger les machines virtuelles en les répliquant vers un autre site.
- **Objectif** : Configurer la réplication et comprendre ses paramètres et ses objectifs de point de reprise.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27675

### VMware Live Recovery : reprise après sinistre

- **Référence** : HOL-2734-03-VCF-L
- **Description** : Lab illustrant un scénario de reprise après sinistre avec VMware Live Recovery : planification, orchestration et bascule.
- **Objectif** : Construire et tester un plan de reprise d'activité pour assurer la continuité de service.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27709

### VMware Live Recovery : reprise après ransomware

- **Référence** : HOL-2734-04-VCF-S
- **Description** : Lab court portant sur la récupération après une attaque par ransomware, avec restauration vers un environnement sain.
- **Objectif** : Savoir restaurer des charges de travail de manière sûre après une cyberattaque.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27710

---

## Mobilité, services de données et IA privée

### VMware Cloud Foundation Operations HCX : prise en main, planification et migration avancée

- **Référence** : HOL-2705-03-VCF-L
- **Description** : Lab consacré à HCX pour la planification et la réalisation de migrations de charges de travail, des premiers pas aux scénarios avancés.
- **Objectif** : Planifier et exécuter des migrations vers ou entre environnements avec un minimum d'interruption.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27707

### VMware Data Services Manager : prise en main

- **Référence** : HOL-2705-04-VCF-L
- **Description** : Lab d'introduction à Data Services Manager pour provisionner et gérer des bases de données en libre-service sur le cloud privé.
- **Objectif** : Offrir des services de données gérés, standardisés et rapides à déployer.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27671

### VMware Private AI Foundation avec NVIDIA : prise en main

- **Référence** : HOL-2705-12-VCF-L
- **Description** : Lab de découverte de VMware Private AI Foundation avec NVIDIA, pour exécuter des charges d'intelligence artificielle sur une infrastructure privée.
- **Objectif** : Comprendre comment déployer des charges d'IA tout en conservant la maîtrise des données et de l'infrastructure.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27644

---

## Sécurité avec vDefend

### Parcours sécurité du pare-feu vDefend

- **Référence** : HOL-2770-01-ANS-L
- **Description** : Lab présentant le parcours de sécurisation d'un environnement avec le pare-feu vDefend, de la visibilité à l'application des politiques.
- **Objectif** : Comprendre la démarche progressive de mise en place de la segmentation et de la sécurité réseau.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27651

### Pare-feu vDefend avec protection avancée contre les menaces

- **Référence** : HOL-2770-02-ANS-L
- **Description** : Lab sur la détection et la prévention des menaces avancées en complément du pare-feu vDefend.
- **Objectif** : Renforcer la posture de sécurité en identifiant et en bloquant les comportements malveillants.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27638

### Pare-feu distribué vDefend : prise en main et sécurité avancée

- **Référence** : HOL-2770-03-ANS-L
- **Description** : Lab couvrant le pare-feu distribué vDefend, depuis la prise en main jusqu'aux fonctions de sécurité avancées.
- **Objectif** : Mettre en œuvre la micro-segmentation et appliquer des politiques de sécurité au plus près des charges de travail.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27652

---

## Équilibrage de charge avec Avi

### Équilibrage de charge des applications VCF avec Avi

- **Référence** : HOL-2740-01-ANS-L
- **Description** : Lab sur l'utilisation d'Avi Load Balancer pour répartir le trafic des applications déployées sur VMware Cloud Foundation.
- **Objectif** : Garantir la disponibilité et les performances des applications grâce à un équilibrage de charge adapté.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27697

### Prise en main de l'équilibrage de charge Avi

- **Référence** : HOL-2740-02-ANS-L
- **Description** : Lab d'introduction aux concepts et à la configuration de base d'Avi Application Load Balancing.
- **Objectif** : Créer ses premiers services virtuels et comprendre l'architecture d'Avi.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27678

### Migration d'un équilibrage de charge existant avec l'outil de conversion Avi

- **Référence** : HOL-2740-05-ANS-L
- **Description** : Lab consacré à la migration de configurations d'équilibrage de charge héritées vers Avi à l'aide de l'outil de conversion.
- **Objectif** : Moderniser un équilibrage de charge existant en limitant les erreurs et le travail manuel.
- **Lien** : https://labs.hol.vmware.com/HOL/catalog/lab/27689

---

## Évolutions par rapport à la version précédente

- Plusieurs labs de la version précédente ont été regroupés dans un même lab VCF 9.1, notamment pour VCF Operations, le réseau NSX et les performances vSphere.
- Un lab a été retiré sans remplaçant : « Gestion des organisations pour toutes les applications avec VCF Automation ».
- Les labs portant le suffixe « S » sont des formats courts, ceux portant le suffixe « L » sont des labs complets.

## Ressources

- Catalogue VCF 9.1 : https://labs.hol.vmware.com/HOL/catalog?search=HOL-27
- Annonce et correspondance entre les labs VCF 9.0 et VCF 9.1 : https://blogs.vmware.com/cloud-foundation/2026/09/21/the-next-generation-of-hands-on-labs/
- Blog VMware Cloud Foundation : https://blogs.vmware.com/cloud-foundation/
