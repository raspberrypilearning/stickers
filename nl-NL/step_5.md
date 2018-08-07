## Leuke robot sticker

Je kunt een verloopsticker maken met een afbeelding. Als je een afbeelding met een transparante achtergrond gebruikt, wordt het verloop weergegeven.

Je kunt ook verlopen maken die in verschillende richtingen lopen.

+ Voeg een sticker toe aan `index.html` met behulp van de afbeelding `firerobot.png`:
    
    ![screenshot](images/stickers-fire-html.png)
    
    Je kunt `height` aanpassen om het formaat van de afbeelding te wijzigen, de breedte wordt automatisch gewijzigd.

+ Normaal loopt een lineair verloop van boven naar beneden, maar je kunt `to` gebruiken om de richting te wijzigen. Bijvoorbeeld: `to top` (naar boven), `to left `(naar links) of `to right `(naar rechts).
    
    Voor een diagonaal verloop geef je twee richtingen. In dit voorbeeld wordt `to bottom left `(naar linksonder).
    
    Voeg deze stijl toe aan `style.css` om je nieuwe robotsticker een diagonaal verloop en een mooie rand te geven:
    
    ![screenshot](images/stickers-fire-gradient.png)
    
    Merk op dat je `outline` kunt gebruiken om een ​​andere rand buiten de gebruikelijke rand te maken. `outline-offset` geeft de opening tussen de rand en de omtrek.

+ Laten we wat tekst toevoegen aan deze sticker.
    
    Voeg een `<span>` met de tekst "ROBOTS" toe aan `index.html` en geef deze een ID.
    
    ![screenshot](images/stickers-fire-span.png)

+ De tekst zal er beter uitzien als je hem groter maakt en positioneert.
    
    Om de tekst te positioneren, moet je `position: relative;` aan `#greensticker` en `position: absolute` aan `#greentext` toe voegen. Positionering wordt in meer detail behandeld in het `Bouw een Robot` project.
    
    Voeg de volgende code toe aan `style.css`:
    
    ![screenshot](images/stickers-fire-text-style.png)

+ En tot slot draaien we de tekst met `transform: rotate`.
    
    ![screenshot](images/stickers-fire-rotate.png)
    
    Probeer het aantal graden dat de tekst wordt geroteerd te wijzigen.