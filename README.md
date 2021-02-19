# 🦩 Super Simple, Sass-friendly Wordpress Theme Boilerplate 🦩
---
## This is a barebones theme consisting of *mostly empty* default (index.php), header, footer, front-page, home & 404 page templates.

---
### Do This First:
- rename the theme directory 
- search for __\<theme\>__ & replace it with your theme name
- search for __\<company\>__ & replace it with the name of the company
- search for __\<author\>__ & replace it with your name/email/github
- delete this readme
- delete vendor scripts, vendor css files & theme supports you don't need/want
- delete the example page template if you don't need it (page-templates/example-template.php)
- commit your initial code before installing node modules and compiling css
- add your favicons/site.manifest files to the root or delete the links in the header

### Notes:
- this theme has a preconfigured .gitignore file
- this theme compiles css using <pre>npm run start</pre>
- all css compiles to style.css
- the 'Roboto' google font is enqueued by default
- __changes made directly to style.css will not persist__
- all css & sass code should go in the sass directory
- all sass files are imported into /assets/sass/style.scss
- this theme imports the [bootstrap grid](https://github.com/twbs/bootstrap/blob/main/dist/css/bootstrap-grid.min.css) and [normalize.css](https://necolas.github.io/normalize.css/)
- scripts for [slick slider](https://kenwheeler.github.io/slick/), [micromodal](https://micromodal.now.sh) & [perfect scrollbar](https://github.com/mdbootstrap/perfect-scrollbar) are commented out in functions.php
- this theme supports a primary menu and a footer menu 
- support for an example custom post type is commented out in functions.php
- this theme supports an [advanced custom fields](https://www.advancedcustomfields.com) site options page (see functions.php)
- included and commented-out vendor scripts/files may not be totally up-to-date...it's best to double check 🤓