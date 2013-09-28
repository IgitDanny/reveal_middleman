Middleman Reveal.js
===================

Middleman Reveal.js is a simple boilerplate project for generating [reveal.js](http://lab.hakim.se/reveal-js/) presentations by using the [Middleman](http://middlemanapp.com/) static page generator.

But why ... ?
-------------

This morning I stumbled again about [reveal.js](http://lab.hakim.se/reveal-js/) and wanted to try it out. But at first look in the HTML I got a little bit sick. There was this huge file with nested sections in it. And just don't want to this anymore.

So I decided that I need something that helps me. And because of my new love for  [Middleman](http://middlemanapp.com/) and especially its capability to render Rails-like partials I configured a middleman project to build a Reveal.js Presentation.

Second reason: [Livereload!](https://github.com/guard/guard-livereload)

How to use it
-------------

To run this you need a shell, Ruby (>= 1.8.3) (so the standard ruby in most Linux distributions and OS X will do it) and the [bundler gem](http://bundler.io/)

1. Download the zip file & unzip
2. Enter the directory
3. Run `bundle install`
4. Start middleman development server by `middleman server`
5. Build your presentation
6. Build the final version for hosting by `middleman build`