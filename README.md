g-liu.com
=========
See http://g-liu.com.

Development
===========

First, install all dependencies

    npm install && npm update
    bower install

To build the website

    grunt

To build _and_ view the website

    grunt serve

Do *not* directly edit `index.html`! This file is automatically generated from the corresponding `index.jade` template file; you should edit that instead.

Similarly, you should edit `style.scss` instead of `style.css`.

Project structure
-----------------

At the top level, there are four important folders:

* `assets`. Contains all files that the website depends on, e.g. images, documents.
* `bower_components`. Contains all front-end dependencies for the website, such as JavaScript and CSS frameworks.
* `node_modules`. Contains all dependencies used solely in the development process of the website
* `vendor`. Contains all third-party assets that the website depends on. This is actually an automatically generated copy of a subset of the `bower_components` folder.

The entire folder can be opened in Sublime Text, which is my preferred text editor, by clicking on the `project.sublime-project` file.
