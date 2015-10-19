=== Multisite Post Duplicator ===

Contributors: MagicStick, SergiAmbel
Tags: multisite, multi site, duplicate, copy, post, page, meta, individual, one
Requires at least: 3.0.1
Tested up to: 4.3.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Duplicate any individual page, post or custom post type from one site on your multisite network to another.

== Description ==

Duplicate any page, post or custom post type from one site on your multisite network to another.

Features:

*   Includes any custom post type on your network as long as the post type exists in your destination site
*   Copies all custom fields
*   Copies all related post meta
*	Copies any featurd image
*	Copies assiciated tags
*   Automatically copy your post/page/custom post type from one site to another from within your workflow 
*   Works with Advance Custom Fields
*   Clean and friendly User Interface
*   Select what status you want your new copies post to be i.e Published, Draft etc
*   Specify a prefix for the new post to avoid confusion
*   Works with Contact Form 7
*	Settings page to customise the default behaviour

== Installation ==

1. Upload `multisite-post-duplicator` folder to your `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. In WordPress admin on any of your sites within your multisite network go to Tools > Multisite Post Duplicator
4. Customise the default behaviour by going to Setting > Multisite Post Duplicator Settings

== Frequently Asked Questions ==

= Does this only work on a multisite network? =

Yes.

= Can I copy custom post types? =

Yes.

= What about post meta? Will these be copied over? =

Yes.

= Does this work with advanced custom fields? =

Yes. However, you have to have the same custom fields defined in each of your site on your network. See to help keep the fields in sync https://wordpress.org/plugins/acf-multisite-sync/

== Screenshots ==

1. User Interface
2. Meta Box

== Changelog ==

= 0.5 =
* NEW: Now copies featured images from posts (can be turned off in Settings page)
* NEW: Now copies any image media within the post content to the desination site (can be turned off in Settings page).
* NEW: Now copies post tags (can be turned off in Settings page)
* NEW: Admin notice on success of dupication. Has a link to go straight to the new post
* NEW: Submit button on WordPress post edit page will now update to show that a duplication has been requested
* FIXED: Fixed User prefix having unintentional double space in some senarios
* Settings page now global for all sites in the multisite network
* Prepared plugin for localisation (any translators welcome to contact me please!)
* Cleaned code for improved efficiency

= 0.4 =
* Added Meta Box within the post type so you can now duplicate your post to another site on your network as you work (Thanks to Sergi Ambel!).
* Added settings page to customise default behaviour.

= 0.3.1 =
* Fixed Activation errors.

= 0.3 =
* You can now filter by 'any' post type.

= 0.2.1 =
* Fixed bug where all posts were not appearing in certain scenarios

= 0.2 =
* Added support for Contact Form 7
* Duplication now correctly deals with serialised post meta

= 0.1 =
* Initial Release

== Upgrade Notice ==

= 0.1 =
Initial release
