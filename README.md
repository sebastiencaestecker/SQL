# Projet SQL Business Case : Base de Données WideWorldImporter


## 🎯 **Objectif**

Ce projet applique les concepts de DDL, DML et DQL dans un contexte commercial, simulant des scénarios réels d’utilisation de SQL pour gérer les données d’une entreprise fictive d'import-export, WideWorldImporter.

---

## 📚 **Thèmes Abordés**

- **Instructions DDL** :
  - Création, suppression et modification de bases de données, de tables et de contraintes (`CREATE`, `DROP`, `ALTER`).

- **Instructions DML** :
  - Manipulation des données avec `INSERT INTO`, `UPDATE` et `DELETE`.

- **Instructions DQL** :
  - Interrogation des données avec des fonctions scalaires (`CONCAT`, `LEFT`, `RIGHT`) et des fonctions d'agrégation (`AVG`, `SUM`, `MAX`).

- **Requêtes Complexes** :
  - Rédaction de requêtes avancées avec des sous-requêtes `SELECT` imbriquées.

- **Triggers** :
  - Mise en place de triggers pour automatiser l'exécution de commandes SQL en réponse à des événements.

- **Procédures Stockées** :
  - Création de procédures stockées pour réutiliser du code SQL.

- **Variables SQL** :
  - Utilisation de variables pour rendre les requêtes plus flexibles.

---

## 🏢 **Contexte Commercial**

Cette étude de cas implique une entreprise fictive, WideWorldImporter, avec des besoins commerciaux spécifiques nécessitant l'utilisation de SQL pour gérer les données clients, fournisseurs, commandes, stocks et entrepôts.

---

## 🛠️ **Mise en Place de la Base de Données**

1. **Créer la Base de Données WideWorldImporter** :
   - Connectez-vous au portail Azure.
   - Téléchargez le fichier `WideWorldImporters_Database.bacpac`.
   - Créez un nouveau container nommé "wideworldimporters".

2. **Importer la Base de Données** :
   - Allez sur la page du serveur, sélectionnez "Import Database" et choisissez le bon container.
   - Attendez que l'importation soit terminée (cela peut prendre quelques minutes).

---

## 📊 **Description de la Base de Données**

La base de données **WideWorldImporter** représente une entreprise fictive et contient des tables pour :

- **Customers** : Informations sur les clients.
- **Suppliers** : Détails des fournisseurs.
- **Orders** : Données sur les commandes (date, livraison, statut).
- **OrderLines** : Produits commandés (ID produit, quantité, prix).
- **StockItems** : Informations sur les stocks (nom de l'article, description, prix).
- **Warehouse** : Informations sur les entrepôts (adresse, contact).

