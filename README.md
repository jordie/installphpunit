installphpunit
==============


cd /tmp && mkdir pear && cd pear
curl http://pear.php.net/go-pear.phar > go-pear.phar
sudo php -d detect_unicode=0 go-pear.phar


sudo pear channel-discover pear.phpunit.de
sudo pear channel-discover components.ez.no
sudo pear channel-discover pear.symfony.com
sudo pear channel-discover pear.symfony-project.com
sudo pear install phpunit/PHPUnit


echo "edit you php.ini file add pear path to the include path"
