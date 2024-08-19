Netdisco is written in Perl and Python and self-contained apart from the PostgreSQL
database, so is very easy to install and runs well on any linux or unix
system. We also have [docker images](https://store.docker.com/community/images/netdisco/netdisco) if you prefer.

It includes a lightweight web server for the interface, a backend daemon to
gather data from your network, and a command line interface for
troubleshooting. There is a simple configuration file in YAML format.

Please check out the [installation
instructions](https://metacpan.org/pod/App::Netdisco) on CPAN.

You can also speak to someone in the
[`irc.libera.chat#netdisco`](https://kiwiirc.com/nextclient/irc.libera.chat/netdisco)
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
* Keep historic data of system IPs and locations
* Search and retrieve data via the [API](https://netdisco2-demo.herokuapp.com/swagger-ui)
* View pretty pictures of your network

[![CPAN version](https://badge.fury.io/pl/App-Netdisco.svg)](https://metacpan.org/pod/App::Netdisco)
[![Release date](https://img.shields.io/github/release-date/netdisco/netdisco.svg?label=released)](https://metacpan.org/pod/App::Netdisco)
[![Tests Status](https://github.com/netdisco/netdisco/actions/workflows/test_and_publish.yml/badge.svg?event=push)](https://github.com/netdisco/netdisco/actions/workflows/test_and_publish.yml)
[![Docker Image](https://img.shields.io/badge/docker%20images-ready-blue.svg)](https://store.docker.com/community/images/netdisco/netdisco)
