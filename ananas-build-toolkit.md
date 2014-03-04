# Ananas Build Toolkit 

## Installation des dépendances

```
./composer.phar install --prefer-dist
```

## Configuration 

Si on a profil du même nom le nom d'utilisateur linux 

```
ant configure build 
```

## Déploiement des sites

 ### En production 

```
ant deploy -D profile=jeroboam 
```

