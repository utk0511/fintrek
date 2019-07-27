# fintrek


## ------------------fintrek------------------
### Install mysql 
For linux follow:
https://dev.mysql.com/doc/refman/8.0/en/linux-installation-yum-repo.html

### Create new database for mysql


### Clone project from git

### Install php
`yum install epel-release yum-utils`
`yum install http://rpms.remirepo.net/enterprise/remi-release-7.rpm`
`yum-config-manager --enable remi-php71`
`yum install php php-common php-opcache php-mcrypt php-cli php-gd php-curl php-mysqlnd`
`yum install php-cli php-zip wget unzip`

### Install composer
`php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"`
`sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer`

To verify:
`Composer`

### Composer Install
`composer install`

### Create migrations
`php artisan migrate`

