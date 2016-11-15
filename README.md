# dihedral

a dark cinnamon theme.

### install

download the `/dihedral` folder and put it into your `~/.themes` folder.

### recommended development workflow

use gulp to watch for changes, build, and set the theme in cinnamon:

0. use node>4 (I recommend tracking your node version with nvm)

1. go to your project folder

2. run `npm i`

3. run `gulp`

Edit the `.scss` files in `/src`, or the assets in `/dihedral/cinnamon`.

* `_colors.scss` This file defines the color variables used by the theme

* `_drawing.scss` Drawing helper mixins/functions to allow for easier definition of widget drawing

let me know if these instructions are confusing and I'll write out something more detailed, I'm pretty much expecting to be shouting out into the void now :D

#### creds

this is a fork of [mint-y-dark-theme](https://github.com/linuxmint/mint-y-theme). build script forked from [zagortenay333](https://github.com/zagortenay333)!

theme [background image](https://flic.kr/p/7EZZJQ) released under [creative commons](https://creativecommons.org/licenses/by-nc-nd/2.0).
