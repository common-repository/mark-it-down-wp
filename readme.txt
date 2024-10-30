=== Mark It Down Wordpress! ===
Contributors: 7php
Donate link: https://www.paypal.me/khayrattee
Tags: markdown, markup
Requires at least: 4.7.0
Tested up to: 4.7.5
Stable tag: 2.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Helping you write posts/pages in plain-text Markdown syntax, while switching-off Visual Editor. It sits on the shoulders of a giant, namely Jetpack.

== Description ==

This is a simple plugin to help you write posts or pages in plain-text Markdown syntax. And even allowing plaint-text Markdown for comments as well. It will also switch-off the Visual Editor, as you don't need distractions. This plugin sits on top of a giant's shoulder, namely Jetpack.


This plugin is also installable via composer, see: https://github.com/7php/MarkItDownWordpress


== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/` directory, or install the plugin through the WordPress plugins screen directly. This plugin is also installable via **Composer**, see [https://github.com/7php/MarkItDownWordpress](https://github.com/7php/MarkItDownWordpress)
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Enable Markdown for posts & pages, by manually checking the checkbox at: **Settings > Writing > 'Use Markdown for posts and pages'**
4. If you want to enable Markdown for comments as well, check the checkbox here also: **Settings > Discussion > 'Use Markdown for comments'**


== Frequently Asked Questions ==

= Can this plugin be installed if the Jetpack module is also installed =

Yes you can. But you will not be able to use the "Markdown" module from Jetpack. I would advise that if you need Markdown support, and you also need to use Jetpack, then only use Jetpack only and use its Markdown functionality. Else if you are not a Jetpack user, this plugin is what you need for Markdown support.

= Why use this plugin instead of Jetpack =

Jetpack is normally a heavy plugin with lots and lots of functionalities which you might not even be using. So if you just need the "Markdown feature" of Jetpack, use *this* plugin only, that is why "Mark It Down Wordpress" was born for.

= Will You Supporting This Plugin Actively =

Yes, I will. I use this plugin in all my blogs and even for some of my clients. So it's in my honest interest to keep this plugin active and supported. If you have any question, shoot me an email at <markitdownwordpress@7php.com>

== Screenshots ==

1. This screen shot description corresponds to installation step 3, which instructs: Enable Markdown for posts & pages, by manually checking the checkbox at: **Settings > Writing > 'Use Markdown for posts and pages'**
2. This screen shot description corresponds to installation step 4, which instructs: to enable Markdown for comments as well, check the checkbox here also: **Settings > Discussion > 'Use Markdown for comments'**

== Changelog ==

= 2.0.1 =
* Remove dependencies to class.jetpack-options.php and trigger E_USER_WARNING if Jetpack plugin is also installed (instead of E_USER_ERROR)
* Allows user to install this plugin even though Jetpack is enabled.
* Not backward compatible to v1.0.0

= 1.0.0 =
* Initial commit of this plugin


== Upgrade Notice ==

= 2.0.1 =
- Removes all dependencies on Jetpack specific classes like class.jetpack-options
- Allows user to install this plugin even though Jetpack is enabled.

== Roadmap ==

- By default, toggle the checkbox to true for Settings > Writing > 'Use Markdown for posts and pages'
- By default, toggle the checkbox to true for Settings > Discussion > 'Use Markdown for comments'
- In plain-tex editor mode, remove the short-formatting buttons, e.g [b, i, link, b-quote, del].. etc. Make the editor, distraction free.
- Make an effort to provide Markdown buttons for the equivalent of [b, i, link, b-quote, del], just like bbcodes.
