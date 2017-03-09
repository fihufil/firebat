# firebat - program for starting iptables firewall on startup

## Description
This program starts iptables rules stored in /etc/ipaas at system boot.

## Usage
`service ipaas {start|stop|restart}`
`start ipaas`
`stop ipaas`

## Building
`dpkg-buildpackage`

## Installation
`dpkg -i ipaas*`
