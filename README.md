# linuxmuster-dockerhost
Skript to turn ubuntu server into a docker host for linuxmuster.

## Benutzung

(getestet auf Ubuntu Server 16.04)

###I nstallation

mkdir /opt/linuxmuster/
cd /opt/linuxmuster/
git clone ...
ln -s /opt/linuxmuster/linuxmuster-dockerhost/linuxmuster-dockerhost  /usr/sbin/linuxmuster/dockerhost

### Update

cd /opt/linuxmuster/linuxuster-dockerhost/
git pull

### Verwendung

linuxmuster-dockerhost -a turnkey

initialisiert den Ubuntu Server für die Verwendung als Dockerhost. 

  * Aktives Netzwerk-Interface wird ermittelt und auf DHCP gestellt 
  * Docker pakete aus den Ubuntu Repos werden entfernt
  * Docker-CE Repo wird eingetragen
  * Docker-CE wird installiert
  * Die in der Konfigurationsdatei angegebene Version von docker-compose wird aus den Docker Repos installiert
 
