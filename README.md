# Redis-installination-on-ubuntu

For your copying and pasting convenience, here are the installation commands

$ sudo apt-add-repository ppa:redislabs/redis
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install redis-server

Once installed, you can start, stop, and restart the server:

$ sudo service redis-server start
$ sudo service redis-server stop
$ sudo service redis-server restart
