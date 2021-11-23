# Nord rice for Xfce4 or i3 

Materials for ricing your Xfce4/i3 desktop with Nord theme

## 1. Xfce

USAGE:
1. ```backgrounds```, ```icons```, ```themes``` and ```xfce4-panel-profiles``` folders: Put in to the respective folders in your ```~/.local/share```. 

- Installation of **xfce4-panel-profile** package is recommended.
- For icons, installation of and **papirus-nord** is recommended.

2. ```conky```: Put the contents into ```~/.conky```.

Of course you have to install **conky** first. Installation of **conky-manager2** is recommended.

3. ```terminal```: contains the config file including the color preset for you xfce4-terminal. Put the contents (the ```terminalrc```) into your ```~/.config/xfce4/terminal```.

PREVIEW

Preview with simplemanjaro conky (although it's Debian)
![img](/nord-simplemanjaro-preview.png)


## 2. i3wm
1. You can do all the steps in the Xfce4 section. Of course, **xfce4=panel-profiles** and **conky** is not required.

2. Install the following packages:

- **feh**: setting background images
- **lxappearance**: setting the fonts, and the gtk themes
- **brightnessctl**: controlling the brightness keys
- **i3blocks**: decorating the i3bar
- **rofi**: dmenu alternatives

3. Put the contents of the ```i3``` folder into ```~/.config/i3 ```

4. Put the contents of ```rofi``` into ```~/.config/rofi```. This folder is just a copy of [rofi themes by adi1090x](https://github.com/adi1090x/rofi)

PREVIEW

![img](/i3-preview.png)