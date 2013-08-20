Munin Plugins for bitcoind and litecoind
========================================

install in /usr/local/share/munin/plugins/

run:
  cd /etc/munin/plugins
  sudo munin-node-configure --libdir=/usr/local/share/munin/plugins --suggest --shell | sudo bash

Edit the config files:
  vi /etc/munin/plugin-conf.d/bitcoin.conf

  [bitcoind_*]
      user <The user running bitcoind>

and likewise for litecoin
  vi /etc/munin/plugin-conf.d/litecoin.conf

  [litecoind_*]
      user <The user running litecoind>

