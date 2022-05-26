Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2012 PPCoin Developers
Copyright (c) 2013-2014 NovaCoin Developers
Copyright (c) 2014 Calmcoin Developers

Distributed under the MIT/X11 software license, see the accompanying
file license.txt or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).  This product includes
cryptographic software written by Eric Young (eay@cryptsoft.com).


Intro
-----
Calmcoin is a free open source project derived from PPCoin, with
the goal of providing a long-term energy-efficient scrypt-based crypto-currency.
Built on the foundation of Bitcoin and PPCoin, innovations such as 
proof-of-stake
help further advance the field of crypto-currency.

Setup
-----
After completing windows setup then run windows command line (cmd)
  cd daemon
  calmd
You would need to create a configuration file calm.conf in the default
wallet directory. Grant access to calmd.exe in anti-virus and firewall
applications if necessary.

The software automatically finds other nodes to connect to.  You can
enable Universal Plug and Play (UPnP) with your router/firewall
or forward port 

23489 (TCP) to your computer so you can receive
incoming connections.  Calmcoin works without incoming connections,
but allowing incoming connections helps the Calmcoin network.

Upgrade
-------
All you existing coins/transactions should be intact with the upgrade.
To upgrade first backup wallet
calmd backupwallet <destination_backup_file>
Then shutdown calmd by
calmd stop
Start up the new calmd.


See the documentation/wiki at the Calmcoin site:
  http://calm.cc/
for help and more information.

