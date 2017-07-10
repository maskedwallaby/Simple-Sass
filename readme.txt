=== Simple Sass WP ===

Contributors: automattic
Tags:

Requires at least: 4.0
Tested up to: 4.8
Stable tag: 1.0.0
License: GNU General Public License v2 or later
License URI: LICENSE

A starter theme called Simple Sass WP.

== Description ==

A simplified Sass/BEM WordPress template using a simplified version of Automatic\'s UnderScores theme. :)

== Installation ==

1. In your admin panel, go to Appearance > Themes and click the Add New button.
2. Click Upload and Choose File, then select the theme's .zip file. Click Install Now.
3. Click Activate to use your new theme right away.

== Compiling SASS ==

If you are not using a build tool, either GUI or CLI-based, you can use the Sass command line to compile the sass files found in this theme. Here’s the command you’ll want to use:

	sudo sass --watch sass/style.scss:style.css

Sudo is necessary to overwrite whatever previous style.css file already exists in the main directory. All of your other sass files should be imported into sass/style.scss.

== Changelog ==

= 1.0 - May 12 2015 =
* Initial release

== Credits ==

* Based on Underscores http://underscores.me/, (C) 2012-2017 Automattic, Inc., [GPLv2 or later](https://www.gnu.org/licenses/gpl-2.0.html)
* normalize.css http://necolas.github.io/normalize.css/, (C) 2012-2016 Nicolas Gallagher and Jonathan Neal, [MIT](http://opensource.org/licenses/MIT)
