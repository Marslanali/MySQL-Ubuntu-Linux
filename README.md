# MySQL-Ubuntu-Linux

MySQL Server, and Workbench Installation and Configuration on Ubuntu Linux


```
ps ax | grep mysql

ls -al /usr/sbin/mmysql*

ls -al /usr/bin/mysql*

sudo ls -al /usr/lib/mysql*

sudo ls -al /var/lib/mysql*

```

```
Get MySQL apt deb file: https://dev.mysql.com/downloads/repo/apt/

cd ~/Downloads

sudo dpkg -i mysql-apt-config_0.8.15-1_all.deb 

sudo apt-get update

sudo apt-get -y install mysql-server
```

MySQL server start/stop/status

```
sudo service mysql start

sudo service mysql status

sudo service mysql stop
```

MySQL server CLI interface:

```
mysql -u root -p 
```

## Password

```
mysql -u root -p -h 127.0.0.1 -P 3306
mysql> ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

```

This will make `username: root` and `password: password`.


## Install MySQL Workbench on Ubuntu

```
sudo apt-get update
sudo apt-get -y install mysql-workbench
```


