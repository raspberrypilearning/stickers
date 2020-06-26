## Sticker elegante de un robot

Puedes crear un sticker de degradado usando una imagen. Si utilizas una imagen con un fondo transparente, el degradado se mostrará a través de la imagen.

También puedes crear degradados que van en diferentes direcciones.

+ Añade un sticker a `index.html` utilizando la imagen `firerobot.png`:
    
    ![captura de pantalla](images/stickers-fire-html.png)
    
    Puedes ajustar la `height` (altura) para redimensionar la imagen, el ancho cambiará automáticamente.

+ Normalmente, un degradado lineal se ejecuta de arriba a abajo, pero puedes usar `to` (hacia) para cambiar la dirección. Por ejemplo: `to top` (hacia arriba), `to left` (hacia la izquierda) o `to right` (hacia la derecha).
    
    Para un degradado diagonal se dan dos direcciones. Este ejemplo usa `to bottom left` (hacia abajo izquierda).
    
    Agrega este estilo a `style.css` para darle a tu nuevo sticker de robot un gradiente diagonal y un borde elegante:
    
    ![captura de pantalla](images/stickers-fire-gradient.png)
    
    Ten en cuenta que puedes utilizar `outline` (contorno) para crear otro borde por fuera del habitual. `outline-offset` (espacio-contorno) da la separación entre el borde y el contorno.

+ Añadamos algo de texto a este sticker.
    
    Agrega un `<span>` que contenga el texto "ROBOTS" a `index.html` y dale un id (identificador).
    
    ![captura de pantalla](images/stickers-fire-span.png)

+ El texto se verá mejor si lo haces más grande y lo posicionas.
    
    Para posicionar el texto, debes agregar `position: relative;` a `#greensticker` y `position: absolute` a `#greentext`. El posicionamiento se trata con más detalle en el proyecto `Build a Robot` (Construir un Robot).
    
    Agrega el siguiente código a `style.css`:
    
    ![captura de pantalla](images/stickers-fire-text-style.png)

+ Y para el detalle final, giremos el texto usando `transform: rotate`.
    
    ![captura de pantalla](images/stickers-fire-rotate.png)
    
    Intenta cambiar el número de grados en que se gira el texto.