# Ananas Build Toolkit 

## Installation des dépendances

```
./composer.phar install --prefer-dist
```

## Configuration 

Si on a un profil du même nom que l'utilisateur linux 

```
ant configure build 
```

## Déploiement des sites

### En production 

```
ant deploy -D profile=jeroboam 
```

