# Transcendence

Jeu multijoueur 3D dans le navigateur, projet final du tronc commun de l'école 42 Paris, réalisé en équipe.

## Stack

- **Frontend** : Three.js, Vite, Tailwind CSS
- **Serveur de jeu** : Node.js + WebSockets (modes *Crown* et *Survive*)
- **API** : Node.js / Express, authentification JWT + 2FA par email
- **Base de données** : MariaDB
- **Infra** : Docker Compose, nginx en reverse proxy HTTPS

## Fonctionnalités

- Inscription / connexion avec double authentification (2FA)
- Profils, avatars, amis, historique des parties
- Leaderboard, achievements, XP
- Parties multijoueur en temps réel

## Lancer le projet

```bash
cp .env.example .env   # puis remplir les valeurs
make                   # génère un certificat auto-signé et lance les conteneurs
```

L'application est ensuite accessible sur https://localhost:8443.

## Équipe

Florian Bouteille, Alban Neumann, Maxime Hanarte, Zakaria Meliani, Enzo Nzuguem Tiko.

Repo original de l'équipe : https://github.com/FlorianBouteille/Transcendence
