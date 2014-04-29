Localhost Directory GUI
=============

A facelift for the localhost directory

<img src="http://norther.li/_github/localhost-gui.png"/>

###About
Uses native apache configuration options to make directory listings a little prettier.
###Installation
To Install, copy the .htaccess file into the root folder of your localhost directory (i.e. htdocs/). It will be inherited by subfolders.
Preserve this folder for css and easier update process through git.
###Notes on Responsive Functionality
It's responsive—_Technically_. Because we're using Apache config, we can't inject a ``<meta name=viewport>`` tag. That means that mobile devices that use a 960px baseline viewport won't use their native screen size when browsing your localhost.
What I've done instead is use a @viewport rule to ask devices this. The @viewport rule is still new, so support isn't quite there yet. You can keep track of support over at [the webplatform.org article](http://docs.webplatform.org/wiki/css/atrules/@viewport).