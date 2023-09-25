## ExpressJS

Ce repo contient une appli express.js 'hello world'pour tester le déploiement.

### Prérequis

- Compte GitHub / GitLab

### Installation

```
cd deploiment
npm install
```

### Utilisation

```
node app.js
```

### Installation sur render.com

Forker le repository sur github si nécessaire.

- Créer un compte sur [Render](https://render.com/)
- Créez un nouveau web service en cliquant sur l'icone +
- Choisissez l'option "Build and deploy from a git repository"
- Cliquez sur 'connect account' dans la section 'Github' à droite
- Vous vous retrouvez sur le site de github
- Tapez votre Mot de passe github
- Sélectionnez le repository que vous voulez publier
- Confirmer les permissions accordées
- Vous revenez sur le site de render
- Cliquez sur le bouton "connect" du repository que vous voulez publier
- Remplissez les champs avec les données suivantes

```
General:Name: SOUS-DOMAINE-DE-VOTRE-APP
Region: Frankfurt (EU Central)
Instance Type: FreeBuild & Deploy:Repository: https://github.com/jibundeyare/src-express
Branch: main 
Build Command: npm install
Start Command: node app.js
```

- Validez la configuration et allez voir le lien disponible en haut de la page
