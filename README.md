# EVALUATION 7

## Prérequis

-PHP 7 ou plus
-MySQL
-Apache2

## Plugins installés:

Yoast SEO  : plugin permettant d'aider l'utilisateur à améliorer son site afin d'etre mieux référencé.
All-in-One WP migration : Plugin de migration de site wordpress.



### GUIDE D'INSTALLATION

Pour installer le projet wordpress sur votre machine, il vous faut créer une base de donées vierge sur PHPmyAdmin Et creer un localhost avec apache2.

***

Ensuite, rendez vous sur votre navigateur à l'adresse que vous avez choisie dans le virtual host.

Suivez ensuite les instructions de wordpress afin de finaliser la création du site, en indiquant bien les informations de votre base de données. Et validez !

Si wordpress n'as pas pu créer de fichier wp-config, copier le texte indiquer et créer votre `wp-config.php` à la racine du dossier wordpress/ 

Choisissez le titre du site ainsi que l'identifiant et le mot de passe de l'administrateur.


Connectez vous.

***

Cliquez sur `extensions` et activer 
<dt>All-in-One WP Migration</dt>

Dans le menu d'administration est donc apparu le plugin, allez sur import et importez le fichier `.wpress`
Cliquez sur Proceed.

Le projet est désormais monté. 

