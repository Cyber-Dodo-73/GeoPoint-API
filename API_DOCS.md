# Documentation API - Gestion de Points Géographiques

## Base URL

`https://api.monapplication.com/v1`

## Endpoints

### GET /points

- **Description** : Liste tous les points géographiques.
- **Responses** :
  - `200` : Une liste de points (type: `array` de `Point`).

### POST /points

- **Description** : Ajoute un nouveau point géographique.
- **Request Body** : Requiert un objet `Point`.
- **Responses** :
  - `201` : Point créé.
  - `400` : Données invalides.

### GET /points/{id}

- **Description** : Récupère un point spécifique par son ID.
- **Path Parameters** :
  - `id` (integer) : ID du point.
- **Responses** :
  - `200` : Détails du point.
  - `404` : Point non trouvé.

### PUT /points/{id}

- **Description** : Met à jour un point existant.
- **Path Parameters** :
  - `id` (integer) : ID du point.
- **Request Body** : Requiert un objet `Point`.
- **Responses** :
  - `200` : Point mis à jour.
  - `400` : Données invalides.
  - `404` : Point non trouvé.

### DELETE /points/{id}

- **Description** : Supprime un point.
- **Path Parameters** :
  - `id` (integer) : ID du point.
- **Responses** :
  - `204` : Point supprimé.
  - `404` : Point non trouvé.

## Schema Definition

### Point

- **id** : integer, identifiant unique du point.
- **latitude** : double, latitude géographique.
- **longitude** : double, longitude géographique.
- **adresse** : string, adresse postale associée.
