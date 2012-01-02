=== User Role Editor ===
Contributors: shinephp
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=vladimir%40shinephp%2ecom&lc=RU&item_name=ShinePHP%2ecom&item_number=User%20Role%20Editor%20WordPress%20plugin&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted
Tags: user, role, editor, security, access, permission, capability
Requires at least: 3.0
Tested up to: 3.3
Stable tag: 3.3.1

User Role Editor WordPress plugin makes the role capabilities changing easy. You can change any standard WordPress user role (except administrator).

== Description ==

With User Role Editor WordPress plugin you can change user role (except Administrator) capabilities easy, with a few clicks.
Just turn on check boxes of capabilities you wish to add to the selected role and click "Update" button to save your changes. That's done. 
Add new roles and customize its capabilities according to your needs, from scratch of as a copy of other existing role. 
Unnecessary self-made role can be deleted if there are no users whome such role is assigned.
Role assigned every new created user by default may be changed too.
Capabilities could be assigned on per user basis. You can add new capabilities and remove unnecessary capabilities which could be left from uninstalled plugins.
Multi-site support is provided.

To read more about 'User Role Editor' visit [this page](http://www.shinephp.com/user-role-editor-wordpress-plugin/) at [shinephp.com](shinephp.com).

Русская версия этой статьи доступна по адресу [ru.shinephp.com](http://ru.shinephp.com/user-role-editor-wordpress-plugin-rus/)


== Installation ==

Installation procedure:

1. Deactivate plugin if you have the previous version installed.
2. Extract "user-role-editor.zip" archive content to the "/wp-content/plugins/user-role-editor" directory.
3. Activate "User Role Editor" plugin via 'Plugins' menu in WordPress admin menu. 
4. Go to the "Settings"-"User Role Editor" menu item and change your WordPress standard roles capabilities according to your needs.

== Frequently Asked Questions ==
- Does it work with WordPress 3.3 in multi-site environment?
Yes, it works with WordPress 3.3 multi-site. By default plugin works for every blog from your multi-site network as for locally installed blog.
To update selected role globally for the Network you should turn on the "Apply to All Sites" checkbox.


== Screenshots ==
1. screenshot-1.png User Role Editor main form
2. screenshot-2.png Add/Remove roles or capabilities
3. screenshot-3.png User Capabilities link
4. screenshot-4.png User Capabilities Editor

To read more about 'User Role Editor' visit [this page](http://www.shinephp.com/user-role-editor-wordpress-plugin/) at [shinephp.com](shinephp.com).


== Special Thanks to ==
* [Lorenzo Nicoletti](http://www.extera.com) - For the code enhancement. CUSTOM_USER_META_TABLE constant is used now for more compatibility with core WordPress API.
* Marcin - For the code enhancement. This contribution allows to not lose new custom capability if it is added to other than 'Administrator' role.
* [FullThrottle](http://fullthrottledevelopment.com/how-to-hide-the-adminstrator-on-the-wordpress-users-screen) - For the code to hide administrator role at admin backend.

= Translations =
* Russian: [Vladimir Garagulya](http://shinephp.com)
* -----------------------------------------------------
* translations below are included to the package, but all of them are outdated and every file needs to be updated.
* French: [Whiler](http://blogs.wittwer.fr/whiler)
* Finnish: [Lauri Merisaari](http://www.viidakkorumpu.fi)
* Japanese: Kaz, [Technolog.jp](http://technolog.jp)
* Hebrew: [Sagive](http://www.sagive.co.il)
* Italian: [Umberto Sartori](http://venezialog.net), [Talksina](http://www.iadkiller.org), [Alessandro Mariani](http://technodin.org), [Tristano Ajmone ](http://www.zenfactor.org)
* Spanish: [Dario Ferrer](http://www.darioferrer.com)
* Turkish: [Muhammed YILDIRIM](http://ben.muhammed.im), [Sadri Ercan](http://www.faydaliweb.com), [Can KAYA](http://www.kartaca.com)
* Belorussian: [Marsis G.](http://pc.de) - needs update
* Brasilian Portuguese: [Rafael Galdencio](http://www.arquiteturailustrada.com.br) - needs update
* Chinese: [Yackytsu](http://www.jackytsu.com) - needs update
* Dutch: [Rémi Bruggeman](http://www.remisan.be) - needs update
* German: [Peter](http://www.red-socks-reinbek.de) - needs update
* Hungarian: [István](http://www.blacksnail.hu) - needs update
* Persian: [Good Life](http://good-life.ir) - needs update
* Polish: [TagSite](http://www.tagsite.eu) - needs update
* Swedish: [Christer Dahlbacka](www.startlinks.eu) - needs update

Dear plugin User!
If you wish to help me with this plugin translation I very appreciate it. Please send your language .po and .mo files to vladimir[at-sign]shinephp.com email. Do not forget include you site link in order I can show it with greetings for the translation help at shinephp.com, plugin settings page and in this readme.txt file.
If you have better translation for some phrases, send it to me and it will be taken into consideration. You are welcome!
Share with me new ideas about plugin further development and link to your site will appear here.


== Changelog ==
= 3.3.1 =
* 12.12.2011
* Compatibility with Internet Explorer fix: It automatically replaced '&copy' in '&copy_from_user_role' URL parameter inside JavaScript code to copyright sign.So I should use other name for this parameter. Thanks to Michael Wiekenberg for the help with isolating this issue.

= 3.3 =
* 10.12.2011
* New role can be created as a copy of other existing one.
* You can hide/show deprecated capabilties (level_1 - level_10).
* Users with "Administrator" role are not shown to other users with "list_users" capability.
* Plugin data cleanup is added - plugin options will be automatically deleted if you delete plugin via WordPress link.
* Some code enhancements are applied, e.g. optimization and using of WordPress API instead of self-written routine.
* New bugs are added :) - it's a joke of course, but if you find some, please report, I will fix it ASAP.

= 3.2.1 =
* 01.08.2011
* This is minor bug-fix update. If you didn't meet this bug you can skip this update. "usermeta" table doesn't exist bug appearing on some multi-site blogs is fixed. Read [this post](http://wordpress.org/support/topic/multisite-setup-gives-usermeta-table-error) for more information. Thanks to harpinder for discovering this bug and for the help with testing updated code. "usermeta" Db table name is define by more universal way now.

= 3.2 =
* 25.07.2011
* If you run multi-site WordPress network, User Role Editor will automatically duplicate all roles from the main blog (blog with mininal ID) to every new created blog.
* Some fixes, refactoring and logic change were applied to code to enhance its productivity. There were some complaints for PHP timeout error after trying to open plugin Settings page. 
* Thanks to Grant Norwood for code fix to hide PHP warnings he met during plugin usage. 
* Hebrew translation is added. Thanks to Sagive.
* French translation is updated. Thanks to Whiler.
* Japan translation is updated. Thanks to Kaz.
* Spanish translation is updated. Thanks to Dario.

= 3.1.1 =
* 07.07.2011
* CUSTOM_USER_META_TABLE constant is used now for more compatibility with core WordPress API. Thanks to [Lorenzo Nicoletti](http://www.extera.com) 
* Turkish translation is updated. Thanks to Muhammed YILDIRIM. Other language translators are welcome!

= 3.1 =
* 03.06.2011
* Add/Remove capability boxes are added to the User Role Editor
* Capabilities could be assigned directly to the user, additionally to the assigned role
* PHP4 is not supported by this plugin anymore. Update your site to PHP5 in order to use this plugin and [near to release WordPress 3.2 :)](http://wordpress.org/about/requirements/) 
* Minor compatibility issues with other plugins  were fixed

= 3.0.4 =
* 18.04.2011
* minor update: PHP4 compatibility issue in code was discovered and fixed. PHP5 users could skip it. PHP4 users should think about update to PHP5, as WordPress 3.2 (planned to July 2011) will not provide PHP4 compatibility more.

= 3.0.3 =
* 17.04.2011
* Capabilities in human readable form are sorted by alphabet (usefull for translated form) now, not by inner capability name.
* Finnish translation is added.

= 3.0.2 =
* 11.04.2011
* Swedish translation is added.
* Alternative Italian translation is added. Rename ure-it_IT_1.* files to ure-it_IT.* if wish to try it.
* ShinePHP.com RSS feed is excluded from plugin settings page. Use this link http://feeds.feedburner.com/shinephp with your favorite RSS reader if you wish to read it.

= 3.0.1 =
* 27.02.2011
* Spanish translation is updated. Thanks to [Dario Ferrer](http://www.darioferrer.com). Other language translation wait for update too. You are welcome :).

= 3.0 =
* 06.02.2011
* Compatibility with WordPress 3.1 Release Candidate 3 and real multi-site feature are provided.
* Role capabilities list are sorted now in the alphabetical order. Easier to find - easier to manage.
* Code fix: allows to not lose new custom capability if it is added to other than 'Administrator' role. Thanks to Marcin for the contribution to the code of this plugin.
* Under multi-site environment:
* 1) URE has additional option 'Apply to All Sites' which allows you to apply updates to the selected role at all sites of your network. If some site has not such role, it will be added. You should know, that this option works for the role update only. All other actions as 'Add' or 'Delete' role still works for the currently selected blog/site only.
* 2) URE plugin settings page is available only to user with network superadministrator rights.

Older records are available at [this page](http://www.shinephp.com/user-role-editor-wordpress-plugin/#changelog).

== Additional Documentation ==

You can find more information about "User Role Editor" plugin at [this page](http://www.shinephp.com/user-role-editor-wordpress-plugin/)

I am ready to answer on your questions about plugin usage. Use [ShinePHP forum](http://shinephp.com/community/forum/user-role-editor/) or [plugin page comments](http://www.shinephp.com/user-role-editor-wordpress-plugin/) for it please.
