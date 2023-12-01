# pfsense_unbound_pihole.sh

Here is THE ultimate script that is used to return localhost IPv4 and IPv6 to DNS queries from multiple lists of hosts files found here and there on the net

An Adblock in the PfSense, no more need for Pi-Hole!!!

## Instructions

set the script in your pfsense device, then type :

<code>./pfsense_unbound_pihole.sh</code>

- Add "include: /unbound/ad_servers.conf" in expert unbound configuration
- Uncheck "Register DHCP static mapping in the DNS Resolver" and "Register DHCP leases in the DNS Resolver" for resolver restart fix
