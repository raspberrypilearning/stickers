## Naljepnica sa šarenim kodiranjem

Gradijent je postupna promjena iz jedne boje u drugu. Gradijenti se mogu koristiti za stvaranje hladnih efekata. Koristit ćete ih za stvaranje naljepnica koje možete koristiti na svojim web stranicama.

+ Otvori ovaj trinket: <a href="http://jumpto.cc/web-stickers" target="_blank">jumpto.cc/web-stickers</a>.
    
    Projekt bi trebao izgledati ovako:
    
    ![screenshot](images/stickers-starter.png)

+ Napravimo 'I <3 Coding' sticker.
    
    Koristite `<div>` s `naljepnicom` klasa i</code> kodom `kako biste ga mogli oblikovati:</p>

<p><img src="images/stickers-coding-error.png" alt="screenshot" /></p></li>
<li><p>Jeste li primijetili da ste imali pogrešku? To je zato što je "<" posebni znak u HTML-u. Umjesto "<" morate koristiti posebni kod <code>&lt;`.
    
    Ažurirajte kôd da biste koristili `&lt;` tako da pogreška nestane.
    
    ![screenshot](images/stickers-coding-fixed.png)
    
    `<br>` daje novu liniju.

+ Sada neka nova naljepnica izgleda zanimljivo.
    
    Prijeđite na `style.css` datoteku. Vidjet ćete da vam `.sticker` klasa postoji. To će postaviti naljepnice na stranici i centrirati njihov sadržaj.
    
    Imajte na umu da ste dodali ID `kodiranje` na svoju naljepnicu. Pri dnu `style.css` dodajte sljedeći kod za stiliranje teksta:
    
    ![screenshot](images/stickers-coding-font.png)

+ Sada možete dodati gradijent za pozadinu naljepnice. Linearni gradijent mijenja se s jedne boje na drugu uzduž ravne linije.
    
    Ovaj gradijent će se promijeniti od crvene na vrhu do magenta na dnu. Dodajte kôd gradijenta na `kodni` stil:
    
    ![screenshot](images/stickers-coding-gradient.png)

+ Na rezultat možete poboljšati dodavanjem paddinga i zaobljenih uglova.
    
    Dodaj označeni kôd:
    
    ![screenshot](images/stickers-coding-padding.png)
    
    `padding` stil dodaje padding od 50px na vrhu i dnu i 30px s lijeve i desne strane.