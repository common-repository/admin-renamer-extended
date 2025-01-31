=== Admin renamer extended ===
Contributors: Ramon Fincken
Donate link: http://donate.ramonfincken.com
Tags: admin,admins,rename,founder,change,user,users,renamer,extended,username
Requires at least: 3.0
Tested up to: 4.6
Stable tag: 3.2.1

Read this first https://wordpress.org/support/topic/better-plugins/ <br>
Plugin to change your default admin username ( with GUI to change all other admin names too ).

== Description ==

Read this first https://wordpress.org/support/topic/better-plugins/ <br>
Plugin to change your default admin username ( with GUI to change all other admin names too ).<br>
Tested on multisite<br>
Will check for:<br>
* Empty names<br>
* Existing usernames<br>
* Valid username ( no funky special characters )<br><br>
As always -> make a backup first

== Installation ==

1. Upload directory `admin_renamer_extended` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Visit Plugins menu to change your admin name(s).

== Frequently Asked Questions ==

= I have a lot of questions and I want support where can I go? =

<a href="http://pluginsupport.mijnpress.nl/">http://pluginsupport.mijnpress.nl/</a> or drop me a tweet to notify me of your support topic over here.<br>
I always check my tweets, so mention my name with @ramonfincken and your problem.


== Changelog ==

= 3.2.1 =
Changed: Possible XSS bugfix reported by CBiu

= 3.2 =
Changed: removed mysql_real_escape_string

= 3.1 =
Added: Extra check to prevent empty username

= 3.0 =
Added: Multisite support. Thanks to Peter Luit for reporting!

= 2.0 =
Changed: WP standards used to get all admins<br>
Added: Extra security check based on 'remove_users' capabilities

= 1.1 =
First release

= 1.2 =
Tidying of html code, added screenshots

= 1.3 =
Applied WP way of handling usernames

= 1.4 =
Same as 1.3 Commit error so scipped 1 version

= 1.5 =
Added links to plugin page & some extra security

== Screenshots ==

1. Before rename
2. After rename
