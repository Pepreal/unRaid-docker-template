# Custom Template for unRaid
unRaid custom template for the orginal Teamspeak docker image

I'm not a developer, the template was to learn how to work with dockerman.

If you want to use the template 
* ```mkdir -p /boot/config/plugins/community.applications/private/myrepo cp teamSpeak-officialdocker.xml /boot/config/plugins/community.applications/private/myrepo```<br>
* Go to the Community Apps tab, go to private apps on the left and install from there.<br>
* Set ```AppData``` folder and ```accept``` the licence.<br>

## Extras: 
For importing an existing database and/or licence key.

* Put the database and licence in the ```AppData``` folder and restart the docker. The docker will set the permissions in the ```Host Path``` on every start/restart.

## Links:
[Teamspeak Github Page](https://github.com/TeamSpeak-Systems/teamspeak-linux-docker-images)<br>
[Teamspeak Docker Page](https://hub.docker.com/_/teamspeak)
