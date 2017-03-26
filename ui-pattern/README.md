#UI Patterns


## Prerequisites

The Pattern Lab Node - Gulp Edition uses [Node](https://nodejs.org) for core processing, [npm](https://www.npmjs.com/) to manage project dependencies, and [gulp.js](http://gulpjs.com/) to run tasks and interface with the core library. Node version 4 or higher suffices. You can follow the directions for [installing Node](https://nodejs.org/en/download/) on the Node website if you haven't done so already. Installation of Node will include npm.

It's also highly recommended that you [install gulp](hhttps://github.com/gulpjs/gulp/blob/4.0/docs/getting-started.md) globally.

> Note: The Gulp Edition of Pattern Lab uses Gulp 4, which may require a new global install of the Gulp command line interface. Follow the [gulp upgrade instructions](https://github.com/pattern-lab/edition-node-gulp/wiki/Updating-to-Gulp-4) if you already have gulp installed and need to upgrade. Gulp 4 is in alpha, but brings many benefits to the table and is relatively stable. You can alternatively [run with local gulp instead of global gulp](https://github.com/pattern-lab/patternlab-node/wiki/Running-with-Local-Gulp-Instead-of-Global-Gulp), but commands are a bit more verbose. The rest of this documentation assumes a global install.

### Install dependencies

* download or `git clone` this repository to an install location.

* run the following

    ```
    cd install/location
    npm install
    ```
   
 ### Generate Pattern Lab
   
   To generate the front-end for Pattern Lab type:
   
       gulp patternlab:build
   
   ### Watch for changes and re-generate Pattern Lab
   
   To watch for changes, re-generate the front-end, and server it via a BrowserSync server,  type:
   
       gulp patternlab:serve
   
   BrowserSync should open [http://localhost:3000](http://localhost:3000) in your browser.