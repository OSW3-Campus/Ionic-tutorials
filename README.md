# Création d'un projet Ionic + Angular
> ### Objectifs :
> Savoir créer un nouveau projet Ionic + Angular
> ### Notes :
> Dans ce cours, le terme **my-project** réprésente le nom du projet. Remplacez ce terme par le nom de votre projet.




# Création d'un projet 

```bash
ionic start my-project
```

Avant d'installer le projet, plusieurs question vous seront posées afin de déterminer quelles dépendances de base Angular doit installer :

```bash
? Try Ionic 4? (y/N) 
? Starter template: (Use arrow keys)
  tabs
❯ blank
  sidemenu
  super
  tutorial
  aws
? Integrate your new app with Cordova to target native iOS and Android? (y/N) 
? Install the free Ionic Pro SDK and connect your app? (Y/n) 
```



# Se rendre dans le répertoire du projet

Pensez maintenant à pointer votre Terminal dans le répertoire de votre nouveau projet pour pouvoir travailler.

```bash
cd my-project
```



# Utiliser les options

- L'option `--type` permet de définir le type de projet : angular, ionic-angular ou ionic1.

```bash
ionic start my-project blank --type=angular --cordova=true
ionic start my-project tutorial --type=ionic-angular --cordova=true
ionic start my-project aws --type=ionic-angular --cordova=true
```



# Avant d'aller plus loin

Pour les tutoriels suivant nous nous baserons sur la commande d'installation suivante :

```bash
ionic start my-project blank --type=angular --cordova=true
```

Notre projet Ionic sera basé sur le framework Angular (`--type=angular`) et intégrera Cordova pour la compatibilité iOS et Android (`--cordova=true`)