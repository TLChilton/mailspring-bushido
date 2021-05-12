**Note:** The adjustments I've made are in the context of my own personal Linux Thinkpad running MX Linux. Your mileage may vary

# Bushido

Bushido is a theme for the Mailspring mail client, forked from the [Idido theme](https://github.com/NeoMahler/mailspring-idido), which is based on the [Ido theme](https://github.com/edipox/n1-ido), which is in turn based on [Taiga](https://github.com/noahbuscher/N1-Taiga). *Ido* means *offspring* in Esperanto, so *Idido* is *Offspring of the offspring*, and my spin on it *Bushido* abandons the Esperanto theme entirely.

# Theming
The sidebar color can be changed by updating the color value in [this file](https://github.com/NeoMahler/mailspring-idido/blob/master/styles/variables.less#L32). [Here is a video showing how to do that.](https://youtu.be/4L2v6tuAonE)

## Firebrick
![](./firebrick.png)

## Freedom
![](./freedom.png)

## Skyfall
My personal favorite, and the default theme
![](./skyfall.png)

## Inbox
![](./inbox.png)
But if you are looking for an Inbox inspired theme you should definitely try [agapanthus](https://github.com/taniadaniela/n1-agapanthus)

## Polymail
![](./polymail.png)


## Examples


![](./examples.png)

## Installing

1. [Download](https://getmailspring.com/) Mailspring - (desktop email client) if you have not yet.
2. [Download the latest release of Bushido](https://github.com/TLChilton/mailspring-bushido/releases)
4. Unzip the folder wherever it is, likely called `mailspring-bushido.zip`
4. In the settings dropdown in Mailspring go to  `Edit` -> `Install new theme...` and choose the unzipped folder
6. The theme should now be available in `Edit` -> `Change theme...`

## Uninstalling
This is the procedure I've discovered for uninstalling themes.

1. Remove the theme's directory from your Mailspring/packages folder. For me on MX Linux it is in ~/.config/Mailspring/packages
2. In Mailspring go to `Developer` -> `Reload` in the dropdown settings
3. Restart Mailspring and the theme will no longer be in the themes settings

## Differences between Ido and Idido
This is a list of the differences between both themes:

* Window controls have been replaced by traffic lights (inspired by macOS).
* Buttons don't have borders (as opposed to the circular borders of the original Ido theme).
* Circular hover effect on buttons.

## Differences between Idido and Bushido
This is a list of the differences between both themes:

* Centered the options button within the border in the top right

More could be added as I find things to change in my normal use

## Current Issues
Currently the toolbar icons do not work if using the two-pane vertical mode.
