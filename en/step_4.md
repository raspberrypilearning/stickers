## Fancy robot sticker 

### Add an image

--- task ---

Add a sticker to `index.html` using the `firerobot.png` image.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 7
line_highlights: 11-13
---
<body>

  <div class="sticker" id="coding">I &lt;3 <br> Coding</div>
  <div class="sticker" id="web">HTML &amp; CSS</div>
  <div class="sticker" id="firerobot">
    <img height="180" src="firerobot.png"/>
	</div>

</body>

--- /code ---

--- /task ---

**Tip**: You can adjust the `height` to resize the image, the width will change automatically. 

### Change the gradient direction

Gradients can run in different directions. 

Normally a linear gradient runs from top to bottom, but you can use `to` to change the direction. For example: `to top`, `to left`, or `to right`.

For a diagonal gradient you give two directions. This example uses `to bottom left`.

--- task ---

Open `style.css`

--- /task ---

--- task ---

Add this style to `style.css` to give your new robot sticker a diagonal gradient and a fancy border.

--- code ---
---
language: css
filename: style.css
line_numbers: false
line_number_start: 
line_highlights:
---
#firerobot {
  background: linear-gradient(to bottom left, white, yellow, tomato);
  border: 10px dashed tomato;
  outline: 4px solid tomato;
  outline-offset: 2px;
}

--- /code ---

This uses `outline` to create another border outside the usual one. 
`outline-offset` gives the gap between the border and the outline. 

--- /task ---

### Add text

--- task ---

Open `index.html`

--- /task ---

--- task ---

Add a `<span>` containing the text "ROBOTS" to `index.html` and give it an id. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 7
line_highlights: 13
---
<body>

  <div class="sticker" id="coding">I &lt;3 <br> Coding</div>
  <div class="sticker" id="web">HTML &amp; CSS</div>
  <div class="sticker" id="firerobot">
    <img height="180" src="firerobot.png"/>
    <span id="firetext">ROBOTS</span>
  </div>

</body>

--- /code ---

--- /task ---

--- task ---

Open style.css

--- /task ---

Make the text bigger and position it. 

--- task ---

In style.css, add `position: relative;` to `#firerobot` and style `#firetext`, including `position: absolute`. 

--- code ---
---
language: css
filename: style.css
line_numbers: false
line_number_start: 
---
#firerobot {
  background: linear-gradient(to bottom left, white, yellow, tomato);
  border: 10px dashed tomato;
  outline: 4px solid tomato;
  outline-offset: 2px;
  position: relative;
}

#firetext {
  font-size: 30px;
  font-family: Impact;
  position: absolute;
  bottom: 60px;
  left: 10px;
}

--- /code ---

--- /task ---

--- task ---

Rotate the text using `transform: rotate`.

--- code ---
---
language: css
filename: style.css
line_numbers: false
line_number_start: 
---
#firetext {
  font-size: 30px;
  font-family: Impact;
  position: absolute;
  bottom: 60px;
  left: 10px;
  transform: rotate(-15deg);
}

--- /code ---

**Tip**: Try changing the number of degrees that the text is rotated. 

--- /task ---
