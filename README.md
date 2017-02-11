Wallabag v2: A TT-Rss to Wallabag v 2.x plugin
=====================

A Wallabag v 2.x plugin for Tiny-Tiny-RSS designed to login via Oauth and work with the Wallabag v 2.x api.


### Installing the plugin:

1. Clone this repository in a directory readable by your http server or php-fpm daemon.

2. Add a symbolic link from `tt-rss/plugins.local/wallabag_v2` to the directory `wallabag_v2` of this repository.

3. Get Oauth token configuration

	* In Wallabag: Create a new Oauth client in the Developer tab, take note of the client id and client secret.
	* In TT-Rss: Enable the plugin and enter the Wallabag credentials in the *Wallabag v2* accordion pane below *Plugins*: *username*, *password*, *client_id* and *client_secret*.
     	
4. Enjoy posting directly to Wallabag with 1-click in the footer of each article!

### Troubleshoot

If you keep getting 404 errors, check if you didn't add a trailing slash to the url of your Wallabag instance in preferences.

For 400 errors, check your credentials.

### TODO ... which may or not actually ever get done...

1. Enable use of the refresh token
2. Fine tune error messages
3. Add tag support
4. Add hotkey support
5. Add colour changing button
6. Rewrite the entire code as it's really dirty.

### Helpfull Links:

* [Official TT-RSS Plugin Documentation](https://tt-rss.org/gitlab/fox/tt-rss/wikis/Plugins)
* [Official Wallabag Documentation](http://doc.wallabag.org/en/v2/)
* [Wallabag on GitHub](https://github.com/wallabag/wallabag)
* [Wallabag Home Page](https://www.wallabag.org/)

### Credits

Thanks to:

* [fxneumann's OneClickPocket plugin for TTRSS](https://github.com/fxneumann/oneclickpocket)
* [xppppp's Wallabag v1 plugin for TTRSS](https://github.com/xppppp/ttrss-wallabag-plugin)
* [joshp23's version of this plugin](https://github.com/joshp23/ttrss-to-wallabag-v2)
