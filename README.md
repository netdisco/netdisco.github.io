Netdisco is written in Perl and self-contained apart from the PostgreSQL
database, so is very easy to install and runs well on any linux or unix
system. We also have [docker images](https://store.docker.com/community/images/netdisco/netdisco) if you prefer.

It includes a lightweight web server for the interface, a backend daemon to
gather data from your network, and a command line interface for
troubleshooting. There is a simple configuration file in YAML format.

Please check out the [installation
instructions](https://metacpan.org/pod/App::Netdisco) on CPAN.

You can also speak to someone in the
[`#netdisco@freenode`](https://webchat.freenode.net/?randomnick=1&prompt=1&channels=%23netdisco)
IRC channel, or on the [community email
list](https://lists.sourceforge.net/lists/listinfo/netdisco-users).

---

<a href="https://raw.githubusercontent.com/netdisco/upstream-sources/master/screenshots/nd2-shot-2.png"><img src="https://raw.githubusercontent.com/netdisco/upstream-sources/master/screenshots/nd2-shot-2.png" alt="Device Search" width="150"></a>
<a href="https://raw.githubusercontent.com/netdisco/upstream-sources/master/screenshots/nd2-shot-1.png"><img src="https://raw.githubusercontent.com/netdisco/upstream-sources/master/screenshots/nd2-shot-1.png" alt="Device Ports and Nodes" width="150"></a>
<a href="https://raw.githubusercontent.com/netdisco/upstream-sources/master/screenshots/nd2-shot-3.png"><img src="https://raw.githubusercontent.com/netdisco/upstream-sources/master/screenshots/nd2-shot-3.png" alt="Device Details" width="150"></a>

---

Some of the things you can do with Netdisco:

* Locate a machine on the network by MAC or IP
* Turn off a switch port, or change the VLAN or PoE status of a port
* Inventory your network by model, vendor, and software
* Pretty pictures of your network

[![Build Status](https://travis-ci.org/netdisco/netdisco.svg?branch=master)](https://travis-ci.org/netdisco/netdisco)
[![CPAN version](https://badge.fury.io/pl/App-Netdisco.svg)](https://metacpan.org/pod/App::Netdisco)
[![Docker Backend Image](https://img.shields.io/microbadger/image-size/netdisco/netdisco/latest-backend.svg?label=backend)](https://store.docker.com/community/images/netdisco/netdisco)
[![Docker Backend Image](https://img.shields.io/microbadger/image-size/netdisco/netdisco/latest-web.svg?label=frontend)](https://store.docker.com/community/images/netdisco/netdisco)
