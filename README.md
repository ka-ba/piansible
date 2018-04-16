Bit of [Ansible](http://docs.ansible.com/ansible/latest/) stuff to do basic set-up on [Raspberry Pis](https://www.raspberrypi.org/) (and, presumably, other flavours as well) and to set them up as UPNP/DLNA media player as described in this [post](http://www.knight-of-pi.org/raspberry-pi-as-wifi-jukebox-with-dlna-and-upnp-smartphone-controls/).

You have to make up your own host file, following the example.

An initial OS is already expected. You can set up a raspbian (see [here](http://www.knight-of-pi.org/installation/)). Don't forget to add the files `ssh` and `wpa_supplicant.conf` (see [here](https://www.raspberrypi.org/forums/viewtopic.php?t=191252), or [here](https://www.raspberrypi.org/documentation/remote-access/ssh/) (point 3)).