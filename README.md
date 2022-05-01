# JB's Portfilio 
jb4earth.github.io/portfolio

# Credits

This webpage was forked from https://ryanfitzgerald.github.io/devportfolio/ in 2018 (what feels like a lifetime ago)

## Features

* Gulp ready (compiles Sass and minifies JS)
* Sass ready with lots of commenting
* Fully responsive
* Comes with Bootstrap grid system
* Easy colour changes can be done through simple variable edits

### Making Edits / Customizing the Template

To setup, simply fork the repo and run `npm install` in order to get all the Gulp dev dependencies. Next, run `Gulp watch` to compile the Sass and minify the JavaScript. Alternatively, if you don't have Gulp installed globally, you can run the npm script `npm run watch`. Any changes done to the JavaScript (js/scripts.js) or Sass (sass/styles.scss) will be autocompiled and ready to go.

All scripts are within `js/scripts.js` and get minified to `js/scripts.min.js`. All styles are in `sass/styles.scss` and get compiled to `css/styles.css`. Both the minified scripts file and compiled CSS file are what is loaded on the page by default.

## License

Completely free (MIT)! See [LICENSE.md](LICENSE.md) for more.
