---
title: Install Kdenlive on Nvidia Jetson | Pi-Apps
---
<div class="simple-install-content content">

# Install <img src="/img/app-icons/Kdenlive/icon-64.png" height=24> Kdenlive on <img src=/img/other-icons/nvidia-icon.svg height=24> Nvidia Jetson

## <img src="/img/app-icons/Kdenlive/icon-64.png"> Kdenlive
> Newest version of a popular video editor, compatible with PiOS Bookworm
> Most Linux video editors have issues on Wayland, including the default (old) version of Kdenlive available with sudo apt install.
> This version is straight from flatpak, and is kept quite up to date.
> 
> Good video tutorial video here: https://youtu.be/zYD0b8LpiQA
> To run: Menu -> Sound & Video -> Kdenlive
> To run in a terminal: flatpak run --file-forwarding org.kde.kdenlive

Fortunately, Kdenlive is very easy to install on your Nvidia Jetson in just two steps.
1. Install Pi-Apps - the best app installer for Nvidia Jetson.
2. Use Pi-Apps to install Kdenlive.
</div>
<div class="simple-install-content content">

## Compatibility
For the best chance of this working, we recommend using the latest version of [Nvidia Jetpack](https://developer.nvidia.com/embedded/jetpack-archive) for your specific Jetson (Jetson Xavier, or Jetson Orin).
Kdenlive will run on L4T Ubuntu ARM64.
</div>
<div class="simple-install-content content">

## Install Pi-Apps

Pi-Apps is a free tool that makes it incredibly easy to install the most useful programs on your Nvidia Jetson with just a few clicks.

Open a terminal and run this command to install Pi-Apps:
```bash
wget -qO- https://raw.githubusercontent.com/Botspot/pi-apps/master/install | bash
```
Feel free to check out the Pi-Apps source code here: https://github.com/Botspot/pi-apps
</div>
<div class="simple-install-content content">

## Install Kdenlive

Now that you have Pi-Apps installed, it is time to install Kdenlive.
First launch Pi-Apps from your start menu:
<img src="/img/start-menu.png">
Then click on the <b>Multimedia</b> category.
<img src="/img/category-selections/Multimedia.png">
Now scroll down to find <b>Kdenlive</b> in the list.
<img src="/img/app-icons/Kdenlive/app-selection.png">
Just click Install and Pi-Apps will install Kdenlive for you!
</div>
<div class="simple-install-content content">

Pi-Apps is a free and open source tool made by [Botspot and other contributors](/about/#contributors). Find out more at https://pi-apps.io
</div>
