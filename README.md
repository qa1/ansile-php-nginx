# PHP-NGINX installer ansible playbook

This playbook will install PHP, Nginx and other related essential packages on remote server.

## Installation

For installation you need to grab a fresh copy of app.

```bash

git clone https://github.com/ordidaad/php-nginx-playbook.git

```

## Usage

```bash

ansible-playbook php_nginx_installer.yml -i /path/to/your/inventory.cfg  -u root

```

## Test

After ansibe get his job done, Nginx start to listening on port 8081 on your server and you should be able to see success message by hiting your server address on port 8081.

```bash

http://server-address:8081

```