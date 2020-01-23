
<img src="https://symphonies-boreales.web.app/img/logo.png" alt="Logo symphonies boréales" title="Symphonies boréales" align="right" height="60" />

Symphonies boréales
======================

- [Installer le site sur son poste](#installer-le-site-sur-son-poste)
- [Modifier les fichiers du site](#modifier-les-fichiers-du-site)
- [Éditer les sections du site](#diter-les-sections-du-site)
    - [Accueil](#accueil)
    - [Pages informationnelles](#pages-informationnelles)
    - [Membres d'équipe](#membres-dquipe)
    - [TODO articles / salle de presse](#articles--salle-de-presse)

## Installer le site sur son poste

Cloner le projet Git. 

`git clone https://github.com/symphoniesboreales/symphoniesboreales.git`

Installer [Hugo](https://gohugo.io/getting-started/installing).

Dans le répertoire où le projet a été cloné, rouler la commande
`hugo serve`.

Pointer ensuite son navigateur web sur l'adresse `http://localhost:1313/`

## Modifier les fichiers du site

Deux méthodes possibles:

1. Éditer directement les fichiers à partir de github.
2. Cloner le répertoire git sur son poste:

`git clone https://github.com/symphoniesboreales/symphoniesboreales.git`

Effectuer les modifications désirées sur les fichiers sur son poste.

Lorsque prêt à pousser les modifications sur github, lancer les commandes suivantes:


`git add .` (marque tous les fichiers du répertoire courant pour modification)

`git commit` (permet de journaliser l'ensemble des changements avec un message)

`git push oridign` (pousse les modifications vers le répertoire sur github.com)

## Éditer les sections du site

### Accueil

Le contenu de la bannière "à la une" peut être édité grâce au fichier suivant:

`/data/carousel/a-la-une.yaml`.

Il est possible de remplacer l'image de fond:

`/static/img/a-la-une.jpg`.

Les blocs d'aperçus de la page d'accueil sont situés dans le répertoire `/data/apercus`.

### Pages informationnelles

Tout le contenu des pages régulières doit être édité en respectant le standard [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Des [shortcodes](https://gohugo.io/content-management/shortcodes/) propres à hugo peuvent être utilisés pour insérer du contenu plus complexe.

Le contendu markdown des pages informationnelles se retrouve dans les répertoires suivants, selon la langue:
`/content/fr`
`/content/en`.

### Membres d'équipe

Présentement un composant alimente automatiquement les membres de l'équipe sous les pages à propos/about.
Pour modifier les membres d'équipe, éditer les fichiers dans le répertoire`/data/team`.

Les images des membres d'équipe doivent être déposées dans `/static/img/team-members`.

### Articles / salle de presse

TODO


