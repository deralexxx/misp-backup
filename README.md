shell script for making a MISP backup

You need to install locate on your system:
````
sudo apt-get install locate
````



Installation
============

Modify config file:
````
cp misp-backup.conf.sample misp-backup.conf
sudo cat /var/www/MISP/app/Config/database.php | grep password
#adjust values
vi misp-backup.conf
````

Running
=======

run the script:
````
sh misp-backup.sh
````

Open
====

````
    sample files
    server certificates for sync connections
    organisation logos (though this isn't as important, but it's still annoying to lose them)

````


Licence
=======

See LICENSE
initial idea based daverstephens on https://github.com/daverstephens/The-SOC-Shop
