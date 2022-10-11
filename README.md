# iso-nginx-server

simple nginx server that serves iso for kvm because `sudo python3 -m http.server 80`<sup>1</sup> doesn't work with `virt-manager`.




1. [http.server does not support HTTP range requests](https://bugs.python.org/issue42643)