# Projet Kafka Big Data
**Étudiant:** AMRANI Hamza  
**Filière:** IDF  
**Année:** 2025-2026

---

## Structure du Repository
```
kafka_project/
│
├── Compte_Rendu/                                      # Rapport de laboratoire (PDF)
│   └── Compte Rendu TP Kafka.pdf           
│
├── .idea/                                             # Configuration IntelliJ IDEA
│
├── E1_kafka_Event_producer/                           # Exercice 1: Producer d'événements
│
├── E2_kafka_Event_Consumer/                           # Exercice 2: Consumer d'événements
│
├── E3_kafka_Streams/                                  # Exercice 3: Kafka Streams WordCount
│
├── E4_kafka_consumer/                                 # Exercice 4: WordCount Consumer interactif
│
├── E4_kafka_producer/                                 # Exercice 4: WordCount Producer interactif
│
├── kafka-consumer-app-jar-with-dependencies.jar       # JAR Consumer
├── kafka-producer-app-jar-with-dependencies.jar       # JAR Producer
├── kafka-word-consumer-jar-with-dependencies.jar      # JAR WordCount Consumer
├── kafka-word-producer-jar-with-dependencies.jar      # JAR WordCount Producer
├── kafka-WordCount-app-jar-with-dependencies.jar      # JAR Kafka Streams
│
├── docker-compose.yml
├── pom.xml
├── .gitignore
└── README.md
```

---

## Comment Examiner le Projet

**Lisez d'abord le compte rendu dans le dossier `Compte_Rendu/`**

Le rapport contient toutes les informations organisées pour comprendre la structure et le contenu du TP :

* **Section 1-2** → Installation et première utilisation de Kafka avec Zookeeper
* **Section 3** → Développement d'applications Producer/Consumer et Kafka Streams
* **Section 4** → Kafka Connect (ingestion de données fichier → Kafka → fichier)
* **Section 5** → Cluster multi-brokers et application WordCount interactive en temps réel

Chaque section décrit les objectifs, les commandes exécutées, et les résultats obtenus.
