## Pegatina colorida de programación

Un degradado o gradiente es un cambio gradual de un color a otro. Los gradientes se pueden utilizar para crear efectos geniales. Los vas a utilizar para crear adhesivos que puedes usar en tus páginas web.

+ Abre este Trinket: <a href="http://jumpto.cc/web-stickers" target="_blank">jumpto.cc/web-stickers</a>.
    
    El proyecto debería parecerse a esto:
    
    ![captura de pantalla](images/stickers-starter.png)

+ Hagamos una pegatina "Yo <3 programar"g' sticker.
    
    Utiliza un `<div>` con una clase `sticker` y una Identificación `coding` para que puedas darle estilo:
    
    ![captura de pantalla](images/stickers-coding-error.png)

+ Hmm, ¿notaste que recibiste un error? Esto se debe a que '<' es un carácter especial en HTML. En lugar de '<' necesitas usar el código especial `&lt; `.
    
    Actualiza tu código usando `&lt; ` para que el error desaparezca.
    
    ![captura de pantalla](images/stickers-coding-fixed.png)
    
    `<br>` da una nueva línea.

+ Ahora vamos a hacer que la pegatina se vea interesante.
    
    Cambia al archivo ` style.css`. Verás que ya tienes la clase `.sticker `. Esto diseñará pegatinas en la página y centrará su contenido.
    
    Recuerda que agregaste el la identificación `coding` a tu pegatina. En la parte inferior de ` style.css ` agrega el siguiente código para darle estilo al texto:
    
    ![captura de pantalla](images/stickers-coding-font.png)

+ Ahora puedes agregar un gradiente para el fondo de la etiqueta. Un degradado lineal cambia de un color a otro a lo largo de una línea recta.
    
    Este gradiente cambiará de rojo en la parte superior a magenta en la parte inferior. Agrega el código de gradiente a tu estilo `coding`:
    
    ![captura de pantalla](images/stickers-coding-gradient.png)

+ Puedes mejorar el resultado agregando espacio alrededor y esquinas redondeadas.
    
    Agrega el código resaltado:
    
    ![captura de pantalla](images/stickers-coding-padding.png)
    
    El estilo `padding` agrega espacio de 50px en la parte superior e inferior y 30px a la izquierda y a la derecha.