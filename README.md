mongod-daemon
=============
<br />
init.d script for mongod and mongoc servers. (CentOS)<br />
<br />
Configuration:<br />
1. Place script in /etc/init.d<br />
2. Rename script to desired configuration name. ex: /etc/init.d/mongoc will load /etc/init.d/mongoc.conf<br />
<br />
Improvements:<br />
1. This script will no longer kill all mongod processes when executing '/etc/init.d/mongod stop'<br />
2. This script will automatically find associated configuration files from /etc/<br />
3. This script will make it easier to run both mongod and mongoc on the same server.<br />
