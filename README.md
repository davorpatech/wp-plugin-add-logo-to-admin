# WORDPRESS :: Add Logo to Admin

Add a custom logo to your wp-admin and login page.

**Contributors**: `c.bavota`, `tinkerpriest`, `davorpatech`
**Tags**: *custom logo*, *admin*, *login*, *wp-admin*, *admin logo*
**Text Domain**: *add-logo*
**Domain Path**: `/languages`
**Requires at least**: 3.5
**Tested up to**: 5.4.0
**Stable tag**: 1.7.0
**License**: [GPLv2 or later](http://www.gnu.org/licenses/gpl-2.0.html)

## == Description ==

This plugin allows you to customize your admin by adding your own logo to the header. It also replaces the WordPress logo on the login screen with the same custom logo. Tested in Firefox, Safari, Chrome and IE.

## == Installation ==

1. Unzip the add-logo-to-admin.zip file.
2. Upload the `add-logo-to-admin` folder to the `/wp-content/plugins/` directory.
3. Activate the plugin through the 'Plugins' menu in WordPress.
4. Go to Settings => Add Logo to Admin and set your options and add your logo.

## == Frequently Asked Questions ==

### 1) How do I add my own logo?

Just go to Settings => Add Logo to Admin and click on "Select image" to upload your logo.

### 2) How big does my logo need to be?

Your logo shouldn't exceed 320px by 80px or it will be resized on the login screen.

## == Screenshots ==

1. The Add Logo to Admin page
![wp-admin pages](./screenshot-1.jpg)
2. How your logo will appear on the login screen
![wp-admin login page](./screenshot-2.jpg)

## == Change Log ==

= `1.7.0 (2020-04-15)` =

* Fixed compatibility warnings on Wordpress 5.2.0+ about the [Login HeaderTitle Hook](https://developer.wordpress.org/reference/hooks/login_headertitle/).

= `1.6.2 (2015-09-30)` =

* Changed text domain to add-logo-to-admin
* Updated language files
* Updated version and stable tag

= `1.6.1 (2015-08-18)` =

* Small CSS update
* Updated version and stable tag

= `1.6 (2014-02-12)` =

* Added WP media uploader
* Rebuilt plugin using OOP
* Created language file
* Updated screenshots to reflect new admin page
* Added validation to settings
* Now you can easily select your logo using the WordPress media uploader.
* Plus the login screen logo will redirect back to your site and use your site name for the link's title tag.

= `1.5.1 (2012-10-04)` =

* Fixed login screen image size

= `1.5 (2012-01-12)` =

* Updated for WP 3.3
* Improved coding
* Added security nonce

= `1.4 (2011-02-18)` =

* Updated for WP 3.1
* Removed extraneous CSS and JS files
* Improved coding

= `1.3.3 (2009-03-10)` =

* Fixed issue with IE7 and logo not displaying

= `1.3.2 (2009-03-01)` =

* Fixed issue with invading other admin pages save function

= `1.3.1 (2009-02-26)` =

* Fixed issue with spaces in filename

= `1.3 (2009-02-25)` =

* Created uploader for logos
* Added "Settings" link on plugins page
* Added option to delete logo
* Added logo select option
* Updated CSS

= `1.2 (2009-02-23)` =

* Fixed issue with WP installs in subdirectories
* Removed old code
* Tested on WP version 2.7.1

= `1.1 (2008-12-24)` =

* Added admin page with options
* Fixed window.onload JavaScript issue
* Fixed issue with blogs not located in the root directory
* Removed extraneous code

= `1.0.2 (2008-12-16)` =

* Fixed weirdness with extra folder

= `1.0.1 (2008-12-16)` =

* Fixed the code to direct to the proper plugin folder

= `1.0 (2008-12-15)` =

* Initial Public Release
