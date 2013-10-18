# Flatland-Alt

## About

Flatland-Alt is a *slightly* tweaked version of the [Flatland](https://github.com/thinkpixellab/flatland) theme and accompanying color scheme for Sublime Text 2 & 3. I **DO NOT** take any credit for the real work that was done by [The Pixel Lab](https://github.com/thinkpixellab).

## Tweaks

There are only a few things different in Flatland-Alt:

1. There is only a dark version
2. There are only square tabs, and they have been made bigger and more minimal
3. The accent color has been changed from blue to an orange
4. The selection color has been changed to black
5. A new icon has been designed to match

![Screen Shot!](https://raw.github.com/jamiewilson/flatland-alt/master/screenshot.png)  

![Screen Shot!](https://raw.github.com/jamiewilson/flatland-alt/master/sublime-flatland-alt-icon.png)

## Installation
Flatland-Alt is a Sublime package. Currently, you must install it manually.

1. [Download the theme files](https://github.com/jamiewilson/flatland-alt/archive/master.zip)
2. Unzip the files and rename the newly created folder to `flatland-alt`
3. Copy the folder into the Sublime Text Packages folder. On a Mac that's located at Library > Application Support > Sublime Text > Packages. You can find that directory by selecting Preferences > Browse Packages...


## Activating the Theme
Activate the theme by modifying your user preferences to include the following:

```javascript
{
  "color_scheme": "Packages/flatland-alt/flatland-alt.tmTheme",
  "theme": "flatland-alt.sublime-theme"
}

```

If you need help locating your user preferences file, you can find it selecting "Preferences > Settings - User".

## Optional Settings
The following options can be set in your user preferences:

```javascript
{
  // Ability to change row height of sidebar tree
  // Options: xsmall, small, medium, large, xlarge
  "flatland_sidebar_tree_xsmall" : true
}
```
