# Flatland-MKS

## About

Flatland-MKS is a modified version of the [Flatland-Alt](https://github.com/jamiewilson/flatland-alt) theme and accompanying color scheme for Sublime Text 2 & 3. We **DO NOT** take any credit for the real work that was done by [The Pixel Lab](https://github.com/thinkpixellab).

## Tweaks

Here are the changes in Flatland-MKS:

1. Frost colors for both dark chrome theme and syntax highlighting theme
2. Shorter tab height
3. Support for Slim

![Screen Shot!](https://raw.github.com/makersquare/flatland-mks/master/screenshot.png)

## Installation (OS X)
Flatland-mks is a Sublime package. Currently, you must install it manually.

```bash
# SUBLIME TEXT 2
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
git clone https://github.com/makersquare/flatland-mks.git

# SUBLIME TEXT 3
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
git clone https://github.com/makersquare/flatland-mks.git
```

## Activating the Theme
In Sublime's menu, go to "Preferences > Settings - User". Add or modify `color_scheme` and `theme` so that it matches the following:

```javascript
{
  "color_scheme": "Packages/flatland-mks/flatland-mks.tmTheme",
  "theme": "flatland-mks.sublime-theme"
}

```

## Optional Settings
The following options can be set in your user preferences:

```javascript
{
  // Ability to change row height of sidebar tree
  // Options: xsmall, small, medium, large, xlarge
  "flatland_sidebar_tree_xsmall" : true
}
```
