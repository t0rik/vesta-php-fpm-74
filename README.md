# vesta-php-fpm-74
VestaCP PHP templates for PHP 7.4

Usage:

```
apt-get install php7.4-apcu php7.4-mbstring php7.4-bcmath php7.4-cli php7.4-curl php7.4-fpm php7.4-gd php7.4-intl php7.4-mysql php7.4-soap php7.4-xml php7.4-zip php7.4-memcache php7.4-memcached php7.4-zip
update-rc.d php7.4-fpm defaults
a2enconf php7.4-fpm
systemctl restart apache2
cp -r /etc/php/7.4/ /root/vst_install_backups/php7.4/
rm -f /etc/php/7.4/fpm/pool.d/*
wget https://github.com/t0rik/vesta-php-fpm-74/raw/master/PHP-FPM-74.stpl -O /usr/local/vesta/data/templates/web/apache2/PHP-FPM-74.stpl
wget https://github.com/t0rik/vesta-php-fpm-74/blob/master/PHP-FPM-74.tpl -O /usr/local/vesta/data/templates/web/apache2/PHP-FPM-74.tpl
wget https://raw.githubusercontent.com/t0rik/vesta-php-fpm-74/master/PHP-FPM-74.sh -O /usr/local/vesta/data/templates/web/apache2/PHP-FPM-74.sh
chmod a+x /usr/local/vesta/data/templates/web/apache2/PHP-FPM-74.sh

```
