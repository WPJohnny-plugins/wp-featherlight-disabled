=== WP Featherlight Disabled ===

Contributors: wpjohnny, yin
Tags: lightbox, jquery lightbox, jquery, gallery, image, lightbox images, image lightbox, lightbox gallery, lightbox image, lightbox popup, featherlight, photo gallery, popup image, popup images, popup lightbox, responsive lightbox, swipe, wordpress image lightbox, wordpress lightbox, wordpress slideshow lightbox, photography, images, minimal, responsive, photo, photos  
Requires at least: 4.0  
Tested up to: 5.4.2  
Stable tag: 1.0
Donate link: https://www.paypal.me/wpjohnny
License: GPL-2.0+  

The most lightweight WordPress lightbox plugin...and the featherlight CSS/JS (only 7kb) is automatically disabled unless you manually enable within each post.

== Description ==

This minimal WordPress lightbox plugin adds high performance, responsive jQuery lightbox functionality to your images. When standard WordPress images/galleries are clicked, the background fades out into black as images display in lightbox popup. Galleries can be navigated with on-screen arrows, touchscreen swipes, or pressing arrows keys. 

In order for WordPress images and galleries to be lightboxed:
- You must select the "Media File" option when choosing where thumbnails should link. You can also select the "Custom Link" option if it links directly to an image file. This should work for any image file, even if it's hosted on another website.
- Enable on each post by checking "Enable lightbox" on the WP Featherlight settings.
- You can also lightbox videos, iframes, and ajax content by adding data attributes to your content. For more details on custom content loading, check out the [featherlight documentation](https://github.com/noelboss/featherlight/#usage).

My plugin is simply a forked version of the original [WP Featherlight plugin](https://wordpress.org/support/plugin/wp-featherlight). Only difference is the original loads the featherlight CSS/JS on every page whereas mine only loads when you manually enable.

= Features: =
* Ultra-lightweight - even more lightweight than the original WP Featherlight since the lightbox CSS/JS is not loaded automatically.
* Manual activation - to enable lightbox functionality, simply click the checkbox in your post settings.
* Retains WP Featherlight features - has all the same features and filters as the original WP Featherlight plugin (up to version 1.3.3)

== Installation ==
<ol>
	<li>Upload the folder wp-featherlight-disabled to the `/wp-content/plugins/` directory</li>
	<li>Activate the plugin through the 'Plugins' menu in WordPress</li>
</ol>

== Frequently Asked Questions ==

= Does this plugin work with the newest WP version and also older versions? =
Yes, this plugin works perfect with the latest version of WordPress! It also works with older versions as well but you should always run the latest WordPress and PHP version for best security and performance. This plugin is used in my critical sites so you can be assured it works perfect.

= Will this plugin slow down my site? =
No. It's the most lightweight lightbox plugin possible. It does only the essential function and nothing more. No heavy PHP processing or database queries. I'm an absolute speed fanatic.

= Do you plan to add more features? =
Probably not. This was intended as a free community plugin and to be as lightweight as possible. You're welcome to fork it and make your own.

= What if I have a display problem? =
Display problems can be related to your theme. You can open a support request or see more information on the official Featherlight script [GitHub page](https://noelboss.github.io/featherlight/).

= What filters are available? =

Plugin has no GUI options. Some handy filters are available to modify default behavior. All images using default WordPress captions will also include a caption when the image is lightboxed. To disable this behavior, filter `wp_featherlight_captions` to false.

== Screenshots ==

1. A view of the (clicked) image displaying in jQuery lightbox.
2. Manual checkbox on post setting (unchecked by default).

== Changelog ==

= 1.0 =

Starting fork off of the official WP Featherlight version 1.3.3. (Only thing changed was the default load behavior, and checkbox wording in post setting.) For older changes, see [the official WP Featherlight changelog on GitHub](https://github.com/cipherdevgroup/wp-featherlight/blob/release/CHANGELOG.md)
