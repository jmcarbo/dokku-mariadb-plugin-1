MariaDB single container plugin for Dokku
========================

Install mysql client in host:

sudo apt-get install mysql-client

Install plugin

cd /var/lib/dokku/plugins
git clone https://github.com/jmcarbo/dokku-mariadb-plugin-single.git
dokku plugins:install
