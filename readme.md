# CSS Examples

This repository contains examples of some cool effects using CSS.

## Sassy CSS (.scss)

Some of the CSS files are generated using Sassy CSS, a superset of CSS. While HTML doesn't natively support .scss files it is easy to generate a CSS file from an .scss file. To do so install Sass `npm install -g sass` then you can run `sass input.scss output.css`. To generate a .css file in realtime you can run `sass --watch input.scss output.css` and anytime you save your .scss file the corresponding .css file will automatically be regenerated for you. In your html file just and a link to the .css file `<link rel="stylesheet" href="output.css">`.