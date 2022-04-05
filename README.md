# setup

## in windows GUI
- install 'pl' fonts https://github.com/microsoft/cascadia-code/releases
- download zip to windows desktop
- extract ttf folder
- select the font files and install
- in ms terminal settings.json, ensure fontface is 'Cascadia Mono PL'

## in WSL Linux
- install starship binary
- add to .bashrc
- clone this code
- softlink the starship.toml in this code to the location it wants:
```bash
mkdir ~/.config
mkdir ~/.starship_conf
ln -s ~/.starship_conf/starship.toml ~/.config/starship.toml
```
