# Introduction #

This module is compatible with both Joomla! versions 1.5, 1.6, 1.7 as well as 2.5+ and it uses the Bookmarking services of [AddThis.com](http://www.addthis.com). For a complete list of the AddThis features take a look [at this page](http://www.addthis.com/features). The module ValAddThis allows the easy configuration as well the display of the AddThis Button or AddThis Toolbox. It produces valid markup for XHTML as well as for CSS. ValAddThis is free software, which has been released under the [GNU/GPL v2.0](http://www.gnu.org/licenses/gpl-2.0.html) license.

This version of the module supports the latest [AddThis Menu API](http://www.addthis.com/help/menu-api) 2.0, in combination with the old API 1.0 (which is still used to display an RSS-Feed button). With ValAddThis you're also able to display the new [AddThis Toolbox](http://www.addthis.com/help/toolbox), as well as several other special buttons (such as: LinkedIn and Stumbleupon counters), which aren't supported officially by AddThis yet.


# Details #

**1. Installation**

  * If you have already an older version (prior to 2.5.0) of the module ValAddThis installed, please uninstall it first and then continue with the installation steps below.
  * Go to your Joomla administration backend and on the menu Extensions and click on "Install/Uninstall" (Extensions Manager in J1.6+).
  * Upload the file contained here by clicking on "Browse..." and selecting the zipped file.
  * Click on "Upload file & Install".

Now the module "ValAddThis" is installed in Joomla and you can use it.


**2. Configuration**

  * For detailed documentation on ValAddThis module, please [visit this page](http://www.valandis.de/extensions/valaddthis.html).

In order to display the module in a Joomla article follow [these instructions](http://code.google.com/p/joomla-mod-valaddthis/wiki/HOWTOdisplayAModuleInAnArticle).


**3. Support**

**Support for the module ValAddThis is only free for my customers or donators of the module. If you need a one-time email support please make a donation by using the PayPal "Donate" button on the right hand side of the documentation pages on my website. Donators will be listed at the end of the documentation.**

If you have any suggestions or found any bugs in the module, feel free to:
  * send me an email to [valandis@valandis.de](mailto:valandis@valandis.de)
  * visit my website [Val Web Design](http://www.valandis.de)
  * visit the module's page at [Joomla Extensions](http://extensions.joomla.org/extensions/communities-&-groupware/social-bookmarking/7998/details)
  * visit the [Website](http://www.addthis.com) or [Forum](http://www.addthis.com/forum/) of AddThis.com
  * post any issues here


**4. Open Issues**

The following are issues of the AddThis script and not of the module itself:
  * When the AddThis Button parameter "Display on" is set to "Mouse click" and used in conjunction with the AddThis Toolbox, some of the Toolbox icons (like email) don't behave properly. This isn't an issue of the module itself, rather an issue of the AddThis script and thus it cannot be fixed from me, unless AddThis fixes it.

  * if you use the module together with the plugin ValAddThis (in case of a Toolbox), you should be aware there could be some issues with conflicting CSS styles; in order to bypass any conflict, use the available option with which you can deactivate the loading of any of the module's CSS files.


**Please vote for the module at the web-page of [Joomla Extensions](http://extensions.joomla.org/extensions/communities-&-groupware/social-bookmarking/7998/details). Thank you!**



# ChangeLog #

**Version 2.5.4 (29 April 2012)**
  * Fixed: bug in the AddThis script that was caused by a typo and affected the Google Analytics Integration.

**Version 2.5.3 (26 April 2012)**
  * Added: latest config options for the AddThis script ui\_open\_windows and data\_track\_textcopy.
  * Added: 14 new 3rd party special buttons. Some of them use the AddThis script and others are exclusively called by ValAddThis.
  * Removed: all Google Buzz 3rd party buttons, since it doesn't exist anymore.
  * Removed: deprecated AddThis config option ui\_use\_embeddable\_services\_beta.
  * Changed: the google analytics integration method conforms to the latest one used by AddThis.
  * Changed: the order and services/buttons used by the quick toolboxes.
  * Changed: the 3rd party buttons cannot be used in the Toolbox anymore when combined with the styles CSS Horizontal, CSS Vertical #1 and CSS Vertical #2.
  * Changed: the CSS file user.css is now an exact copy of default.css.
  * Changed: some of the CSS styles.

**Version 2.5.2 (11 Oct 2011)**
  * Added: one more ValAddThis-only counter button (tweetmeme\_vertical).
  * Fixed: issue with the URL being shared by the ValAddThis-only counter buttons; the URL pointed always to the homepage and not the current page.
  * Changed: some of the CSS styles.

**Version 2.5.1 (21 Sep 2011)**
  * Fixed: issue when the Facebook like/recommend buttons were used inside a Toolbox; the content could not be shared.

**Version 2.5.0 (09 Sep 2011)**
  * Added: the module is now fully compatible with Joomla! versions 1.6 and 1.7. You can use the hybrid installer package for both Joomla! 1.5 as well as 1.6 and 1.7.
  * Added: option to disable the loading of the module's CSS files, in case you use it together with the plugin ValAddThis.
  * Added: option to disable the loading of the AddThis CSS file.
  * Added: option to use the AddThis counter as a standard button.
  * Added: selection of 12 quick toolboxes (with predefined services).
  * Added: ability to insert the AddThis pill counter and the AddThis bubble counter as Toolbox services.
  * Added: option for a share image, which will be displayed next to the Toolbox. 2 sample images are already included with ValAddThis.
  * Added: 15 button counters; these counters are supported by ValAddThis only and won't be included in your personal AddThis Analytics.
  * Added: option to add an attribute "rel=nofollow" to the services links of the Toolbox.
  * Added: a couple of CSS files for the new styles of the Toolbox (icons with 32px width).
  * Added: option for a user-defined text in place of "Send to" for the tooltips of the service icons.

**Version 2.1.0 (21 Jun 2010)**
  * Added: one more CSS file for the "default" Toolbox style.
  * Added: option for a user-defined title text to be displayed next to the AddThis Toolbox.
  * Added: options to enter a user-defined HTML code before and/or after the AddThis Button/Toolbox.
  * Fixed: minor bug in the Toolbox code, which displayed an empty icon, even if no services were defined by the user.
  * Fixed: bug in the code of the CSS Vertical #2 Toolbox style, which caused an XHTML validation error.
  * Fixed: a couple of typos in the German translation file (thanks to Kurt from Austria).

**Version 2.0.4 (31 Mar 2010)**
  * Fixed: issue with 2 undefined variables.

**Version 2.0.3 (26 Mar 2010)**
  * Fixed: minor bug (typo) in the code.
  * Changed: the way the AddThis script is called; the AddThis script has a serious issue when it's called from within the 

&lt;head&gt;

 of a web-page and it caused an "operation aborted" error in versions of IE6 and below! The only workaround was to call the script in the 

&lt;body&gt;

 section of the page after the button/toolbox code.

**Version 2.0.2 (25 Feb 2010)**
  * Fixed: minor bug that didn't allow the correct display of the spacers (separators) in the module's configuration backend.
  * Added: support for 2 new global AddThis variables (Use Embeddable-Only Services, Use Google Analytics).
  * Changed: some CSS styles.

**Version 2.0.1 (7 Dec 2009)**
  * Fixed: minor bug that didn't allow the proper alignment of the module.
  * Changed: a couple of CSS styles.

**Version 2.0.0 (16 Nov 2009)**
  * Added: support for the new AddThis API 2.0; Standard, Email-only buttons and toolboxes use the new API 2.0, except the RSS-Feed buttons, that still make use of the old API 1.0.
  * Added: option to use the new AddThis Toolbox.
  * Added: CSS files to use with the AddThis Toolbox and support for a user-defined CSS file.
  * Added: support for multiple Toolboxes and/or Buttons on a single page; in addition, the Toolboxes may use different CSS files.
  * Added: option to specify the default User-Interface language, on top of the already translatable AddThis texts.
  * Added: various other configuration options; all available up-to-date from AddThis.
  * Changed: most parameters are now passed to the AddThis script using the new API 2.0.
  * Changed: calls to the AddThis script for both secure and non-secure servers.
  * Removed: option for logo graphic; not applicable any more.

**Version 1.2.0 (19 May 2009)**
  * Added: option to install the module on a secure Web-Server.
  * Added: option for user-defined texts in place of the AddThis ones (no need to wait for any translations in your own language anymore).
  * Changed: the file helper.php changed so that the module supports the PHP version 4 (some versions of PHP 4.x stated error messages).
  * Changed: some of the parameters will no longer be passed to the AddThis script, if they are not needed (e.g. the Hover delay will not be passed if the RSS Feed button is used).

**Version 1.1.0 (23 Apr 2009)**
  * Updated: new bookmarking services from AddThis.
  * Added: the graphic files of the standard buttons are installed together with the module.
  * Added: choice betweet 2 new button types (RSS Feed and Email).
  * Added: choice of a user-defined image for the button.
  * Added: choice between image and/or text for the button.
  * Added: possibility to enter a user-defined CSS style for the button's text.
  * Added: possibility to enter a user-defined "alt" text for the button.

**Version 1.0.2 (15 Apr 2009)**
  * Added: choice of optional brand name.
  * Removed: backlink to my website.
  * Fixed: error in the german language file.

**Version 1.0.1 (11 Apr 2009)**
  * Added: dummy index.html files.
  * Added: helper file.
  * Added: template file.
  * Changed: module's core file, for calling the helper as well as the template file.

**Version 1.0.0 (24 Mar 2009)**
  * No change - First version of the module.