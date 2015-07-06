Ivory Jones


To optimize the speed for pizza.html, I did the following:

Compressed the images using compressnow.com

Added a variable to define the length of pizzaContainer

Inlined style.css and added async to style tag in pizza.html

Tested the speed and got a 95/100 summary for desktop experience and 89/100 for mobile from pagespeed insights

Configured a viewport to scale fonts for mobile experience

For the website, bootstrap-grid.css and main.js have been minified

Changed document.querySelectorAll() to document.getElementsByClassName() for speed optimization

Reduced the number of pizzas that load on the screen

Changed the height of the pizzas that load to fit most screen sizes