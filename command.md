commands:

**Ifconfig** - Interface Configuration
 
hostname -I - for address
 
**ip route / route** -n  [these two commands to list the routing table]
 
ping  - to check network connectivity
 
**traceroute** -  trace how the packet is reaching destination.  example : traceroute google.com 
 
netstat [-a | -tln | -ulp]
 
ss - socket statstics , similar to netstat
 
Hostname
 
nslookup
 
dig - similar to nslookup
 
**route** - Destination     Gateway         Genmask         Flags Metric Ref    Use Iface  - all these will be listed, 
route add  -  used to add routes into rotue table
 
**iptabels/firewalld** -  packet filtering(firewall)
 
**telnet** - access remote host but with no encryption like ssh
 
scp  - secure copy
 
wget  - to download from internet
 
curl
 
**Iftop** - display bandwidth on the interface
 
**nmap** - security scanner
 
**lsof** - list of open files
 
**arp -a**  - display arp cache
 
**mtr**  - similar to traceroute - network diagnostic tool
 
fping - ping multiple host together
