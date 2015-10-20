# Predawn

### A dark interface and syntax theme for [Sublime Text](https://sublime.wbond.net/packages/Predawn) and [Atom](https://atom.io/packages/predawn-ui).

![](http://i.imgur.com/r6B1Exd.png)

[View a larger screenshot](http://i.imgur.com/r6B1Exd.png)

# All Options and Defaults
#### See images below for examples

	// Panel Options
	"predawn_findreplace_small": false,
	"predawn_quick_panel_small": false,

	// Sidebar Options
	"predawn_sidebar_arrows": false,
	"predawn_sidebar_large": false,
	"predawn_sidebar_medium": false,
	"predawn_sidebar_narrow": false,
	"predawn_sidebar_small": false,
	"predawn_sidebar_xlarge": false,
	"predawn_sidebar_xsmall": false,

	// Tabs Options
	"predawn_tabs_active_underline": false,
	"predawn_tabs_large": false,
	"predawn_tabs_medium": false,
	"predawn_tabs_small": false

# [Atom](https://atom.io/packages/predawn-ui) Installation

Search for `predawn` in the Packages section of your Atom settings tab. Install both:

1. `predawn-ui`
2. `predawn-syntax`

Or from the command-line run:

	apm install predawn-ui

and

	apm install predawn-syntax


_Also, you can view on the repo on Atom.io at http://atom.io/packages/predawn-ui_

---

# [Sublime Text](https://sublime.wbond.net/packages/Predawn) Installation

###Recommended
For easy installation, install with [Package Control](https://sublime.wbond.net/docs).

1. <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (OS X) <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (Win/Linux)
2. Type `Package Control: Install Package`
3. Search `predawn`

**Other Methods**

You can clone the repo to your `Packages` folder. Just make sure the repo folder is named `Predawn`.

Of course, you can always [install manually](https://github.com/jamiewilson/predawn/archive/master.zip), too.

# Activating the Theme

_Note: File icons are only supported for **[DEV BUILDS 3062](http://www.sublimetext.com/3dev)+**._

Open your user settings file `preferences.sublime-settings` as shown below:

![](http://i.imgur.com/dDxZTwu.png)

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


#### !! IMPORTANT !!
Make sure to restart Sublime after installing and activating Predawn

# Options

### Tabs Height
![](http://i.imgur.com/V5bch3X.png)

### Active Tab Underline
![](http://i.imgur.com/gHtilo3.jpg)

### Find & Replace Small Size
![](http://i.imgur.com/nMMu5AD.png)

After enabling the smaller size, you'll need to drag the height of the Find/Replace panel up and down to adjust it to the new dimemension.

### Sidebar Height
![](http://i.imgur.com/3Y3psRy.png)

### Sidebar Width
![](http://i.imgur.com/1p0WjBL.jpg)

# Markdown 
![](http://i.imgur.com/hDMgN39.png)

## To enable Predawn for Markdown

First, **open a markdown(.md) file**, then navigate to `Sublime Text` > `Preferences` > `Settings - More` > `Syntax Specific - User`  in the menu bar.

![](http://i.imgur.com/SFyHdVX.png)

## Add to your current settings or replace with the following:

	{
		"color_scheme": "Packages/Predawn/predawn-markdown.tmTheme",
		"draw_centered": true, // Centers the column in the window
		"draw_indent_guides": false,
		"font_size": 15,
		"trim_trailing_white_space_on_save": false,
		"word_wrap": true,
		"wrap_width": 80  // Sets the # of characters per line
	}

# Interface and File Icons
The source files for the interface icons are located in the [jamiewilson/predawn-icons](https://github.com/jamiewilson/predawn-icons).

![](http://i.imgur.com/O9QgDad.jpg)

# Dock Icons
There are also some [dock icons](/dock-icons) for you to choose from:

![](http://i.imgur.com/dF2d4Fv.png)
