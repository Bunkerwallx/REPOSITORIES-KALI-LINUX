# REPOSITORIES-KALI
# Greetings to all ladies, gentlemen I hope to help you a little with something that was very helpful for me, I leave some 
# repositories for you to edit your SOURCES.LIST configuration file (/etc/apt/sources.list) to load packages in Kali Linux


# Saludos a todos damas, caballeros espero les ayude un poco con algo que para mi fue de gran ayuda les dejo algunos repostorios # para qe editen su  archivo de configuracion  SOURCES.LIST  (/etc/apt/sources.list ) para cargar paquetes en kali linux



deb http://deb.debian.org/debian/ oldstable main contrib non-free
deb-src http://deb.debian.org/debian/ oldstable main contrib non-free

deb http://deb.debian.org/debian/ oldstable-updates main contrib non-free
deb-src http://deb.debian.org/debian/ oldstable-updates main contrib non-free

deb http://deb.debian.org/debian-security oldstable/updates main
deb-src http://deb.debian.org/debian-security oldstable/updates main

deb http://ftp.debian.org/debian stretch-backports main
deb-src http://ftp.debian.org/debian stretch-backports main

deb http://deb.debian.org/debian/ unstable main contrib non-free
deb-src http://deb.debian.org/debian/ unstable main contrib non-free

deb http://ftp.br.debian.org/debian/ unstable main contrib non-free
deb-src http://ftp.br.debian.org/debian/ unstable main contrib non-free

deb http://deb.debian.org/debian/ stable main contrib non-free
deb  http://kali.download/kali kali-rolling main contrib non-free
deb-src http://deb.debian.org/debian/ stable main contrib non-free

deb http://deb.debian.org/debian/ stable-updates main contrib non-free
deb-src http://deb.debian.org/debian/ stable-updates main contrib non-free

deb http://deb.debian.org/debian-security stable/updates main
deb-src http://deb.debian.org/debian-security stable/updates main

deb-src http://ftp.debian.org/debian buster-backports main

deb http://ppa.launchpad.net/tista/adapta/ubuntu bionic main
deb-src http://ppa.launchpad.net/tista/adapta/ubuntu bionic main
deb [arch=amd64] https://packagecloud.io/AtomEditor/atom/any/ any main

deb [arch=amd64,i386] https://www.deb-multimedia.org buster main non-free

deb [arch=amd64] https://download.docker.com/linux/debian buster stable
deb http://repo.sinew.in/ stable main

deb http://debian.froxlor.org stable main

deb http://ppa.launchpad.net/wereturtle/ppa/ubuntu bionic main 
deb-src http://ppa.launchpad.net/wereturtle/ppa/ubuntu bionic main

deb http://ppa.launchpad.net/gns3/ppa/ubuntu bionic main

deb-src http://ppa.launchpad.net/gns3/ppa/ubuntu xenial main
deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main

deb https://dl.bintray.com/gopasspw/gopass bionic main

deb http://ppa.launchpad.net/noobslab/icons/ubuntu bionic main
deb-src http://ppa.launchpad.net/noobslab/icons/ubuntu artful main

###Jabber.at ejabberd Repo
deb [arch=i386,amd64] https://apt.jabber.at buster ejabberd

deb [arch=i386,amd64] https://apt.jabber.at buster mcabber

deb http://repo.liveconfig.com/debian/ main main

deb [arch=i386,amd64] http://mirror.23media.de/mariadb/repo/10.2/debian stretch main
deb-src [arch=i386,amd64] http://mirror.23media.de/mariadb/repo/10.2/debian stretch main


###nginx
deb [arch=amd64,i386] http://nginx.org/packages/debian/ buster nginx
deb-src [arch=amd64,i386] http://nginx.org/packages/debian/ stretch nginx

###NodeJs
deb https://deb.nodesource.com/node_12.x buster main
deb-src https://deb.nodesource.com/node_12.x buster main

###Open Shot
deb http://ppa.launchpad.net/openshot.developers/ppa/ubuntu bionic main 

deb-src http://ppa.launchpad.net/openshot.developers/ppa/ubuntu bionic main 


###PHP
deb https://packages.sury.org/php/ buster main

###PostgreSQL
deb [arch=amd64,i386] http://apt.postgresql.org/pub/repos/apt/ buster-pgdg main


###### 3rd Party Binary Repos
###Debian Multimedia
deb [arch=amd64,i386] http://www.deb-multimedia.org sid main non-free


###PostgreSQL
deb [arch=amd64,i386] http://apt.postgresql.org/pub/repos/apt/ sid-pgdg main


deb http://ftp.ru.debian.org/debian/ stable main contrib non-free
deb-src http://ftp.ru.debian.org/debian/ stable main contrib non-free

deb http://ftp.ru.debian.org/debian/ stable-updates main contrib non-free
deb-src http://ftp.ru.debian.org/debian/ stable-updates main contrib non-free

deb http://security.debian.org/ stable/updates main
deb-src http://security.debian.org/ stable/updates main

deb http://ftp.debian.org/debian buster-backports main


###Google Earth
deb [arch=amd64] http://dl.google.com/linux/earth/deb/ stable main


deb http://ftp.ca.debian.org/debian/ unstable main contrib non-free
deb-src http://ftp.ca.debian.org/debian/ unstable main contrib non-free

#------------------------------------------------------------------------------#
#                      UNOFFICIAL  REPOS                       
#------------------------------------------------------------------------------#

###### 3rd Party Binary Repos
###Visual Studio Code



deb http://ftp.debian.org/debian unstable main contrib non-free

deb http://deb.debian.org/debian experimental main

deb https://ftp.halifax.rwth-aachen.de/kali kali-bleeding-edge main

deb http://http.kali.org/kali kali-rolling main contrib non-free
deb http://old.kali.org/kali sana main non-free contrib
deb http://old.kali.org/kali moto main non-free contrib

deb https://ftp.halifax.rwth-aachen.de/kali debian-testing main

deb https://ftp.halifax.rwth-aachen.de/kali kali-rolling main 

deb https://ftp.halifax.rwth-aachen.de/kali kali-experimental main
deb-src https://ftp.halifax.rwth-aachen.de/kali kali-experimental main

deb https://ftp.halifax.rwth-aachen.de/kali kali-last-snapshot main
deb-src https://ftp.halifax.rwth-aachen.de/kali kali-last-snapshot main

deb https://ftp.halifax.rwth-aachen.de/kali kali-dev main
deb-src https://ftp.halifax.rwth-aachen.de/kali kali-dev main

deb https://ftp.halifax.rwth-aachen.de/kali kali-debian-picks main

deb http://http.kali.org/kali debian-testing main contrib non-free
deb-src http://http.kali.org/kali debian-testing contrib

deb http://http.kali.org/kali kali-bleeding-edge main contrib non-free
deb-src  http://http.kali.org/kali kali-bleeding-edge main contrib non-free

deb http://kali.mirror.garr.it/mirrors/kali debian-testing main contrib non-free


deb http://kali.mirror.garr.it/mirrors/kali kali-rolling main contrib non-free
deb-src http://kali.mirror.garr.it/mirrors/kali kali-rolling main contrib non-free

deb http://kali.mirror.garr.it/mirrors/kali kali-rolling-only main contrib non-free
deb-src http://kali.mirror.garr.it/mirrors/kali kali-rolling-only main contrib non-free


deb http://kali.download/kali debian-testing main contrib non-free
deb-src http://kali.download/kali debian-testing main contrib non-free
