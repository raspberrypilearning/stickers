## HTML & CSS sticker

Gradients can also change colour from the centre out towards the edges, this is called a radial gradient. 

--- task ---

Create a new sticker with the text `HTML & CSS.`  

`&` is another character that needs encoding in HTML, the code is `&amp;`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 7
line_highlights: 10
---
<body>

  <div class="sticker" id="coding">I &lt;3 <br> Coding</div>
  <div class="sticker" id="web">HTML &amp; CSS</div>

</body>

--- /code ---

--- /task ---

--- task ---

Switch to your `style.css` file and add a style for your new sticker:

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 21
line_highlights:
---
#web {
  font-size: 40px;
  font-family: Impact;
  text-shadow: 2px 2px grey;
}

--- /code ---

The `text-shadow` code adds a shadow which extends 2px below and to the right of the text to make it stand out. 

--- /task ---

--- task ---

Add a radial gradient for the background. 

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 21
line_highlights: 25
---
#web {
  font-size: 40px;
  font-family: Impact;
  text-shadow: 2px 2px grey;
  background: radial-gradient(yellow, orange, red);
}

--- /code ---

The colour will change from yellow in the centre through to orange and then red. 

--- /task ---

--- task ---

Add padding and a border to improve the sticker.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 21
line_highlights: 26-27
---
#web {
  font-size: 40px;
  font-family: Impact;
  text-shadow: 2px 2px grey;
  background: radial-gradient(yellow, orange, red);
  padding: 30px;
  border-radius: 100px;
}

--- /code ---

--- /task ---
