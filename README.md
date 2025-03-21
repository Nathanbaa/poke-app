# Poke-App 🎮

Une application web moderne pour explorer et découvrir les Pokémon, construite avec React et Node.js.

## 🌟 Fonctionnalités

- Interface utilisateur moderne et responsive
- Liste complète des Pokémon
- Détails détaillés pour chaque Pokémon
- Recherche de Pokémon
- Filtrage par type
- Interface utilisateur intuitive

## 🛠️ Technologies Utilisées

### Frontend

- React.js
- TypeScript
- Tailwind CSS

### Backend

- Node.js
- Express.js
- MariaDB

## 🚀 Installation

### Prérequis

- Node.js (v14 ou supérieur)
- Docker et Docker Compose
- MariaDB

### Configuration

1. Clonez le repository :

```bash
git clone https://github.com/Nathanbaa/poke-app.git
cd poke-app
```

2. Configurez les variables d'environnement :

```bash
cp .env.example .env
# Modifiez les variables dans le fichier .env selon vos besoins
```

3. Lancez l'application avec Docker Compose :

```bash
docker-compose up
```

## 🔗 Liens du Projet

Frontend: http://localhost:3001/login
Backend: http://localhost:3000
PhpMyAdmin: http://localhost:8080

## 📁 Structure du Projet

```
poke-app/
├── frontend/           # Application React
│   ├── src/           # Code source du frontend
│   ├── public/        # Fichiers statiques
│   ├── Dockerfile     # Configuration Docker pour le frontend
│   └── package.json   # Dépendances frontend
├── backend/           # Serveur Node.js
│   ├── src/          # Code source du backend
│   ├── Dockerfile    # Configuration Docker pour le backend
│   └── package.json  # Dépendances backend
├── docker-compose.yaml # Configuration Docker
└── .env              # Variables d'environnement
```

## 🔧 Développement

### Frontend

```bash
cd frontend
npm install
npm run start
```

### Backend

```bash
cd backend
npm install
npm run dev
```

## 👥 Auteur

- Nathan.B
