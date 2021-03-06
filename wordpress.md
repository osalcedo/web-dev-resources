WordPress
=

[WordPress](http://wordpress.org/) is an open source, PHP-based content management system for the web, developed by the [WordPress core community](http://make.wordpress.org/core/).

Get [latest major version](http://wordpress.org/download/), or clone the git mirror of alpha development: git://develop.git.wordpress.org.

## Caching

[WordPress + Memcached](http://scotty-t.com/2012/01/20/wordpress-memcached/) An overview of caching in WordPress.

[Evan Solomon's "Fast WordPress"](http://evansolomon.me/notes/faster-wordpress-multisite-nginx-batcache/)

See also [Web Servers > Caching](web-servers.md#caching), [HTTP > Caching](http.md#caching) and [PHP > Caching](php.md#caching).

[WordPress Memcached Object cache](https://wordpress.org/plugins/memcached/) Use the WordPress object cache API with Memcached.

## Debugging

[Debug Bar](https://wordpress.org/plugins/debug-bar/) Add a debug menu to the admin bar that shows query, cache and other helpful debugging info.

[Debug Bar Console](https://wordpress.org/plugins/debug-bar-console/) Add a PHP/MySQL console to the debug bar.

[Query Monitor](https://wordpress.org/plugins/query-monitor/) Adds debug output including: all DB queries, all hooks and their callbacks, PHP errors, constants, WP_Http requests.

[Rewrite Rules Inspector](https://wordpress.org/plugins/rewrite-rules-inspector/)

[Demo Data Creator](https://wordpress.org/plugins/demo-data-creator/)

[WPDB Migrate Pro](https://deliciousbrains.com/wp-migrate-db-pro/) Sync DB content between WordPress installs. Requires a paid license.

## Libraries

Standalone libraries that can be included with plugins or themes.

[Posts 2 Posts](https://github.com/scribu/wp-posts-to-posts/) Create relationships between posts, pages, custom post types, and users.

[Custom Metaboxes and Fields](https://github.com/WebDevStudios/Custom-Metaboxes-and-Fields-for-WordPress) Create admin UI for post metadata.

## Plugins

[Memcached Object Cache](https://wordpress.org/plugins/memcached/) Use Memcached as an object cache. Requires Memcached, see <sup>1</sup>.

[Mercator](https://github.com/humanmade/Mercator) Multisite domain mapping for the modern era (requires 3.9+). A sequel-plugin to [WPMU Domain Mapping](http://wordpress.org/plugins/wordpress-mu-domain-mapping/).

[Require Login](https://github.com/manovotny/wordpress-require-login) Limit front-end access to logged in users.

[Gravity Forms](http://www.gravityforms.com/) offers UI for administrators to create forms with ease and output them on the front-end. Requires a paid license. Not easily extensible in some regards, and development takes place in a closed community.

[Regenerate Thumbnails](https://wordpress.org/plugins/regenerate-thumbnails/)

## Themes

[Timber](https://github.com/jarednova/timber) adds support for the [Twig Template engine](http://twig.sensiolabs.org/) in WordPress theme templates, which means you can benefit from features like multiple inheritance while templating.

## Blogs

[Post Status](http://www.poststat.us/), Brian Krogsgard's WordPress News site.

## Podcasts

[Apply Filters](http://applyfilters.fm/), A WordPress development podcast.

[Dradcast](http://dradcast.com/), A general WordPress community news podcast.

## Footnotes

* <sup>1</sup> Memcached is not available in common shared environments or the core PHP install, as it is a PECL extension. For installation, see ["How to install and use Memcached on Ubuntu 12.04"](php.md)
