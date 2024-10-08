=== Schedule Posts Calendar ===
Contributors: GregRoss
Plugin URI: http://toolstack.com/schedulepostscalendar
Author URI: http://toolstack.com
Tags: admin, posts, calendar
Requires at least: 3.0.0
Tested up to: 6.4.1
Stable tag: 5.3

Adds a JavaScript calendar to the scheduled publish widget to allow you to select a date and time graphically instead of via the text entry boxes.

== Description ==

Adds a JavaScript calendar to the scheduled publish widget to allow you to select a date and time graphically instead of via the text entry boxes.

This plugin uses the gpl'd dhtmlxcalendar (http://dhtmlx.com/docs/products/dhtmlxCalendar/index.shtml) for the calendar control.

This code is released under the GPL v2, see license.txt for details.

== Installation ==

1. Extract the archive file into your plugins directory in the schedule-posts-calendar folder.
2. Activate the plugin in the Plugin options.

== Frequently Asked Questions ==

= What browsers are supported? =

Try it and find out, the JavaScript to insert the calendar is pretty standard and should support any reasonably modern browser.

= Why is the calendar overlapping the other areas? =

If you are using IE in compatibility mode the calendar will overlap other areas, disable compatibility mode.

== Screenshots ==

1. The publish panel with the schedule menu expanded showing the calendar.
2. The publish panel with the schedule menu expanded with the default WordPress date/time fields hidden.
3. The publish panel with the default WP fields hidden and a popup calendar field.
4. The publish panel with the default WP fields hidden and a popup calendar visible.
5. The control panel options.
6. The schedule menu item in the posts/pages list.
7. The schedule mode in the posts/pages list.

== Changelog ==
= 5.3 =
* Release date: August 22, 2023
* Fixed medium severity security issues.
* Added full translation support.

= 5.2 =
* Release date: February 8, 2018
* Updated calendar code to v5.1.
* Fixed bug where post dates at the end of a month would wrap if the current month had lest days in it.
* Fixed PHP warning if the options had not yet been saved.

= 5.1 =
* Release date: February 5, 2016
* Fixed: Cleaned up some WP_DEBUG messages.
* Fixed: Incorrect month set when the today button was pressed with the popup calendar enabled.

= 5.0 =
* Release date: April 3, 2015
* Added "wordpress" theme that copies the colors from the current wordpress admin theme.
* Updated calendar code to v4.1.3.
* Updated default calendar style to the new "wordpress" theme.

= 4.3 =
* Release date: December 30, 2013
* Fixed bug with the start of week setting that was being overwritten.

= 4.2 =
* Release date: December 27, 2013
* Fixed issue with Tuesday/Thursday translations in the calendar

= 4.1 =
* Release date: December 27, 2013
* Fixed bug in translation code, enable/disable logic was inverted
* Fixed bug in preferences code, would not allow you to disable translations

= 4.0 =
* Release date: December 24, 2013
* Added language support.

= 3.6 =
* Release date: December 21, 2013
* Add 'Today' button to reset the calendar to the current date.

= 3.5 =
* Release date: December 11, 2013
* Updated to new dhtmlxcalendar calendar code (version 3.6 build 131108).
* Support new dhtmlxcalendar theme 'Terrace' (now the default for new installs).
* Re-styled Cancel link in the post/page edit, it is now a button aligned to the right.
* Added uninstall routine.
* Tested with WordPress 3.8.

= 3.4 =
* Release date: November 25, 2013
* Bug fix on the quick edit theme selection code.

= 3.3 =
* Release date: November 24, 2013
* Bug fix on the theme selection code, thanks JochenT.
* Code update to resolve deprecated use of role/responsibilities when adding the admin page, thanks JochenT.

= 3.2 =
* Release date: July 18, 2012
* Minor update, in previous versions if you use the quick edit mode and make a change to the scheduled date it would not update the scheduled date in the list.
* Test up to WordPress 3.4.1.

= 3.1 =
* Release date: May 1, 2012
* Minor bug fix, when using the new quick edit mode in the posts/pages changing the date/time would incorrectly set the hour to be the same as the minute.

= 3.0 =
* Release date: April 16, 2012
* Major update to include support for a schedule calendar in the posts/pages list.

= 2.1 =
* Release date: March 10, 2012
* Minor bug fix that caused the in-line calendar to start one month in the future.

= 2.0 =
* Release date: March 8. 2012
* Created settings page.
* Added options to set the start of the week.
* Added theme option.
* Added option to hide default WordPress date/time fields.
* Added popup option to the calendar instead of the default in-line.

= 1.1 =
* Release date: March 5, 2012
* Minor update to reduce the size of the calendar div from 250px to 230px.
* Added FAQ's.

= 1.0 =
* Release date: March 2, 2012
* Initial release.

== Upgrade Notice ==
= 5.2 =
None.

== Roadmap ==
* None at this time.
