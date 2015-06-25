# basic setup
Basic setup with usual tools and configuration.

### What will be installed ?

Default setup :
- zsh
- [oh-my-sh](https://github.com/robbyrussell/oh-my-zsh) with [agnoster](https://gist.github.com/agnoster/3712874) dark theme
- [solarized](http://ethanschoonover.com/solarized)
- [powerline fonts](https://github.com/powerline/fonts)

Optional setup :
- [Atom text editor](https://atom.io/) and pep8 linter
- [DynDNS updater](http://dyn.com/apps/updater-linux/)

Optional setup can be changed in the file `roles/common/defaults/main.yml`. Simply change `install_XXX` to `True` or `False`
