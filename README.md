## Welcome to Netdisco!

Netdisco is a web-based network management tool suitable for small to very large networks. IP and MAC address data is collected into a PostgreSQL database using SNMP, CLI, or device APIs.

Some of the things you can do with Netdisco:

* Locate a machine on the network by MAC or IP and show the switch port it lives at
* Turn off a switch port, or change the VLAN or PoE status of a port
* Inventory your network hardware by model, vendor, software and operating system
* Pretty pictures of your network

See the demo at: https://netdisco2-demo.herokuapp.com/

## Installation

Netdisco is written in Perl and self-contained apart from the PostgreSQL database, so is very easy to install and runs well on any linux or unix system. It includes a lightweight web server for the interface, a backend daemon to gather data from your network, and a command line interface for troubleshooting. There is a simple configuration file in YAML format.

Please check out the installation instructions on CPAN.

You can also speak to someone in the `#netdisco@freenode` IRC channel, or on the [community email list](https://lists.sourceforge.net/lists/listinfo/netdisco-users).
