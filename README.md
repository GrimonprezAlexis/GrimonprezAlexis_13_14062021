# A propos

Projet 13 - Utilisez une API pour un compte utilisateur bancaire avec React

- Remede Agency : Spécialisée dans le développement d'application web
- Projet : Nouvelle banque Argent Bank

### Fonction

- Développeur web

✅
❌

### Details du projet

Argent Bank essai de percer dans le secteur et a besoin d'aide pour mettre en place son application web React pour le nouveau système d'authentification des utilisateurs.

### Objectif

- Phase 1 : Authentification et gestions des utilisateurs via une application web
- Phase 2 : Transactions / Spécifications de endpoints d'API pour une deuxime mission

### Ressource

- [HTML statisque et le CSS : Page d'accueil / connexion et page de profil](https://github.com/OpenClassrooms-Student-Center/Project-10-Bank-API/tree/master/designs)
- [Modèles de GitHub issues](https://github.com/OpenClassrooms-Student-Center/Project-10-Bank-API/tree/master/.github/ISSUE_TEMPLATE)
- [Forker du Repo](https://github.com/OpenClassrooms-Student-Center/Project-10-Bank-API)
- [Documentation Swagger](https://editor.swagger.io/)
- [Cours Redux](https://openclassrooms.com/fr/courses/5511091-organisez-votre-application-avec-la-logique-redux)

### Contraintes techniques

- Créer une application web responsive avec React
- Utiliser Redux pour gérer le state de l'ensemble de l'app
- Code Robuste / Lisible
- Version moderne (ES6 ou supérieure) de JavaScript
- Validation W3C sans erreur

### Livrable

- Le lien du repository Github
- Le code React du projet

- Contact / Avery Moreau VP Engineering Argent Bank

> Phase 1

- L'utilisateur peut visiter la page d'accueil ✅
- L'utilisateur peut se connecter / déconnecter au sytème ✅
- L'utilisateur ne peut voir les informations relatives à son propre profil qu'après s'être connecté avec succès ✅
- L'utilisateur peut modifier le profil et conserver les données dans la base de données ✅

> Phase 2

- L'utilisateur peut visualiser toutes leurs transactions pour le mois en cours
- L'utilisateur peut visualiser les détails d'une transaction d'une autre vue
- L'utilisateur peut ajouter, modifier, supprimer des informations sur une transaction

> Spécification décrivant les API pour les transactions selon directives de swagger YAML

- La metode HTTP (ex: GET, POST, etc..)
- La route (ex: /store/inventory)
- La description de ce à quoi correspond l'endpoint (ex: Retour de l'inventaire des animaux de compagnie)
- Les paramètres possibles pour tenir compte des différents scénarios
- Les différentes réponses avec les codes de réponse correspondants qui ont un sens pour cet endpoint (ex: 404 : réponse d'erreur d'article inconnu)

### Technlogies

HTML, CSS, SASS, Javascript, Jquery, NodeJS, React, Github, Heroku, API, Swagger

### Hébergement

> Heroku
> [#Projet 13 - Argent Bank](https://google.fr/)

# React Express Starter Pack

> full stack apps with React and Express. Run your client and server with a single command.
> [React, Redux, API, SCSS, Heroku, starter](https://github.com/GrimonprezAlexis/React-custom-starter)

## Quick Start

```bash
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

### Author

[Alexis GRIMONPREZ](grimonprez-alexis.herokuapp.com)

### Version

1.0.0

# Project #10 - Argent Bank API

This codebase contains the code needed to run the backend for Argent Bank.

## Getting Started

### Prerequisites

Argent Bank uses the following tech stack:

- [Node.js v12](https://nodejs.org/en/)
- [MongoDB Community Server](https://www.mongodb.com/try/download/community)

Please make sure you have the right versions and download both packages. You can verify this by using the following commands in your terminal:

```bash
# Check Node.js version
node --version

# Check Mongo version
mongo --version
```

### Instructions

1. Fork this repo
1. Clone the repo onto your computer
1. Open a terminal window in the cloned project
1. Run the following commands:

```bash
# Install dependencies
npm install

# Start local dev server
npm run dev:server

# Populate database with two users
npm run populate-db
```

Your server should now be running at http://locahost:3001 and you will now have two users in your MongoDB database!

## Populated Database Data

Once you run the `populate-db` script, you should have two users in your database:

### Tony Stark

- First Name: `Tony`
- Last Name: `Stark`
- Email: `tony@stark.com`
- Password: `password123`

### Steve Rogers

- First Name: `Steve`,
- Last Name: `Rogers`,
- Email: `steve@rogers.com`,
- Password: `password456`

## API Documentation

To learn more about how the API works, once you have started your local environment, you can visit: http://localhost:3001/api-docs

## Design Assets

Static HTML and CSS has been created for most of the site and is located in: `/designs`.

For some of the dynamic features, like toggling user editing, there is a mock-up for it in `/designs/wireframes/edit-user-name.png`.

And for the API model that you will be proposing for transactitons, the wireframe can be found in `/designs/wireframes/transactions.png`.
