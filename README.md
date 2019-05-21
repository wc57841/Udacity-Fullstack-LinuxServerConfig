# Udacity-Fullstack-LinuxServerConfig

# Access Instructions
Ip Address: 54.89.82.65
Ssh port: 2200

Web url: http://54.89.82.65/home

# Sofware and Packages Installed
Finger: apt-get install finger
Apache: apt-get install apache2
Mod_wsgi: apt-get install libapache2-mod-wsgi-py3
Git: apt-get install git
Pip: apt-get install python3-pip
Postgresql: apt-get install postgresql
Virtualenv: pip3 install virtualenv
Flask: pip3 install Flask
Httplib2: pip3 install httplib2
Oauthclient: pip3 install oauth2client
Sqlalchemy: pip3 install sqlalchemy
Psycopg2: pip3 install psycopg2
Requests: pip3 install requests

# Configuration Changes
sshd_config changes:
  PasswordAuthentication
  Port
  PermitRootLogin
  
configured ufw firewall to only allow:
  ssh (port 2200)
  http (port 80)
  ntp (port 123)
  
changed apache config in /etc/apache2/sites-available/catalof.config
  ServerName
  ServerAlias
  ServerAdmin
  WSGIDaemonProcess
  WSGIProcessGroup
  WSGIScriptAlias
  
# Third Party Resources:
https://knowledge.udacity.com/
https://www.google.com/
https://stackoverflow.com
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
http://leonwang.me/post/deploy-flask
https://www.jakowicz.com/flask-apache-wsgi/
http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/
https://github.com/juvers/Linux-Configuration/blob/master/README.md

  
  
