## Adesivo con un robot di fantasia

Puoi creare un adesivo con gradiente usando un'immagine. Se utilizzi un'immagine con uno sfondo trasparente, il gradiente apparirà attraverso l'immagine.

Puoi anche creare gradienti che hanno diverse direzioni.

+ Aggiungi un adesivo a `index.html` utilizzando l'immagine `firerobot.png`:

	![screenshot](images/stickers-fire-html.png)

	Puoi regolare l'altezza `height` per ridimensionare l'immagine, l'ampiezza cambierà automaticamente.

+ Normalmente la direzione di un gradiente è dall'alto verso il basso, ma puoi usare `to` per cambiare la direzione. Ad esempio: `to top` (in alto), `to left` (a sinistra) o `to right` (a destra).

	Per un gradiente diagonale, devi dare due direzioni. In questo esempio è utilizzato `to bottom left`(a verso il basso a sinistra).

	Aggiungi questo stile a `style.css` per dare al tuo nuovo adesivo con il robot un gradiente diagonale e un bordo originale.

	![screenshot](images/stickers-fire-gradient.png)

	Nota che puoi usare `outline` (contorno) per creare un altro bordo al di fuori del solito.
	`outline-offset`(compensazione contorno) include uno spazio tra il bordo e il contorno.

+ Aggiungiamo un po' di testo a questo adesivo.

	Aggiungi uno `<span>` contenente il testo "ROBOTS" a `index.html` e assegnagli un id.  

	![screenshot](images/stickers-fire-span.png)

+ Il testo avrà un aspetto migliore se lo rendi più grande e lo posizioni.

	Per posizionare il testo dovrai aggiungere `position: relative;` to `#greensticker` e `position: absolute` a `#greentext`. Il posizionamento è trattato in maggiore dettaglio nel progetto "Costruisci un robot".

	Aggiungi il codice seguente a `style.css`:

	![screenshot](images/stickers-fire-text-style.png)

+ E per il tocco finale, ruotiamo il testo utilizzando `transform: rotate`.

	![screenshot](images/stickers-fire-rotate.png)

	Prova a cambiare il numero di gradi a cui il testo viene ruotato.




