## Pegatina lujosa de un robot

Puedes hacer una pegatina con degradado utilizando una imagen. Si utilizas una imagen con un fondo transparente, el degradado se verá a través de él.

También puedes crear degradados que van en diferentes direcciones.

+ Añade una pegatina a ` index.html ` utilizando la imagen` firerobot.png `:
    
    ![captura de pantalla](images/stickers-fire-html.png)
    
    Puedes ajustar `height` para redimensionar la imagen, el ancho cambiará automáticamente.

+ Normalmente, un degradado lineal se ejecuta de arriba a abajo, pero puede usar ` to` para cambiar la dirección. Por ejemplo: `to top`, `to left` o `to right`.
    
    Para un gradiente diagonal se dan dos direcciones. Este ejemplo usa `to bottom left`.
    
    Agrega este estilo a ` style.css ` para darle a tu nueva etiqueta de robot un degradado diagonal y un borde elegante:
    
    ![captura de pantalla](images/stickers-fire-gradient.png)
    
    Ten en cuenta que puedes utilizar `outline` para crear otro borde por fuera del habitual. `outline-offset` da la separación entre el borde y el contorno.

+ Añadamos algo de texto a esta pegatina.
    
    Agrega un `<span>` que contenga el texto "ROBOTS" a ` index.html ` y dale un id.
    
    ![captura de pantalla](images/stickers-fire-span.png)

+ El texto se verá mejor si lo haces más grande y lo posicionas.
    
    Para posicionar el texto, debes agregar `position: relative; ` a ` #greensticker ` y `position: absolute` a ` #greentext `. El posicionamiento se trata con más detalle en el proyecto ` Construye un robot `.
    
    Agrega el siguiente código a ` style.css `:
    
    ![captura de pantalla](images/stickers-fire-text-style.png)

+ Y para el detalle final, giremos el texto usando `transform: rotate`.
    
    ![captura de pantalla](images/stickers-fire-rotate.png)
    
    Intenta cambiar el número de grados en que se gira el texto.