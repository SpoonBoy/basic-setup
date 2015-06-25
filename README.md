# basic setup
Basic setup with usual tools and configuration.

### What will be installed ?

Default setup :
- zsh
- vim
- curl
- [oh-my-sh](https://github.com/robbyrussell/oh-my-zsh) with [agnoster](https://gist.github.com/agnoster/3712874) dark theme
- [solarized](http://ethanschoonover.com/solarized)
- [powerline fonts](https://github.com/powerline/fonts)
- keepnote

Optional setup :
- [Atom text editor](https://atom.io/) and pep8 linter
- [DynDNS updater](http://dyn.com/apps/updater-linux/)

Optional setup can be changed in the file `roles/common/defaults/main.yml`. Simply change `install_XXX` to `True` or `False`


### Note
You will have to manually set the font of your terminal to `meslo` in order to have a proper display of the `agnoster` theme
