# blog-template

## Avant-propos

Dans le cadre d'une collaboration entre le cours English For Science et le cours  de Science des données I, vous êtes amené à créer un blog scientifique. Ce blog va comprendre des articles qui traitent d'analyse de la littérature de vulgarisation scientifique et de description de données.

Ce dernier est un projet qui va évoluer avec votre progression dans les différents modules. Pour ce faire, suivez avec attention les attendus pour chaque module.

Il est possible que ce document évolue au cours du temps. N'hésitez pas à aller vérifier le lien suivant afin de voir les modifications dans les consignes : https://github.com/BioDataScience-Course/blog-template

----

## Module 1

### Objectif

- Créer votre site web scientifique personnel

### Procédure

Vous allez réaliser votre premier **fork** et le cloner en local. Suivez les étapes suivantes :

Sur GitHub :

0. Connecter vous à GitHub si cela est nécessaire
1. Cliquer sur `Use this template`
2. Nommer votre dépots en respectant l'exemple (ex: guyliann/guyliann_blog)
3. Compléter la description en un phrase en anglais (ex:  my personal blog)
4. Cliquer sur `Create repository from template`

Vous venez de créer votre repository

5. Cliquer sur `code`
6. Cliquer sur le bouton pour copier l'URL (https)

Dans RStudio :

7. Cliquer sur `Project` puis `New Project...`, puis `Version Control`, puis `Git`
8. Copier votre URL du point 6 dans la section `Repository URL` (La section `Project directory name` se complète automatiquement sur base de l'URL copié.)
9. Cliquer sur `Browse...` de la section `Create project as subdirectory of`. Sélectionner le dossier `shared` puis `projects`

Vous venez de créer votre dépôt local de votre blog personnel. Vous devez éditer plusieurs fichiers afin de rendre votre site accessible en ligne.

Dans le fichier `_site.yml`

11. Editer la ligner 2 `title`, nommez votre blog
12. Editer la ligne 13 `href`, remplacer l'url par l'url de votre blog sur github. (ex: https://github.com/Guyliann/guyliann_blog)
13. Editer la ligne 14 `base_url`, remplacer l'url par `profil github + .github.io/ + nom de votre dépot + /` (ex: guyliann.github.io/guyliann_blog/, que l'on peut traduire par `profil github + .github.io/ + nom de votre dépot + /`)

Dans le fichier `index.Rmd`

14. Editer la ligne 2 par le titre de votre blog.

Dans la section Build ( en haut à droite de votre IDE RStudio),

15. Cliquer sur `Build Website`

Dans la section `Git`

16. Réalisez un `Commit` et un `Push` de vos modifications.

Dans votre dépôt en ligne sur Github, 

17. Cliquer sur Settings 
18. Dans la section Github Pages, aller dans la setion GitHub Pages, remplacer None par `Master` et `docs`

Au bout de quelques minuts votre site sera en ligne.

### Etat de progression

A la fin de ces modules, vous devez avoir créé votre site web. Ce site doit comprendre les informations de base afin de vous identifier (il ne s'agit donc pas de laisser le template de base sans aucune modification). Vous devez éditer le fichier about.Rmd qui se situe dans `_posts/about/about.Rmd`.

Lorsque vous avez édité un article, vous devez cliquer sur Knit afin de créer votre article. Ensuite vous devez aller dans la section `Build` et cliquez sur `Build Website`

- Vous devez avoir complété la section about me.

-----

## Module 2

### Objectif

- Rédiger votre premier article

### Procédure

Dans Rstudio

1. Ouvrer votre projet de blog

Dans la console de RStudio,

2. Entrer l'instruction suivante 

```
distill::create_post("mon article")
```

### Etat d'avancement 

A la fin de ce module, vous devez 

- avoir créé votre premier article.
- avoir ajouté disqus à votre site. 

-----

## Module 4

### Etat d'avancement 

A la fin de ce module, vous devez proposer un court article qui comprend un graphique dont vous proposez une description **en anglais**. Cet article doit débuter par 2-3 lignes qui présente le sujet du graphique. En dessous du graphique, vous devez écrire 2-3 lignes afin d'expliquer le graphique.


Consultez le site suivant afin de personnaliser votre blog <https://rstudio.github.io/distill/blog.html>

