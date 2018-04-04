## Sticker robot fantaisiste

Vous pouvez faire un sticker dégradé en utilisant une image. Si vous utilisez une image avec un arrière-plan transparent, alors le dégradé se verra à travers. 

Vous pouvez aussi créer des dégradés dans plusieurs directions différentes. 

+ Ajoutez un sticker à `index.html` en utilisant l'image `firerobot.png` :

	![screenshot](images/stickers-fire-html.png)

	Vous pouvez ajuster la `height` pour redimensionner l'image, la largeur changera automatiquement. 

+ Normalement, un dégradé linéaire part du haut vers le bas, mais vous pouvez utiliser `to` pour changer la direction. Par exemple : `to top`, `to left`, ou `to right`.

	Pour un dégradé diagonal, vous avez deux directions. Cet exemple utilise `to bottom left`.

	Ajoutez ce style à `style.css` pour donner à votre nouveaux stick robot un dégradé diagonal et une bordure fantaisiste :

	![screenshot](images/stickers-fire-gradient.png)

	Notez que vous pouvez utiliser `outline` pour créer une autre bordure en dehors de l'habituelle. 
	`outline-offset` donne l'écart entre la bordure et le contour. 

+ Ajoutons un peu de texte à ce sticker. 

	Ajoutez un `<span>` contenant le texte "ROBOTS" à `index.html` et donnez-lui un id. 

	![screenshot](images/stickers-fire-span.png)

+ Le texte aura une meilleure apparence si vous le grossissez et le positionnez. 

	Pour positionner le texte, il vous faudra ajouter `position: relative;` à `#greensticker` et `position: absolute` à `#greentext`. Le positionnement est abordé plus en détails dans le projet `Construire un robot`. 

	Ajoutez le code suivant à `style.css`:

	![screenshot](images/stickers-fire-text-style.png)

+ Et pour le twist final, faisons pivoter le texte en utilisant `transform: rotate`.

	![screenshot](images/stickers-fire-rotate.png)

	Essayez de changer le nombre de degrés de rotation du texte. 


