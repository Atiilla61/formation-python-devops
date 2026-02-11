# Plan 6 mois — Python/DevOps

## MOIS 1 : Le "Bootcamp" Algorithmique
**Objectif :** casser ton cerveau pour qu’il pense comme une machine. Logique pure, console uniquement.

### Semaine 1 : Syntaxe vitale
- Variables, types (int, float, string, bool)
- Opérations mathématiques et logiques
- Entrées / sorties (input, print)

### Semaine 2 : Contrôle du flux
- Conditions (if, elif, else)
- Boucles (for, while) et itérations
- Exceptions de base (try, except)

### Semaine 3 : Structures de données
- Listes, tuples, dictionnaires, ensembles (sets)
- Manipulation : ajout, suppression, tri, slicing

### Semaine 4 : Modularité
- Fonctions (paramètres, retour, portée des variables)
- Modules et importations (math, random, time)

#### 🔥 Épreuve du feu (Validation Mois 1) — “Gestionnaire de Casino”
Programme console permettant :
- inscription (pseudo, solde de départ)
- choix entre 3 jeux (roulette, nombre mystère, machine à sous)
- mise, gain/perte, quitter avec solde final

**Critère :** le code ne doit jamais planter, même si l’utilisateur tape n’importe quoi.

---

## MOIS 2 : Python Système & Automatisation
**Objectif :** faire de Python ton esclave pour piloter ton ordinateur.

### Semaine 5 : Manipulation de fichiers (I/O)
- Lire/écrire : .txt, .csv, .json
- Encodage (UTF-8)

### Semaine 6 : Interaction système (OS)
- os, sys, shutil
- Parcours dossiers, renommage en masse, infos système

### Semaine 7 : Réseau (bases)
- HTTP avec requests
- Télécharger du contenu, scraping basique (BeautifulSoup)

### Semaine 8 : Environnements virtuels
- venv, pip
- requirements.txt

#### 🔥 Épreuve du feu (Validation Mois 2) — “Archiviste Automatique”
Script qui :
- scanne un dossier “Bordel” (téléchargements)
- identifie types de fichiers (images/docs/vidéos)
- déplace en dossiers par catégorie + date
- génère un rapport .csv

---

## MOIS 3 : Programmation Orientée Objet (POO)
**Objectif :** passer de “scripteur” à “développeur”.

### Semaine 9 : Classes et objets
- Attributs, méthodes, constructeur (__init__)
- Différence classe vs instance

### Semaine 10 : Piliers de la POO
- Héritage (parent/enfant)
- Polymorphisme & encapsulation (privé/public)

### Semaine 11 : Méthodes magiques
- __str__, __repr__, __eq__, etc.

### Semaine 12 : Conception logicielle
- Lire un UML simple
- Structurer un projet multi-fichiers

#### 🔥 Épreuve du feu (Validation Mois 3) — “Système RPG Textuel”
- classe Personnage
- classes filles Guerrier, Mage
- inventaire
- combat tour par tour

**Critère :** code propre, réutilisable, héritage intelligent.

---

## MOIS 4 : Bases de Données & SQL
**Objectif :** mémoire persistante.

### Semaine 13 : SQL pur
- SELECT, INSERT, UPDATE, DELETE
- JOINs (Inner, Left, Right)

### Semaine 14 : Python & SQL
- sqlite3
- CRUD depuis Python

### Semaine 15 : ORM
- SQLAlchemy ou Peewee
- manipuler la DB comme des objets Python

### Semaine 16 : Modélisation
- One-to-One, One-to-Many, Many-to-Many

#### 🔥 Épreuve du feu (Validation Mois 4) — “Bibliothèque Intelligente”
Appli console (SQLite) :
- ajouter livre, auteur
- emprunter un livre (indisponible)
- persistance après fermeture/réouverture

---

## MOIS 5 : Web Back-End & API
**Objectif :** rendre ton code accessible au monde entier.

### Semaine 17 : Web (théorie)
- HTTP (GET, POST, PUT, DELETE)
- codes de statut (200, 404, 500)
- JSON

### Semaine 18 : Flask (bases)
- routing
- templates (Jinja2)

### Semaine 19 : API REST
- renvoyer JSON (pas HTML)
- tests avec Postman ou cURL

### Semaine 20 : Authentification
- sécuriser l’API (token simple ou login)

#### 🔥 Épreuve du feu (Validation Mois 5) — “API Météo Locale”
Serveur local :
- endpoint `http://localhost:5000/meteo/Paris`
- récupère météo via une API publique (ex: OpenWeatherMap)
- stocke en DB (cache)
- renvoie JSON propre

---

## MOIS 6 : Professionnalisation & Projet Final
**Objectif :** qualité, tests, déploiement.

### Semaine 21 : Qualité du code
- PEP8
- lint (pylint/flake8)
- docstrings

### Semaine 22 : Tests
- pytest
- jamais livrer sans tests

### Semaine 23 : Docker & déploiement
- Dockerfile
- exécution en conteneur

### Semaines 24–26 : Projet final (portfolio)
#### 🔥 Grand final — “Dashboard de Monitoring Infrastructure”
App web complète (Flask + DB + Docker) qui :
- affiche en temps réel l’état machine (CPU, RAM)
- lance des scripts de maintenance via boutons web
- page login sécurisée
- docker-compose up
- couverture de tests > 80%
