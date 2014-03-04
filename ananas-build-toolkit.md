# Ananas Build Toolkit 

## Installation des dépendances

```
./composer.phar install --prefer-dist
```

## Configuration 

Si il y a un profile avec le même nom que l'utilisateur linux

```
ant configure build 
```

## Déploiement des sites

### En production 

```
ant deploy -D profile=jeroboam 
```

