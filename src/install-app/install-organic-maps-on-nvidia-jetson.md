---
title: Install Organic Maps on Nvidia Jetson | Pi-Apps
---
<div class="simple-install-content content">

# Install <img src="/img/app-icons/Organic Maps/icon-64.png" height=24> Organic Maps on <img src=/img/other-icons/nvidia-icon.svg height=24> Nvidia Jetson

## <img src="/img/app-icons/Organic Maps/icon-64.png"> Organic Maps
> Free offline maps for everyone
> The Linux version of Organic Maps has not reached feature parity with the Android and iPhone versions yet, and has not been optimized for mobile devices yet. Organic Maps is the ultimate companion app for travelers, tourists, hikers, and cyclists:
> 
> - Detailed offline maps with places that don't exist on other maps, thanks to OpenStreetMap
> - Cycling routes, hiking trails, and walking paths
> - Contour lines, elevation profiles, peaks, and slopes
> - Turn-by-turn walking, cycling, and car navigation with voice guidance
> - Fast offline search on the map
> - Bookmarks and tracks export and import in KML, KMZ, GPX formats
> - Dark Mode to protect your eyes
> - Countries and regions don't take a lot of space
> - Free and open-source
> 
> To run: Menu -> Education -> Organic Maps
> To run in a terminal: flatpak run --branch=stable --arch=aarch64 --command=OMaps app.organicmaps.desktop

Fortunately, Organic Maps is very easy to install on your Nvidia Jetson in just two steps.
1. Install Pi-Apps - the best app installer for Nvidia Jetson.
2. Use Pi-Apps to install Organic Maps.
</div>
<div class="simple-install-content content">

## Compatibility
For the best chance of this working, we recommend using the latest version of [Nvidia Jetpack](https://developer.nvidia.com/embedded/jetpack-archive) for your specific Jetson (Jetson Xavier, or Jetson Orin).
Organic Maps will run on L4T Ubuntu ARM64.
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

## Install Organic Maps

Now that you have Pi-Apps installed, it is time to install Organic Maps.
First launch Pi-Apps from your start menu:
<img src="/img/start-menu.png">
Then click on the <b>Tools</b> category.
<img src="/img/category-selections/Tools.png">
Now scroll down to find <b>Organic Maps</b> in the list.
<img src="/img/app-icons/Organic Maps/app-selection.png">
Just click Install and Pi-Apps will install Organic Maps for you!
</div>
<div class="simple-install-content content">

Pi-Apps is a free and open source tool made by [Botspot and other contributors](/about/#contributors). Find out more at https://pi-apps.io
</div>
