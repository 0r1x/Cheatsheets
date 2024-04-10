





**Remove existing host keys from affected machine**

`sudo /bin/rm -v /etc/ssh/ssh_host_*`

**Run dpgk-reconfigure to generate new host keys**

`sudo dpkg-reconfigure openssh-server`

**Restart SSH service (systemd hosts**)

`sudo systemctl restart ssh`