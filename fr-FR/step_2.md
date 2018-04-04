## Sticker codage coloré

Un dégradé est un changement graduel d'une couleur à une autre. Les dégradés peuvent être utilisés pour créer des effets cool. Vous allez les employer pour créer des stickers que vous pouvez utiliser sur vos pages Web. 

+ Ouvrez ce trinket : <a href="http://jumpto.cc/web-stickers" target="_blank">jumpto.cc/web-stickers</a>. 

	Le projet doit ressembler à ça :

	![screenshot](images/stickers-starter.png)

+ Faisons un sticker 'I <3 Coding'. 

	Utilisez une `<div>` avec une classe `sticker` et un id `coding` pour que vous puissiez y appliquer un style : 

	![screenshot](images/stickers-coding-error.png)


+ Hmm vous venez d'avoir une erreur ? C'est parce que '<' est un caractère spécial en HTML. À la place de '<', vous devez utiliser le code spécial `&lt;`. 

	Mettez à jour votre code pour utiliser `&lt;` afin que l'erreur disparaisse. 

	![screenshot](images/stickers-coding-fixed.png)

	`<br>` donne une nouvelle ligne. 

+ Maintenant, rendons le sticker plus intéressant. 

	Passez au fichier `style.css`. Vous allez voir que la classe `.sticker` vous a été fournie. Elle agencera les stickers sur la page et centrera leur contenu. 

	Souvenez-vous que vous avez ajouté l'id `coding` à votre sticker. Au bas de `style.css`, ajoutez le code suivant pour styliser le texte :

	![screenshot](images/stickers-coding-font.png)

+ Maintenant, vous pouvez ajouter un dégradé à l'arrière-plan du sticker. Un dégradé linéaire passe d'une couleur à une autre le long d'une ligne droite.

	Ce dégradé sera rouge au sommet et magenta en bas. Ajoutez le code dégradé à votre style `coding` :

	![screenshot](images/stickers-coding-gradient.png)

+ Vous pouvez améliorer le résultat en ajoutant un remplissage et des angles arrondis. 

	Ajoutez le code en surbrillance :

	![screenshot](images/stickers-coding-padding.png)

	Le style `padding` ajoute un remplissage de 50 px au sommet et au bas et de 30 px à gauche et à droite. 

