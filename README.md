# Cahier des Charges - GeoPoint

## 1. Introduction

### Objectif du document
Ce document vise à définir les spécifications fonctionnelles et techniques pour le développement d'une application web destinée à la gestion et à la visualisation de points géographiques avec adresses postales sur une carte interactive.

### Portée du projet
Développement d'une solution web permettant aux utilisateurs de gérer des points d'intérêt, avec fonctionnalités de visualisation et de recherche par proximité.

## 2. Description du projet

### Contexte
Destinée à des utilisateurs variés, cette application facilitera la gestion et la visualisation de données géographiques.

### Objectifs
- Gérer des points d'intérêt sur une carte interactive.
- Recherche de points dans un rayon spécifique.
- Interface utilisateur intuitive pour la gestion des points.

## 3. Spécifications des utilisateurs

- **Utilisateurs finaux** : Toute personne nécessitant une gestion facile des points d'intérêt géographiques.
- **Administrateurs** : Gérer les utilisateurs et les données.

## 4. Exigences fonctionnelles

1. **Interface Utilisateur**
   - Carte interactive pour la visualisation des points.
   - Formulaire pour l'ajout et la modification des points.
   - Options de recherche par rayon.

2. **Gestion des données**
   - CRUD complet pour les points géographiques.
   - Sécurité des données utilisateurs et points.

## 5. Spécifications techniques

- **Backend** : Java avec Spring Boot.
- **Frontend** : React avec Next.js.
- **Base de données** : PostgreSQL avec PostGIS.
- **API** : RESTful API pour les interactions front/back-end.

## 6. Sécurité

- **Authentification** : JWT pour sécuriser l'accès à l'API.
- **Autorisations** : Niveaux de contrôle pour divers rôles utilisateur.

## 7. Déploiement et maintenance

- **Environnement de déploiement** : Cloud (AWS, Azure, etc.).
- **Maintenance** : Mises à jour régulières et monitoring.
