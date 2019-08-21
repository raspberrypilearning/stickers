## Kleurrijke code sticker

Een verloop is een geleidelijke overgang van de ene kleur naar de andere. Verlopen kunnen worden gebruikt om coole effecten te creëren. Je gaat ze gebruiken om stickers te maken die je op je webpagina's kunt gebruiken.

+ Open deze trinket: <a href="http://jumpto.cc/web-stickers" target="_blank">jumpto.cc/web-stickers</a>.
    
    Het project zou er als volgt uit moeten zien:
    
    ![screenshot](images/stickers-starter.png)

+ Laten we een 'I <3 Coding (I love coding) makeng' sticker.
    
    Gebruik een `<div>` met een `sticker` klasse en een `coding` id zodat je het kunt opmaken:
    
    ![screenshot](images/stickers-coding-error.png)

+ Hmm, heb je gemerkt dat je een foutmelding kreeg? Dit komt omdat '<' een speciaal teken in HTML is. In plaats van '<' moet je de speciale code `&lt;` gebruiken.
    
    Werk je code bij door `&lt;` te gebruiken, zodat de fout verdwijnt.
    
    ![screenshot](images/stickers-coding-fixed.png)
    
    `<br>` maakt een nieuwe regel aan.

+ Laat de sticker er interessanter uitzien.
    
    Schakel over naar het `style.css` bestand. Je ziet dat de `.sticker` class er al voor je bestaat. Hiermee worden stickers op de pagina opgemaakt en wordt de inhoud gecentreerd.
    
    Vergeet niet dat je de id `coding` hebt toegevoegd aan je sticker. Voeg onderaan de `style.css` de volgende code toe om de tekst op te maken:
    
    ![screenshot](images/stickers-coding-font.png)

+ Nu kun je een verloop toevoegen aan de achtergrond van de sticker. Een lineaire verloop verandert langs een rechte lijn van de ene naar de andere kleur.
    
    Dit verloop verandert van rood aan de bovenkant naar magenta aan de onderkant. Voeg de verloopcode toe aan je `coding` stijl:
    
    ![screenshot](images/stickers-coding-gradient.png)

+ Je kunt het resultaat verbeteren door opvulling (Engels: padding) en afgeronde hoeken toe te voegen.
    
    Voeg de gemarkeerde code toe:
    
    ![screenshot](images/stickers-coding-padding.png)
    
    De `padding` stijl voegt een padding toe van 50px aan de boven- en onderkant en 30px aan de linker- en rechterkant.