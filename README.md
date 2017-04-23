#frontend-nanodegree Home of NBA Teams


##HOW TO RUN
### portfolio
1、Download and extract the files. <br>
2、Open "index.html" with your browser.

### pizzas
1、Download and extract the files. <br>
2、Open "views/pizza.html" with your browser.

##optimizations
### index.html
1、inline style.css. <br>
2、Add async attribute to all script tags. <br>
### pizza main.js
The key is to avoid generating variable and computing inside the for...in loop.
1、In function "updatePositions": <br>
+ move the phase variable outside the loop.
+ store the result of "document.body.scrollTop / 1250" outside the loop.
2、In function "changePizzaSizes": <br>
+ move allPizzas, dx, newwidth variable outside the loop.
