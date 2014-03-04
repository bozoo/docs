Ananas Build Toolkit 
====================

Installation des dépendances
----------------------------

./composer.phar install --prefer-dist

Configuration 
-------------
Si il y a profile de configuration avec le même nom que l'user dans linux :

ant configure build 

Déploiement des sites
---------------------

- En production 

ant deploy -D profile=jeroboam 


