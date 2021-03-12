Récapitulatif pour composer un fichier **Markdown**.
=  
**Liste des commandes à savoir**.

# Retour à la ligne

Pour éffectuer un retour à la ligne il faut appliquer deux espace après chaque fin de phrase puis entrée.

je suis un retour à la ligne `espace espace enter `

# **Gras** et _italique_

Écrire en gras et en italique est particulièrement facile avec Markdown. Il suffit d’utiliser les étoiles, appelées aussi astérisques. Pour écrire en italique, insérez tout simplement une étoile devant et derrière l’expression le mot ou concerné. Pour le gras, insérez deux étoiles avant et après. Pour le gras et l’italique, vous devrez opter pour trois étoiles. Une autre option consiste à utiliser les tirets bas.

`_Texte en italique_`  
`_Texte en italique_`  
`**Texte en gras**`  
`**Texte en gras**`  
`**_Texte en italique et en gras_**`  
`**_Texte en italique et en gras_**`

# ~~Barré~~ Barré

Pour barrer un texte avec Markdown, précédez-le de deux tildes et refermez la chaîne avec deux autres tildes.

`~~`Ce texte est barré.`~~` => ~~barré le texte~~ mais pas celui-là.

# Les titres

Par défaut, pour rédiger un titre avec Markdown, on utilise le dièse. On le sépare du texte avec une espace. Pour créer des sous-titres de hiérarchie inférieure, et donc rédigés en plus petits, il suffit d’insérer des dièses supplémentaires. Comme pour l’édition HTML, vous pourrez créer jusque 6 niveaux de sous-titres.

# Titre

`#` titre 1

`##` titre 2

`###` titre 3

`####` titre 4

`#####` titre 5

`######` titre 6

Les listes
=  
Si vous souhaitez établir une liste simple avec Markdown, vous avez le choix entre le `signe plus`, le `tiret` ou un `astérisque`. Ces trois options donnent le même rendu.

`-` Liste1

`-` Liste 2

`-` Liste 3

> Pour créer une liste numérotée, il vous suffira d’inscrire un chiffre suivi d’un point.

`1.` Liste 1  
`2.` Liste 2  
`3.` Liste 3

Markdown permet aussi d’éditer des listes à cocher. Ces listes sont précédées d’une case à cocher pouvant être activée par clic. Ces cases peuvent d’ailleurs être cochées par défaut au moment de la création de la liste. Pour ce faire, vous devez utiliser les crochets et le X.

- `[ ]` A

- `[x]` B

- `[ ]` C

# Lignes horizontales

---

---

Vous pouvez insérer une ligne horizontale dans votre texte. Pour cela il est nécessaire d'utiliser au moins trois symboles parmis :  
 les astérisques \*, les tirets - ou les barres de soulignement \_ , seuls, sur une ligne.  
 Si vous le souhaitez, des espaces peuvent être utilisés entre chaque charactère. Les lignes suivantes sont toutes valides :

`* * *`

`***`

`*****`

`- - -`

`------------------`

# Emphase

Le Markdown accepte deux caractères pour générer les balises HTML d'emphase : l'astérisque `*` et le caractère de soulignement `_`. Du texte placé entre l'un de ces deux symboles sera entouré par l’élément HTML `<em>`. Si on double ces caractères, alors le texte sera entouré de balises `<strong>`. Par exemple :

`*astérisques simples*` => _astérisques simples_

`_caractères de soulignement simples_` => _caractères de soulignement simples_

`**astérisques doublées**` => **astérisques doublées**

`__caractères de soulignement doublés__` => **caractères de soulignement doublés**

Code  
 =
Pour écrire un morceau de code dans un texte, Markdown l’identifie au moyen du caractère appelé le `Backtick` ` [``] ` ou apostrophe inversée.  
**Attention**, à ne pas confondre avec les guillemets. Le marquage est donc constitué d’une apostrophe inversée au début et à la fin du segment correspondant au code.  
 C’est ainsi que vous pourrez incorporer directement le code source ou une commande logicielle dans le texte.

C’est le `code`.

# Images et hyperliens

**Markdown** permet aussi d’insérer des images et des hyperliens dans votre texte. Cette insertion se fait en combinant des parenthèses et des crochets. Pour créer un lien, vous devrez écrire les mots ou les phrases visibles dans le texte entre crochets, suivis directement de l’adresse URL entre parenthèses. Si vous souhaitez ajouter au lien un titre facultatif, visible par l’utilisateur au survol de la souris, c’est tout à fait possible : ce texte devra être ajouté à l’adresse URL entre les parenthèses, mais sera séparé d’une espace de l’URL, et inscrit entre guillemets doubles.

Si vous insérez une adresse URL ou une adresse électronique dans votre texte ordinaire, la plupart des éditeurs Markdown créeront automatiquement un hyperlien accessible par clic. Pour forcer cette fonction, utilisez les signes inférieur et supérieur à. Si, en revanche, vous souhaitez empêcher les éditeurs d’activer cette fonction, marquez l’URL comme code, et utilisez à nouveau les apostrophes inversées.

> `<https://example.com>`  
> `https://example.com`

La syntaxe permettant d’insérer des images est semblable à celle des liens. On commence cependant par insérer un point d’exclamation. Suivent ensuite les crochets entre lesquels on insère le texte alternatif de l’image, puis l’URL de l’image entre parenthèses. L’image sera dans ce cas directement affichée dans le texte.

# Les tableaux

Les barres verticales (|) permettent d’éditer des tableaux avec Markdown. Chaque cellule du tableau est séparée d’une barre verticale. Pour créer des lignes de titre qui se distinguent du reste du tableau, vous devrez souligner les cellules concernées avec les tirets du 6.

`| cellule 1 | cellule 2 |`

`| --------- | --------- |`

`| A | B |`

`| C | D |`

Résultat prévisualisation :

| cellule 1 | cellule 2 |
| --------- | --------- |
| A         | B         |
| C         | D         |

Il n’est pas nécessaire d’aligner les barres verticales les unes en dessous des autres. Si elles sont alignées, la lisibilité du tableau est cependant meilleure dans la version brute du document Markdown. La même chose s’applique aux barres verticales latérales. Elles n’ont aucune utilité pour la compilation du document.

# Les notes de bas de page

Markdown vous permet aussi d’éditer des notes de bas de page. Ajoutez tout simplement dans votre texte un numéro d’annotation, et reprenez ce numéro en bas de votre page dans une note de bas de page. Markdown créera alors automatiquement une ligne. Le chiffre correspondant à l’annotation est automatiquement formaté en lien, ce qui vous permet d’atteindre la note de bas de page par un simple clic. Pour pouvoir bénéficier de cet automatisme, commencez par inscrire le numéro de l’annotation derrière le mot souhaité : commencez par écrire un accent circonflexe entre les crochets, suivi du numéro.

Le choix du chiffre (ou autres valeurs) n’a aucune espèce d’importance. Comme pour la création de liste, Markdown se charge de la numérotation. Ce qui est important, c’est de créer ensuite un renvoi vers la désignation que vous aurez sélectionnée. Pour ce faire, vous devez reprendre le même chiffre dans une nouvelle ligne, inséré à nouveau entre crochets avec un accent circonflexe, vous ajoutez le signe des deux points, et vous rédigez le texte de l’annotation. Ce texte pourra d’ailleurs faire l’objet d’un formatage de votre choix, et s’étendre sur plusieurs lignes.

Dans le texte ordinaire `[^1]` vous pouvez facilement placer des notes de bas de page `[^2]`

`[^1]`: Vous trouverez ici le texte de la note de bas de page.

`[^2]`:

`**Note de page de page**` peut aussi être

`_formatée_`.

Et celles-ci comprennent même plusieurs lignes

# & et <>

Markdown étant très proche de HTML, il convient de regarder de plus près à l’usage du « et commercial » ainsi que les signes supérieur et inférieur. Ces caractères sont employés en HTML pour ouvrir et fermer des balises (<>) ou pour travailler avec des entités (&). Si l’on veut utiliser ces caractères dans leur signification d’origine, il faudra les masquer en HTML : &, < et >. Avec Markdown, il n’y a normalement aucune raison de ne pas utiliser ces caractères tels quels. Mais comme il est possible pour les utilisateurs de combiner Markdown et HTML, la situation est un peu complexe. Pour vous éviter de devoir faire face à de tels problèmes, l’analyseur syntaxique sait faire la différence entre les moments où vous souhaitez utiliser ces caractères et les situations de code HTML.

A & B

1 < 2

# Masquer les barres obliques inversées

En plus des caractères spéciaux imposés par HTML, Markdown utilise quelques autres caractères pour le formatage. Si l’on insère ces caractères, l’analyseur syntaxique en tiendra compte au moment de la conversion.  
Voici les caractères concernés :

Astérisque :` \*`

Trait d’union :`-`

Souligné :`\_`

Parenthèses :`()`

Crochets : `[]`

Accolades : `{}`

Point : `.`

Point d’exclamation : `!`

Dièse :`#`

Accent grave :

Barre oblique inversée : `\ `

Si l’on veut utiliser ces caractères dans leur sens premier, il suffit de les précéder d’une barre oblique inversée. Important : Cette barre oblique inversée doit impérativement précéder chacun de ces caractères. Cela concerne donc autant une parenthèse ouvrante qu’une parenthèse fermante.
