# dnsmasq-nocachelimit
AUTHOR: Alexandro Olivares Acosta <aoa141@gmail.com>

Personal fork for dnsmasq that removes the cache limit of 10000 names.

Meant for modern servers with lots of RAM.

A cache size of 1M names uses about 100MB or RAM. 



You can install my binary packages for Debian Jessie from 

https://drive.google.com/folderview?id=0B38VG7HG0bZ2Z2d6YVl0MUNvVEk&usp=sharing

After installing, hold the package with

sudo apt-mark hold dnsmasq dnsmasq-base


TODO:

Later I plan to dump the cache to disk and reload it when restarting the server
so it survives server restarts.