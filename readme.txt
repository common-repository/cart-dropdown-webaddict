=== Cart Dropdown - Webaddict ===
Tags: woocommerce, cart, cart dropdown, cart items, woocommerce cart, cart in dropdown, woocommerce cart dropdown
Requires at least: 3.0
Tested up to: 4.9
Stable tag: 4.3
Requires PHP: 5.2.4
License: GPLv2
License URI: https://www.gnu.org/licenses/gpl-2.0.html

WooCommerce Cart Dropdown
A simple WordPress plugin for WooCommerce to show cart items as dropdown.

== Installation ==
Go to your dashboard and add new plugin via dashboard. You can also install it manually. Simply extract zip and upload it to plugins folder.

== Frequently Asked Questions ==
Question 1. How to display cart dropdown?
Answer: Use [wd-mini-cart] shortcode into page or `<?php echo do_shortcode('wd-mini-cart') ?>` in templates.

Question 2. Add filter to change cart dropdown text?
`<?php
function change_text($text) {
	$text = 'BAG';
	return $text;
}
add_filter('WH_Filter_Text','change_text');
?>`

Question 3. Add filter to change cart dropdown text?
`<?php
function change_icon($icon) {
	$icon = '<i class="fa fa-shopping-cart" aria-hidden="true"></i>';
	return $text;
}
add_filter('WH_Filter_Icon','change_icon');
?>`

== Changelog ==

= 0.5 =
This is beta version.

== Screenshots ==
screenshot-1.jpg
