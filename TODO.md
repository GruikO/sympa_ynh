- manifest
  - maintainer
  - requirements
  - services
  - install : https://www.sympa.org/manual_6.2/installing-sympa#installing_sympa

- scripts
  - install : disable multisite for now

- conf
  - /etc/nginx/conf.d/<DOMAIN>.d/sympa.conf
  - /etc/nginx/sympa_fcgi.conf
  - /etc/sympa/sympa.conf

- static content

- database
  - create_db.mysql 

- errors
  - Config error: wwsympa should run with UID 1000 (instead of 33). *** Switching to maintenance mode. ***
	What about support for something like mod_suexec?
