# A bash script that can install, update, and manage all versions of Discord. If you have 'dialog' installed, a GUI will automatically be shown. 

## discord-install can be executed remotely by running `bash -c "$(wget --quiet https://github.com/simoniz0r/discord-install/raw/master/discord-install.sh -O -)"` in your terminal.

### discord-install has three options.  It can install all verions of Discord (Canary, PTB, and Stable) and also uninstall versions of Discord that were installed using discord-install.  discord-install can also be used to update Discord just by going through the install process again.  The third option will add an alias for remotely executing discord-install through your terminal so you don't have to keep it downloaded and it will always be up to date.

### discord-install will create a config file in ~/.config/discord-install for each version of Discord that you install using discord-install.  This allows discord-install to keep track of your Discord installs, which allows it to uninstall them for you or remove them before updating to a new version.
