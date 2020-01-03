
Nagios Core Docker image URL
----------------------------
https://hub.docker.com/r/quantumobject/docker-nagios/

Usage
-----------
I used this To run container use the command below:

$ docker run -d -p 25 -p 80 quantumobject/docker-nagios
login : nagiosadmin password: admin please replace it after install.

to access the container please use :

$ docker exec -it container_id  /bin/bash
to replace password :

$ htpasswd -c /usr/local/nagios/etc/htpasswd.users nagiosadmin
note: to access site is http://IP:PORT/nagios/

update to nrpe-3.2.1

update to nagios-plugins-2.2.1
