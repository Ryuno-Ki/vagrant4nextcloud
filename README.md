# vagrant4nextcloud

Vagrantfile to hack on Nextcloud.

## Getting started

Make sure, that you have Vagrant installed.

```
$ cd $HOME
$ mkdir github
$ cd github
$ git clone https://github.com/Ryuno-Ki/vagrant4nextcloud.git
$ cd vagrant4nextcloud
$ vagrant up
```

Open a browser and surf to
[http://127.0.0.1:8888/setup-nextcloud.php](http://127.0.0.1:8888/setup-nextcloud.php)
and follow the instructions there.

When creating an admin account use the data below:
```
$ mysql -u root --passwd=root
> CREATE DATABASE nextcloud;
```

    MYSQLUSER = 'root'
    MYSQLPASSWD = 'root'
    MYSQLDBNAME = 'nextcloud'
    MYSQLHOST = '127.0.0.1'
