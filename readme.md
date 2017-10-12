<h1> Multisite Shared Menu </h1>
<p>Contributors: ben.greeley, Third Boxcar, Giuseppe Bonanno, Bradford Nelson, slushman</p>
<p>Requires at least: 4.6</p>
<p>Tested up to: 4.8.2</p>
<p>Allows users in a WordPress multisite network pull in menus from a main site in order to achieve universal navigation or shared navigation without needing to manually recreate menus. </p>
<p>Plugin is intended for WordPress Multisite environment for plugin to function properly and use the same theme to ensure menu name compatibility.</p>

<h2>Installation </h2>
<ul>
<li>Copy the folder into your /wp-content/plugins directory.</li>
<li>Activate for the sites you wish to use plugin on.<br />NOTE: Should not be activated on master menu site, and all sites sharing menus should use the same theme.</li>
<li>If your master/main site does not yet have a menu, set up a menu to use as a “master”. </li>
<li>To use this menu on other sites, browse to the site you wish to use the menu on. </li>
<li>Navigate to ‘Shared Menu Settings’ under the ‘Appearance’ menu. </li>
<li>Select the source site that contains the menu you wish to use and select the menu location(s) to pull in from your primary site.</li>
<li>Click ‘save changes’ to save your changes.</li>
</ul>

<h2> Changelog </h2>
<h3>1.2.4</h3>
Fix has_nav_menu return value

<h3>1.2.3</h3>
Nothing changed

<h3>1.2.2</h3>
Nothing changed

<h3>1.2.1</h3>
Fix WP admin bar break
Fix deprecatd wp_get_sites()

<h3>1.2</h3>
Multiple menu selection! You can now include one or more menus from your master menu site.

<h3>1.11</h3>
Documentation improvements and screenshots.

<h3>1.1</h3>
Fixed bugs relating to registered menu locations.

<h3>1.0</h3>
Initial Release
