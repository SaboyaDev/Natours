# Sass and Gulp 4

This boilerplate is use for simple front-end websites that use HTML, SCSS, and JavaScript. Gulp 4 is used to compile, prefix, and minify the files.

I also wrote a rather detailed walkthrough on how to get up and running with Gulp 4, as well as migration tips from Gulp 3.

You can read that on my blog [here](https://coder-coder.com/gulp-4-walk-through).

- Run `npm install`
- Run `gulp` to run the default Gulp task

In this proejct, Gulp is configured to run the following functions:

- Compile the SCSS files to CSS
- Autoprefix and minify the CSS file
- Concatenate the JS files
- Uglify the JS files
- Move final CSS and JS files to the `/dist` folder
