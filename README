# Pré-requis

```sh
apt-get install apache2 libapache2-mod-php5 php5 php5-ldap ca-certificates
```

# Fichier host apache

```sh
<VirtualHost *:80>
	DocumentRoot /home/phpldapadmin
	DirectoryIndex index.php

	<Directory /home/phpldapadmin>
		AllowOverride All
		Require all granted
	</Directory>

	ErrorLog ${APACHE_LOG_DIR}/error.log
	CustomLog ${APACHE_LOG_DIR}/access.log combined
</VirtualHost>
```

```sh
service apache2 reload
```

# PhpLDAPADMIN

## Sources
https://goo.gl/t6sFrM
## Patches (à mettre dans lib)
https://goo.gl/QKhDTd
https://goo.gl/zjEAmm

