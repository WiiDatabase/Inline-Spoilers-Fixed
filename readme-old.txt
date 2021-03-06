=== Inline Spoilers ===
Contributors: sergeykuzmich, iCON
Tags: shortcode, spoiler
Requires at least: 3.9.1
Tested up to: 4.7.2
Stable tag: 1.2.6.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

The plugin allows to create content spoilers with simple shortcode. This version works with Infinite Scroll and integrates a few fixes.

== Description ==
`Example: [spoiler title="Expand Me"]Spoiler content[/spoiler]`

== Installation ==
1. Upload folder `inline-spoiler` to the `/wp-content/plugins/` directory;
1. Activate the plugin through the 'Plugins' menu in WordPress;
1. Place shortcode (*Example:* `[spoiler title="Expand Me"]Spoiler content[/spoiler]`) in your content;

== Frequently Asked Questions ==

= How do I can customize design of the spoiler? =
To change layout of a spoiler, please, edit `styles/inline-spoilers-styles.css` file.

= How to remove text from the title? =
To remove default title you can use
`
[spoiler title="&nbsp;"]
...
[/spoiler]
`

== Screenshots ==

1. To add a spoilered content to your post/page just put that content between `[spoiler][/spoiler]` shortcode
2. Collapsed spoiler in your post/page
3. Expanded spoiler

== Changelog ==
= 1.2.6.1 (mod) =
* Style fixes
* Load JS & CSS everywhere (workaround for bug)

= 1.2.6 (mod) =
* Modification by iCON from WiiDatabase.de
* Plugin now works with Infinite Scroll
* Fix paragraph tags inside spoiler (for real this time)
* Few style changes to reduce spoiler height

= 1.2.5 =
* Update spoiled content formatting method

= 1.2.4 =
* Add WP_DEBUG mode
* Fix incorrect paragraph tags inside the spoiler

= 1.2.3 =
* JavaScript bug fix

= 1.2.2 =
* Update spoiler default behaviour

= 1.1.2 =
* Update Russian translation
* Add attribute 'initial_state' to define default state of a spoiler `initial_state=(expanded|collapsed)`. Default state is 'collapsed'
* Security updates

= 1.0.2 =
* Update Russian translation

= 1.0.1 =
* Plugin Release