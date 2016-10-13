## Website Performance Optimization portfolio project


### 1. How to run.
Open `index.html` to run the app.
### 2.Optimize PageSpeed Insights score for `index.html`
  1. I turned the 'web fonts' to 'local fonts'.
  2. I compressed the `g.font` and `style.css`.
  3. I added `media="none" onload="if(media!='all')media='all'"` to the `g.font` and `style.css` so that the index can render more quickly.
  4. I added a `media = "print"` to the `print.css` so that it won't block the index rendering.
  5. I optimized the images by compressing  and resizing them.
  6. I take the `scrips` to the bottom of the page.
### 3.optimize for `views/js/main.js`
  1. I decleared a variable called `randomPizzaContainers` out of the for loop and I take the `dx` and `newwidth` out of the for loop.  
  2. I tured the pizza numbers from 200 to 30.
  3. I decleared a new array and push the phase in it before the for loop.
