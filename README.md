## What is an IP address
In the TCP/IP protocol, the unique identifier for a computer on a network is called its [IP address](https://computer.howstuffworks.com/internet/basics/what-is-an-ip-address.htm).
IPv4 | IPv6
------------ | -------------
32 binary bits | 128 binary bits
216.27.61.137 | 2001:cdba:0000:0000:0000:0000:3257:9652

## What is a Netmask
A netmask is a 32-bit binary mask used to divide an IP address into subnets and specify the network's available hosts.
The capable amount of networks a netmask
```
2^(netmask length - # of used segments) - 2
```
The number of hosts a [netmask](https://www.computerhope.com/jargon/n/netmask.htm) is capable of supporting
```
2^(# of zeroes) - 2
```
Class | Netmask length | # of networks | # of hosts | Netmask
------------ | ------------- | ------------- | ------------- | -------------
Class A | 8 | 126 | 16,777,214 | 255.0.0.0
Class B | 16 | 16,382 | 65,534 | 255.255.0.0
Class C | 24 | 2,097,150 | 254 | 255.255.255.0

## What is the subnet of an IP with Netmask
A standard that defines how to establish and maintain a network conversation through which application programs can exchange data.
## What is the broadcast address of a subnet
An IP broadcast address is the highest number in its class; for example, the broadcast address of a Class C 192.168.16.0 network is 192.168.16.255.
The broadcast address for a subnet must account for the part of the address that is reserved for the subnet
https://www.pcmag.com/encyclopedia/term/broadcast-address
## What are the different ways to represent an ip address with the Netmask

## What are the differences between public and private IPs
Private IP Address and Public IP Address are used to uniquely identify a machine on the internet. Private IP address is used with a local network and public IP address is used outside the network. Public IP address is provided by ISP, Internet Service Provider
WAN | LAN
------------ | -------------
global | local

## What is a class of IP addresses
Class A IP addresses are used for huge networks, like those deployed by Internet Service Providers (ISPs). Class A IP addresses support up to 16 million hosts (hosts are devices that connect to a network (computers, servers, switches, routers, printers…etc.) and a Class A network can be divided into 128 different networks.

Class B IP addresses are used for medium and large-sized networks in enterprises and organizations. They support up to 65,000 hosts on 16,000 individual networks.

Class C addresses are most common and used in small business and home networks. These support up to 256 hosts on each of 2 million networks.

Class D and E addresses are least used. Class D is reserved for a not widely used, and reserved for special cases largely for services and applications to stream audio and video to many subscribers at once. Class E addresses are reserved for research purposes by those responsible for Internet networking and IP address research, management, and development.

Class | Address range |  Supports 
------------ | ------------- | -------------
Class A | 1.0.0.1 to 126.255.255.254 | Supports 16 million hosts on each of 127 networks.
Class B | 128.1.0.1 to 191.255.255.254 | Supports 65,000 hosts on each of 16,000 networks.
Class C | 192.0.1.1 to 223.255.254.254 | Supports 254 hosts on each of 2 million networks. 
Class D | 224.0.0.0 to 239.255.255.255 | Reserved for multicast groups. 
Class E | 240.0.0.0 to 254.255.255.254 | Reserved for future use, or research and development purposes.
## What is TCP
TCP ([Transmission Control Protocol](https://searchnetworking.techtarget.com/definition/TCP#:~:text=TCP%20(Transmission%20Control%20Protocol)%20is,of%20data%20to%20each%20other)) is a standard that defines how to establish and maintain a network conversation through which application programs can exchange data.

## What is UDP
The [User Datagram Protocol](https://www.cloudflare.com/learning/ddos/glossary/user-datagram-protocol-udp/), or UDP, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups. It speeds up communications by not formally establishing a connection before data is transferred. This allows data to be transferred very quickly, but it can also cause packets to become lost in transit — and create opportunities for exploitation in the form of DDoS attacks.
## What are the network layers
[7 layers](https://www.plixer.com/blog/network-layers-explained/)
## What is the OSI model
The OSI Model ([Open Systems Interconnection Model](https://www.forcepoint.com/cyber-edu/osi-model#:~:text=The%20OSI%20Model%20(Open%20Systems,between%20different%20products%20and%20software.)) is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software. 
## What is a DHCP server and the DHCP protocol
A [DHCP Server](https://www.infoblox.com/glossary/dhcp-server/) is a network server that automatically provides and assigns IP addresses, default gateways and other network parameters to client devices. 
[Dynamic Host Configuration Protocol](https://www.efficientip.com/what-is-dhcp-and-why-is-it-important/#:~:text=A%20DHCP%20server%20dynamically%20assigns,DNS%2DDHCP%2DIPAM).) (DHCP) is a network management protocol used to automate the process of configuring devices on IP networks, thus allowing them to use network services such as DNS, NTP, and any communication protocol based on UDP or TCP. 
## What is a DNS server and the DNS protocol
[DNS Server](https://www.cloudflare.com/learning/dns/what-is-a-dns-server/)
The Domain Name System (DNS) is the phonebook of the Internet. When users type domain names such as ‘google.com’ or ‘nytimes.com’ into web browsers, DNS is responsible for finding the correct IP address for those sites. Browsers then use those addresses to communicate with origin servers or CDN edge servers to access website information. This all happens thanks to DNS servers: machines dedicated to answering DNS queries.
[DNS Protocol](https://ns1.com/resources/dns-protocol)
## What are the rules to make 2 devices communicate using IP addresses
ISP assigns an IP address, which is a unique address given to your computer or network to communicate on the Internet.
## How does routing work with IP
IP routing is a process of transferring data from one network to another as IP packets. Routers provide [IP routing](https://www.computernetworkingnotes.com/ccna-study-guide/basic-of-ip-routing-explained-with-example.html)
## What is a default gateway for routing
A default gateway is an interface of a router that connects the local network with the remote network. By default, an IP protocol forwards all packets to the default gateway except the packets that belong to the local IP network.
## What is a port from an IP point of view and what is it used for when connecting to another device
Just as the IP address identifies the computer, The [network port](http://www.steves-internet-guide.com/tcpip-ports-sockets/) identifies the application or service running on the computer.
### Additional Resources
[IP Subnet Calculator](https://www.calculator.net/ip-subnet-calculator.html)
