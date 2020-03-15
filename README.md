# **RStudio Zinogre theme** <img src="./img/zinogre_icon.png" width="50">

Zinogre color theme for RStudio.

## Overview

This repo contains RStudio theme file that make your RStudio editor Zinogre color theme.

From Rstudio version 1.2, you can create your own custom themes without having to overwrite an existing one. Check out the [RStudio IDE Custom Theme Support](https://blog.rstudio.com/2018/10/29/rstudio-ide-custom-theme-support/)  for an instruction.

## Feature & Image

### Syntax highlighting (+Image) in RStudio

![sample_code](./img/sample_code.png)

Sample code is using [Fira Code Retina](https://github.com/tonsky/FiraCode)

## Requirement

![RStudiobadge](https://img.shields.io/static/v1?label=RStudio&message=version%20>=1.2&logoColor=9cf&color=9cf&logo=RStudio&style=plastic)

RStudio 1.2.x or higher

## Installation

### 1. Installation via RStudio

- If you have RStudio >=v1.2, you can directly import the .rstheme file into RStudio settings.

   See [RStudio IDE Custom Theme Support](https://blog.rstudio.com/2018/10/29/rstudio-ide-custom-theme-support/) for a pictorial step-by-step, or creating custom themes for RStudio if you want to learn more.

- To download and apply the theme, run the following code in RStudio.

```R
install.packages("rstudioapi")

rstudioapi::addTheme("https://raw.githubusercontent.com/takemal-studio/RStudio_Zinogre_theme/master/zinogre.rstheme", apply = TRUE)

# To install, but not apply the theme, just switch the apply argument to FALSE.
```

### 2. Manual Installation & Changing Theme

- If you switch the apply argument to FALSE or the steps above don't work, you can manually download the `zinogre.rstheme` file and place it in `.R/rstudio/themes` in your R home directory.

- To change your current theme, select the theme by going to `Tools > Global Options > Appearance > Editor theme`

## Recommended RStudio settings for zinogre theme

- Enable: `Tools -> Global Options -> Code -> Display -> Highlight selected line`
- Enable: `Tools -> Global Options -> Code -> Display -> Show margin (Marzin column [80])`
- Enable: `Tools -> Global Options -> Code -> Display -> Show indent Guides`
- Enable: `Tools -> Global Options -> Code -> Display -> Show syntax highlighting in console input`
- Enable: `Tools -> Global Options -> Code -> Display -> Highlight R function calls`

## Uninstallation

To uninstall (removing from the list of available themes) zinogre theme, execute the following code:

```R
rstudioapi::removeTheme("zinogre")
```

or delete `zinogre.rstheme` file from `.R/rstudio/themes` in your R home directory.

## Supported Platforms

Zinogre theme has only been tested on **Windows**. Feedback from other platforms welcome.

## Author

takemal-studio

## License

- MIT
  - see LICENSE

- Copyright
  - This repo uses material from the [Zinogre Photo Gallery](https://monsterhunter.fandom.com/wiki/Zinogre_Photo_Gallery) on the Monster Hunter Wiki at  [Fandom](https://www.fandom.com/) and is licensed under the Creative Commons Attribution-Share Alike License.
