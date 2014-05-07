=== HTTP URLs ===
Contributors:      McGuive7, MIGHTYminnow
Donate link:       http://wordpress.org/plugins/http-urls
Tags:              http, https, url, protocol, change, switch, address
Requires at least: 3.0
Tested up to:      3.9
Stable tag:        1.0
License:           GPLv2 or later
License URI:       http://www.gnu.org/licenses/gpl-2.0.html

The easiest way to get the HTTP/HTTPS version of any URL.

== Description ==

Use the simple `[http-url]` shortcode to convert any URL to either HTTP or HTTPS.

= Shortcode =
`[http-url]`
By default the `http-url` shortcode will output the URL of the current post (must be used within the loop), converted to HTTP.

= Shortcode Attributes =
Manually specify the URL to be converted:
`[http-url url="https://mysite.com"]`

Convert URL to HTTPS, instead of to HTTP:
`[http-url to_https="true"]`

= PHP Usage =
HTTP URLs also provides two functions that can be used in your php:
`hu_get_http_url( $url ); // Returns URL converted to HTTP
hu_get_https_url( $url ); // Returns URL converted to HTTPS`

= Why Use This? =
The most common case for using this plugin is in conjunction with social media sharing/commenting plugins, in which data is tied to a specific URL. On sites that are visible via both HTTP and HTTPS, this means that two different sets of differing data are created for every page. [Learn More &rarr;](http://www.mightyminnow.com/2014/05/how-to-make-social-media-shares-counts-and-comments-work-across-http-and-https/)

== Installation ==

Simply install and activate the plugin. The [http-url] shortcode and related PHP functions will now be available for you to use.

== Changelog ==

= 1.0 =
* First release

== Upgrade Notice ==

= 1.0 =
* First Release