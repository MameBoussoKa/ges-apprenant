# GES-APPRENANT

**GES-APPRENANT** est une application de gestion des apprenants à l'**ODC (Orange Digital Center)**, développée en PHP en suivant l'architecture **MVC (Modèle-Vue-Contrôleur)**.

---

##  Objectif

Permettre une gestion centralisée et sécurisée des informations des apprenants, avec des accès différenciés selon les rôles (Admin, Apprenant, Vigile).

---

##  Architecture

- **Modèle (Model)** : Gère les interactions avec les données (fichiers ou base de données).
- **Vue (View)** : Affiche les interfaces utilisateur.
- **Contrôleur (Controller)** : Gère la logique métier et les requêtes utilisateurs.

---

## 👥 Rôles

- **Admin** :

  - Inscrire les apprenants.
  - Gérer les comptes (modification, suppression).
  - Consulter les statistiques.

- **Apprenant** :

  - Se connecter après inscription.
  - Modifier son mot de passe à la première connexion.
  - Accéder à un **dashboard responsive**.
  - Voir un **QR Code personnel** contenant ses informations (matricule, prénom, nom, email...).

- **Vigile** :
  - Scanner ou vérifier les QR codes des apprenants.
  - Contrôler l'accès aux locaux.

---

##  Fonctionnalités principales

- Authentification et gestion de session.
- Interface responsive.
- Génération de QR Code personnalisé.
- Séparation claire des rôles et des permissions.
- Validation manuelle des formulaires avec gestion des erreurs.

---

##  Technologies utilisées

- PHP (Vanilla)
- HTML/CSS
- JavaScript
- [Endroid QR Code](https://github.com/endroid/qr-code) (pour la génération de QR codes)

---

## Connexion

- Utilisateur Admin:

Admin1
login : admin1@gmail.com
password : admin123

Admin2
login : admin2@gmail.com
password : admin123
