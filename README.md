# xfce4-panel-thubuntux
A Custom Profile for Panel Preferences on Xfce

## Recruitmen
1. Before you use this profile, you must to make sure was installed AppMenu-Plugin.
If you doesnt, you can install with this command:
```bash
sudo apt-get install xfce4-appmenu-plugin
```
After that, you can log out session and log in then.

2. I suggest you to install Plank docker
```bash
sudo apt-get install plank
```

## Download
```bash
git clone https://github.com/addthoriq/xfce4-panel-thubuntux
```
or if you using SSH:
```bash
git@github.com:addthoriq/xfce4-panel-thubuntux.git
```

## Install Xfce Panel Preference Profiles
- Open Xfce Panel Preferences, choose Backup and restore
- Click Impor Button
- Choose your path where you downloaded this repository
- Select `xfce4_panel_profile.tar.bz2`
- And then click Open Button.
- Done

## Install Xfce Panel Preferences Profiles on session Startup
- Open Session and Startup
- Choose Application Autostart tabs
- Click +Add button
- Fill name as Xfce Panel Preference Profiles or whatever you want
- Fill desc whatever or just blank it
- In the Command sections, fill as `bash /path/your/downloaded/xfce4-panel-thubuntux/xfce4-panel.sh`
