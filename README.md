# frontend-nanodegree Website optimization


## HOW TO RUN
### Portfolio
1、Download and extract the files. <br>
2、Open "index.html" with your browser.<br>

### Pizzas
1、Download and extract the files. <br>
2、Open "views/pizza.html" with your browser.

## Optimizations
### /index.html
1、inline style.css. <br>
2、Add async attribute to all script tags. <br>
3、add media to the link tag of print.ss.<br>
4、compress the images
### /views/js/main.js
The key is to avoid generating variable and computing inside the for...in loop. <br>
1、In function "updatePositions": <br>
+ move the phase variable outside the loop.
+ store the result of "document.body.scrollTop / 1250" outside the loop.<br>

2、In function "changePizzaSizes": <br>
+ move allPizzas, dx, newwidth variable outside the loop.
