<!-- TITLE: Tutoriel : Créer une page Wiki -->
<!-- SUBTITLE: Comment contribuer au Wiki -->

Cet article décrit la procédure à suivre pour contribuer au Wiki.

# Créer une page
Pour créer une page, rien de plus simple. Cliquez simplement sur le bouton `+CRÉER` qui est visible dans le bandeau en haut à droite du site.
Il vous sera alors demandé d'entrer le nouveau "chemin de la page".
Le chemin d'une page, ça ressemble à cela : 

```
dossier1/dossier2/mon_fichier
```
Ce chemin signifie qu'un fichier nommé `mon_fichier` sera créé dans le dossier `dossier1` et dans le sous-dossier `dossier2`.

```
dossier1
└── dossier2
    └── mon_fichier
```

Une fois validé, vous serez redirigé vers la source de la page vide, c'est à dire que vous pourrez créer le contenu.

 Attention : Afin que le projet reste clair, il est primordial de ne pas créer des fichiers n'importe où. Il faut utiliser des dossiers pour regrouper les choses similaires entre elles (comme on le ferait sur son propre PC). Par exemple, tout ce qui concerne l'atelier devra être dans un dossier nommé `atelier`, éventuellement avec des sous-dossier à l'intérieur.

Garder une architecture claire est le seul moyen d'empêcher le projet de partir dans tous les sens ! Merci :)


# Modifier une page

Pour modifier une page, c'est également très simple, il suffit de cliquer sur le bouton `ÉDITER` qui est visible dans le bandeau en haut à droite du site.

Une fois cliqué, vous serez redirigé vers la source de la page, c'est à dire que vous pourrez modifier le contenu.

# Rédiger une page

Cette partie la est plus compliquée. Effet, pour écrire une page de Wiki, il faut respecter une syntaxe très particulière appelée `Markdown`.

Notez que la plupart des fonctionnalités sont facilement disponibles en cliquant directement dans la barre du haut. Par exemple, vous pourrez facilement mettre un titre, mettre en gras, souligner, mettre en italique, créer des listes, etc... en utilisant juste les boutons de l'interface.

Pour vous entraîner, je vous recommande vivement d'aller sur le site [https://stackedit.io/app](https://stackedit.io/app). Ce site permet d'écire du `Markdown` dans la partie gauche de l'écran, et de voir le résultat dans la partie droite.

Pour aller plus loin, il est tout de même nécéssaire de connaître la syntaxe `Markdown` dont les règles princpiales sont expliquées ci-dessous :


## Sommaire  
[Titres](#titres)  
[Italique, gras, rayé](italique_gras_raye)  
[Listes](#listes)  
[Liens](#liens)  
[Images](#images)  
[Bloc de code](#bloc_de_code)  
[Tableaux](#tableaux)  
[Blocs de citations](#citations)  
[Trait horizontal](#trait_horizontal)  
[Saut de ligne](#saut_de_ligne)  
[Vidéos YouTube](#videos)

<a name="titres"/>

# Titres

```
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6
```

# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6

<a name="italique_gras_raye"/>

# Italique, gras, rayé

```
Pour faire de l'italique, on met le texte entre *astérisques*.

Pour mettre en gras, on utilise des doubles **astérisques**.

On peut combiner **gras et *italique***.

Pour rayer le texte, on met le texte entre deux ~~tildes~~.
```

Pour faire de l'italique, on met le texte entre *astérisques*.

Pour mettre en gras, on utilise des doubles **astérisques**.

On peut combiner **gras et *italique***.

Pour rayer le texte, on met le texte entre deux ~~tildes~~.


<a name="listes"/>

# Listes

```
1. Premier élément de la liste
1. autre élément
   * une sous liste. 
1. Un 3ème élément (remarquez que le nombre que l'on écrit au début n'a pas besoin d'être le bon, il suffit de mettre un 1)
   1. Une sous liste ordonnée
   1. Un autre élément de la sous liste ordonnée
1. Un dernier élément.
```

1. Premier élément de la liste
1. autre élément
   * une sous liste. 
1. Un 3ème élément (remarquez que le nombre que l'on écrit au début n'a pas besoin d'être le bon, il suffit de mettre un 1)
   1. Une sous liste ordonnée
   1. Un autre élément de la sous liste ordonnée
1. Un dernier élément.

<a name="liens"/>

# Liens

Il y a plusieurs façon de faire un lien :

```
[Je suis un lien](https://www.google.com)

[Je suis un lien avec un titre](https://www.google.com "Page d'acccueil de Google")

[Je suis un lien de type référence][reference]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[On peut utiliser des nombres pour les liens de type référence][1]

Les URLS ou URLs entre chevrons sont automatiquement changés en liens.
http://www.example.com ou <http://www.example.com>.

Du texte pour montrer que les lien de type référence peuvent suivre.

[reference]: https://www.google.com
[1]: https://fr.wikipedia.org
[Le texte du lien]: http://www.google.com
```
[Je suis un lien](https://www.google.com)

[Je suis un lien avec un titre](https://www.google.com "Page d'acccueil de Google")

[Je suis un lien de type référence][reference]

[Je suis un lien relatif vers une page du wiki](/tuto/page-wiki)

[On peut utiliser des nombres pour les liens de type référence][1]

Les URLS ou URLs entre chevrons sont automatiquement changés en liens.
http://www.exemple.com ou <http://www.exemple.com>.

Du texte pour montrer que les lien de type référence peuvent suivre.

[reference]: https://www.google.com
[1]: https://fr.wikipedia.org
[Le texte du lien]: http://www.google.com

<a name="images"/>

# Images

```
Voici le logo de l'école Boulle (passer la souris dessus pour voir le texte):

![Description de l'image, si l'image ne s'affiche pas](https://www.orbec.fr/wp-content/uploads/2017/01/logo-Ecole-Boulle-212x300.jpg "Logo de l'école Boulle")
```

Voici le logo de l'école Boulle (passer la souris dessus pour voir le texte):

![Description de l'image, si l'image ne s'affiche pas](https://www.orbec.fr/wp-content/uploads/2017/01/logo-Ecole-Boulle-212x300.jpg "Logo de l'école Boulle")

Pour ajouter une image qui ne vient pas d'internet, vous pouvez utiliser les boutons du bandeau en haut pour envoyer une image directement sur le site.

<a name="bloc_de_code"/>

# Bloc de code

```
On peut mettre en valeur un `mot` en le mettant entre apostrophes inversées.
```
On peut mettre en valeur un `mot` en le mettant entre apostrophes inversées.


pre lang="no-highlight"code
```
On peut écrire un bloc de code en mettant 3 apostrophes inversées.
Dans un bloc de code, je peux écrire du *Markdown* sans qu'il soit mis en forme.
```
/code/pre



```
On peut écrire un bloc de code en mettant 3 apostrophes inversées.
Dans un bloc de code, je peux écrire du *Markdown* sans qu'il soit mis en forme.
```

<a name="tableaux"/>

# Tableaux


```
Des `:` permettent de choisir l'alignement des colonnes. On peut aussi mettre du `Markdown` dedans

| Alingé à gauche | Centré | Alingé à droite |
| --------------- |:------:| ---------------:|
| `élément 1` | *mot 1* | **Coucou** |
| élément 2 | mot 2 | les |
| ~~élément 3~~ | mot 3 | amis |
```
Des `:` permettent de choisir l'alignement des colonnes. On peut aussi mettre du `Markdown` dans les cellules.

| Alingé à gauche | Centré | Alingé à droite |
| --------------- |:------:| ---------------:|
| `élément 1` | *mot 1* | **Coucou** |
| élément 2 | mot 2 | les |
| ~~élément 3~~ | mot 3 | amis |

<a name="citations"/>

# Blocs de citations

```
> Ceci est un bloc de citation.
> Cette ligne fait partie de la même citation.

Ceci est une pause dans la citation.

> Ceci est une très très longue ligne qui va tout de même s'affiche proprement comme une citation. Aller... pour s'assurer que la phrase soit suffisamment longue, j'écris du texte au hasard. Et en plus je peux mettre du `Markdown` dedans.
```

> Ceci est un bloc de citation.
> Cette ligne fait partie de la même citation.

Ceci est une pause dans la citation.

> Ceci est une très très longue ligne qui va tout de même s'affiche proprement comme une citation. Aller... pour s'assurer que la phrase soit suffisamment longue, j'écris du texte au hasard. Et en plus je peux mettre du `Markdown` dedans.

<a name="trait_horizontal"/>

# Trait horizontal

```
Trois tirets ou plus... et une ligne apparaît !

---
```
Trois tirets ou plus... et une ligne apparaît !

---

<a name="saut_de_ligne"/>

# Saut de ligne

Le mieux pour comprendre comment les sauts de ligne fonctionne, c'est d'essayer d'appuyer sur `Enter` plusieurs fois. Grosso modo, il faut faire deux sauts de ligne en `Markdown` pour faire un saut de ligne dans la page.

```
Voici une ligne pour commencer.

Cette ligne est séparée de la précédente par 2 sauts de ligne. Elle sera donc visible dans un *paragraphe différent*.

Cette ligne est aussi dans un paragraphe séparé, mais...
Cette ligne est seulement séparée par un seul saut de ligne. Elle sera donc considérée comme étant du *même paragraphe*.
```

Voici une ligne pour commencer.

Cette ligne est séparée de la précédente par 2 sauts de ligne. Elle sera donc visible dans un *paragraphe différent*.

Cette ligne est aussi dans un paragraphe séparé, mais...
Cette ligne est seulement séparée par un seul saut de ligne. Elle sera donc considérée comme étant du *même paragraphe*.

<a name="videos"/>

# Vidéos YouTube

On ne peut pas mettre directement de vidéo Youtube, mais on peut mettre une image avec un lien vers la vidéo comme ceci :

```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=IDENTIFIANT_DE_LA_VIDEO_YOUTUBE_ICI
" target="_blank"><img src="http://img.youtube.com/vi/IDENTIFIANT_DE_LA_VIDEO_YOUTUBE_ICI/0.jpg" 
alt="Texte à affiche si problème d'affichage" width="240" height="180" border="10" /></a>
```

Vous trouverez l'identifiant de la vidéo en allant voir la vidéo sur Youtube. Dans l'url de la vidéo, vous pourrez lire l'identifiant.

Par exemple, si le lien d'une vidéo est `https://www.youtube.com/watch?v=yqE6xH901ow`, alors l'identifiant est yqE6xH901ow.
Ce qui nous donne :

<a href="http://www.youtube.com/watch?feature=player_embedded&v=yqE6xH901ow
" target="_blank"><img src="http://img.youtube.com/vi/yqE6xH901ow/0.jpg" 
alt="Texte à affiche si problème d'affichage" width="240" height="180" border="10" /></a>
