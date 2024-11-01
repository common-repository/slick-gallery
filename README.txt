=== Slick Gallery ===
Contributors: herooutoftime
Tags: gallery, slick
Requires at least: 4.5.3
Tested up to: 4.6.1
Stable tag: 4.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Easily turn WP gallery into a Slick slider. Enable the plugin, add/edit your galleries and set slick properties through custom gallery sidebar options.

== Description ==

Wordpress plugin to easily turn any gallery into a Slick-driven slider.

**Before:**

`
[gallery ids="1,2,3"]
`

**After:**

`
[gallery
    slick_use_slick="1"
    slick_slides_to_show="1"
    slick_slides_to_scroll="1"
    slick_dots="1"
    slick_arrows="1"
    slick_infinite="0"
    slick_draggable="1"
    slick_autoplay="1"
    slick_autoplay_speed="1"
    slick_speed=".5"
    slick_responsive="{breakpoint: 1024,settings: {slidesToShow: 3,slidesToScroll: 3,infinite: false,dots: true}}"
    columns="4"
    size="large"
    ids="7,9,5,6"]
`

== Installation ==

This section describes how to install the plugin and get it working.

= Manually =

1. Upload `slick-gallery` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress


== Constants ==

Enable developer mode to use non-minified JS & output slick properties in frontend. Don't forget to turn off in production environment.
`define('WP_SLICK_DEV', true);`

To turn off CSS & JS injection via the plugin:

`
define('WP_SLICK_CSS', false);
define('WP_SLICK_JS', false);
`

If `WP_SLICK_CSS` is set to `false` you need to inject `slick.css` & `slick-theme.css` by yourself.
If `WP_SLICK_JS` is set to `false` you need to inject `slick.js` by yourself and initialize `slick`.

== Frequently Asked Questions ==

= A question that someone might have =

An answer to that question.

= What about foo bar? =

Answer to foo bar dilemma.

== Screenshots ==

1. WP Gallery MCE View enhanced with Slick properties
2. Enhanced sidebar options for gallery create/edit view modal

== Changelog ==

= 1.0.4 =
* Minor improvements and bugfixes

= 1.0 =
* Initial version

== Thanks ==

[Ken Wheeler](https://github.com/kenwheeler) for [Slick](https://github.com/kenwheeler/slick/)