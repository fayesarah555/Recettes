# Recette

Web App sur lequelle il est possible de:
- crée une Recette
- modifier une Recette
- supprimer une Recette
- lire une Recette

Réalisée à l'aide de Ruby on Rails 
----------------------------------------------------------------------------------------------
##  Création de base de données

```bash
  rails g scaffold post titre:string ingredients:text
```

------------------------------------------------------------------------------------------------
##  Création du back

```bash
 rails new react-crud-video
```
------------------------------------------------------------------------------------------------
##  Création du front

```bash
  npx react-crud-rails frontend --template redux-typescript
```
------------------------------------------------------------------------------------------------
## Déploiement

Pour déployer ce projet, exécutez

Avoir aux préalables rails d'installer

pour le back:
```bash
  rails s
```
Pour le front:
```bash
  cd frontend
```
Pour les depandances:
```bash
  npm i  
```
```bash
  npm run start
```
---------------------------------------------------------------------------------------------------
## Tech Stack

**Client:** React, Redux, Typescript

**Server:** Rails
