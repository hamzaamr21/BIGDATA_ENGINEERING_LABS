# Projet MongoDB – Big Data & Applications

**Étudiant :** AMRANI Hamza  
**Filière :** IDF  
**Année :** 2025-2026

---

## Structure du Repository

mongodb*lab4/
│
├── Compte_Rendu/ # Rapports du Lab 4 MongoDB
│ ├── 1-LAB 4* mongodb*IDF_section[1-5].pdf # Partie I : Introduction à MongoDB (CRUD, Agrégations, KPIs)
│ └── 2-LAB 4* mongodb*IDF*[MapReduce&Dashboard].pdf # Partie II : PyMongo, MapReduce et MongoDB Charts
│
├── data/ # Données utilisées (ex: transactions.json)
│
├── MapReduce.ipynb # Notebook Python : connexion, analyses et visualisations
│
├── .gitignore # Fichiers à ignorer par Git
└── README.md # Documentation du projet

yaml
Copy code

---

## Description du Projet

Ce projet fait partie du module **Big Data & Applications** et vise à maîtriser les fondements de **MongoDB**, de la manipulation basique à l’analyse avancée via **PyMongo** et **MongoDB Charts**.  
L’objectif principal est d’apprendre à :

- Créer et administrer une base de données sur **MongoDB Atlas**.
- Manipuler des données à l’aide des **opérations CRUD** et des **pipelines d’agrégation**.
- Implémenter des analyses statistiques et visuelles avec **Python (PyMongo, Matplotlib, Seaborn)**.
- Concevoir un **dashboard interactif** avec MongoDB Charts pour l’analyse en temps réel.

---

## Contenu du Compte Rendu

### Partie I — Initiation à MongoDB

**Fichier :** `1-LAB 4_ mongodb_IDF_section[1-5].pdf`  
Cette première partie détaille :

- La **création d’un cluster MongoDB Atlas** et la connexion via Compass
- Les **opérations CRUD** (Insert, Find, Update, Delete)
- Les **requêtes d’agrégation** et les **indicateurs clés (KPI)**
- Les **requêtes complexes** (fraudes, montants élevés, latence réseau, etc.)

---

### Partie II — MapReduce & Dashboard MongoDB Charts

**Fichier :** `2-LAB 4_ mongodb_IDF_[MapReduce&Dashboard].pdf`  
Cette section explore :

- L’utilisation de **PyMongo** pour manipuler MongoDB avec Python
- La création d’**agrégations avancées et MapReduce**
- L’analyse de **fraudes**, **latence**, et **transactions par appareil**
- La conception d’un **dashboard MongoDB Charts** avec :
  - KPIs (nombre total, montant total, taux de fraude, taux d’échec)
  - Visualisations principales (fraudes, statuts, appareils, géolocalisation)
  - Analyses détaillées (pourcentage de fraude, top montants, tendances temporelles)

---

---

## Base de Données utilisée

**Nom de la base :** `BankDB`  
**Collection :** `transactions`

Conclusion

Auteur
AMRANI Hamza - ENSIAS
Filière IDF
Année universitaire 2025–2026
