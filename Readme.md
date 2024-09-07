## Gestion des Commandes

## Description

Ce projet implémente un composant métier en JavaScript pour gérer les commandes, incluant les opérations CRUD (Créer, Lire, Mettre à jour, Supprimer) sur les commandes, les clients et les articles. Ce composant permet la gestion des commandes passées par les clients, incluant le calcul du total de la commande, l'ajout et la suppression d'articles.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les éléments suivants :

- [ [Node.js](https://nodejs.org/fr)] (version 12 ou supérieure)
  (version 4.0 ou supérieure)

## Installation

Suivez ces étapes pour configurer le projet sur votre machine locale :

**Clonez le repository :**

```bash
git clone https://github.com/Mbaye01/TP45-Express-Exo1.git

```

**Accédez au dossier du projet :**

```bash
cd gestion-commande
```

**Installez les dépendances :**

```bash
npm install
```

```bash
npm install express
```

```bash
npm install body-parser
```

**Utilisation**

Pour démarrer l'application, exécutez la commande suivante :

```bash
npm start
```

## Modelisation du projet

[UML](./assets/UML.png)

## Les Classes

#### Customer :

Gère les informations du client, telles que le nom et l'email.

- Méthodes :

`createCustomer(customer)`: Crée un nouveau client avec un nom et un email.

`destroyCustomer()`: Supprime le client.

`editCustomer(newCustomer)`: Met à jour les informations du client.

`getCustomer()`: Retourne le nom et l'email du client.

#### Product

Gère la création, la modification et la suppression des produits.

_Méthodes_ :

`createProduct(product)`: Crée un produit avec nom, quantité et prix.

`destroyProduct()`: Supprime le produit.

`editProduct(newProduct)`: Met à jour les détails du produit.

`getProduct()`: Retourne le nom, la quantité et le prix du produit.

#### Commande

Gère la création, la modification et la suppression des commandes.

_Méthodes_ :

`createOrder(order)`: Crée une nouvelle commande avec la date, le montant, les détails, et un client.

`destroyOrder()`: Supprime la commande.
editOrder(newOrder): Met à jour les détails de la commande.

`getOrder()`: Retourne la date de la commande, le montant, le nombre de détails, et le client.

#### DétailCommande :

Représente les détails d'une commande, incluant la quantité, le prix, et le produit associé.

## Author

[Mbaye Abdellahi Kalidou](https://github.com/Mbaye01/TP45-Express-Exo1.git)
