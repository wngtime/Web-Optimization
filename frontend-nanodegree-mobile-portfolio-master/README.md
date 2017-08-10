## Improvements and fixes

### Index.html and other files

* Compressed all images with [Optimizilla](http://optimizilla.com/).
* I have added ``async`` to the ``script`` tags.
* I have moved the scripts to the bottom of the page.
* Since the ``style.css`` is used across different pages I have created a link to the css files after it loads.
* Replaced images with smaller images.
* Removed **Google Fonts** link since it was not used.

### main.js
* Changed the ``changePizzaSizes()`` to include the calculation and removed ``determineDx().

* The variable ``scrollPosition`` is now declared outside the loop.

* The background pizzas now depends on the size of the viewport.