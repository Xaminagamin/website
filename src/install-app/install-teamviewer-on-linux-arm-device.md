---
title: Install TeamViewer on Linux ARM Device | Pi-Apps
---
<div class="simple-install-content content">

# Install <img src="/img/app-icons/TeamViewer/icon-64.png" height=24> TeamViewer on Linux ARM Device

## <img src="/img/app-icons/TeamViewer/icon-64.png"> TeamViewer
> Remote desktop server and client software.
> 
> To run: Menu -> Internet -> TeamViewer
> To run in terminal: teamviewer
> 
> NOTE: If your system uses Wayland, it cannot accept incoming connections. If you cannot connect to this machine with Teamviewer, either disable Wayland or switch to RustDesk which actually works and is more secure.
> On Raspberry Pi OS, Wayland can be disabled by running "sudo raspi-config" in a terminal and navigating to Advanced Options, where Wayland/X11 can be toggled.
> Again, RustDesk is recommended. It's open source and works better.

Fortunately, TeamViewer is very easy to install on your Linux ARM Device in just two steps.
1. Install Pi-Apps - the best app installer for Linux ARM Device.
2. Use Pi-Apps to install TeamViewer.
</div>
<div class="simple-install-content content">

## Compatibility
For the best chance of this working, we recommend using the latest LTS of Ubuntu or Debian from your hardware manufacturer.
TeamViewer will run on either an Ubuntu/Debian ARM32 OS or ARM64 OS.
</div>
<div class="simple-install-content content">

## Install Pi-Apps

Pi-Apps is a free tool that makes it incredibly easy to install the most useful programs on your Linux ARM Device with just a few clicks.

Open a terminal and run this command to install Pi-Apps:
```bash
wget -qO- https://raw.githubusercontent.com/Botspot/pi-apps/master/install | bash
```
Feel free to check out the Pi-Apps source code here: https://github.com/Botspot/pi-apps
</div>
<div class="simple-install-content content">

## Install TeamViewer

Now that you have Pi-Apps installed, it is time to install TeamViewer.
First launch Pi-Apps from your start menu:
<img src="/img/start-menu.png">
Then click on the <b>Internet</b> category.
<img src="/img/category-selections/Internet.png">
Now scroll down to find <b>TeamViewer</b> in the list.
<img src="/img/app-icons/TeamViewer/app-selection.png">
Just click Install and Pi-Apps will install TeamViewer for you!
</div>
<div class="simple-install-content content">

Pi-Apps is a free and open source tool made by [Botspot and other contributors](/about/#contributors). Find out more at https://pi-apps.io
</div>
