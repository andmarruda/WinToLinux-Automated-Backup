# WinToLinux-Automated-Backup
# Powered by Anderson Matheus Arruda < andmarruda at gmail dot com >
# Linkedin http://www.linkedin.com/in/anderson-arruda-48435595

Make a backup from Windows OS to Linux Debian With Log

First of all you have to determine wich directory will be backuped by this system.
To shared the folder on windows see this link https://technet.microsoft.com/en-us/library/cc770880(v=ws.11).aspx . Will teach you to do this.
In windows disable password protected sharing.

In Linux Debian "i have tested in Debian 6" you have to install smbclient.

If you're not in super user you have to use sudo like this:
sudo apt-get update || sudo apt-get install smbclient

If you're on super user login, just do it:
apt-get update || apt-get install smbclient
