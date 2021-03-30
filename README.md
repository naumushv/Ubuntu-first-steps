Hello there! It's my first markdown, where I would like to share my configuration for Ubuntu

Contents:  
[Essentials](#Essentials)  
[Software](#Software)  
[Gnome Extensions](#Gnome-Extensions)  
[Browser Extensions](#Browser-extesions)  
[Last steps](#Last-steps)  



# Essentials
**All essntials combined:**
sudo apt update && sudo apt upgrade -y && sudo apt-get -y install git tig cmake cmake-curses-gui build-essential automake autoconf autogen libncurses5-dev libc++-dev pkg-config libtool net-tools openssh-server xserver-xorg-input-all python2.7-dev python3-dev python-setuptools python3-setuptools python3-pip gtk-3.0 python3-gi && sudo apt install ubuntu-restricted-extras && sudo apt-get install synaptic && sudo add-apt-repository universe && sudo apt-get install gnome-tweak-tool && sudo apt install ubuntu-restricted-extras


**Update & Upgrade:**  
sudo apt update && sudo apt-get dist-upgrade

**base packages:**  
sudo apt-get -y install git tig cmake cmake-curses-gui build-essential automake autoconf autogen libncurses5-dev libc++-dev pkg-config libtool net-tools openssh-server xserver-xorg-input-all

**Python**  
sudo apt-get -y install python2.7-dev python3-dev python-setuptools python3-setuptools python3-pip

**Complete multimedia support**  
sudo apt install ubuntu-restricted-extras

**Synaptic**  
sudo apt-get install synaptic

**Gnome tweak tool**  
sudo add-apt-repository universe
sudo apt-get install gnome-tweak-tool

**Media codecs**  
sudo apt install ubuntu-restricted-extras

## Software
**VLC**
sudo snap install vlc

**Steam**
sudo apt-get install steam-installer

**Brasero**
sudo apt install brasero

**Features for gedit**
sudo apt install gedit-developer-plugins

**Vim**
sudo apt install vim

**Discord**
sudo apt install discord

**Chromium**
sudo snap install chromium

**Firefox**
sudo snap install firefox

**Telegram**
sudo snap install telegram-desktop

**Spotify**
sudo snap install spotify

**Docker**
sudo snap install docker

**Ocular**
sudo apt install okular

**Ebook viewer**
git clone https://github.com/michaldaniel/Ebook-Viewer.git && cd Ebook-Viewer/ && sudo make install

**Zoom**
sudo snap install zoom-client

**Neofetch**
sudo apt-get install neofetch

**Brightness controller**
sudo add-apt-repository ppa:apandada1/brightness-controller && sudo apt-get update && sudo apt-get install brightness-controller

# Gnome Extensions
**Open weather**  
https://extensions.gnome.org/extension/750/openweather/  

**Net speed**  
https://extensions.gnome.org/extension/104/netspeed/

**Dash to Dock**  
https://extensions.gnome.org/extension/307/dash-to-dock/

**Clipboard Indicator**  
https://extensions.gnome.org/extension/779/clipboard-indicator/

**Apt Update Indicator**  
https://extensions.gnome.org/extension/1139/apt-update-indicator/

**Drop Down Terminal**  
https://extensions.gnome.org/extension/442/drop-down-terminal/

**Auto Move Windows**  
https://extensions.gnome.org/extension/16/auto-move-windows/

**Gnome-sushi**  
sudo apt install gnome-sushi

# Browser extesions
OctoLinker
https://github.com/OctoLinker/OctoLinker

Octotree
https://github.com/ovity/octotree

uBlock
https://github.com/gorhill/uBlock

TouchVPN
https://chrome.google.com/webstore/detail/touch-vpn-secure-and-unli/bihmplhobchoageeokmgbdihknkjbknd
https://addons.mozilla.org/ru/firefox/addon/touch-vpn/

Zenmate VPN
https://chrome.google.com/webstore/detail/zenmate-free-vpn%E2%80%93best-vpn/fdcgdnkidjaadafnichfpabhfomcebme
https://addons.mozilla.org/en-US/firefox/addon/zenmate-free-vpn-best/

Browsec VPN
https://chrome.google.com/webstore/detail/browsec-vpn-free-vpn-for/omghfjlpggmjjaagoclmmobgdodcjboh
https://addons.mozilla.org/ru/firefox/addon/browsec/

Tab2QR
https://chrome.google.com/webstore/detail/tab2qr/mkfcgekjddmlceifimndhbliepfgnogo?hl=en
https://addons.mozilla.org/en-US/firefox/addon/tab2qr/

Ghostery
https://chrome.google.com/webstore/detail/ghostery-%E2%80%93-privacy-ad-blo/mlomiejdfkolichcflejclcbmpeaniij?hl=en
https://addons.mozilla.org/en-US/firefox/addon/ghostery/

Bypass paywalls
https://github.com/iamadamdev/bypass-paywalls-chrome

Dark reader
https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh
https://addons.mozilla.org/en-US/firefox/addon/darkreader/

Cookie AutoDelete
https://chrome.google.com/webstore/detail/cookie-autodelete/fhcgjolkccmbidfldomjliifgaodjagh
https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/

Https everywhere
https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp
https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/

Vimium
https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb
https://addons.mozilla.org/en-US/firefox/addon/vimium-c/

Raindrop
https://chrome.google.com/webstore/detail/raindropio/ldgfbffkinooeloadekpmfoklnobpien?hl=en
https://addons.mozilla.org/en-US/firefox/addon/raindropio/

Simple translate
https://chrome.google.com/webstore/detail/simple-translate/ibplnjkanclpjokhdolnendpplpjiace?hl=en
https://addons.mozilla.org/en-US/firefox/addon/simple-translate/

More awesome extensions
https://github.com/learn-anything/chrome-extensions

## Last steps

**Remove amazon**  
sudo apt purge ubuntu-web-launchers

**Make cleaup**  
sudo apt-get autoclean && sudo apt-get clean && sudo apt-get autoremove

**Stop private data collection**  
System Settings > Privacy > Problem Reporting > Manual

**Minimize on click**  
gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'

**Xkill shortcut**  
Settings > Keyboard Shortcuts > add a new shortcut >
