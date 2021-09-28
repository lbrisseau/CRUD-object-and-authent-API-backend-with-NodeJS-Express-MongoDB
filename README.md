# API Backend en NodeJS-Express-MongoDB fonctionnelle pour CRUD d'un objet Thing
structurée avec router, controller et middleware

## GET: /api/products
Retournera tous les produits

## GET: /api/stuff/:id
Retournera le produit avec le _id fourni

## POST: /api/stuff
Créera un nouveau Thing dans la base de données.
Il retournera le Thing ainsi créé (y compris son champ _id ).

## PUT: /api/stuff/:id
Modifiera le produit avec le _id fourni selon les données envoyées dans le corps de la requête.

## DELETE: /api/products/:id
Supprimera le produit avec le _id fourni.

# API Backend en NodeJS-Express-MongoDB fonctionnelle pour Authent (login et signup) d'un User
structurée avec router, controller et middleware

## POST: /api/auth/signup
Créera un nouveau User dans la base de données.

## POST: /api/auth/login
Réalise l'authent du client gâce au module bcrypt
