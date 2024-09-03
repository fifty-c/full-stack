# Test Technique - Stagiaire Full-stack
Afin d'évaluer vos compétences, nous vous demandons de réaliser un petit projet qui permet de faire une gestion de tâches (ToDoList).

Le projet doit comprendre ces fonctionnalités :
- Authentification (register, login, forgot password, reset password)
- Ajouter/Modifier/Supprimer une tâche
- Changer les statuts d'une tache (complété, en attente, en cours)
- Liste de toutes les tâches

Veuillez fournir le code source de votre application via un dépôt GitHub.
Assurez-vous d’inclure un README avec des instructions pour configurer et exécuter votre application.
Si vous complétez les bonus, veuillez le mentionner dans votre documentation.

## Front-end - Angular
- Utiliser bootstrap ou tailwind pour le design des composants.
- Bonus : Ajouter une fonctionnalité de filtrage des tâches par statut.
- Bonus 2 : mettre en place un UNDO sur l'action précédente.

## Back-end - Laravel
- Mettre en place une API REST en Laravel pour gérer les tâches (CRUD).
- Utiliser une base de données MySQL pour stocker les données des tâches.
- Sécuriser les routes de l’API avec une authentification basée sur des tokens.
- Vous devez faire une gestion des erreurs 404, 403
- Bonus : Écrire des tests unitaires pour l’API.

## DevOps
Vous devez fournir un docker-compose pour pouvoir tester votre travail.

- Pour les emails vous devez utiliser Mailtip.
- Pour le serveur Http vous devez utiliser nginx
- Pour la base de donnée, vous pouvez utiliser MySQL ou MariaDB
- Vous devez utiliser la Version 8.4 de php