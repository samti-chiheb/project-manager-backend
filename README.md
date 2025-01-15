# Project Manager (Backend)

## Description
Project Manager est une API robuste et sécurisée permettant de gérer les fonctionnalités nécessaires pour l'application de gestion de projets et d'équipes. Ce dépôt contient le code source du backend, développé avec **Node.js** et **Express.js**, conçu pour fournir des services fiables et performants.

---

## Fonctionnalités principales
- Gestion sécurisée des utilisateurs avec authentification basée sur JWT.
- Création, modification et suppression de projets.
- Gestion des tâches et assignation aux membres de l’équipe.
- API RESTful robuste et bien documentée.
- Middleware pour la gestion des erreurs et la validation des données.

---

## Prérequis
Assurez-vous d'avoir les éléments suivants installés sur votre machine :
- **Node.js** (version 16 ou supérieure)
- **npm** ou **yarn**
- Une base de données MongoDB ou MySQL configurée.

---

## Installation
1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/samti-chiheb/project-manager-backend.git
   ```

2. Accédez au répertoire du projet :
   ```bash
   cd project-manager-backend
   ```

3. Installez les dépendances :
   ```bash
   npm install
   # ou
   yarn install
   ```

4. Configurez les variables d'environnement :
   - Créez un fichier `.env` à la racine du projet.
   - Ajoutez les variables nécessaires, par exemple :
     ```env
     PORT=5000
     DATABASE_URL=your_database_url
     JWT_SECRET=your_secret_key
     ```

---

## Démarrage
Pour lancer le serveur en mode développement :
```bash
npm run dev
# ou
yarn dev
```
Le serveur sera accessible à l'adresse [http://localhost:5000](http://localhost:5000).

Pour lancer le serveur en mode production :
```bash
npm start
# ou
yarn start
```

---

## Scripts disponibles
- `dev` : Lance le serveur en mode développement.
- `start` : Lance le serveur en mode production.
- `test` : Exécute les tests unitaires (si configuré).

---

## Technologies utilisées
- **Langage** : Node.js
- **Framework** : Express.js
- **Base de données** : MongoDB ou MySQL
- **Authentification** : JSON Web Tokens (JWT)
- **Tests** : Tests unitaires et d’intégration (optionnel)

---

## Structure du projet
```
project-manager-backend/
├── controllers/      # Gestion des fonctionnalités principales
├── middlewares/      # Middleware pour la validation et les erreurs
├── models/           # Modèles de données
├── routes/           # Définition des routes de l'API
├── utils/            # Fonctions utilitaires
├── .env              # Variables d'environnement
```

---

## Contribution
Les contributions sont les bienvenues ! Pour contribuer :
1. Forkez le projet.
2. Créez une branche pour votre fonctionnalité :
   ```bash
   git checkout -b feature/ma-fonctionnalite
   ```
3. Commitez vos modifications :
   ```bash
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   ```
4. Poussez vos modifications :
   ```bash
   git push origin feature/ma-fonctionnalite
   ```
5. Créez une Pull Request.

---

## Licence
Ce projet est sous licence MIT. Consultez le fichier `LICENSE` pour plus d'informations.

---

## Auteur
Développé par [Chiheb Eddine](https://github.com/samti-chiheb).

---

## Le repo frontend
Le dépôt du frontend est disponible ici : [Project Manager Frontend](https://github.com/samti-chiheb/project-manager).
