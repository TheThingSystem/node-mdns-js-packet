mdns-js-packet
==============

DNS packet parser specifically built for mdns-js
[mdns-js](https://github.com/kmpm/node-mdns-js)

You probably want to have a look at 
[native-dns-packet](https://github.com/tjfontaine/native-dns-packet)
first and if that does do what you need, you might start looking at this.

mdns-js-packet should produce the same output as native-dns-packet,
it even uses it's test fixtures and borrows some parts of it.

This was made before i knew about native-dns-packet but since that
still has some bugs in handling some mDNS packets I cant use it.