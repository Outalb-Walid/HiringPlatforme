# Hiring Project

Bienvenue dans le Hiring Project! Ce projet a été conçu pour simplifier et automatiser le processus de recrutement au sein de notre entreprise. Ce README vous guidera à travers les étapes pour configurer et utiliser le projet.

## Table des matières

- [Introduction](#introduction)
- [Fonctionnalités](#fonctionnalités)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Configuration](#configuration)
- [Utilisation](#utilisation)
- [Structure du projet](#structure-du-projet)
- [Contribuer](#contribuer)
- [Licence](#licence)
- [Auteurs](#auteurs)

## Introduction

Le Hiring Project est une application web qui permet de gérer les candidatures, les entretiens et les offres d'emploi. Il est conçu pour être intuitif et facile à utiliser, tout en offrant des fonctionnalités puissantes pour les recruteurs.

## Fonctionnalités

- **Gestion des candidatures** : Suivez et gérez les candidatures en un seul endroit.
- **Planification des entretiens** : Organisez et planifiez des entretiens avec les candidats.
- **Suivi des offres** : Créez et suivez les offres d'emploi.
- **Rapports et analyses** : Générez des rapports pour analyser les performances de recrutement.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/)

## Installation

Pour installer et exécuter le projet en local, suivez les étapes ci-dessous :

1. Clonez le dépôt :

   ```sh
   git clone https://github.com/votre-utilisateur/Hiring-Project.git
   ```

2. Accédez au répertoire du projet :

   ```sh
   cd Hiring-Project
   ```

3. Installez les dépendances :
   ```sh
   npm install
   ```

## Configuration

Avant de lancer l'application, vous devez configurer certains paramètres :

1. Créez un fichier `.env` à la racine du projet et ajoutez les variables d'environnement suivantes :

   ```env
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/hiring
   SECRET_KEY=your_secret_key
   ```

2. Assurez-vous que MongoDB est en cours d'exécution :
   ```sh
   mongod
   ```

## Utilisation

Pour lancer l'application en mode développement :

```sh
npm run dev
```
