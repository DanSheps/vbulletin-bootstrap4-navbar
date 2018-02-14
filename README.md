# vBulletin Bootstrap 4 Navbar
A vBulletin Bootstrap 4 Navbar Mod, which transforms the standard vBulletin 5 Navbar into a BS4 Navbar.

Table of Contents
=================

* [Table of Contents](#table-of-contents)
* [vBulletin Changes](#vbulletin-changes)
  * [Files](#files)
  * [Templates](#templates)
  * [StyleVars](#stylevars)
  * [Hooks](#hooks)
  * [Phrases](#prases)
* [Installation](#installation)
  * [Template Change: header](#template-change-header)

vBulletin Changes
=================

Files
-----

The following files are included

	./upload/core/packages/navigation/xml/product_navigation.xml
	./upload/vendor/bootstrap/LICENSE
	./upload/vendor/bootstrap/README.md
	./upload/vendor/bootstrap/css/dist/bootstrap.css
	./upload/vendor/bootstrap/css/dist/bootstrap-grid.css
	./upload/vendor/bootstrap/css/dist/bootstrap-reboot.css
	./upload/vendor/bootstrap/css/prefixed/bootstrap.css
	./upload/vendor/bootstrap/css/prefixed/bootstrap-grid.css
	./upload/vendor/bootstrap/css/prefixed/bootstrap-reboot.css
	./upload/vendor/bootstrap/js/bootstrap.js
	./upload/vendor/bootstrap/js/bootstrap.bundle.js
	./upload/vendor/font-awesome/css/font-awesome.css
	./upload/vendor/font-awesome/css/font-awesome.min.css
	./upload/vendor/font-awesome/fonts/FontAwesome.otf
	./upload/vendor/font-awesome/fonts/fontawesome-webfont.eot
	./upload/vendor/font-awesome/fonts/fontawesome-webfont.svg
	./upload/vendor/font-awesome/fonts/fontawesome-webfont.ttf
	./upload/vendor/font-awesome/fonts/fontawesome-webfont.woff
	./upload/vendor/font-awesome/fonts/fontawesome-webfont.woff2
	./upload/vendor/font-awesome/HELP-US-OUT.txt
	./upload/vendor/popper/CONTRIBUTING.md
	./upload/vendor/popper/LICENSE.md
	./upload/vendor/popper/MENTIONS.md
	./upload/vendor/popper/README.md
	./upload/vendor/popper/js/popper.min.js
	

Templates
-----

The following templates have been added:
	
	css_bootstrap_navbar_custom.css
	css_bootstrap_navbar.css
	css_bootstrap.css
	navigation_menu
	navigation_menu_item
	navigation_menu_item_dropdown_item
	navigation_admin_sitebuilder_menu
	navigation_menu_pmchat
	navigation_menu_user
	navigation_footer
	navigation_header

The following templates require changes:

	header
	

StyleVars
-----

The following stylevars have been added:

	bootstrap_navbar_base_class
	bootstrap_navbar_font
	bootstrap_navbar_font_transform
	bootstrap_navbar_font_color
	bootstrap_navbar_link_color
	bootstrap_navbar_link_hover_color
	bootstrap_navbar_link_active_color
	bootstrap_navbar_mainnav_background
	bootstrap_navbar_mainnav_background_gradient
	bootstrap_navbar_mainnav_background_active
	bootstrap_navbar_mainnav_background_active_gradient
	bootstrap_navbar_mainnav_background_hover
	bootstrap_navbar_mainnav_background_hover_gradient
	bootstrap_navbar_mainnav_padding
	bootstrap_navbar_subnav_background
	bootstrap_navbar_subnav_background_gradient
	bootstrap_navbar_subnav_background_active
	bootstrap_navbar_subnav_background_active_gradient
	bootstrap_navbar_subnav_background_hover
	bootstrap_navbar_subnav_background_hover_gradient
	bootstrap_navbar_subnav_font
	bootstrap_navbar_subnav_font_color
	bootstrap_navbar_subnav_font_transform
	bootstrap_navbar_subnav_link_color
	bootstrap_navbar_subnav_link_hover_color
	bootstrap_navbar_subnav_link_active_color

Hooks
-----

	The following hooks have been added:

	BS4 Navigation Header CSS
		Location: header_head
		Template: navigation_header

	BS4 Navigation Hover Dropdown Activate
		Location: footer_before_body_end
		Template: navigation_footer

Phrases
-----

The following phrases have been added:

	group_navigation
	stylevar_bootstrap_navbar_base_class_name
	stylevar_bootstrap_navbar_base_class_description
	stylevar_bootstrap_navbar_font_name
	stylevar_bootstrap_navbar_font_description
	stylevar_bootstrap_navbar_font_transform_name
	stylevar_bootstrap_navbar_font_transform_description
	stylevar_bootstrap_navbar_font_color_name
	stylevar_bootstrap_navbar_font_color_description
	stylevar_bootstrap_navbar_link_color_name
	stylevar_bootstrap_navbar_link_color_description
	stylevar_bootstrap_navbar_link_hover_color_name
	stylevar_bootstrap_navbar_link_hover_color_description
	stylevar_bootstrap_navbar_link_active_color_name
	stylevar_bootstrap_navbar_link_active_color_description
	stylevar_bootstrap_navbar_mainnav_background_name
	stylevar_bootstrap_navbar_mainnav_background_description
	stylevar_bootstrap_navbar_mainnav_background_gradient_name
	stylevar_bootstrap_navbar_mainnav_background_gradient_description
	stylevar_bootstrap_navbar_mainnav_background_active_name
	stylevar_bootstrap_navbar_mainnav_background_active_description
	stylevar_bootstrap_navbar_mainnav_background_active_gradient_name
	stylevar_bootstrap_navbar_mainnav_background_active_gradient_description
	stylevar_bootstrap_navbar_mainnav_background_hover_name
	stylevar_bootstrap_navbar_mainnav_background_hover_description
	stylevar_bootstrap_navbar_mainnav_background_hover_gradient_name
	stylevar_bootstrap_navbar_mainnav_background_hover_gradient_description
	stylevar_bootstrap_navbar_mainnav_padding_name
	stylevar_bootstrap_navbar_mainnav_padding_description
	stylevar_bootstrap_navbar_subnav_background_name
	stylevar_bootstrap_navbar_subnav_background_description
	stylevar_bootstrap_navbar_subnav_background_gradient_name
	stylevar_bootstrap_navbar_subnav_background_gradient_description
	stylevar_bootstrap_navbar_subnav_background_active_name
	stylevar_bootstrap_navbar_subnav_background_active_description
	stylevar_bootstrap_navbar_subnav_background_active_gradient_name
	stylevar_bootstrap_navbar_subnav_background_active_gradient_description
	stylevar_bootstrap_navbar_subnav_background_hover_name
	stylevar_bootstrap_navbar_subnav_background_hover_description
	stylevar_bootstrap_navbar_subnav_background_hover_gradient_name
	stylevar_bootstrap_navbar_subnav_background_hover_gradient_description
	stylevar_bootstrap_navbar_subnav_font_name
	stylevar_bootstrap_navbar_subnav_font_description
	stylevar_bootstrap_navbar_subnav_font_color_name
	stylevar_bootstrap_navbar_subnav_font_color_description
	stylevar_bootstrap_navbar_subnav_font_transform_name
	stylevar_bootstrap_navbar_subnav_font_transform_description
	stylevar_bootstrap_navbar_subnav_link_color_name
	stylevar_bootstrap_navbar_subnav_link_color_description
	stylevar_bootstrap_navbar_subnav_link_hover_color_name
	stylevar_bootstrap_navbar_subnav_link_hover_color_description
	stylevar_bootstrap_navbar_subnav_link_active_color_name
	stylevar_bootstrap_navbar_subnav_link_active_color_description

Installation
=================

Installation should be relatively easy.  Import the xml file in ./core/packages/navigation/xml/product_navigation.xml and perform the below Template Changes.

Template Change: header
-----

As part of the installation, you will be required to remove a significant portion of the header template.  You can do this to the master style if desired, however it may make upgrading more difficult.  It is recommended to edit the sub-styles instead (Themes, Default and any sub-styles).

For the change, you need to open the header template and make the following changes.

1. At line 154, after:
    ```html
    <vb:else />
		{vb:set sitebuilderEnabled, 0}
    </vb:if>
    ```
    Remove until line 174, the code:
    ```html
    <div class="b-top-menu__background js-top-menu-user">
		<div class="b-top-menu__container">
			<ul class="b-top-menu b-top-menu--user js-top-menu-user--list js-shrink-event-parent">
				{vb:template top_menu_user,
					useSitebuilder={vb:raw useSitebuilder},
					sb_state_cookie={vb:raw sb_state_cookie}
				}
			</ul>
		</div>
	</div>
	```
	And Add:
	{vb:template navigation_menu}
2. At line 229, remove from:
	```html
	<vb:comment><!-- ===== TOP BACKGROUND HOOK: HEADER-MAINNAV-SUBNAV ===== --></vb:comment>
	```
	to:
	```html
	<vb:comment><!-- ===== END: TOP BACKGROUND HOOK: HEADER-MAINNAV-SUBNAV ===== --></vb:comment>
	```
3. Go into the AdminCP, select your theme, edit the following stylevars at a minimum:
	bootstrap_navbar_base_class
	bootstrap_navbar_subnav_background
	
	Base class can be any BS4 base classes (navbar-dark bg-dark, navbar-light bg-primary, etc)