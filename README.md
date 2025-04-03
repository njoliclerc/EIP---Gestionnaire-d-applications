# Plateforme de Formation - Gestionnaire d'Application Mainframe

## 🧭 Introduction

Bienvenue sur cette plateforme de formation dédiée aux consultants intervenant sur des environnements **mainframe** dans le cadre de missions d’**exploitation** ou de **gestion d’applications** (GA).  
Avant de plonger dans les outils et technologies, il est essentiel de comprendre **le contexte**, **les enjeux métiers**, et **les spécificités techniques** liés à ce type d’environnement. Cette section répond aux principales questions que vous devez maîtriser pour prendre de la hauteur dès le début de votre mission. 

Tout d'abord, une petite vidéo de deux minutes sur la question suivante : pourquoi les entreprises utilisent aujourd'hui le grand système, autrement appelé "Mainframe" pour faire tourner leurs applications ? 

- https://www.youtube.com/watch?v=T2ZHRW1a5hk
- https://www.youtube.com/watch?v=rR-ixE5xxJc

---

## ❓ C’est quoi une infrastructure informatique ?

- https://blog.pleo.io/fr/infrastructure-informatique#section-5 

## ❓ C’est quoi l’exploitation ?

L’**exploitation** regroupe toutes les activités de **gestion quotidienne** du système d’information : lancement des traitements batch, supervision, remontée d’alertes, gestion des incidents, interventions planifiées, automatisation, etc.  
Son objectif est d’**assurer la disponibilité, la performance et la fiabilité** des applications utilisées en production. Quelques notions de bases : 

Qu'est ce qu'un système d'exploitation, autrement appelé OS (operating system) ?
- https://www.youtube.com/watch?v=AcZ87MTiXr4

---

## ❓ C’est quoi la production ?

La **production** est l’environnement **réel et actif** où s’exécutent les applications utilisées par les utilisateurs finaux (équipes métiers ou clients).  
C’est un environnement **critique**, où chaque action a des conséquences directes. Toute modification y est donc encadrée, validée et traçable.

Un ingénieur de production informatique joue un rôle essentiel dans la gestion et le bon fonctionnement des systèmes informatiques au sein d’une organisation. Leur travail consiste à garantir la disponibilité, la performance et la fiabilité des systèmes informatiques. Cela implique la surveillance constante, la gestion des pannes, et la mise en place de solutions pour optimiser les performances.

---

## ❓ Mais alors quelle est la différence entre l'exploitation et la production ?

La production informatique regroupe l'ensemble des méthodes et compétences nécessaires pour maintenir une infrastructure opérationnelle, son but est de garantir que l'infrastructure pourra supporter toutes les opérations d'exploitation.
A l'inverse, l'exploitation informatique consiste à exploiter, à utiliser cette infrastructure matérielle ou logicielle - à travers des applications typiquement - et de manière à répondre aux besoins des utilisateurs finaux (création de compte de messagerie par exemple).

---

## ❓ Pourquoi ces technologies (z/OS, JCL, DB2, etc.) ?

Les technologies **mainframe** sont utilisées car elles offrent une **fiabilité, une performance et une robustesse** inégalées pour les traitements de masse.  
Elles sont au cœur des systèmes critiques de grandes entreprises (banque, assurance, énergie, etc.), avec des outils comme **z/OS** (OS IBM), **JCL** (langage de lancement de job), **TWS** (ordonnancement), **IMS/DB2** (bases de données), etc.

---
## ❓ Explication des différents environnements 

Focus sur les deux environnement qui nous intéressent : l'environnement de pré-production et l'environnement de production. 

### ❓ C'est quoi un environnement de préproduction ?

La **préproduction** est une **copie quasi-identique de la production**, utilisée pour **tester les évolutions**, les correctifs ou les nouvelles mises en production.  
Elle permet de sécuriser les changements avant leur bascule en prod.

### ❓ C’est quoi un environnement de production ?

Il s’agit de l’environnement dans lequel tournent les **versions validées des applications**, utilisées au quotidien.  
Il est soumis à des exigences fortes de **continuité de service**, de **sécurité** et de **suivi opérationnel**.

![image](https://github.com/user-attachments/assets/151b0247-2aff-42c2-a31b-4efadafae8db)

---

## ❓ Et maintement, c’est quoi le métier de GA (Gestionnaire d’Application) ?

Le Gestionnaire d’Application (GA) est responsable du bon fonctionnement des applications en environnement de production. Son rôle est à la fois **technique**, **opérationnel** et **transverse**. Ses principales missions incluent :

📌 *N'hésite pas à cliquer sur les mots en gras pour en savoir plus sur leurs définitions*

- **Intégrer les traitements** dans les outils de [**supervision**](https://www.les-innovations-pour-toi.com/actu/5/que-savoir-sur-la-supervision-informatique), de [**plannification**](https://www.weodeo.com/blog-maintenance-informatique/ordonnancement-informatique-principes-techniques-et-applications) et [**d’ordonnancement**](https://www.weodeo.com/blog-maintenance-informatique/ordonnancement-informatique-principes-techniques-et-applications)
- **Effectuer les livraisons** en environnement de [**recette**] Cf.[Explication des différents environnements](, puis en **production** (MEP – mise en production)
- **Rédiger la documentation** liée au fonctionnement des applications (**procédures d’exploitation**)
- **Assurer la supervision** des applications et faire le lien avec les **équipes métiers** (**coordination technique**)
- **Traiter les incidents** jusqu’à leur **résolution complète** (support **niveau 3**) et réaliser les **interventions techniques** nécessaires
- **Optimiser, fiabiliser, automatiser et sécuriser** les traitements existants ainsi que leurs **performances**

---

📌 Vous pouvez maintenant parcourir les différentes pratiques et technologies pour vous préparer au poste de Gestionnaire d'Application dans un environnement mainframe.

---


## Introduction  

Cette plateforme de formation est dédiée aux **gestionnaires d'application** travaillant dans un environnement **mainframe**. L'objectif est de fournir une **série de ressources**, y compris des **liens vers des documentations**, des **vidéos**, et des **tutoriels** pour vous aider à comprendre et à maîtriser les principaux outils et concepts utilisés dans cet environnement technique. 

Les ressources sont organisées par catégories afin de faciliter la navigation. Chaque section vous guidera vers des **documents techniques** ainsi que des **vidéos explicatives** pour approfondir vos connaissances sur des sujets clés comme le **z/OS**, **MVS**, **JCL**, **IMS**, **DB2**, et bien d'autres.

---

## Prérequis: Scripting Unix et Windows sur Mainframe - Raphaël

### Le Scripting sous Unix et Windows

Le **scripting** sous Unix et Windows est également une compétence clé. Le scripting permet d'automatiser des tâches et de gérer les fichiers dans un environnement mainframe.

- [Introduction au Scripting Unix sous z/OS](https://www.ibm.com/docs/en/zos/2.5.0?topic=zos-unix-system-services)  
  La documentation pour vous initier au scripting Unix dans un environnement mainframe.

- [Documentation sur PowerShell et scripts DOS pour mainframe](https://docs.microsoft.com/en-us/powershell/)  
  Des ressources pour utiliser PowerShell et DOS dans un environnement mainframe.

- [Liste de commandes utilisables sur l'éditeur VIM](https://www.linuxtrainingacademy.com/vim-cheat-sheet/)  
  Cheat sheet des commandes utilisables sur l'éditeur VIM, un des éditeurs les plus utilisés pour le scripting Unix.

- [Liste de commandes utilisables sous Linux](https://www.linuxtrainingacademy.com/linux-commands-cheat-sheet/)  
  Cheat sheet des commandes utilisables sous Linux.

- [Vidéo: Cours sur le scripting Bash](https://www.youtube.com/watch?v=e7BufAVwDiM)  
  Cette vidéo explique comment utiliser les scripts Bash.

- [Vidéo: Cours sur le scripting Powershell](https://www.youtube.com/watch?v=ZOoCaWyifmI)  
  Cette vidéo explique comment utiliser les scripts Bash.  

- [Cours d'introduction aux commandes Linux et Scripting : Openclassroom](https://openclassrooms.com/fr/courses/7274161-administrez-un-systeme-linux/7529306-initiez-vous-au-shell-linterpreteur-de-commandes)  
  Cours + Exercices sur divers sujets autour de Linux / Scripting : OpenClassRoom.

- [Cours d'instroduction administration Linux : Openclassroom](https://openclassrooms.com/fr/courses/7274161-administrez-un-systeme-)
  Cours + exercice orientés Administration système Linux

---

Ces près-requis sont nécessaires pour bien appréhender un environnement mainframe, à ne pas négliger. 

## FORMATION : ressources z/OS - Raphaël

### Qu'est-ce que z/OS ?

z/OS est un système d'exploitation puissant et central pour les environnements mainframe. Il gère les ressources matérielles et logicielles, et permet le traitement de données à grande échelle.

- [Documentation détaillée sur z/OS](https://www.ibm.com/docs/en/zos/2.5.0)    
  Accédez à la documentation complète d'IBM sur z/OS pour une compréhension approfondie du système d'exploitation.

- [Vidéo d'introduction à z/OS](https://www.youtube.com/watch?v=7-9cOM5fpQ0)  
  Une vidéo introductive qui présente les bases de z/OS et ses fonctionnalités essentielles pour les gestionnaires d'applications.
  
- [Utilisation d'IBM Developer pour z/OS](https://www.ibm.com/docs/fr/adffz5/developer-for-zos/15.0)   
  Accédez à la documentation complète d'IBM sur z/OS pour une compréhension approfondie de l'ensemble d'outil IBM Developer.
---

## Ressources pour MVS et Gestion des Ressources - AURELIEN

### MVS : Multiple Virtual Storage

**MVS (Multiple Virtual Storage)** est un sous-système de Z/OS, utilisé principalement sur les grands ordinateurs (mainframes), qui permet de gérer efficacement les ressources matérielles et logicielles de manière virtuelle. Il a été développé par IBM et est une partie centrale de l’architecture des systèmes mainframe. MVS a été conçu pour exécuter de multiples applications simultanément tout en maximisant l’utilisation des ressources du système, telles que la mémoire et les processeurs.
L'un des concepts clés de MVS est la gestion de la mémoire virtuelle, ce qui permet à chaque programme d'avoir l'impression d’avoir accès à toute la mémoire de l'ordinateur, même si la mémoire physique est limitée. Cela améliore l'efficacité, la flexibilité et la gestion des ressources.

**Principales caractéristiques de MVS :**

**1. Virtualisation de la mémoire :** Chaque utilisateur ou programme a une vue séparée de la mémoire, ce qui permet une gestion plus souple et un meilleur isolement des processus.

**2. Multiprogrammation et multitâche :** MVS permet l'exécution simultanée de plusieurs applications, ce qui améliore l'efficacité des ressources.

**3. Systèmes de fichiers :** MVS utilise des systèmes de fichiers complexes qui permettent d’organiser et de stocker les données de manière fiable.

**4. Système de gestion des tâches :** Il offre un gestionnaire de tâches très performant qui permet de planifier et d'exécuter des programmes de manière ordonnée.

- [Cours (Vidéo)](https://www.youtube.com/watch?v=TRwXKWQ2i00)

- [Cours / TP (Vidéo)](https://www.youtube.com/watch?v=YA3FQOzr0ag)

- Pour aller plus loin: [Documentation MVS d'IBM](https://www.ibm.com/docs/en/zos/2.4.0)

---

## Accès aux Données : VSAM, Séquentielle, Partitionnée - Raphaël

### Accès aux données sur z/OS

Les méthodes d'accès aux données telles que **VSAM** et l'accès **séquentiel** sont au cœur des systèmes mainframe. Comprendre comment elles fonctionnent est essentiel pour gérer les données de manière efficace.

- [Introduction à VSAM](https://www.ibm.com/docs/en/zos/2.4.0?topic=vsam)  
  Un guide sur VSAM (Virtual Storage Access Method), une méthode d'accès aux fichiers fréquemment utilisée sur z/OS.

- [Accès séquentiel aux fichiers sur z/OS](https://www.ibm.com/docs/en/zos/2.4.0?topic=sequential)  
  La méthode d'accès séquentiel et comment elle est utilisée pour les fichiers sur z/OS.

- [Vidéo : Accès aux données avec VSAM sur z/OS](https://www.youtube.com/watch?v=0xtfPzIn0Bc)  
  Une vidéo expliquant le fonctionnement du système d'accès aux données VSAM.

---

## JCL : Job Control Language - AURELIEN

### Qu'est-ce que le JCL ?

Le **JCL (Job Control Language)** est un langage utilisé dans les environnements mainframe IBM pour gérer et exécuter des tâches (jobs). Il sert d’interface entre l’utilisateur et le système d’exploitation z/OS, permettant de soumettre, contrôler et organiser l’exécution de programmes et de traitements batch.

**Pourquoi le JCL est-il important ?**
Les mainframes sont utilisés par de nombreuses grandes entreprises (banques, assurances, industries) pour traiter d’énormes volumes de données. Le JCL permet d’automatiser ces traitements de manière efficace et sécurisée.

- [Vidéos introduction a JCL](https://www.youtube.com/watch?v=4eZODpPUy_g&list=PLYCbBREygUWR9eCUgHcP6jp_0AX_vBBoM)

- [Cours (Vidéos) de base](https://www.youtube.com/watch?v=pemN0qJrmzE&list=PLLcYGaQ7eeuTQGWRJ_B04qPowNWuHHfaz)

- [Cours de débutant à avancé](https://www.youtube.com/playlist?list=PL6HD6MMTq7le8nnKdLO2wz5KCvHI8yJfG)

- [Cours complet](https://www.ibmmainframer.com/jcl-tutorial/#main)

- [Exemples JCL](https://www.ibmmainframer.com/reference/jcl-example-sample-reference-code)

- [Commandes JCL](https://www.ibm.com/docs/en/zos/2.4.0?topic=statements-jcl)

- [Quizz JCL](https://www.ibmmainframer.com/mainframe/mainframe-quiz/jcl-quiz-mcq-online-test/)

Pour aller plus loin:
- [Documentation complète JCL](https://www.ibm.com/docs/en/zos/2.4.0?topic=mvs-zos-jcl-users-guide)
  
---

## Ordonnancement avec TWS (Tivoli Workload Scheduler) - AURELIEN

### Ordonnancement des tâches avec TWS

Le **Tivoli Workload Scheduler (TWS)**, développé par IBM, est une solution d'ordonnancement et d'automatisation des tâches qui permet de gérer efficacement les charges de travail au sein d'un environnement informatique. En automatisant les processus de production, TWS optimise l'exécution des tâches, réduit les interventions manuelles et améliore la fiabilité des opérations.

**Fonctionnalités principales de TWS :**

1- **Automatisation des tâches :** Planification et exécution automatiques des jobs en fonction de calendriers prédéfinis ou d'événements spécifiques.​

2- **Gestion des dépendances :** Coordination des tâches en tenant compte des interdépendances, garantissant ainsi une exécution séquentielle appropriée.​

3- **Surveillance et suivi :** Supervision en temps réel des tâches en cours, avec des capacités de suivi et de reporting pour assurer la transparence des opérations.​

4- **Flexibilité multiplateforme :** Compatibilité avec divers environnements, y compris z/OS, UNIX, Linux et Windows, facilitant l'intégration dans des infrastructures hétérogènes. ​

En résumé, TWS est un outil puissant pour les entreprises cherchant à automatiser et optimiser leurs processus de production informatique, contribuant ainsi à une meilleure efficacité opérationnelle.

- [Vidéo d'introduction à TWS](https://www.youtube.com/watch?v=mm9dpkDiPtA)

- [Guide d'utilisation en Français](https://tnit.fr/guide-dutilisation-dadministration-planificateur-charge-travail-tivoli-installation-faq)

- [Tutoriel d'IBM](https://www.ibm.com/docs/en/workload-automation/9.2.0?topic=tutorials-using-tivoli-workload-scheduler-tutorial-utility)

Pour aller plus loin: 
- [Documentation d'IBM](https://www.ibm.com/docs/en/workload-automation/9.2.0)

- [Guide utilisateur complet](https://github.com/njoliclerc/EIP---Gestionnaire-d-applications/blob/main/Guide%20d'utilisation%20complet%20TWS.pdf)

Ordonnanceur HAWz de HCL basé sur Mainframe:
- [Cours Ordonnanceur HCL (Vidéo)](https://www.youtube.com/watch?v=gA6uogw9yX0&list=PLZ87gBR2Z805Eyip2v0EUxSQjSZKTAkIB&index=2)

- [HAWz Commandes](https://help.hcl-software.com/workloadautomation/v101/zos/src_wapl/c_wapl_core_commands.html)
---

## Gestion des Traitements Batch et Transactionnels - AURELIEN

### Les Traitements Batch

Les systèmes mainframe z/OS sont conçus pour gérer efficacement des volumes massifs de **traitements batch et transactionnels**, essentiels pour les opérations critiques des grandes entreprises.​ Cela ce fait notamment avec l'ordonnanceur **TWS**.
- **Traitements Batch :** Ces processus exécutent des tâches en masse sans intervention humaine, telles que la mise à jour de bases de données ou la génération de rapports, généralement planifiées à des moments spécifiques pour optimiser l'utilisation des ressources. ​
- **Traitements Transactionnels :** Ces processus gèrent des opérations en temps réel, comme les transactions bancaires en ligne, en assurant la cohérence et la fiabilité des données. Sur z/OS, des sous-systèmes tels que CICS (Customer Information Control System) fournissent un environnement robuste pour le traitement transactionnel. 

- [Introduction au Batch](https://www.youtube.com/watch?v=WlZbN_vs7us)
	
- [Tutoriel d'un outils de Transactions](https://www.mainframestechhelp.com/tutorials/cics/)

---

## Bases de Données IMS et DB2 - Raphaël

### Bases de Données IMS et DB2

Les bases de données **IMS** et **DB2** sont essentielles pour la gestion des données sur un mainframe. Vous trouverez ici des ressources pour comprendre leur structure et leur utilisation.

- - https://www.youtube.com/watch?v=bPeeq2ZvEZk 

- [Guide d'installation IMS & DB2](https://www.youtube.com/watch?v=4hMGzhIQS7k)  
  Tutoriel d'installation IMS et DB2 sur Windows.

- [Documentation sur IMS (Information Management System)](https://www.ibm.com/docs/en/ims)  
  Un guide complet sur le système de gestion de bases de données IMS.

- [Guide DB2 sous z/OS](https://www.ibm.com/docs/en/db2/12.1)  
  La documentation sur DB2, un des systèmes de bases de données relationnelles les plus utilisés sur mainframe.

- [Vidéo : Utilisation de DB2 avec SQL dans un environnement Mainframe](https://www.youtube.com/watch?v=5Vgzm2Wz8g4)  
  Cette vidéo montre comment utiliser DB2 avec SQL dans un environnement mainframe.

---


