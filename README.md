<h1 align="center">Google drive gnome extension</h1>
<h3 align="center">Keep your files in sync</h3>
<br>


### some image with google-drive-for-linux goes here

<h3>Prerequisites</h3>
* Ruby >= 2.0.0, see [rvm](https://rvm.io/)
* Bash >= 4.4.19 (tested, but will probably work on other versions as well)
* GNOME >= 3.28.2 (tested, but will probably work on other version as well)

<h2>Installation</h2>
There's an install script, but manually installing the 2 dependencies of this plugin is recommended for optimal usage.

<h4>Install script</h4>
```bash
wget -o /tmp/gdrivegnome.sh https://raw.githubusercontent.com/Thomas-X/google-drive-gnome/master/top.50s+.sh && chmod +x /tmp/gdrivegnome.sh && ./tmp/gdrivegnome.sh 
```
<h4>Manually</h4>
* Make sure you've got all the prerequisites installed
* Clone both [this](https://github.com/Thomas-X/drivesync.git) and [this](https://github.com/Thomas-X/argos.git) repo
* Make sure the drivesync repo is in `~/.config/.gdfl/` make the directory if needed
* Follow install instructions of both repos (see README.md)
* Move the .sh script to your ~/.config/argos dir and restart gnome via `Alt+F2` and typing `r` in the command prompt
* You're all set!
