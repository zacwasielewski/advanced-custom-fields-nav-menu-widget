# Advanced Custom Fields: Nav Menu Widget

This WordPress plugin supplements [Advanced Custom Fields: Nav Menu Field](http://wordpress.org/plugins/advanced-custom-fields-nav-menu-field/) by enabling a widget to display any ACF Nav Menu field.

This is useful if you need to display a navigation menu that varies depending on which page it appears.

## Requirements

- [WordPress](http://wordpress.org/) >= 3.9
- [Advanced Custom Fields](http://www.advancedcustomfields.com/) >= 4.3
- [Advanced Custom Fields: Nav Menu Field](http://wordpress.org/plugins/advanced-custom-fields-nav-menu-field/) >= 1.1

## Installation

1. Copy the `advanced-custom-fields-nav-menu-widget` directory into your `wp-content/plugins` directory
2. Navigate to the *Plugins* dashboard page
3. Locate the menu item that reads *Advanced Custom Fields: Nav Menu Widget*
4. Click on *Activate*

## Usage

1. Navigate to the *Custom Fields* dashboard page
2. In a new or existing *Field Group*, create a *Custom Field* with a *Field Type* of *Nav Menu*. ([screenshot](http://cl.ly/image/413I0G2x431B))
	- Note the *Field Name*
	- Set *Return Value* to *Nav Menu HTML*
3. On a *Post* or *Page* edit screen (targeted by the *Location* settings of the *Field Group* in step 1), select a *Navigation Menu* from the new dropdown menu. ([screenshot](http://cl.ly/image/0N2I2Q0u3A0A))
4. In *Appearance > Widgets*, drag an *ACF Nav Menu* widget to the desired sidebar.
5. Set the widget's *ACF Field Name* value to the *Field Name* noted in step 1, above. ([screenshot](http://cl.ly/image/1n2C0R030Y1Z))
6. Enjoy your new navigation menu ([screenshot](http://cl.ly/image/2n042M1i460w))
