# hxp-dvorak keyboaord layout

## Works on Ubuntu 18.04 LTS
* Windows version: [hxp-dvorak-windows](https://github.com/HUST-IBPE-HuXiping/hxp-dvorak-windows) 

## Changed the keyboard layout to a more favorable one
* TAB -> Page Down
* CapsLock -> Space
* LCtrl -> LSuper
* LSuper -> LCtrl
* Menu -> RCtrl
* RCtrl -> Page Up
* Space -> Tab

## Changed the keyboard layout to programmer dvorak
* See: [Programmer Dvorak](https://www.kaufmann.no/roland/dvorak/)

## How to Deploy
* install xmodmap via apt
* Add Programmer Dvorak to system (Programmer Dvorak does not exist on Ubuntu 18.04 LTS by default)
[Guide](https://www.kaufmann.no/roland/dvorak/linux.html)
* Place .xmodmap and .xmodstartup to your home folder
* Place hxp-dvorak-startup.desktop under ~/.config/autostart/
* Give .xmodstartup execute permission: Run Command "chmod +x ~/.xmodstartup"
* Logout and it will start automatically every time you login

## Happy Hacking!

