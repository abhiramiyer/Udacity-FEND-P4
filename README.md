## Website Performance Optimization portfolio project
To view the website, open index.html in a browser.  

####Part 1: Optimize PageSpeed Insights score for index.html
index.html was optimized for PageSpeed scores above 90 for both mobile and desktop. 
Key changes:
* Added async attribute to google analytics js file
* set media="print" for print.css
* Compressed the images using tinyjpg.com
* CSS optimization for above the fold content by inlining
* Commented link to the google font stylesheet. This should ideally not be required, but it is resulting in a dip in the PageSpeed measurement.


####Part 2: Optimize Frames per Second in pizza.html
view/js/main.js was optimized for 60fps
* Optimized updatePositions() to remove FSL
* Optimized resizePizzas() to remove FSL
* Optimized the number of sliding pizzas shown to be proportional to the browser window height
