# 📚 MyInk — Logiciel de Création de Livres Interactifs (LDVH)
Projet académique — Université Paris Cité  
Développé en groupe de 4 étudiants (2024–2025)

MyInk est une application Java complète permettant de créer, éditer, lire et exporter des **Livres Dont Vous Êtes le Héros (LDVH)**.  
Ce projet a été réalisé dans le cadre de la Licence 2 Informatique à l’**Université Paris Cité**, en collaboration avec trois camarades.  
Il constitue un projet de fin d’année complet incluant **toute la chaîne de production logicielle** : analyse, conception, développement, tests, documentation et packaging.

---

## 🎯 Objectif du projet

Créer un logiciel permettant :

- de rédiger des histoires non linéaires,
- de construire un graphe narratif interactif,
- d’ajouter des choix conditionnels,
- de gérer un inventaire d’objets,
- de détecter automatiquement les sections inatteignables,
- de lire les livres via une interface dédiée,
- d’exporter les livres en **PDF** ou en **version web interactive (HTML5)**.

MyInk vise à offrir un outil complet pour auteurs, étudiants ou passionnés souhaitant créer des récits interactifs.

---

## 🧠 Fonctionnalités principales

### ✏️ Création & édition de livres
- Création de nouveaux livres avec couverture, titre et auteur.
- Éditeur graphique basé sur un **graphe narratif**.
- Ajout, suppression et modification de :
  - pages (nœuds),
  - liens (choix),
  - objets (obtention / nécessité).
- Détection automatique des graphes invalides (pages orphelines, cycles incohérents…).

### 📖 Lecture interactive
- Mode lecture immersif avec navigation fluide.
- Gestion de l’inventaire du lecteur.
- Choix conditionnels basés sur les objets collectés.
- Retour automatique au menu en fin de livre.

### 📤 Exportation
- Export PDF avec numérotation aléatoire des sections.
- Export HTML5 interactif (lecture dans un navigateur).
- Génération d’exécutables multiplateformes via **jpackage** :
  - Windows (.exe + Setup Wizard)
  - macOS (.app)
  - Linux (.AppImage, .deb)

---

## 🏗️ Architecture & technologies

- **Java 21**
- **JavaFX** (UI)
- **FXML** (interfaces)
- **Scene Builder** (édition visuelle)
- **MVP (Model–View–Presenter)** comme architecture logicielle
- **Maven** pour la gestion des dépendances
- **Subversion (SVN)** pour le versionnement en équipe

L’application est entièrement **desktop**, fonctionne **hors ligne**, et ne nécessite **aucune création de compte**.

---

## 📄 Documentation produite

Dans le cadre du projet, l’équipe a réalisé l’ensemble des documents professionnels suivants :

- Cahier des charges  
- Cahier de conception détaillée  
- Cahier de recette (tests fonctionnels et techniques)  
- Cahier de tests  
- Manuel d’installation  
- Manuel d’utilisation  
- Diagrammes UML (cas d’utilisation, classes, séquences)  
- Maquettes et arborescences complètes  

Ces documents assurent une traçabilité complète du projet, de la conception à la validation.

---

## 👩‍💻 Contexte académique

MyInk a été développé dans le cadre du module **L2O1 – Livre Dont Vous Êtes le Héros** à l’Université Paris Cité.  
Le projet avait pour objectifs :

- d’appliquer les méthodes de conception logicielle,
- de travailler en équipe sur un logiciel complet,
- de produire une application robuste et multiplateforme,
- de livrer une documentation professionnelle,
- de mettre en œuvre une architecture logicielle avancée (MVP).

---

## 🚀 Avancement

Le projet est **terminé** et fonctionnel.  
Le code source, les ressources et la documentation seront ajoutés au dépôt.
