---
title: Programs to Install
parent: Linux
last_modified_date: 2020-06-30
---

1. TOC
{:toc}

---

## Everyday

| Program                                               | Purpose                                                                                                                 |
| :---------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------- |
| [Chrome](https://www.google.com/chrome/)              | Browser                                                                                                                 |
| `sudo apt install tilix`                              | Better terminal ([configuration](/linux/system-config#using-tilix-as-default-terminal-application-with-gnome-at-least)) |
| `sudo apt install inkscape`                           | Vector graphics editor (or the [PPA](https://inkscape.org/release/inkscape-1.0rc1/gnulinux/ubuntu/ppa/dl/))             |
| `sudo apt install gimp`                               | Raster graphics editor                                                                                                  |
| [Typora](https://typora.io/)                          | Markdown editor                                                                                                         |
| [MuseScore](https://musescore.org/en)                 | Music notation                                                                                                          |
| [Spotify](https://www.spotify.com/us/download/other/) | Music ([add themes with Spicetify](/linux/program-config#spotify-themes-with-spicetify-cli))                            |
| [Z shell](/linux/zsh)                                 | Better interactive shell ([configuration](/linux/zsh))                                                                  |
| [Lutris](https://lutris.net/)*                        | Playing not-native-Linux games                                                                                          |
| [Steam](https://store.steampowered.com)               | Games!                                                                                                                  |
| [Discord](https://discord.com/new/download)           | Chat servers for everything                                                                                             |

\* Usually, I'll use Proton (from within Steam) if I'm playing a Steam game, and Lutris for non-Steam games (like GTA V through Epic games store).

## Visuals

| Program                                                                                              | Purpose                             |
| :--------------------------------------------------------------------------------------------------- | :---------------------------------- |
| [Adapta GTK Theme](https://github.com/adapta-project/adapta-gtk-theme)                               | Clean dark theme                    |
| [Adapta-gtk-theme-colorpack](https://www.gnome-look.org/p/1190851/)                                  | Change Adapta accent color          |
| [Plata GTK Theme](https://www.linuxuprising.com/2018/11/plata-is-new-gtk-theme-based-on-latest.html) | Clean darker theme                  |
| [Papirus icons](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)                        | Material-inspired icons             |
| [Papirus folders](https://github.com/PapirusDevelopmentTeam/papirus-folders)                         | Match folder icons to Adapta colors |


## Gnome Extensions

These are what I'm currently using:

| Program                                                                                                                                  | Purpose                                                     |
| :--------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------- |
| [Alternatetab](https://extensions.gnome.org/extension/15/alternatetab/)                                                                  | Alt+Tab switches by window instead of program               |
| [Bring out submenu of power off/logout button](https://extensions.gnome.org/extension/2917/bring-out-submenu-of-power-offlogout-button/) | Fix a system menu annoyance                                 |
| [Clipboard indicator](https://extensions.gnome.org/extension/779/clipboard-indicator/)                                                   | Show clipboard history                                      |
| [Gsconnect](https://extensions.gnome.org/extension/1319/gsconnect/)                                                                      | Connect my phone to the computer                            |
| [Material Shell](https://github.com/PapyElGringo/material-shell)                                                                         | Tiling WM style for Gnome (clear `~/.cache` if misbehaving) |
| [Lock Keys](https://extensions.gnome.org/extension/36/lock-keys/)                                                                        | Show Caps lock indicator                                    |
| [Panel osd](https://extensions.gnome.org/extension/708/panel-osd/)                                                                       | Move the notification popup                                 |
| [Sound Input & Output Device Chooser](https://extensions.gnome.org/extension/906/sound-output-device-chooser/)                           | Show audio input/output in system menu                      |
| [Tweaks in Systems Menu](https://extensions.gnome.org/extension/1653/tweaks-in-system-menu/)                                             | Show Tweaks with regular Settings                           |
| [User themes](https://extensions.gnome.org/extension/19/user-themes/)                                                                    | Allow user themes described above                           |
| [Windowoverlay icons](https://extensions.gnome.org/extension/302/windowoverlay-icons/)                                                   | Show program icons in the Alt+Tab view                      |

These are worthwhile extensions I've used in the past:

| Program                                                                                 | Purpose                                         |
| :-------------------------------------------------------------------------------------- | :---------------------------------------------- |
| [Dash to dock](https://extensions.gnome.org/extension/307/dash-to-dock/)                | More configuration of dash bar                  |
| [Dash to panel](https://extensions.gnome.org/extension/1160/dash-to-panel/)             | Replace the dash with something more functional |
| [Desktop icons](https://extensions.gnome.org/extension/1465/desktop-icons/)             | Use this to remove the trash/home icons         |
| [OpenWeather](https://extensions.gnome.org/extension/750/openweather/)                  | Show weather in top bar                         |
| [ShellTile](https://extensions.gnome.org/extension/657/shelltile/)                      | More places to snap windows                     |
| [Suspend button](https://extensions.gnome.org/extension/826/suspend-button/)            | Add a suspend button to the main dropdown       |
| [Workspace Indicator](https://extensions.gnome.org/extension/21/workspace-indicator/)   | Label/number workspaces in the top bar          |
| [Workspace switcher](https://github.com/Tomha/gnome-shell-extension-workspace-switcher) | Name workspace and show them in the top bar     |

## Work/Research

| Program                                                                                   | Purpose                                                                        |
| :---------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------- |
| [Kilogui](https://github.com/acornejo/kilogui/releases)                                   | Programmer interface for Kilobots                                              |
| [Mendeley](https://www.mendeley.com/guides/download-mendeley-desktop/ubuntu/instructions) | Managing papers                                                                |
| [Eagle](https://www.autodesk.com/products/eagle/overview)                                 | PCB design ([configuration](/linux/program-config#eagle-create-desktop-entry)) |
| `sudo apt install minicom`                                                                | Serial monitor terminal (for Kilobots and LARVAbot)                            |
| [PrusaSlicer](https://github.com/prusa3d/PrusaSlicer/releases)                            | 3D printing slicer                                                             |
| `sudo apt install openscad`                                                               | Script-based CAD                                                               |
| [Slack](https://slack.com/downloads/linux)                                                | Channels for everything!                                                       |

## Programming

| Program                                                                                               | Purpose                                                                                   |
| :---------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------- |
| [Visual Studio Code](https://code.visualstudio.com/Download)                                          | General-purpose code editor + git integration                                             |
| [Arduino IDE](https://www.arduino.cc/en/guide/linux)                                                  | Programming Arduinos/microcontrollers ([configuration](/research/larvabot#arduino-setup)) |
| [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)                                        | Manage Heroku projects                                                                    |
| [Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-engine---community-1) | Containers for development                                                                |
| [Coral Edge TPU](https://coral.ai/docs/accelerator/get-started/#1-install-the-edge-tpu-runtime)       | API for the USB TPU                                                                       |

Install relevant development packages all at once:

| Item            | Install                                                                                                                                            |
| :-------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| Python 3        | `sudo apt install python3-dev python3-pip python3-venv`                                                                                            |
| Python packages | `pip3 install numpy scipy matplotlib pandas seaborn tables h5py jupyter pylint dash plotly`                                                        |
| Jekyll          | `sudo apt install ruby-full build-essential zlib1g-dev && sudo gem install jekyll bundler`                                                         |
| Node/NPM        | `sudo apt install nodejs build-essential` or [PPA or NVM](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04) |
| Other           | `sudo apt install libhdf5-dev htop`                                                                                                                |

## Miscellaneous/Utilities

| Program                                                             | Purpose                                                         |
| :------------------------------------------------------------------ | :-------------------------------------------------------------- |
| [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher) | Automatic desktop integration when you first launch an AppImage |
| `sudo apt install synaptic`                                         | GUI for package management                                      |
| `sudo apt install gparted`                                          | GUI for disk partitioning                                       |
| [Insync](https://www.insynchq.com/)                                 | Google Drive client for Linux                                   |
| `sudo apt install duplicity`                                        | Déjà Dup automatic backups                                      |
| `sudo apt install gnome-tweaks`                                     | Make Gnome usable                                               |
| `sudo apt install dconf-editor`                                     | Edit Dconf files                                                |

## OctoPrint Plugins

For OctoPrint installation/setup and more information, see my [OctoPrint page](/3d-printing/octoprint)

| Program                                                                                | Purpose                                   |
| :------------------------------------------------------------------------------------- | :---------------------------------------- |
| [3D Geeks](https://plugins.octoprint.org/plugins/geeks3d/)                             | Phone notifications for prints            |
| [CustomBackground](https://github.com/jneilliii/OctoPrint-CustomBackground)            | Change background on temperature graph    |
| [FileManager](https://github.com/Salandora/OctoPrint-FileManager)                      | Separate tab for direct file management   |
| [Firmware Updater](https://github.com/OctoPrint/OctoPrint-FirmwareUpdater)             | Update printer firmware                   |
| [Fullscreen Camera](https://github.com/BillyBlaze/OctoPrint-FullScreen)                | Make camera full screen with double click |
| [Navbar Temperature](https://github.com/imrahil/OctoPrint-NavbarTemp)                  | Show temperatures in top bar              |
| [Octolapse](https://github.com/FormerLurker/Octolapse)                                 | Pretty timelapses                         |
| [Print Time Genius](https://github.com/amsbr/OctoPrint-Stats)                          | Better print time estimation              |
| [Prusa Leveling Guide](https://plugins.octoprint.org/plugins/PrusaLevelingGuide/)      | Interactive bed leveling for Nylock mod   |
| [Prusa Mesh Leveling](https://github.com/PrusaOwners/OctoPrint-PrusaMeshMap)           | View bed level variance                   |
| [PrusaSlicer Thumbnails](https://plugins.octoprint.org/plugins/prusaslicerthumbnails/) | Show thumbnail previews of objects        |
| [TabOrder](https://github.com/jneilliii/OctoPrint-TabOrder)                            | Set tab order and icons                   |
| [Themeify](https://github.com/birkbjo/OctoPrint-Themeify)                              | Dark theme!                               |
| [TouchUI](https://github.com/BillyBlaze/OctoPrint-TouchUI)                             | Make it finger-friendly                   |