# MySQL-Ubuntu-Linux

MySQL Installation and Configuration on Ubuntu Linux


```
ps ax | grep mysql

ls -al /usr/sbin/mmysql*

ls -al /usr/bin/mysql*

sudo ls -al /usr/lib/mysql*

sudo ls -al /var/lib/mysql*

```

```
cd ~/Downloads

sudo dpkg -i mysql-apt-config_0.8.15-1_all.deb 

sudo apt-get update

sudo apt-get -y install mysql-server
```

```
sudo service mysql start

sudo service mysql status

sudo service mysql stop
```

```
mysql -u root -p 
```

## Password

```
mysql -u root -p -h 127.0.0.1 -P 3306
mysql> ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

```

username: root
password: password


## Install MySQL Workbench on Ubuntu

```
sudo apt-get -y install mysql-workbench
```
