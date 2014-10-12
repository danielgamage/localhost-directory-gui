Localhost Directory GUI
=============

A facelift for the localhost directory

<img src="http://norther.li/_github/localhost-gui.png"/>

###About

Uses native apache configuration options to make directory listings a little prettier.

###Installation

To Install, copy the .htaccess file into the root folder of your localhost directory (i.e. htdocs/). It will be inherited by subfolders.
Preserve this folder for css and easier update process through git.

```
htdocs/
  .htaccess (COPY)
  folder-a/
  localhost-directory-gui/
    .htaccess (ORIGINAL)
    style.css
  folder-b/
  folder-c/
```