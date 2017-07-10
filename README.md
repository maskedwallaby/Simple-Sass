[![Build Status](https://travis-ci.org/Automattic/_s.svg?branch=master)](https://travis-ci.org/Automattic/_s)

Simple Sass WP
===

Hi. I'm a starter theme called Simple Sass. I'm a theme based on Automattic's Underscores them, and I'm meant for hacking. Don't use me as a parent theme, but flex me like a piece of putty. You know you want to.

My CSS is Sass-based and based on a simplified version of the BEMit methodology. That's why you downloaded me, right?

* A just right amount of lean, well-commented, modern, HTML5 templates.
* A helpful 404 template.
* Custom template tags in `inc/template-tags.php` that keep your templates clean and neat and prevent code duplication.
* Some small tweaks in `inc/template-functions.php` that can improve your theming experience.
* A script at `js/navigation.js` that makes your menu a toggled dropdown on small screens (like your phone), ready for CSS artistry. It's enqueued in `functions.php`.
* Smartly organized starter CSS in `the /sass/ directory` that will help you to quickly get your design off the ground.
* Licensed under GPLv3 or later. :) Use it to make something cool.

Getting Started
---------------

== Compiling SASS ==

If you are not using a build tool, either GUI or CLI-based, you can use the Sass command line to compile the sass files found in this theme. Here’s the command you’ll want to use:

	sudo sass --watch sass/style.scss:style.css

Sudo is necessary to overwrite whatever previous style.css file already exists in the main directory. All of your other sass files should be imported into sass/style.scss.

That said, there's no shame in using GUI tools. [Prepos](https://prepros.io/), [Koala](http://koala-app.com/), and [Scout](http://scout-app.io) are some great free options. At work, I use [CodeKit](https://codekitapp.com), but it's Mac-only. Then of course there's [Gulp].) :)

Now you're ready to go! The next step is easy to say, but harder to do: make an awesome WordPress theme. :)

Good luck!
