#Kaiya Torres - Wines Science Fair Project 2016

##Animals Around The World
Animals Around The World is a presentation of different animals and their habitats. A responsive image gallery of different animals around the world.

Here is a [version](https://github.com/herb-t/science-fair-2016) that uses service workers to cache the page so it runs offline. It's hosted on gh-pages [here](https://herb-t.github.io/science-fair-2016/#/home).

# Getting Started

This scaffold has three global dependencies: Node and Gulp and Bower. To
install Node, find the installer here:

* [Node](https://nodejs.org/)

To install Gulp 4, run:

    npm run gulp4

* [Bower](http://bower.io/)

To install Bower, run:

    npm install -g bower

Finally, to install local project dependencies, run:

    npm install
    bower install

To kick off a dev build, start a local server and open the project in a browser,
run:

    gulp

# Gulp

This project uses the Gulp taskrunner to run a number of different tasks
including file copying, moving, and deletion, validation, testing, image
processing, distribution packaging, and open the project in a browser.

## Tasks

The tasks listed here are in the format __taskname__ *(dependencies)*. Each task
may be called on the command line with the command `gulp taskname`. The
following tasks will probably be called most often:

### default *(watch-dev)*

The default task, which can be called with just `gulp`. Dev build + local
server.

### watch-dev

Dev build + local server.

### build-dev

Dev build, with sourcemaps

### watch-prod

Prod build + local server.

### build-prod

Prod build, optimized
