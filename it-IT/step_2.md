## Programmare un adesivo colorato

Un gradiente è un cambiamento graduale da un colore all'altro. Le sfumature possono essere utilizzate per creare effetti interessanti. Le userai per creare adesivi che potrai utilizzare sulle tue pagine web.

+ Apri questo trinket: <a href="http://jumpto.cc/web-stickers" target="_blank">jumpto.cc/web-stickers</a>.
    
    Il progetto dovrebbe assomigliare a questo:
    
    ![screenshot](images/stickers-starter.png)

+ Facciamo un adesivo "I <3 Coding"g' sticker.
    
    Utilizza un `<div>` con classe `adesivo` e id `codifica` in modo tale da poterne modificare lo stile:
    
    ![screenshot](images/stickers-coding-error.png)

+ Hmm hai notato che hai ottenuto un errore? Questo perché "<" è un carattere speciale in HTML. Invece di '<' è necessario utilizzare il codice speciale `&lt; ` .
    
    Aggiorna il tuo codice utilizzando `&lt; ` in modo da rimuovere l'errore.
    
    ![screenshot](images/stickers-coding-fixed.png)
    
    `<br>` dà una nuova linea.

+ Ora facciamo in modo che l'adesivo abbia un aspetto interessante.
    
    Passa al file `style.css`. Vedrai che la classe `.sticker` è già stata creata per te. Questo imposterà gli adesivi sulla pagina e centrerà il loro contenuto.
    
    Ricorda che hai aggiunto l'Id `codifica` al tuo adesivo. Nella parte inferiore di `style.css` è necessario aggiungere il seguente codice per definire lo stile del testo:
    
    ![screenshot](images/stickers-coding-font.png)

+ Ora puoi aggiungere una sfumatura per lo sfondo dell'adesivo. Un gradiente lineare passa da un colore all'altro lungo una linea retta.
    
    Questo gradiente cambierà da rosso in alto a magenta in basso. Aggiungi il codice gradiente allo stile dell'Id codifica ` `:
    
    ![screenshot](images/stickers-coding-gradient.png)

+ Puoi migliorare il risultato aumentando la spaziatura e arrotondando gli angoli.
    
    Aggiungi il codice evidenziato:
    
    ![screenshot](images/stickers-coding-padding.png)
    
    Il parametro `padding` aggiunge una spaziatura di 50px nella parte superiore e inferiore e 30px a sinistra e a destra.