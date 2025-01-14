# API pour la Gestion de Location de Véhicules
<p align="center">
  <img src="images/logo.png" alt="Logo" />
</p>
<p align="center">
  <img src="images/image.png" alt="Logo" />
</p>


## Introduction

Bienvenue à ce TP dédié à la validation des fonctionnalités d'une API pour un système de gestion de location de véhicules. Cette API permet d'effectuer des opérations CRUD (Create, Read, Update, Delete) sur les ressources liées aux utilisateurs, catégories, véhicules, agences, disponibilités, locations et avis.

## Prérequis

- Environnement de test configuré avec un serveur web (comme XAMPP).
- Accès à la base de données `location_vehicules`.
- Documentation de l'API accessible à l'URL [/doc].
- API accessible à l'URL [/API].

## Installation

1. **Cloner le dépôt**

   ```bash
   git clone https://github.com/tomDeprez/API-pour-la-Gestion-de-Location-de-V-hicules.git
   cd API-pour-la-Gestion-de-Location-de-V-hicules
   ```

2. **Configurer la base de données**

   Importez le fichier `Base de données.sql` dans votre serveur MySQL pour créer les tables nécessaires.

   ```bash
   mysql -u root -p location_vehicules < "path/to/Base de données.sql"
   ```

3. **Configurer l'environnement**

   Placez le fichier `index.php` dans le répertoire racine de votre serveur web (par exemple, `C:/xampp/htdocs` pour XAMPP).

## Configuration Git

Si vous rencontrez des problèmes de propriété lors de l'ajout du remote, exécutez la commande suivante pour ajouter une exception pour votre répertoire de travail :

```bash
git config --global --add safe.directory C:/xampp/htdocs
```

## Objectifs du TP

Vous allez effectuer les tâches suivantes :

1. **Tester les opérations de lecture** : Valider les endpoints `GET` pour récupérer les listes et les détails des utilisateurs, catégories, véhicules, agences, disponibilités, locations et avis.
2. **Tester les opérations de création** : Valider les endpoints `POST` pour ajouter de nouvelles entrées dans chaque catégorie.
3. **Tester les opérations de mise à jour** : Valider les endpoints `PUT` pour modifier les entrées existantes.
4. **Tester les opérations de suppression** : Valider les endpoints `DELETE` pour supprimer les entrées.

## Plan du TP

1. **Prérequis** : Assurez-vous d'avoir un environnement de test configuré avec l'accès à la base de données `location_vehicules`.
2. **Documentation de l'API** : Référez-vous à la documentation accessible à l'URL [/doc] pour comprendre la structure des requêtes et des réponses.
3. **Scénarios de Test** : Utilisez les différents endpoints pour tester les fonctionnalités décrites. Documentez vos résultats et les anomalies rencontrées.

## Consignes

- Suivez la logique ISTQB pour les tests.
- Créez une stratégie de test complète comprenant des cas de test détaillés.
- Exécutez les cas de test sur Postman.
- Vérifiez les codes de réponse HTTP pour chaque requête et comparez les résultats attendus avec ceux obtenus.
- Notez les erreurs et les comportements inattendus pour un retour d'expérience complet.

## Endpoints de l'API

### Utilisateurs

- `GET /API/utilisateurs`
- `GET /API/utilisateurs/{id}`
- `POST /API/utilisateurs`
- `PUT /API/utilisateurs/{id}`
- `DELETE /API/utilisateurs/{id}`

### Catégories

- `GET /API/categories`
- `GET /API/categories/{id}`
- `POST /API/categories`
- `PUT /API/categories/{id}`
- `DELETE /API/categories/{id}`

### Véhicules

- `GET /API/vehicules`
- `GET /API/vehicules/{id}`
- `POST /API/vehicules`
- `PUT /API/vehicules/{id}`
- `DELETE /API/vehicules/{id}`

### Agences

- `GET /API/agences`
- `GET /API/agences/{id}`
- `POST /API/agences`
- `PUT /API/agences/{id}`
- `DELETE /API/agences/{id}`

### Disponibilités

- `GET /API/disponibilites`
- `GET /API/disponibilites/{id}`
- `POST /API/disponibilites`
- `PUT /API/disponibilites/{id}`
- `DELETE /API/disponibilites/{id}`

### Locations

- `GET /API/locations`
- `GET /API/locations/{id}`
- `POST /API/locations`
- `PUT /API/locations/{id}`
- `DELETE /API/locations/{id}`

### Avis

- `GET /API/avis`
- `GET /API/avis/{id}`
- `POST /API/avis`
- `DELETE /API/avis/{id}`

## Conclusion

Merci de votre participation et bonne chance dans vos tests ! Pour toute question ou problème, veuillez me contacter.