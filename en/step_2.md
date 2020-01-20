## Colourful coding sticker

A gradient is a gradual change from one colour to another. Gradients can be used to create cool effects. You're going to use them to create stickers that you can use on your web pages. 

+ Open this trinket: <a href="http://jumpto.cc/web-stickers" target="_blank">jumpto.cc/web-stickers</a>. 

	The project should look like this:

	![screenshot](images/stickers-starter.png)

+ Let's make an 'I <3 Coding' sticker. 

	Use a `<div>` with a `sticker` class and a `coding` id so that you can style it: 

	![screenshot](images/stickers-coding-error.png)

+ Hmm did you notice that you got an error? This is because '<' is a special character in HTML. Instead of '<' you need to use the special code `&lt;`. 

	Update your code to use `&lt;` so that the error goes away. 

	![screenshot](images/stickers-coding-fixed.png)

	`<br>` gives a new line. 

+ Now let's make the sticker look interesting. 

	Switch to the `style.css` file. You'll see that the `.sticker` class has been provided for you. This will layout stickers on the page and centre their content. 

	Remember that you added the id `coding` to your sticker. At the bottom of `style.css` add the following code to style the text:

	![screenshot](images/stickers-coding-font.png)

+ Now you can add a gradient for the background of the sticker. A linear gradient changes from one colour to another along a straight line.

	This gradient will change from red at the top to magenta at the bottom. Add the gradient code to your `coding` style:

	![screenshot](images/stickers-coding-gradient.png)

+ You can improve on the result by adding padding and rounded corners. 

	Add the highlighted code:

	![screenshot](images/stickers-coding-padding.png)

	The `padding` style adds padding of 50px at the top and bottom and 30px on the left and right. 




