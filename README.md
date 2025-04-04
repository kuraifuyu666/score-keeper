# Application React ScoreKeeper

## Description
L'application ScoreKeeper est une application React simple permettant de suivre les scores de deux équipes. Elle offre une interface conviviale pour mettre à jour et afficher les scores des deux équipes de manière dynamique.

## Commencer

### Prérequis
- Node.js
- npm (Node Package Manager)

### Installation
1. Cloner le dépôt :
    ```sh
   git clone https://github.com/kuraifuyu666/score-keeper.git
    ```

2. Naviguer vers le répertoire du projet :
    ```sh
    cd scorekeeper-app
    ```

3. Installer les dépendances :
    ```sh
    npm install
    ```

### Lancer l'application

Démarrer le serveur de développement :

    ```sh
    npm start
    ```

Ouvrir votre navigateur et aller sur :

    ```arduino
    http://localhost:3000
    ```

### Structure du projet

    ```pgsql
score-keeper/
│
├─ public/
│  └─ index.html
│
├─ src/
│  ├─ components/
│  │  ├─ ScoreKeeper.jsx
│  │  ├─ ScoreView.jsx
│  │  └─ App.jsx
│  ├─ styles/
│  │  ├─ App.css
│  │  ├─ ScoreKeeper.css
│  │  └─ ScoreView.css
│  ├─ index.jsx
│  └─ index.css
│
└─ package.json
    ```

### Utilisation

- Cliquez sur les boutons "+1 Team One" et "+1 Team Two" pour mettre à jour les scores.

- Les scores et l'équipe en tête sont affichés dynamiquement.


### License

This project is licensed under the MIT License.