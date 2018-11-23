# Projet Symfony A2 DW IIM 2018
## Date de rendu maximum : 30 novembre 2018, 23:59

### Création d'un site internet administrable avec back-office sous Symfony 4

### Fonctionalités requises :

#### Back-office éditable

- Posts de blog
	- Création d'un post
	- Édition d'un post
	- Mise à jour d'un post
	- Supression d'un post 	
	
	Un post doit contenir :
	
	- Titre
	- Description
	- Date de création
	- Catégorie prédéfinie (select)	

- Liste de pages

	- Édition une page (home / about / contact)
	- Mise à jour de page (home / about / contact)

	3 pages doivent être crées :
	
	- Page home
	- About
	- Contact
	
	Une page doit contenir :
	
	- Titre
	- Description
	- Type (home ou about ou contact)
	- Date de création

Le champ "Type" doit être unique. Chaque page doit être unique.

- Connexion utilisateur pour administration. Lien de déconnexion.

**Les posts, pages et utilisateurs doivent être généres via des fixtures.**

#### Front office

- Générer une route pour :
	- Page home
	- Page about
	- Page contact
	- Page liste de blogs (ou mettre la liste des posts du blog sur la page home)
	- Page(s) de(s) post(s). Un post = une page, dont la route est générée dynamiquement.

### Points bonus : 

- Pagination pour la page "liste des posts" (ou la homepage)
- Code aux normes PSR-2 (https://www.php-fig.org/psr/psr-2/)
- Back-office HTML propre

## Pour vous aider :

- Template back-office gratuit : https://adminlte.io/
- Template front-office gratuit : https://startbootstrap.com/template-overviews/clean-blog/

## Quelques liens utiles

Controller Symfony : https://symfony.com/doc/current/controller.html

Routing Symfony : https://symfony.com/doc/current/routing.html

Syntaxe twig : https://twig.symfony.com/

Formulaires Symfony : https://symfony.com/doc/current/forms.html

Doctrine : https://symfony.com/doc/current/doctrine.html

## Quelques commandes utiles

`cache:clear` Clears the cache

`doctrine:database:create` Creates the configured database

`doctrine:fixtures:load` Load data fixtures to your database

`doctrine:schema:update --force` Executes the SQL needed to update the database schema to match the current mapping metadata

`make:auth` Creates a Guard authenticator of different flavors

`make:controller` Creates a new controller class

`make:crud` Creates CRUD for Doctrine entity class

`make:entity` Creates or updates a Doctrine entity class, and optionally an API Platform resource

`make:fixtures` Creates a new class to load Doctrine fixtures

`make:form` Creates a new form class

`make:user` Creates a new security user class

`make:validator` Creates a new validator and constraint class

`server:run` Runs a local web server

## Livraison
Mettre votre prénom et nom dans la description du repository GitHub.
M'ajouter à votre repository git privé (@pgrimaud), et m'envoyer le lien par email à grimaud.pierre@gmail.com.


Bon courage
