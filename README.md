# qterminal-snap-packaging

A lightweight Qt-based terminal emulator  
QTerminal is a lightweight Qt terminal emulator based on QTermWidget.  

This is the unofficial snap packaging.  

## Snap packaging

Build status:
[![Snap Status](https://build.snapcraft.io/badge/ito32bit/qterminal-snap-packaging.svg)](https://build.snapcraft.io/user/ito32bit/qterminal-snap-packaging)

## Install on your Linux distribution

[![qterminal-snap](https://snapcraft.io//qterminal-snap/badge.svg)](https://snapcraft.io/qterminal-snap)
[![qterminal-snap](https://snapcraft.io//qterminal-snap/trending.svg?name=0)](https://snapcraft.io/qterminal-snap)

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/qterminal-snap)

Terminal:  

    sudo snap install qterminal-snap 

or

    sudo snap install qterminal-snap --edge 
    
#### Connect the snap to optional security confinement interfaces
Terminal:  

    sudo snap connect qterminal-snap:removable-media

## Launch

Main menu: `Qterminal - snap`  
or  
Terminal: `qterminal-snap`  

## Uninstall

Terminal:  
```
    sudo snap remove --purge qterminal-snap
    rm -R ~/snap/qterminal-snap
    sudo snap remove --purge qtermwidget-snap
```

## Upstream

<https://github.com/lxqt/qterminal>
