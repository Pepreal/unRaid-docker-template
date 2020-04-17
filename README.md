# Custom Template for unRaid
unRaid custom template for orginal Teamspeak docker image

I'm not a developer, the file was to learn how to work with dockerman.

If you want to use the template ```mkdir -p /boot/config/plugins/community.applications/private/myrepo
cp teamSpeak-officialdocker.xml /boot/config/plugins/community.applications/private/myrepo```<br>
Go to the Community Apps tab (assuming its installed) go to private apps on the left, and install from there.<br>
Set ```AppData``` folder and ```accept``` the licence.

If you have a license key, put the license key in the ```AppData``` folder and restart the docker. The docker will set the permissions in the ```Host Path``` on every restart. The same goes for the database.

Github page: https://github.com/TeamSpeak-Systems/teamspeak-linux-docker-images<br>
Docker: https://hub.docker.com/_/teamspeak
