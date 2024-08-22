<div align="center">
<img width="60px" src="https://pts-project.org/android-chrome-512x512.png">
<h1>PiRogue PPA for workshops</h1>
<p>
This PPA contains all the Debian packages necessary to facilitate workshops.
</p>
<p>
<b>⚠️ do not use in production ⚠️</b>
</p>
</div>

## Configure the PiRogue repository for Debian 12

To install PiRogue packages repository on your fresh Debian 12 installation, execute the following command in a terminal:

```
sudo curl -o /etc/apt/sources.list.d/pirogue.list https://pts-project.org/debian-12-workshop/pirogue.list
sudo curl -o /etc/apt/trusted.gpg.d/pirogue.gpg   https://pts-project.org/debian-12-workshop/pirogue.gpg
sudo apt update
```
