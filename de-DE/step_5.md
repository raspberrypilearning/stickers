## Ausgefallener Roboter-Aufkleber

Du kannst einen Farbverlaufs-Aufkleber mit einem Bild erstellen. Wenn du ein Bild mit einem transparenten Hintergrund verwendest, wird der Farbverlauf angezeigt.

Du kannst auch Farbverläufe erstellen, die in verschiedene Richtungen verlaufen.

+ Füge einen Aufkleber zu `index.html` mit dem `firerobot.png` Bild hinzu:
    
    ![screenshot](images/stickers-fire-html.png)
    
    Du kannst die Höhe (`height`) anpassen, um die Bildgröße zu ändern, die Breite wird sich automatisch ändern.

+ Normalerweise verläuft ein linearer Farbverlauf von oben nach unten, aber du kannst jedoch (`to`) verwenden, um die Richtung zu ändern. Zum Beispiel: nach oben (`to top`), nach links (`to left`) oder nach rechts (`to right`).
    
    Für einen diagonalen Farbverlauf gebe zwei Richtungen an. Dieses Beispiel verwendet nach unten links `to bottom left`.
    
    Füge diesen Stil zu `style.css` hinzu, um deinem neuen Roboter-Sticker einen diagonalen Farbverlauf und einen ausgefallenen Rand zu geben:
    
    ![screenshot](images/stickers-fire-gradient.png)
    
    Beachte, dass du eine Außenlinie `outline` verwenden kannst, um einen weiteren Rahmen außerhalb der üblichen zu erstellen. `outline-offset` gibt die Lücke zwischen dem Rand und der Umrisslinie an.

+ Fügen wir diesem Sticker-Text hinzu.
    
    Füge ein `<span>` mit dem Text "ROBOTER" zu `index.html` hinzu und gib ihm eine ID.
    
    ![screenshot](images/stickers-fire-span.png)

+ Der Text wird besser aussehen, wenn du ihn vergrößerst und positionierst.
    
    Um den Text zu positionieren, musst du `position: relativ;` to `#greensticker` und `und Position: absolute`to`#greentext` hinzufügen. Die Positionierung wird im `Baue ein Roboter` Projekt detaillierter behandelt.
    
    Füge folgenden Code `style.css` hinzu:
    
    ![screenshot](images/stickers-fire-text-style.png)

+ Und für eine finale Wendung, lass uns den Text mit `transform: rotate` drehen.
    
    ![screenshot](images/stickers-fire-rotate.png)
    
    Versuche, die Anzahl der Grade, mit dem der Text gedreht wird, zu ändern.