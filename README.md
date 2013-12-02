mongod-daemon
=============

init.d script for mongod and mongoc servers. (CentOS)

Configuration:
1. Place script in /etc/init.d
2. Rename script to desired configuration name. ex: /etc/init.d/mongoc will load /etc/init.d/mongoc.conf

Improvements:
1. This script will no longer kill all mongod processes when executing '/etc/init.d/mongod stop'
2. This script will automatically find associated configuration files from /etc/
3. This script will make it easier to run both mongod and mongoc on the same server.
