# Theme-preap

## About

Preap is a minimal Sublime Text theme and a syntax color scheme. It was originally just a slightly tweaked version of the [Predawn](https://github.com/lyqcode/preap) theme.

![image](http://i.imgur.com/zLcqwXA.jpg)

[View a larger screenshot](http://i.imgur.com/zLcqwXA.jpg)


## Requirements

**Sublime Text 3 (recent build)**
File icons are only supported for **[Dev Builds 3062](http://www.sublimetext.com/3dev)+**._

## Installation

For easy installation, install with [Package Control](https://packagecontrol.io).

1. Press <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> on OS X or <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> on Windows/Linux
2. Type `Install Package`
3. Search `preap`

**Other Methods**

You can clone the repo to your `Packages` folder. Just make sure the repo folder is named `Preap`.

Of course, you can always [download latest release](https://github.com/lyqcode/preap/releases/latest) and install manually, too. After download, extract zip and rename the folder to "Preap" then copy it to the `Packages`folder ( `Sublime Text` > `Preferences` > `Browse packages...` )

## Activating the Theme

Open your user settings file `preferences.sublime-settings` as shown below:

![image](http://i.imgur.com/ZTr1qXo.png)

To activate the theme, add or replace your current theme settings with the code below.

	{
		"theme": "preap.sublime-theme",
		"color_scheme": "Packages/Preap/Schemes/preap.tmTheme",
	}

However if you use packages like [SublimeLinter](https://github.com/SublimeLinter/) color theme might fail to load with . To load it manually, delete the `color_scheme` line and selelct from the `Preferences tab -> Color scheme -> Preap -> Schemes -> Preap`. Don't worry about the `color_scheme` line in your `Preferences.sublime_settings`, it'll be updated automatically.

*** IMPORTANT - MAKE SURE TO RESTART SUBLIME AFTER INSTALLING AND ACTIVATING PREAP ***


<!-- ## Markdown Settings
![markdown](http://i.imgur.com/alcPmqB.jpg)

#### To enable Preap for Markdown

First, **open a markdown(.md) file**, then navigate to `Sublime Text` > `Preferences` > `Settings - More` > `Syntax Specific - User`  in the menu bar.


#### Add to your current settings or replace with the following:

	{
		"color_scheme": "Packages/Preap/Schemes/preap-markdown.tmTheme",
		"draw_centered": true, // Centers the column in the window
		"draw_indent_guides": false,
		"font_size": 15,
		"trim_trailing_white_space_on_save": false,
		"word_wrap": true,
		"wrap_width": 80  // Sets the # of characters per line
	}

However if you use packages like [SublimeLinter](https://github.com/SublimeLinter/) color theme might fail to load with . To load it manually, delete the `color_scheme` line and selelct from the `Preferences tab -> Color scheme -> Preap -> Schemes -> preap-markdown`. Don't worry about the `color_scheme` line in your `Preferences.sublime_settings`, it'll be updated automatically. -->


## Tab Size and Appearance Options

![image](http://i.imgur.com/vYDRxth.jpg)

You can edit the height, the appearance of the file tabs by adding this setting to your preferences file:


	"tabs_small": true, 			// Set tabs size to small
	"tabs_medium": true, 			// Set tabs size to medium
	"tabs_border": true, 			// Show the border of the tabs
	"static_modified_tab": true 	// Disable unsaved flashing indicator


## Find & Replace Small Size Option

![image](http://i.imgur.com/zyKx37T.jpg)

You can change the height of the Find/Replace inputs by adding the following to preferences file:

	"findreplace_small": true


After enabling the smaller size, you'll need to drag the height of the Find/Replace panel up and down to adjust it to the new dimemension.

## Sidebar Size Options

![image](http://i.imgur.com/3OIKP5d.jpg)

You can change the vertical spacing of the sidebar by changing `default` to `large`, `xlarge`:


	"sidebar_default": true,
	"sidebar_large": true,
	"sidebar_xlarge": true

If you want you can change the sidebar font size by adding one of this settings
	
	"sidebar_font_big": true,
	"sidebar_font_small": true


## A few of my favorite options
These are just a few of my other favorite options for Sublime Text:

	// Typography

	"font_face": "Consolas",
	"font_size": 14,
	"font_options": ["no_round"],
	"highlight_line": true,
	"caret_extra_width": 1,
	"caret_style": "phase",
	"word_wrap": false,

	// Whitespace, Matching, Copy & Auto-Complete

	"copy_with_empty_selection": false,
	"drag_text": false,
	"match_brackets_content": false,
	"match_selection": false,
	"match_tags": false,
	"translate_tabs_to_spaces": true,
	"trim_trailing_white_space_on_save": true,

	// Interface & Behavior

	"close_windows_when_empty": false,
	"draw_minimap_border": true,
	"enable_tab_scrolling": false,
	"overlay_scroll_bars": "enabled",
	"open_files_in_new_window": false,
	"preview_on_click": false,
	"scroll_past_end": true,
	"scroll_speed": 5.0,
	"show_full_path": false,
