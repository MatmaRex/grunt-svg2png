grunt-svg2png
=============

Grunt plugin to rasterize SVG to PNG images using PhantomJS (requires [Grunt](http://gruntjs.com/) `~0.4.1`)

## Example usage

````javascript
// Gruntfile.js configuration
grunt.loadNpmTasks('grunt-svg2png');

grunt.initConfig({
    svg2png: {
        all: {
            // specify files in array format with multiple src-dest mapping
            files: [
                // rasterize all SVG files in "img" and its subdirectories to "img/png"
                { src: ['img/**/*.svg'], dest: 'img/png/' },
                // rasterize SVG file to same directory
                { src: ['img/logo.svg'] }
            ]
        }
    }
});
````

* * *

## Authors

* [David Bushell](http://dbushell.com) | [@dbushell](http://twitter.com/dbushell)

Copyright © 2013 David Bushell | MIT license
