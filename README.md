# Nate's Front End Web Template

As a web developer, instead of creating the file and folder structure for every front end site or app, I'm making this template to include:
1. A custom css file and javascript file.
2. Commonly used libraries such as Bootstrap, jQuery, and Popper.js (which Bootstrap relies on).
3. The Font Awesome icon set.

## Description:

Everything in this template is hosted locally and doesn't rely on a [CDN](https://www.cloudflare.com/learning/cdn/what-is-a-cdn/). All included files have been added to index.html.

1. Custom style.css and script.js files:
  * assets/css/style.css
    * Bootstrap's default mobile-first breakpoints have been included
  * assets/js/script.js
2. Bootstrap v4.4.1:
  * assets/css/bootstrap-4.4.1.min.css
  * assets/js/bootstrap-4.4.1.min.js
3. jQuery v3.4.1:
  * assets/js/jquery-3.4.1.min.js
4. Popper.js v1.16.0:
  * assets/js/popper-1.16.0.min.js
5. Font Awesome Free v5.12.0: 
  * assets/css/fontawesome-free-5.12.0.all.min.css
    * assets/webfonts
  * assets/js/fontawesome-free-5.12.0.all.min.js

## Installation and Use:

Please feel free to use this template as you wish. This repo consists of front end web files. See the comments inside each file for further information.

#### index.html:
* Font Awesome: You can use either the .js version or the .css version. If you do use the .js version, the assets/webfonts folder can be deleted. I've opted to use the .css version in order to account for users with older computers. See [https://fontawesome.com/how-to-use/on-the-web/other-topics/performance](https://fontawesome.com/how-to-use/on-the-web/other-topics/performance) for more information.

#### script.js:
* A couple empty functions have already been included. Delete them if they are deemed unnecessary. See [https://www.sitepoint.com/jquery-document-ready-plain-javascript](https://www.sitepoint.com/jquery-document-ready-plain-javascript/) for more information.
