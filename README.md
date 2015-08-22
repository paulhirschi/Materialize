# Materialize
Bringing Material to the some of the most popular color schemes for Sublime:

* Brogrammer
* Cobalt
* Flatland
* Monokai
* Oceanic Next
* Seti
* Solarized Dark
* Solarized Light
* Spacegray
* Stereokai
* Twilight
* Zenburn

Click [here](/Screenshots.md) to see some screenshots.

## Installation

### Via Package Control

The easiest way to install is using [Sublime Package Control](https://sublime.wbond.net), just search for "Materialize".

1. Open Command Palette using menu item `Tools -> Command Palette...` (<kbd>⇧</kbd><kbd>⌘</kbd><kbd>P</kbd> on Mac)
2. Choose `Package Control: Install Package`
3. Find `Materialize` and hit <kbd>Enter</kbd>


### Manually

You can also install the theme manually:

1. Download the [latest release](https://github.com/saadq/Materialize/releases/latest), extract and rename the folder to **"Materialize"**.

2. Move the folder inside your sublime Packages directory. **(Preferences > Browse packages...)**


## Activation
Activate the theme with the following preferences at  **(Preferences > Setting - User)**:

#### Material Spacegray:
```json
{
    "theme": "Material Spacegray.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Spacegray.tmTheme"
}
```

#### Material Oceanic Next:
```json
{
    "theme": "Material Oceanic Next.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Oceanic Next.tmTheme"
}
```

#### Material Solarized Dark:
```json
{
    "theme": "Material Solarized Dark.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Solarized Dark.tmTheme"
}
```

#### Material Solarized Light:
```json
{
    "theme": "Material Solarized Light.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Solarized Light.tmTheme"
}
```

#### Material Monokai:
```json
{
    "theme": "Material Monokai.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Monokai.tmTheme"
}
```

#### Material Cobalt:
```json
{
    "theme": "Material Cobalt.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Cobalt.tmTheme"
}
```

#### Material Seti:
```json
{
    "theme": "Material Seti.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Seti.tmTheme"
}
```

#### Material Zenburn:
```json
{
    "theme": "Material Zenburn.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Zenburn.tmTheme"
}
```

#### Material Brogrammer:
```json
{
    "theme": "Material Brogrammer.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Brogrammer.tmTheme"
}
```

#### Material Flatland:
```json
{
    "theme": "Material Flatland.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Flatland.tmTheme"
}
```

#### Material Twilight:
```json
{
    "theme": "Material Twilight.sublime-theme",
    "color_scheme": "Packages/Materialize/schemes/Material Twilight.tmTheme"
}
```

***Note*** : Remember to restart Sublime Text after activating the theme.

## Theme options

```json
{
    "material_theme_small_tab": true,
    "material_theme_disable_fileicons": true,
    "material_theme_disable_folder_animation": true,
    "material_theme_small_statusbar": true,
    "material_theme_disable_tree_indicator": true,
    "material_theme_bold_tab": true,
    "material_theme_accent_lime": true,
    "material_theme_accent_purple": true,
    "material_theme_accent_red": true,
    "material_theme_accent_orange": true,
    "material_theme_accent_yellow": true
}
```

## Recommended UI and font settings
Here are some recommendations for your user settings to make a better experience with the theme:

```json
{
    "overlay_scroll_bars": "enabled",
    "line_padding_top": 1,
    "line_padding_bottom": 1,
    "always_show_minimap_viewport": true,
    "bold_folder_labels": true
}
```

Additionally, if you are on Retina:

```json
{
    "font_options": [ "gray_antialias" ]
}
```

## Known Issues
Please see the issue [#67](https://github.com/equinusocio/material-theme/issues/67) in the original Material theme if you can't see the bottom panel (find/replace, rename, move, can't see the box inputs in SidebarEnhancement, etc..). The quick fix is to just grab the border of the panel and move it:

![Drag the top edge](https://cloud.githubusercontent.com/assets/474329/8178894/a0dd09c0-1412-11e5-8ecf-f7f9ade439ae.gif)


## Custom Requests
If you have a color scheme that you would like me to create a Material theme for, I'd be happy to oblige. Simply create a request in the issues section of this repo or just send me an e-mail saad@saadquadri.com with a subject of "Material Request".

## Credits
Thanks to the original [creator](https://github.com/equinusocio) of the [Material](https://github.com/equinusocio/material-theme) theme.