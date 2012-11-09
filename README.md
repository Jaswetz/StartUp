StartUp
=======

A place to get started

## File Structure

/sass
	_modernizr.scss
	_dependencies.scss

	_settings.scss
	_styles.scss
	_typography.scss
	_mixins.scss
	_ui.scss
	_helper.scss
	_base.scss

	_blocks.scss
	_forms.scss
	_tables.scss
	_sub-blocks.scss

	_site.scss
	_style-guide.scss
	_override.scss

Dependencies
: this is used to import assets such as fonts, icons or other css from plugins or extensions

Settings
: this contains all default and base variables

Styles
: everything in here should be reusible and should be a @mixin or a @extend
: this file defines the "style" of the site including gradients, textures, theme specific colors

Typography
: used to help keep typographical rythem
: all basic text elements are defined here

Mixins and UI
: everything in here should be reusible and should be a @mixin

Helper
: contains helper functions, snippets or mixins
: common helper classes are things like .clearfix or .hidden

Base
: here you set up the base of the site overiding browser defaults 
: reset or normalizr would reside here

Blocks, Forms, Tables
: site default layout blocks are defined here

Sub-Blocks
: any override of blocks goes here

Site
: this contains the scaffolding or overall layout

Style-Guide
: this is used for debugging or getting an overview of site styles

Override
: used for debugging and ideally should be cleaned up at end of project

