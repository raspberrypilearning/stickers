## Colourful coding sticker

--- task ---

Open the <a href="https://editor.raspberrypi.org/en/projects/stickers-starter" target="_blank">starter project</a>.

--- /task ---

### Make an 'I <3 Coding' sticker. 

--- task ---

Add a `<div>` with a `sticker` class and a `coding` id so that you can style it.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 7
line_highlights: 9
---
<body>

  <div class="sticker" id="coding">I <3 <br> Coding</div>

</body>

--- /code ---

`<br>` gives a new line. 

--- /task ---

--- task ---

**Run** your code.

**Notice:** You got an error. This is because `<` is a special character in HTML. Instead of `<` you need to use the special code `&lt;`. 

--- /task ---


--- task ---

Update your code to use `&lt;` so that the error goes away. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 7
line_highlights: 9
---
<body>

  <div class="sticker" id="coding">I &lt;3 <br> Coding</div>

</body>

--- /code ---

--- /task ---

--- task ---

Switch to the `style.css` file. 

--- /task ---

The `.sticker` class has been provided for you. This will layout stickers on the page and centre their content. 

--- task ---

Add this code to the bottom of `style.css` to style the text that uses the id `coding`.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 12
line_highlights:
---

#coding {
  font-size: 40px;
  font-weight: bold;
  font-family: "Courier New";
}

--- /code ---

--- /task ---

--- task ---

Add the gradient code to your `coding` style:

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 12
line_highlights: 16
---

#coding {
  font-size: 40px;
  font-weight: bold;
  font-family: "Courier New";
  background: linear-gradient(red, magenta);
}

--- /code ---

--- /task ---

--- task ---

Add code to improve the sticker with padding and rounded corners.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 12
line_highlights: 17-18
---
#coding {
  font-size: 40px;
  font-weight: bold;
  font-family: "Courier New";
  background: linear-gradient(red, magenta);
  padding: 50px 30px;
  border-radius: 20px;
}

--- /code ---

--- /task ---

This `padding` style adds 50px at the top and bottom and 30px on the left and right. 