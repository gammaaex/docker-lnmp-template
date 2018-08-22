# docker-lnmp-template

This is LNMP template for docker.  

## About
- `/php/Dockerfile` is made for CakePHP3.
- Please change the permissions of all files in the `mariadb/conf.d/` directory to read-only so that the settings are reflected at mysql startup (To avoid the following error -> `Warning: World-writable config file ‘/etc/my.cnf’ is ignored`).