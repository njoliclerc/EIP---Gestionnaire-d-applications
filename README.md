# Plateforme de Formation - Gestionnaire d'Application Mainframe

## 🧭 Introduction

Hello 

Bienvenue sur cette plateforme de formation dédiée aux consultants intervenant sur des environnements **mainframe** dans le cadre de missions d’**exploitation** ou de **gestion d’applications** (GA).  
Avant de plonger dans les outils et technologies, il est essentiel de comprendre **le contexte**, **les enjeux métiers**, et **les spécificités techniques** liés à ce type d’environnement. Cette section répond aux principales questions que vous devez maîtriser pour prendre de la hauteur dès le début de votre mission.

---

### ❓ C’est quoi l’exploitation ?

L’**exploitation** regroupe toutes les activités de **gestion quotidienne** du système d’information : lancement des traitements batch, supervision, remontée d’alertes, gestion des incidents, interventions planifiées, automatisation, etc.  
Son objectif est d’**assurer la disponibilité, la performance et la fiabilité** des applications utilisées en production.

---

### ❓ C’est quoi la production ?

La **production** est l’environnement **réel et actif** où s’exécutent les applications utilisées par les utilisateurs finaux (équipes métiers ou clients).  
C’est un environnement **critique**, où chaque action a des conséquences directes. Toute modification y est donc encadrée, validée et traçable.

---

### ❓ Pourquoi ces technologies (z/OS, JCL, DB2, etc.) ?

Les technologies **mainframe** sont utilisées car elles offrent une **fiabilité, une performance et une robustesse** inégalées pour les traitements de masse.  
Elles sont au cœur des systèmes critiques de grandes entreprises (banque, assurance, énergie, etc.), avec des outils comme **z/OS** (OS IBM), **JCL** (langage de lancement de job), **TWS** (ordonnancement), **IMS/DB2** (bases de données), etc.

---

### ❓ C’est quoi un environnement de production ?

Il s’agit de l’environnement dans lequel tournent les **versions validées des applications**, utilisées au quotidien.  
Il est soumis à des exigences fortes de **continuité de service**, de **sécurité** et de **suivi opérationnel**.

---

### ❓ Et la préproduction ?

La **préproduction** est une **copie quasi-identique de la production**, utilisée pour **tester les évolutions**, les correctifs ou les nouvelles mises en production.  
Elle permet de sécuriser les changements avant leur bascule en prod.

---

### ❓ C’est quoi le métier de GA (Gestionnaire d’Application) ?

Le Gestionnaire d’Application (GA) est responsable du bon fonctionnement des applications en environnement de production. Son rôle est à la fois **technique**, **opérationnel** et **transverse**. Ses principales missions incluent :

- **Intégrer les traitements** dans les outils de **supervision** et d’**ordonnancement**
- **Effectuer les livraisons** en environnement de **recette**, puis en **production** (MEP – mise en production)
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

## Prérequis: Scripting Unix et Windows sur Mainframe

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

## FORMATION : ressources z/OS

### Qu'est-ce que z/OS ?

z/OS est un système d'exploitation puissant et central pour les environnements mainframe. Il gère les ressources matérielles et logicielles, et permet le traitement de données à grande échelle.

- [Documentation détaillée sur z/OS](https://www.ibm.com/docs/en/zos/2.5.0)    
  Accédez à la documentation complète d'IBM sur z/OS pour une compréhension approfondie du système d'exploitation.

- [Vidéo d'introduction à z/OS](https://www.youtube.com/watch?v=7-9cOM5fpQ0)  
  Une vidéo introductive qui présente les bases de z/OS et ses fonctionnalités essentielles pour les gestionnaires d'applications.
  
- [Utilisation d'IBM Developer pour z/OS](https://www.ibm.com/docs/fr/adffz5/developer-for-zos/15.0)   
  Accédez à la documentation complète d'IBM sur z/OS pour une compréhension approfondie de l'ensemble d'outil IBM Developer.
---

## Ressources pour MVS et Gestion des Ressources

### MVS : Multiple Virtual Storage

MVS est un sous-système essentiel de z/OS, et il est crucial de comprendre son rôle dans la gestion des ressources système.

- [Documentation MVS par IBM](https://www.ibm.com/docs/en/zos/2.4.0?topic=mvs)  
  Un guide détaillé sur MVS et ses fonctions dans l'environnement z/OS.

- [Gestion des ressources dans MVS](https://www.ibm.com/docs/en/zos/2.3.0?topic=zos-mvs-overview)  
  Documentation sur la gestion des ressources dans un environnement MVS.

- [Vidéo : Introduction aux systèmes MVS](https://www.youtube.com/watch?v=72Bo7I_GUTo)  
  Une vidéo pour comprendre les concepts de MVS et son impact sur les traitements mainframe.

- [Vidéo : Introduction aux systèmes MVS](https://www.youtube.com/watch?v=YA3FQOzr0ag)   
  Une vidéo concrète sous forme de TP.

---

## Accès aux Données : VSAM, Séquentielle, Partitionnée

### Accès aux données sur z/OS

Les méthodes d'accès aux données telles que **VSAM** et l'accès **séquentiel** sont au cœur des systèmes mainframe. Comprendre comment elles fonctionnent est essentiel pour gérer les données de manière efficace.

- [Introduction à VSAM](https://www.ibm.com/docs/en/zos/2.4.0?topic=vsam)  
  Un guide sur VSAM (Virtual Storage Access Method), une méthode d'accès aux fichiers fréquemment utilisée sur z/OS.

- [Accès séquentiel aux fichiers sur z/OS](https://www.ibm.com/docs/en/zos/2.4.0?topic=sequential)  
  La méthode d'accès séquentiel et comment elle est utilisée pour les fichiers sur z/OS.

- [Vidéo : Accès aux données avec VSAM sur z/OS](https://www.youtube.com/watch?v=0xtfPzIn0Bc)  
  Une vidéo expliquant le fonctionnement du système d'accès aux données VSAM.

---

## JCL : Job Control Language

### Qu'est-ce que le JCL ?

Le **Job Control Language (JCL)** est utilisé pour contrôler l'exécution des programmes et des tâches dans un environnement mainframe. Il est essentiel de comprendre sa syntaxe et ses composants pour optimiser les traitements.

- [Documentation complète sur JCL](https://www.ibm.com/docs/en/zos/2.4.0?topic=jcl)  
  Un guide complet pour maîtriser la syntaxe et les commandes JCL.

- [Tutoriel sur les commandes JCL](https://www.ibm.com/docs/en/zos/2.3.0?topic=jcl-tutorial)  
  Un tutoriel pour vous initier à l'utilisation de JCL et comprendre ses principaux éléments.

- [Vidéo : Introduction au JCL](https://www.youtube.com/watch?v=4TuJKUQmQkc)  
  Une vidéo d'introduction qui explique la syntaxe de base du JCL et son utilisation dans un environnement mainframe.

- [Vidéo : Cours complet (Anglais) sur le JCL en environnement mainframe](https://www.youtube.com/watch?v=bSdNNDscccg)  
  Cours complet sous forme de plusieurs vidéos.
  
---

## Ordonnancement avec TWS (Tivoli Workload Scheduler)

### Ordonnancement des tâches avec TWS

L'**ordonnancement** des tâches est crucial pour la gestion des charges de travail sur un mainframe. TWS est l'outil de choix pour cette tâche.

- [Documentation officielle TWS](https://www.ibm.com/docs/en/workload-automation/9.2.0)  
  Un guide complet pour apprendre à utiliser Tivoli Workload Scheduler (TWS).

- [Série de vidéo : Ordonnancement avec TWS](https://www.youtube.com/watch?v=gA6uogw9yX0&list=PLZ87gBR2Z805Eyip2v0EUxSQjSZKTAkIB)  
  Une série de vidéo introductive pour comprendre le fonctionnement et la gestion des tâches avec TWS.

- [Guide utilisateur](https://www.princeton.edu/~campcomd/tivoli/gc32-0423-00.pdf)  
  Guide utilisateur complet de TWS.

---

## Gestion des Traitements Batch et Transactionnels

### Les Traitements Batch

Les traitements **batch** et **transactionnels** sont des processus fondamentaux dans un environnement mainframe. La gestion de ces traitements via des outils comme **TWS** (Tivoli Workload Scheduler) est un aspect clé du rôle d'un gestionnaire d'application.

- [Guide sur les traitements batch sous z/OS](https://www.ibm.com/docs/en/zos/2.5.0?topic=batch)  
  La documentation pour comprendre les traitements batch sous z/OS.

- [Documentation sur CICS (Customer Information Control System)](https://www.ibm.com/docs/en/cics)  
  CICS est un middleware essentiel pour le traitement transactionnel dans un environnement mainframe.

- [Vidéo : Gestion des traitements batch avec TWS](https://www.youtube.com/watch?v=03f4WiJXZgA)  
  Cette vidéo montre comment gérer les traitements batch à l'aide de l'ordonnanceur TWS.

---

## Bases de Données IMS et DB2

### Bases de Données IMS et DB2

Les bases de données **IMS** et **DB2** sont essentielles pour la gestion des données sur un mainframe. Vous trouverez ici des ressources pour comprendre leur structure et leur utilisation.

- [Guide d'installation IMS & DB2](https://www.youtube.com/watch?v=4hMGzhIQS7k)  
  Tutoriel d'installation IMS et DB2 sur Windows.

- [Documentation sur IMS (Information Management System)](https://www.ibm.com/docs/en/ims)  
  Un guide complet sur le système de gestion de bases de données IMS.

- [Guide DB2 sous z/OS](https://www.ibm.com/docs/en/db2/12.1)  
  La documentation sur DB2, un des systèmes de bases de données relationnelles les plus utilisés sur mainframe.

- [Vidéo : Utilisation de DB2 avec SQL dans un environnement Mainframe](https://www.youtube.com/watch?v=5Vgzm2Wz8g4)  
  Cette vidéo montre comment utiliser DB2 avec SQL dans un environnement mainframe.

---


