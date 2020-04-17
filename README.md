# Custom Template for unRaid
unRaid custom template for the orginal Teamspeak docker image

I'm not a developer, the file was to learn how to work with dockerman.

If you want to use the template ```mkdir -p /boot/config/plugins/community.applications/private/myrepo
cp teamSpeak-officialdocker.xml /boot/config/plugins/community.applications/private/myrepo```<br>
Go to the Community Apps tab (assuming its installed) go to private apps on the left, and install from there.<br>
Set ```AppData``` folder and ```accept``` the licence.<br>

### Extra:
If you want to use an existing database and/or licence key.<br>
put the database and licence in the ```AppData``` folder and restart the docker. The docker will set the permissions in the ```Host Path``` on every start/restart.

### Links:
[Teamspeak Github Page](https://github.com/TeamSpeak-Systems/teamspeak-linux-docker-images)<br>
[Teamspeak Docker Page](https://hub.docker.com/_/teamspeak)
