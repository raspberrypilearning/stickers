## Adesivo con un robot di fantasia

Puoi creare un adesivo con sfumatura usando un'immagine. Utilizzando un'immagine con uno sfondo trasparente, il gradiente verrà visualizzato sullo sfondo.

Puoi anche creare sfumature da eseguire in diverse direzioni.

+ Aggiungi un adesivo a `index.html` usando l'immagine `firerobot.png`:
    
    ![screenshot](images/stickers-fire-html.png)
    
    Puoi cambiare l'altezza dell'immagine utilizzando il parametro `height`. In questo modo la larghezza cambierà automaticamente.

+ Normalmente un gradiente lineare va dall'alto verso il basso, ma puoi usare il parametro `to` cambiare la direzione. Ad esempio: `to top` (verso l'alto), `to left` (verso sinistra) o `to right` (verso destro).
    
    Per un gradiente diagonale si danno due direzioni. Questo esempio utilizza `to bottom left` (in basso a sinistra).
    
    Aggiungi questo stile al file `style.css` per dare al tuo nuovo adesivo robot una sfumatura diagonale e un bordo di fantasia:
    
    ![screenshot](images/stickers-fire-gradient.png)
    
    Nota che puoi usare il parametro `outline` per creare un altro bordo al di fuori del solito bordo. `outline-offset` assegna il divario tra il bordo interno ed esterno.

+ Aggiungiamo un po 'di testo a questo adesivo.
    
    Aggiungi un `<span>` contenente il testo "ROBOT" a `index.html` e assegnali un id.
    
    ![screenshot](images/stickers-fire-span.png)

+ Il testo sembrerà migliore se lo ingrandisci e lo posizioni.
    
    Per posizionare il testo dovrai aggiungere `position: relative;` allo stile dell'adesivo `#greensticker` e `position: absolute` allo stille dello `#greentext`. Il posizionamento è trattato più in dettaglio nel progetto `Costruisci un Robot`.
    
    Aggiungi il seguente codice al file `style.css`:
    
    ![screenshot](images/stickers-fire-text-style.png)

+ E per finire, ruotiamo il testo usando `transform: rotate`.
    
    ![screenshot](images/stickers-fire-rotate.png)
    
    Prova a cambiare il numero di gradi di cui il testo è ruotato.