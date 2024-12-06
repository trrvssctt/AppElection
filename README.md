Task Manager
Task Manager est une application web de gestion de tâches construite avec Angular. Elle permet aux utilisateurs de créer, modifier, supprimer et suivre leurs tâches quotidiennes.

Caractéristiques
📋 Gestion des tâches : Créez, modifiez, supprimez et marquez les tâches comme terminées.
🔍 Recherche et filtres : Recherchez des tâches par nom ou appliquez des filtres (par priorité, statut, etc.).
📆 Planification : Ajoutez des dates d'échéance pour mieux organiser vos tâches.
📊 Statistiques : Visualisez des statistiques sur vos tâches (tâches complétées, en cours, etc.).
Technologies utilisées
Frontend : Angular
UI Framework : Angular Material (ou Bootstrap, si utilisé)
State Management : RxJS (ou NgRx, si applicable)
Backend (optionnel) : API REST ou service simulé avec JSON Server
Installation
Clonez le dépôt :

bash
Copier le code
git clone https://github.com/nom-utilisateur/task-manager.git
cd task-manager
Installez les dépendances :

bash
Copier le code
npm install
Démarrez le serveur de développement :

bash
Copier le code
ng serve
Ouvrez l'application dans votre navigateur :
http://localhost:4200

Scripts disponibles
ng serve : Lance l'application en mode développement.
ng build : Compile l'application pour la production.
ng test : Exécute les tests unitaires.
ng lint : Vérifie la qualité du code.
Configuration
Backend (si applicable)
L'application peut fonctionner avec une API REST. Par défaut, elle utilise un service Angular avec des données simulées. Si vous souhaitez configurer un backend :

Configurez l'URL de l'API dans le fichier environment.ts :

typescript
Copier le code
export const environment = {
  production: false,
  apiUrl: 'http://localhost:3000/api' // Exemple d'URL
};
Assurez-vous que l'API est active avant de démarrer l'application.

Environnements
src/environments/environment.ts : Configuration pour le développement.
src/environments/environment.prod.ts : Configuration pour la production.
Structure du projet
ruby
Copier le code
src/
├── app/
│   ├── components/      # Composants Angular (UI)
│   ├── services/        # Services Angular pour les appels API et la gestion des données
│   ├── models/          # Modèles de données TypeScript
│   ├── pages/           # Pages principales (par exemple, dashboard, détail des tâches)
│   ├── app.module.ts    # Module principal
│   └── app.component.ts # Composant principal
├── assets/              # Fichiers statiques (images, styles, etc.)
└── environments/        # Fichiers de configuration des environnements
Améliorations futures
📅 Intégration d'un calendrier pour planifier les tâches.
📱 Responsive Design pour une meilleure expérience mobile.
🔔 Notifications pour les rappels de tâches.
🔗 Authentification pour gérer des comptes utilisateurs.
Contribuer
Les contributions sont les bienvenues ! Suivez ces étapes pour contribuer :

Forkez ce dépôt.
Créez une branche pour vos modifications :
bash
Copier le code
git checkout -b feature/ma-fonctionnalite
Effectuez vos modifications et validez-les :
bash
Copier le code
git commit -m "Ajout de ma fonctionnalité"
Poussez la branche vers votre fork :
bash
Copier le code
git push origin feature/ma-fonctionnalite
Ouvrez une Pull Request.
Licence
Ce projet est sous licence MIT.

Auteur
Développé par Seydou Dianka.
Pour toute question ou suggestion, contactez-moi à diankaseydou52@gmail.com

