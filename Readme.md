=== Advanced Custom Fields: Image Select Field ===
Contributors: Navid Kashani, cyberwani, konstantp
Stable tag: 2.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Image Select Slider addon for Advanced Custom Fields.
Here is a ![preview](https://www.dropbox.com/s/02njo4uf07l3x96/Screenshot%202017-01-17%2016.53.47.png?dl=0).
Based on [Slick Slider](https://github.com/kenwheeler/slick). 


== Description ==

Image Select addon for Advanced Custom Fields.

= Compatibility =

This add-on will work with:

* version 5

== Installation ==

This add-on can be treated as both a WP plugin and a theme include.

= Plugin =
1. Copy the 'acf-image-select' folder into your plugins folder
2. Activate the plugin via the Plugins admin page

= Include =
1.	Copy the 'acf-image-select' folder into your theme folder (can use sub folders). You can place the folder anywhere inside the 'wp-content' directory
2.	Edit your functions.php file and add the code below (Make sure the path is correct to include the acf-image-select.php file)

`
add_action('acf/register_fields', 'register_fields');

function my_register_fields()
{
	include_once('acf-image-select/acf-image-select.php');
}
`

== Changelog ==

= 0.1.0 =
* Added image-extension property.
* Some Tweaks