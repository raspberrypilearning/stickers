## Crear una pegatina con degradado lineal

Un degradado en un cambio progresivo de un color a otro. Los degradados se pueden usar para crear efectos alucinantes. Vamos a aprender a usarlos para crear pegatinas que podrás usar en tus páginas web. 

+ Abre este trinket: <a href="http://jumpto.cc/web-stickers" target="_blank">jumpto.cc/web-stickers</a>. Si estás leyendo este proyecto en línea, también puedes usar el trinket incrustado que encontrarás a continuación. 

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/af0ea6fa35" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

+ Vamos a hacer una pegatina en la que ponga 'Yo <3 Programar'. 

	Escribe un `<div>` con la class (categoría) `sticker` y el id `programar` para que le puedas dar estilo: 

	![screenshot](images/stickers-coding-error.png)


+ Vaya... ¿Te has dado cuenta de que da un error? Eso es porque '<' es un carácter especial en HTML. En lugar de '<' tendrás que usar el código especial `&lt;`. 

	Cambia tu código y usa `&lt;` para que desaparezca el error. 

	![screenshot](images/stickers-coding-fixed.png)

	`<br>` introduce una nueva línea. 

+ Ahora vamos a hacer que la pegatina parezca más interesante. 

	Cambia a la pestaña `style.css`. Verás que la categoría `.sticker` ya está creada. Con esto, las pegatinas se mostrarán en la página y su contenido se centrará.

	Recuerda que has añadido el id `programar` a tu pegatina. Al final de `style.css` incluye este código para dar estilo al texto:

	![screenshot](images/stickers-coding-font.png)

+ A continuación puedes añadir un degradado para el fondo de la pegatina. Un degradado lineal cambia de un color a otro a lo largo de una línea recta.

	Este degradado cambiará de rojo en la parte superior a magenta en la parte inferior. Añade el código de degradado al estilo `programar`:

	![screenshot](images/stickers-coding-gradient.png)

+ Puedes mejorar el resultado si añades relleno ("padding") y esquinas redondeadas. 

	Escribe el código resaltado:

	![screenshot](images/stickers-coding-padding.png)

	El estilo `padding` añade relleno de 50px en la parte superior en inferior y 30px a la derecha e izquierda. 
