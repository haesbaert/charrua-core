### Charrua DHCP Unix Server

[charrua-unix](http://www.github.com/haesbaert/charrua-unix) is an _ISC-licensed_
Unix DHCP daemon based on
[charrua-core](http://www.github.com/haesbaert/charrua-core).

#### Features

* Supports a stripped down ISC dhcpd.conf. A configuration sample can be found
[here](https://github.com/haesbaert/charrua-core/blob/master/sample/dhcpd.conf)
* Priviledge dropping, the daemon doesn't run as root.
* Almost purely-functional code.
* Support for multiple interfaces/subnets.

Try `charruad --help` for options.
