## Fancy robot sticker

You can make a gradient sticker using an image. If you use an image with a transparent background then the gradient will show through.

You can also create gradients to run in different directions.

+ Add a sticker to `index.html` using the `firerobot.png` image:
    
    ![screenshot](images/stickers-fire-html.png)
    
    You can adjust the `height` to resize the image, the width will change automatically.

+ Normally a linear gradient runs from top to bottom, but you can use `to` to change the direction. For example: `to top`, `to left`, or `to right`.
    
    For a diagonal gradient you give two directions. This example uses `to bottom left`.
    
    Add this style to `style.css` to give your new robot sticker a diagonal gradient and a fancy border:
    
    ![screenshot](images/stickers-fire-gradient.png)
    
    Note that you can use `outline` to create another border outside the usual one. `outline-offset` gives the gap between the border and the outline.

+ Let's add some text to this sticker.
    
    Add a `<span>` containing the text "ROBOTS" to `index.html` and give it an id.
    
    ![screenshot](images/stickers-fire-span.png)

+ The text will look better if you make it bigger and position it.
    
    To position the text you'll need to add `position: relative;` to `#greensticker` and `position: absolute` to `#greentext`. Positioning is covered in more detail in the `Build a Robot` project.
    
    Add the following code to `style.css`:
    
    ![screenshot](images/stickers-fire-text-style.png)

+ And for a final twist, let's rotate the text using `transform: rotate`.
    
    ![screenshot](images/stickers-fire-rotate.png)
    
    Try changing the number of degrees that the text is rotated.