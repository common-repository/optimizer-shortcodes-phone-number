=== Optimizer Shortcodes - Phone Number ===
Contributors: businessoptimizer, rajivlodhia
Tags: phone, phone number, phone number shortcode, phone shortcode
Requires at least: 4.7
Tested up to: 6.0
Requires PHP: 7.3
Stable tag: 1.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

A very simple plugin that turns your phone number into a shortcode. This plugin provides a field and shortcode for your phone number allowing you to use it anywhere on your site. If you ever need to update your phone number, you'd just need to change it in one place.

This plugin works together with other Optimizer Shortcodes plugins. Find a list of all our Optimizer Shortcodes plugins [here](https://businessoptimizer.org/collections/plugins)

== Installation ==

1. Copy the `optimizer-shortcodes-phone-number` folder into your `wp-content/plugins` folder
2. Activate the Optimizer Shortcodes - Phone Number plugin via the plugins admin page
3. Set your phone number in the new field (`/wp-admin/admin.php?page=optimizer-shortcodes`)

== Usage Instructions ==

After setting your phone number in the new settings page (`/wp-admin/admin.php?page=optimizer-shortcodes`), you can use the shortcode [optimizer_phone_number] anywhere on your site to display that phone number.
If you need to use the field value in your theme files or template, you can print it with PHP like this:
<?php echo do_shortcode('[optimizer_phone_number]'); ?>

== Credits ==

Plugin built by [Rajiv Lodhia](https://rajivlodhia.com/) for [Business Optimizer](https://businessoptimizer.org/)

== Screenshots ==
1. The new menu page and custom phone number field

== Changelog ==

= 1.0.0 =
* Initial Release.

= 1.0.1 =
* Tested for WP 6.0+
