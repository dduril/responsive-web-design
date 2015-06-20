# Responsive Websites With Bootstrap 3

#### Project Setup

This project was developed using Visual Studio 2013, but could just as easily been built using a simple text editor or IDE such as Aptana Studio, Brackets, Notepad++, Sublime or WebStorm.

Follow the link for a live demo of the project:
<a href="http://www.doug-duril.com/pages/demos/responsive-web-page/index.html" target="_blank"><strong>Demo</strong></a>

I used some images from a trip to the wine country in Napa, California.

***

Here are some basic instructions, if using Notepad++ or something else, it will be easier to just look at the source on the <code>index.html</code> file to see the references to the CSS and JavaScript libraries. Links
for all of these awesome goodies are listed at the end of this page.

* Open Visual Studio 2013
* Create a new Web Project - empty, accept defaults
* Right-click solution - Manage NuGet Packages...
* Search for and install latest Bootstrap
* Visit Google Fonts - get link for Open Sans
* Add HTML page - index.html
* Add app.css to Custom folder
* Add CSS references in <code><head></code> tag

```
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <link href='http://fonts.googleapis.com/css?family=Open+Sans' rel='stylesheet' type='text/css'>
    <link href="styles/font-awesome.min.css" rel="stylesheet" />
    <link href="styles/bootstrap.min.css" rel="stylesheet" />
    <link href="styles/animate.css" rel="stylesheet" />
    <link href="styles/app.css" rel="stylesheet" />
```
	
* Add JavaScript references before closing <code><body></code> tag 

```
	<script src="scripts/jquery-1.9.1.min.js"></script>
    <script src="scripts/bootstrap.min.js"></script>
    <script src="scripts/classie.js"></script>
    <script src="scripts/cbpAnimatedHeader.js"></script>
    <script src="scripts/jquery.easing.1.3.js"></script>
    <script src="scripts/jquery.stellar.js"></script>
    <script src="scripts/wow.min.js"></script>
    <script src="scripts/scrolling.js"></script>
```

#### Resources

* <a href="https://www.google.com/fonts#" target="_blank">Google Fonts</a>
* <a href="http://getbootstrap.com/css/" target="_blank">Bootstrap Viewport</a>
* <a href="https://github.com/codrops/AnimatedHeader" target="_blank">Codrops - AnimatedHeader</a>
* <a href="http://formstone.it/components/background/" target="_blank">Formstone - Background (Wallpaper)</a>
* <a href="http://www.minimit.com/articles/solutions-tutorials/bootstrap-3-responsive-columns-of-same-height" target="_blank">Same-sized columns</a>	
* <a href="http://getbootstrap.com/components/" target="_blank">Bootstrap Components - navbar</a>
* <a href="http://fortawesome.github.io/Font-Awesome/" target="_blank">Font Awesome</a>
* <a href="http://getbootstrap.com/javascript/#scrollspy" target="_blank">Bootstrap Scrollspy</a>
* <a href="http://daneden.github.io/animate.css/" target="_blank">Animate CSS</a>
* <a href="http://mynameismatthieu.com/WOW/index.html" target="_blank">WOW home page</a>
* <a href="https://github.com/matthieua/WOW" target="_blank">WOW github</a>
* <a href="http://getbootstrap.com/javascript/#carousel" target="_blank">Bootstrap 3 Carousel</a>
* <a href="http://gsgd.co.uk/sandbox/jquery/easing/" target="_blank">jQuery Easing</a>
* <a href="http://markdalgleish.com/projects/stellar.js/" target="_blank">Stellar.js -  Parallax Scrolling</a>