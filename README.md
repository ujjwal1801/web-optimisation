## Website Performance Optimization portfolio project

Project Link : https://github.com/ujjwal1801/web-optimisation

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

The Objective was to optimise the page to get a page insight speed score above 90

> Open index.html from the above link mentioned.
> Unlink the styles.css and make it internal.
> Use media query "print" on print.css.
> Move the script tag from head to the end of the body.

#### Part 2: Optimize Frames per Second in pizza.html

Objective was to optimise the page to achieve 60 fps scrolling speed and reduce pizzaResizeTime to less than 5 ms.

Step 1: Optimising pizza.html
-----------------------------

> Moving script tags from head to the end of the body tag.

Step 2: Optimising main.js
--------------------------

> Declaring variables outside the loops to avoid unnecessary redeclaration.
> Changes in changePizzaSizes() and UpdatePosition() functions.
> Reducing the loop iterations to generate less number of images.

-------------------------------------------------------------------------------------------------------------------------------------------------------
