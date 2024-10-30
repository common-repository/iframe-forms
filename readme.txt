=== iframe forms===
Contributors: econcept
Tags: iframe forms
Requires at least: 3.0
Tested up to: 5.0
Stable tag: 1.0
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html

[iframe src="http://example.com" width="100%" height="500"] shortcode

== Description ==

Allow you to use iframe html tags in wordpress.

== Other Notes ==

= iframe params: =
* **src** - source of the iframe: `[iframe src="http://example.com"]`; by default src="http://example.com";
* **width** - width in pixels or in percents: `[iframe width="100%"]` or `[iframe width="600"]`; by default width="100%";
* **height** - height in pixels: `[iframe height="500"]`; by default height="500";
* **scrolling** - with or without the scrollbar: `[iframe scrolling="no"]`; by default scrolling="yes";
* **frameborder** - with or without the frame border: `[iframe frameborder="0"]`; by default frameborder="0";
* **marginheight** - height of the margin: `[iframe marginheight="0"]`; removed by default;
* **marginwidth** - width of the margin: `[iframe marginwidth="0"]`; removed by default;
* **id** - allows to add the id of the iframe: `[iframe id="custom_id"]`; removed by default;
* **class** - allows to add the class of the iframe: `[iframe class="custom_class"]`; by default class="iframe-class";
* **style** - allows to add the css styles of the iframe: `[iframe style="margin-left:-30px;"]`; removed by default;
* **height_like** - allows to set the height of iframe same as target element: `[iframe height_like="div.sidebar"]`, `[iframe height_like="div#content"]`, `[iframe height_like="body"]`, `[iframe height_like="html"]`; removed by default;

== Installation ==

1. install and activate the plugin on the Plugins page
2. add shortcode `[iframe src="http://example.com" width="100%" height="500"]` to display content in an iframe
