=== MP Tweet List ===
Contributors: MikesPickz
Donate link: http://mikespickzws.com/wordpress-plugins/mp-tweet-list/
Tags: Twitter, display tweets, tweeting, social, tweet list, widget
Requires at least: 3.0
Tested up to: 4.7.5
Stable tag: 4.0

The MP Tweet List allows you to easily display your most recent tweets, with support for multiple Twitter accounts - with no Javascript or Flash.

== Description ==

The MP Tweet List allows you to easily display your most recent tweets, with *support for multiple Twitter accounts* - with *no Javascript or Flash*.

This plugin will add a widget that can be used in any widgetized area in your theme. It is fully customizable, allowing you to choose the widget title, how many tweets to display and which user's tweets to display. It also allows you to choose whether or not to convert @mentions, #hashtags and links independent of eachother. You can also filter out direct replies and add the timestamp to each tweet.

This plugin supports up to two Twitter users at the same time. Many blogs and websites have multiple authors and you may want to display two users' tweets that is where the MP Tweet List comes in handy. If you only want to display one Twitter user, simply leave the second user field blank.

The widget does not require any javascript or external files to work. It generates pure HTML lists.

As of June 11th, 2013, Twitter ended the use of its API 1.0 which allowed access to tweets without authentication. The Twitter API 1.1 requires authentication to access tweet data and therefore only Version 3.0 or greater of the MP Tweet List will continue to work.


== Installation ==

1. Upload the `mp-tweet-list` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. On the Settings page for the Plugin, follow the simple step-by-step process to create a Twitter app and set-up authentication.
1. Drag the MP Tweet List Widget into any widgetized area on your theme.
1. Configure Widget options.

== Frequently Asked Questions ==

= Can I display x number of tweets from user1 and y number of tweets from user2? =
At the moment, no. This plugin will evenly distribute the number of tweets displayed. For example, if 10 is selected - user1 will show 5 tweets and user2 will show 5 tweets. If 9 is selected - user1 will show 4 tweets and user2 will show 4 tweets. Contact Mike@MikesPickzWS.com to request this.

= Tweets are no longer showing up on my website, why? =
Please upgrade to Version 3.0 due to Twitter API changes.

== Screenshots ==

1. trunk/screenshot1.JPG
2. trunk/screenshot2.JPG

== Upgrade Notice ==

1. Version 4.0 adds the ability to filter out direct replies and to add the timestamp to the displayed tweets.

== Changelog ==

= 4.0 =
* Adds option to remove direct replies from the feed
* Adds option to display the tweet timestamp to the feed

= 3.1 =
* Checks if Twitter OAuthException is already declared before declaring it (for better compatibility with other plugins)

= 3.0 = 
* Makes use of Twitter API 1.1's OAuth authentication.

= 2.0 =
* Changed method of gathering tweets to cURL, to better support shared server environments

= 1.0 =
* Initial Release