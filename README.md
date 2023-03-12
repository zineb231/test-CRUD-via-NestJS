# test-CRUD-via-NestJS
ce projet contient 3 modules :
le module auth qui permet l'authentification des utilisateurs , ce module contient 3 fichiers un module qui contient les fournisseurs,
les contrôleurs et les services liés à l'authentification,un service d'authentification  qui gère la vérification des identifiants 
d'utilisateur et la génération de jetons JWT, le fichier jwt.strategy.ts gère la  stratégie d'authentification qui utilise 
un jeton JWT pour authentifier un utilisateur.
Module databases contient un fichier module  qui contient les fournisseurs et les services liés à la base de données , pour la base de données j'ai utilisé mysql,
j'ai essayé mongoDb dans un premier temps mais ça n'a pas marché,et le fichier database.providers.ts  qui définit les fournisseurs de la base de données.
Un module users qui contient un  contrôleur qui contient des routes et des gestionnaires de requêtes HTTP liés aux utilisateurs, un module qui contient les fournisseurs, 
les contrôleurs et les services liés aux utilisateurs et un service qui gère les opérations liées aux utilisateurs (création, mise à jour, suppression, etc...).
Le module ProductModule gère la fonctionnalité de récupération d'un produit à partir d'un code barre de l'API OpenFoodFacts saisi par utilisateur authentifié,
ce module contient un service qui permet l'appel de l'API OpenFoodFacts en utilisant la bibliothèque HTTP (axios), et le fichier module qui fait appel au service
dossier public contient les fichiers statiques dans mon cas un seu fichier d'authentification 
Ce test je l'ai effectué en s'appuyant sur mes compétences en NodeJs et bien evidemmment en s'inspirant des projets sur internet  et la documentation de NestJs.
