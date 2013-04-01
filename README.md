Minifront
=========

A simple, server agnostic, minimal HTML5/CSS3/jQuery skeleton with some features and ideas from [HTML5Boilerplate](http://html5boilerplate.com/), [HTML5Reset](http://html5reset.org/), [Modernizr](http://modernizr.com/) and the [LESS 4 Framework](http://lessframework.com/).

Useful to develop static pages or small websites focusing on the UI before going into back-end development.


## How it works

Just start coding the HTML5 in index.html. Then add some CSS3 awesomeness to css/style.scss, throw some jQuery plugins in js/plugins.js, fight with your semicolons in js/start.js and you'll be ready to go writing some Ruby.


## Filesystem Structure

### index.html
- Conditional IE comments to avoid loading different external stylesheets.
- Minimal custom modernizr.js HTML5 IE Shiv.
- Page template, you can just duplicate and rename it to add a new page.
- Javascript resources loaded in the footer to speed up page loading.

### css/style.scss
- SCSS support.
- Vertical grid with basehold.it as background.
- General reset rules.
- Typography section (Modify according to your needs)
- Variables section (Add SCSS variables here)
- Layout section (Write your layout specific CSS here)
- Objects section (Write global OOCSS classes here)
- Custom section (image replacement and clear float classes)
- IE section (Write here IE specific CSS)

### js/plugins.js
- Place all your jQuery plugins here.

### js/start.js
- Write your own Javascript here.

### js/libs
- The jQuery library.
- The Modernizr HTML5 IE Shiv.

### img/
- Place your images here.

### fonts/
- Place your web fonts here.


## License

Minifront is licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php)


## Credits

- [LESS 4 Framework](https://github.com/jonikorpi/Less-Framework) is licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php)
- [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate)
- [HTML5 Reset](https://github.com/murtaugh/HTML5-Reset)
- [Modernizr](https://github.com/Modernizr/Modernizr) is dual-licensed under the BSD and MIT Licenses.



