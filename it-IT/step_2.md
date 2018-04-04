## Programmare un adesivo colorato

Un gradiente è un cambiamento graduale da un colore a un altro. I gradienti possono essere usati per creare effetti incredibili. Impareremo a usarli per creare degli adesivi e decorare le pagine web.

+ Apri questo trinket: <a href="http://jumpto.cc/web-stickers" target="_blank">jumpto.cc/web-stickers</a>.

	Il progetto dovrebbe avere questo aspetto:

	![screenshot](images/stickers-starter.png)

+ Realizziamo insieme un adesivo con scritto "Io <3 programmare".

	Usa un `<div>` con la class (categoria) `sticker` e un id `coding` per lo stile:

	![screenshot](images/stickers-coding-error.png)


+ Hai notato che ti ha dato errore? Succede perché '<' è un carattere speciale in HTML. Invece di '<' devi usare il codice speciale `&lt;`.

	Aggiorna il codice con `&lt;` e l'errore sparirà.

	![screenshot](images/stickers-coding-fixed.png)

	`<br>` inizia una nuova riga.

+ Ora rendiamo l'adesivo più interessante.

	Passa al file `style.css`. Vedrai che la categoria `.sticker` è stata creata. In questo modo gli adesivi appaiono sulla pagina e il contenuto viene centrato.

	Ricorda che hai aggiunto l'id `coding` all'adesivo. In fondo allo `style.css` aggiungi il codice seguente per dare lo stile al testo:

	![screenshot](images/stickers-coding-font.png)

+ Ora puoi aggiungere un gradiente allo sfondo dell'adesivo. Un gradiente lineare passa da un colore a un altro secondo una linea retta.

	Questo gradiente cambierà dal rosso nella parte superiore al magenta nella parte inferiore. Aggiungi il codice del gradiente allo stile `coding`:

	![screenshot](images/stickers-coding-gradient.png)

+ Puoi migliorare il risultato aggiungendo uno spazio intorno (il padding) e gli angoli arrotondati.

	Aggiungi il codice evidenziato:

	![screenshot](images/stickers-coding-padding.png)

	Lo stile del "padding" aggiunge uno spazio di 50px nella parte superiore e inferiore e uno spazio di 30px a sinistra e a destra.

