Project Tools
=============

* [Modules](modules.md)
* [Libraries](libraries.md)
* [Project Tools](toolsProject.md)
* [Other Tools](toolsOther.md)

# Stable

#### NPM - https://www.npmjs.com/

A package manager for CommonJS packages, command line applications, and many other magical things.

#### Babel - https://babeljs.io/

Formally known as 6to5 transpiles es6 code to es5. (new version of JS to old version)

#### Browserify - http://browserify.org/

Allows you to require CommonJS Modules (modules from NPM) in frontend code. Compiles down
all required files to one single Javascript. Supports source mapping for debugging in Browser.

#### Grunt - http://gruntjs.com/

A build tool for projects. It will help you do things such as compiling JS, compiling Less, 
handlebars, etc. Although we have experimented with Gulp for now most of our projects use 
Grunt. The main reason being the immense amount of plugins which have been written for Grunt.
Less effecient than Gulp because multithreading is harder to support. Plugins are setup via
JSON style syntax which maybe less preferable to Gulp's syntax.

#### Gulp - http://gulpjs.com/

A project build tool which supports Streams. Is quite effecient since it can support multithreading.
Syntax maybe preferable to Grunt's syntax.


#### TexturePacker - https://www.codeandweb.com/texturepacker

The most advanced Sprite Sheet tool out there. Supports multiple platforms outside of the web
and can be used as a commandline application for instance through Grunt/Gulp.

#### Less - http://lesscss.org/

Allows you to write CSS style code which will be compiled to CSS. A css preprocessor. Although
there are many css preprocessors (Stylus, Sass, etc.) Less has been used on multiple projects.

#### Handlebars - http://handlebarsjs.com/

A nice HTML templating library. Supports one way databinding. Templates can be precompiled 
for effiency or templates can be compiled through JS on the fly.

#### nyg - https://github.com/Jam3/nyg

Not another yeoman generator, a simplified project generator based around prompts and events.

# Experimental


