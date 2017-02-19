# Tachyons Setup

A quick and customisable setup for using [tachyons](http://tachyons.io/) in a project with [postCSS](http://postcss.org/)

to add to your project:

copy over:

+ the `css` folder
+ the `postcss-config.js`
+ the `dependencies`, `devDependencies` and `css` script in the `package.json`

to compile the css run:

```sh
> npm run css
```

this will make `style.min.css` containing all the styles in the root directory

to change where postCSS looks for your css files and outputs `style.min.css` edit the `input` and `output` fields in the `postcss-config.js` file
