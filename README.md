# basic setup
Basic setup with usual tools and configuration.

### Usage
This is an [Ansible](http://docs.ansible.com/intro.html) playbook.
You will have to change a few settings in order to install this basic setup.



1. change `inventory.txt` to the corresponding ip. You can use `127.0.0.1` if you want to install it on your current system, or set a virtual machine IP in order to test the change made by the setup.
    ```yaml
    $ vim inventory.txt

    [deploy_target]
    127.0.0.1
    ```

2. change the `user` in the file `roles/common/defaults/main.yml`. That user needs to be sudoer in order to install packages.
    ```yaml
    $ vim roles/common/defaults/main.yml

    ---
      user : "ubuntu"
    ```


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
