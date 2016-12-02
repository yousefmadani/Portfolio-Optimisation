# Website Performance Optimization portfolio project

The challenge is to optimize an online portfolio for speed! In particular, optimize the critical rendering path and make the page render as quickly as possible by applying the techniques picked up in the [Critical Rendering Path course]. The website was hosted on GitHub Pages.


## The project consists of manily 2 parts:

###Part 1: Optimize PageSpeed Insights score for index.html to achieve a PageSpeed score of at least 90 for Mobile and Desktop.

#### Optimisations that were made for Part 1: 
- Images were optimised using ImageOptim (https://imageoptim.com/) 
- CSS was minified, style.css was inlined 
- Media print query added 
- Moved JS and font to the bottom and added async to font and analytics. 
- Inlined and minified perfmatters.js 
- Images were saved locally instead of requesting them 
- Added “project-pizza.jpg” for “index.html”

#### The page can be accesed here: https://yousefmadani.github.io/Portfolio-Optimisation/

#### While the PageSpeed Insights can be accesed here: https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fyousefmadani.github.io%2FPortfolio-Optimisation%2F



###Part 2 consists of two objectives:
###A- Optimisations made to views/js/main.js make views/pizza.html render with a consistent frame-rate at 60fps when scrolling. 
###B- Time to resize pizzas is less than 5 ms using the pizza size slider on the views/pizza.html page. Resize time is shown in the browser developer tools.

#### Optimisations that were made for Part 2:
- Images optimised and pizzeria.jpg resized
- Optimisation of the ‘for’ loop in ‘changePizzaSizes’ function
- ‘querySelectorAll’ changed to ‘getElementsByClassName’
- Optimisation of the ‘for’ loop in the ‘updatePositions‘ function 
- Number of moving pizza’s on (line 545) reduced to 25

#### The page can be accesed here: https://yousefmadani.github.io/Portfolio-Optimisation/views/pizza.html

### Resources:
- Udacity Website Optimization Course
- Udacity Forums
- ImageOptim
- Google PageSpeed Insights 
