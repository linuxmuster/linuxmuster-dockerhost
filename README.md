# linuxmuster-dockerhost
Skript to turn ubuntu server into a docker host for linuxmuster.

## Benutzung

(getestet auf Ubuntu Server 16.04)

Installation

mkdir /opt/linuxmuster/
cd /opt/linuxmuster/
git clone ...
ln -s /opt/linuxmuster/linuxmuster-dockerhost/linuxmuster-dockerhost  /usr/sbin/linuxmuster/dockerhost

Update

cd /opt/linuxmuster/linuxuster-dockerhost/
git pull
