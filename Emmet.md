#EMMET

Bonjour,

Voici un  récapitulatif du “ Live Code “ sur Emmet:

Les liens utiles:

Le site d’Emmet : https://emmet.io/

Le site de la Doc : https://docs.emmet.io/

le site avec les cheat : https://docs.emmet.io/cheat-sheet/

un GitHub avec tout les raccourcis Emmet class par thèmes :

https://github.com/emmetio/emmet/blob/master/lib/snippets.json

Emmet s’utilise pratiquement dans tous les éditeurs de texte.

Visual studio, EMMET est déjà installé et peut être utilisé directement sur une page HTML et CSS.

ATOM, il faut l’installer pour cela il faut seulement, dans la “Welcome Page” cliquer sur “ Install a Package “, ou cliquer dans la barre de menu sur “File” ensuite sur “ Setting”, allez dans “ Install “.
Faire une recherche et sélectionner “ emmet “.

laissez l'installation se faire, cela utilisable tout de suite.


Pour Sublime Text :

allons sur le lien qui suit :

https://packagecontrol.io/installation

copier le texte :


Retournons sur Sublime Text :

ouvrir le La Console dans sublime avec la commande : “CTRL  + ` ( touche 7 ) ” ou menu VIEW et “Show Console”

Coller le texte et appuyer sur entrée
Faire Ctrl + Shift + P
taper Install choisir “ Package Control: Install Package “

faites une recherche sur Emmet

sélectionner le premier Emmet taper sur entrée

après l’installation vous pouvez utiliser directement Emmet sur une Page HTML et CSS

Je vais vous montrer des raccourcis pour une rapide utilisation d’Emmet.

je vais utiliser l'abréviation “tab” pour distinguer la touche tabulations.

pour créer une page HTML :

! + tab

pour ouvrir et fermer une balise :

taper votre balise ex:  h1 + tab.
ainsi de suite pour toute les balises HTML.
il y as aussi des raccourcis :
Header : hdr + tab
Footer : ftr + tab
Section: sect + tab

D’autres raccourcis peuvent etre tres utile mais n'oubliez pas de toujours faire tabulations après avoir écrit votre raccourcis

si vous voulais faire une div avec une class, vous devez seulement faire ca:

un point et le nom de la class ex :  	.nomdelaclass

si voulez en mettre plusieurs class sur une seule balise il faut les mettre les un a la suite des autres avec juste point pour les séparer et surtout pas d'espace.

Un fonction qui peut vous être utile.
vous souhaite imbriquer plusieur balise comme par exemple faire une liste avec des liens.

il vous suffit d'utiliser ce symbole “ > “ par exemple :

ul>li>a +tab
<ul>
	<li><a href= “”></a></li>
</ul>

mais nous ne faisons jamais de liste d’une seule ligne donc pour en faire plusieur il suffit de  multiplier avec ce symbole “ * “.

ul>li*5>a + tab

<ul>
	<li><a href= “”></a></li>
	<li><a href= “”></a></li>
	<li><a href= “”></a></li>
	<li><a href= “”></a></li>
	<li><a href= “”></a></li>
</ul>

et cette méthode marche avec toutes les balises HTML.

Vous voulez avoir plusieurs balises sur le même niveau il suffit de mettre “ + “

article>h2+p+img + tab
<article>
	<h2></h2>
	<p></p>
	<img></img>

<article>

pour finir nous utilisons bcp de text en LOREM, avec Emmet cela devient simple car
il suffit de taper “ lorem” entre des balises pour avoir un texte, si vous souhaitez choisir la longueur de ce texte ajoute simplement le nombre de mots colle a à “ lorem “

Je vous conseil de lire les sites au haut de la page elle vous seront très utile

je vous avez des questions ou d’aide n’hesite pas a me demander ;)
