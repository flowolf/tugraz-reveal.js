# tugraz-reveal.js
Style for reveal.js slides with TU Graz logo

The Logo of TU Graz and IICM are not licensed under the MIT license.

## Usage

put the tugraz.css file in the css/theme folder of your [reveal.js](https://github.com/hakimel/reveal.js) project. set it in your .html file, and you are good to go. Use any file found here with the path relative to your html files.

you can add a footer line, with the 'footer' class.

There is a TU Graz glyph that you can insert into your slides, e.g. in front of a link to show that it goes to TU Graz servers.
use:
```html
<i class="icon-tugraz_logo" aria-hidden="true"></i>
``` 
to insert it.

Additionally [font-awesome](http://fontawesome.io/) is included, which allows you to use great icons in your slides.

## Quickstart

Quickest way to start:
```bash
git clone https://github.com/hakimel/reveal.js my_slides
git clone https://github.com/flowolf/tugraz-reveal.js.git my_slides/tugraz_theme
rsync -av --exclude 'README.md' --exclude 'LICENSE' my_slides/tugraz_theme/* my_slides/
chromium-browser my_slides/tugraz_theme_demo.html
```

Feel free to send a pull request if you have improvements.
