# dnsmasq-nocachelimit
Personal fork for dnsmasq that removes the cache limit of 10000 names.

Meant for modern servers with lots of RAM.

Later I plan to dump the cache to disk and reload it when restarting the server
so it survives server restarts.