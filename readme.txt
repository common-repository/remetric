=== Remetric Live Chat via SMS ===
Version: 1.1.0
Contributors: dallas22ca
Author: Dallas Read
Author URI: http://www.DallasRead.com
Donate link: http://www.remetric.com/
Tags: live chat, live support, marketing, customer support, customer service, remetric
Requires at least: 3.0.1
Tested up to: 4.9.8
Stable tag: 1.1.0
License: MIT

Live Chat with your visitors from your phone via SMS with Remetric Live Chat.

== Description ==

**Remetric puts the power of connecting with visitors in the palm of your hand. You get:**

* Extremely customizable live chat for your visitors to interact with.
* **Chat from your phone:** Perfect for the small business owner. Through SMS (text messages), you'll be able to stay in touch with the visitors on your website.
* **Smart-Conversation Triggers:** Start conversations based on your specified criteria. For example, if they've been on your checkout page too long, ask them "Do you need help checking out?"
* **Multiple Agents:** Put the power of multiple customer service reps to work for you! (Coming Soon!)
* **Canned Messages:** Reply to people with shortcodes. For example, you could set the "#contact" shortcode to get substituted with your contact information.

**We now offer a whitelabelled version of our product for you to resell (you set your own branding and billing)!**

The WordPress Remetric plugin interacts with and uses Remetric.com to deliver files, share data between websites, ensure quick server response times, and real-time data.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/remetric` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Find the Remetric tab in WP Admin area.
4. Visit the "Live Chat" page to set up your agents, availability, & SMS.
5. Visit the "People" page to chat with your online visitors.

== Whitelabel Installation ==

1. At the top of `remetric.php`, set your whitelabel token constant: `define('REMETRIC_WHITELABEL', ’y0ur s3cr3t t0k3n’);`.
2. If you also wish to rename Remetric in the WP Admin area, you can do so in the first two arguments of the `menu_page` function of `remetric.php`. You can also replace the `dashicons-chart-bar` icon in accordance with WP's `add_menu_page` function. You may also want to change the initial loading message on `page.php` in `#remetric-admin`.
3. To find your secret token and set whitelabel options, log in @ https://app.remetric.com/ (or your main Remetric WP Admin) and go to My Account > Whitelabel.

== Frequently Asked Questions ==

Coming soon!

== Screenshots ==

1. Set up your live chat to match your brand.
2. You can set your SMS availability. If you're not online, we will collect your leads and send you their information. All times are displayed according to your current time zone.
3. Canned messages are a great way to respond with quick, well-informed answers. If you have a canned message with a shortcode of "hours", simply respond to a chat with "#hours" and we'll fill in the corresponding message - even through text message.
4. Just like in brick-and-mortar storefront, you're going to get the most out of your customers if you are pro-actively approaching them. Triggers allows you to set greetings and messages targeted at specific scenarios.
5. Add other chat agents so that they can lighten your load. On the Availability page, you can set who is available when and how.
6. The Convos app is where you can chat with your all of your visitors.
7. A clean, simple interface ensures you'll find your live chat a breeze (but you'll probably just chat through your phone anyway)!

== Changelog ==

= 1.1.0 =
* Streamlined the interface

= 1.0.7 =
* Fixes for more consistent conversations.

= 1.0.6 =
* Add whitelabel support.

= 1.0.5 =
* Fix front end JS script.

= 1.0.4 =
* Bars revamp & a clean UI.

= 1.0.3 =
* Fix DEBUG mode bug.

= 1.0.2 =
* Added help chat.
* Fix license link.

= 1.0.1 =
* A UI Revamp (using Bars).

= 1.0.0 =
* Initial release of the Remetric plugin.
