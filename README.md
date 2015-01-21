# Predawn

### A dark interface and syntax theme for [Sublime Text](https://sublime.wbond.net/packages/Predawn) and [Atom](https://atom.io/packages/predawn-ui).

## About

Predawn is a minimal Sublime Text theme and a syntax color scheme. It was originally just a slightly tweaked version (called Flatland-Alt) of the [Flatland](https://github.com/thinkpixellab/flatland) theme, which itself is a flat reworking of [Soda](https://github.com/buymeasoda/soda-theme/). I decided to keep going with customization and rework the entire theme. But I owe a lot to Flatland and Soda. Thanks guys!

![image](screenshots/screenshot.png)

[View a larger screenshot](https://raw.github.com/jamiewilson/predawn/master/screenshots/screenshot.png)

## Installation for [Atom](https://atom.io/packages/predawn-ui)

Search for `predawn` in the Packages section of your Atom settings tab. Install both:

1. `predawn-ui`
2. `predawn-syntax`

Or from the command-line run:

	apm install predawn-ui

and

	apm install predawn-syntax


_Also, you can view on the repo on Atom.io at http://atom.io/packages/predawn-ui_

---

## Installation for [Sublime Text](https://sublime.wbond.net/packages/Predawn)

###Recommended
For easy installation, install with [Package Control](https://sublime.wbond.net/docs).

1. <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (OS X) <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (Win/Linux)
2. Type `Package Control: Install Package`
3. Search `predawn`

**Other Methods**

You can clone the repo to your `Packages` folder. Just make sure the repo folder is named `Predawn`.

Of course, you can always [install manually](https://github.com/jamiewilson/predawn/archive/master.zip), too.

## Activating the Theme

_Note: File icons are only supported for **[DEV BUILDS 3062](http://www.sublimetext.com/3dev)+**._

Open your user settings file `preferences.sublime-settings` as shown below:

![image](screenshots/activate.png)

To activate the theme, add or replace your current theme settings with the code below.

	{
	  "theme": "predawn.sublime-theme",
	  "color_scheme": "Packages/Predawn/predawn.tmTheme"
	}

FOR ALL **[DEV BUILDS 3062](http://www.sublimetext.com/3dev)+** use,

	{
	    "theme": "predawn-DEV.sublime-theme",
	    "color_scheme": "Packages/Predawn/predawn.tmTheme"
	}


*** IMPORTANT - MAKE SURE TO RESTART SUBLIME AFTER INSTALLING AND ACTIVATING PREDAWN ***

## Tab Height Size Options

You can change the height of the file tabs by adding either to your preferences file:


	"tabs_small": true

OR

	"tabs_medium": true


![image](screenshots/tabs.png)

## Find & Replace Small Size Option

You can change the height of the Find/Replace inputs by adding the following to preferences file:


	"findreplace_small": true

![image](screenshots/find-replace.png)

After enabling the smaller size, you'll need to drag the height of the Find/Replace panel up and down to adjust it to the new dimemension.

## Sidebar Size Options

You can change the vertical spacing of the sidebar by changing `default` to `xsmall`, `small`, `medium`, `large`, `xlarge`:


	"sidebar_default": true

for example:

	"sidebar_large": true


![image](screenshots/sidebar.png)

## Markdown Settings
![markdown](screenshots/markdown.png)

#### To enable Predawn for Markdown

First, **open a markdown(.md) file**, then navigate to `Sublime Text` > `Preferences` > `Settings - More` > `Syntax Specific - User`  in the menu bar.

![syntax-specific](screenshots/syntax-specific.png)

#### Add to your current settings or replace with the following:

	{
		"color_scheme": "Packages/Predawn/predawn-markdown.tmTheme",
		"draw_centered": true, // Centers the column in the window
		"draw_indent_guides": false,
		"font_size": 15,
		"trim_trailing_white_space_on_save": false,
		"word_wrap": true,
		"wrap_width": 80  // Sets the # of characters per line
	}

## Interface and File Icons
The source files for the interface icons are located in the [jamiewilson/predawn-icons](https://github.com/jamiewilson/predawn-icons).

## Dock Icons
There are also some [dock icons](/dock-icons) for you to choose from:

![image](screenshots/icons.png)


## A few of my favorite options
These are just a few of my other favorite options for Sublime Text:

	// Typography

	"font_face": "Source Code Pro",
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

## And some recommendations

Also, I highly recommend these Sublime Text packages:

* [Sublime-CSS3](https://github.com/i-akhmadullin/Sublime-CSS3)  
* [GitGutter](https://github.com/jisaacks/GitGutter)  
* [Sidebar Enhancements](https://github.com/titoBouzout/SideBarEnhancements)  
