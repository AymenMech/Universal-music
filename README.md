UniversalMusic
==============

A Symfony project created on November 14, 2016, 9:20 am.

Evaluation sur Symfony.


Après clonage du dépot, exécuter la commande :
 $ composer install
 
Puis regler les configs dans 
app/config/parameters.yml
le nom de la bdd est 'media'

le schéma de la bdd se trouve dans le fichier data.sql
 app/console doctrine:database:create
 mysql -u root -p < data.sql
 
 
    