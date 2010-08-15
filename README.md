Compass Html5 Boilerplate
=========================

A compass extension based on HTML5 Boilerplate by Paul Irish.

Browse [html5boilerplate.com](http://html5boilerplate.com) for the full workup.


Rails Installation
==================

    gem install compass-html5-boilerplate
    cd my_rails_project
    compass init rails -r html5-boilerplate -u html5-boilerplate --force

(The `--force` overwrites existing stuff so you get everything. What, you don't trust me?)

### A few minor points to store into your brainpan...

This has only been tested on Rails3, but should work ok on Rails2.

The installation attempts to overwrite the default rails.js for Prototype with the
Rails jquery driver (found at http://github.com/rails/jquery-ujs). However, it can
only do this if you use the `--force` flag on installation.

If you still have an application.html.erb in your layouts, you might want to
loose it now so Rails uses your shiny new application.html.haml layout instead.


Stand Alone Installation
========================

    gem install compass-html5-boilerplate
    compass create myproject -r html5-boilerplate -u html5-boilerplate


License
=======

HTML5 Boilerplate by Paul Irish
(comments left intact in scss files)

Compass Extension Copyright (c) 2010, Peter Gumeson  
[http://creativecommons.org/licenses/by/3.0](http://creativecommons.org/licenses/by/3.0)