# netdata-wifisignal
[Netdata](https://github.com/firehol/netdata) plugin for WiFi interface signal
strength monitoring.

Consider it obsolete, since release v1.27.0 of netdata
with native and more complete support for `/proc/net/wireles`.

---

It presents chart for link level (in dBm) of every found wireless interface.

This plugin should be placed in `plugins.d` directory of your netdata
installation. It requires source of data in the format of Linux
`/proc/net/wireless` file.

---

Author: Jacek Politowski <dev@jpol.net.pl>
License: GPL-3.0+, see LICENSE for details.
