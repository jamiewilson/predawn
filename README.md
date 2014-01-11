# Flatland-MKS

## About

Flatland-MKS is a *slightly* tweaked version of the [Flatland-Alt](https://github.com/jamiewilson/flatland-alt) theme and accompanying color scheme for Sublime Text 2 & 3. We **DO NOT** take any credit for the real work that was done by [The Pixel Lab](https://github.com/thinkpixellab) nor [Jamie Wilson](https://github.com/jamiewilson).

## Tweaks

There are only a few things different in Flatland-MKS:

1. There is only a dark version
2. There are only square tabs, and they have been made bigger and more minimal
3. The accent color has been changed from blue to an orange
4. The selection color has been changed to black
5. A new icon has been designed to match

![Screen Shot!](https://raw.github.com/jamiewilson/flatland-mks/master/screenshot.png)

![Screen Shot!](https://raw.github.com/jamiewilson/flatland-mks/master/sublime-flatland-mks-icon.png)

## Installation (OS X)
Flatland-mks is a Sublime package. Currently, you must install it manually.

```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
git clone https://github.com/makersquare/flatland-mks.git
```

## Activating the Theme
Activate the theme by modifying your user preferences to include the following:

```javascript
{
  "color_scheme": "Packages/flatland-mks/flatland-mks.tmTheme",
  "theme": "flatland-mks.sublime-theme"
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
