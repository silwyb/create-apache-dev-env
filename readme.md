##Shell for creating dev-env
generate .conf, user & dev-directories.
AutoGenerated-Subdomain by mod_vhost_alias

####Edit Name-Server
You need to edit DNS

```DNS -> * A ip_address```

####Generate .conf

for Apache 2.2

```
sh gen-conf.sh PROJECT_NAME PROJECT_DOMAIN
```
then, move to /etc/httpd/conf.d/ or else.

####Generate user & dev-directories
This generates user-account with password & dev-directory under /var/www/vhosts
```
sh gen-user.sh USER_NAME PROJECT_NAME
```
