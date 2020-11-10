## What is an IP address
In the TCP/IP protocol, the unique identifier for a computer on a network is called its IP address.
IPv4 | IPv6
------------ | -------------
32 binary bits | 128 binary bits
216.27.61.137 | 2001:cdba:0000:0000:0000:0000:3257:9652

[IP address](https://computer.howstuffworks.com/internet/basics/what-is-an-ip-address.htm)

## What is a Netmask
A netmask is a 32-bit binary mask used to divide an IP address into subnets and specify the network's available hosts.
The capable amount of networks a netmask
```
2^(netmask length - # of used segments) - 2
```
The number of hosts a netmask is capable of supporting
```
2^(# of zeroes) - 2
```
Class | Netmask length | # of networks | # of hosts | Netmask
------------ | ------------- | ------------- | ------------- | -------------
Class A | 8 | 126 | 16,777,214 | 255.0.0.0
Class B | 16 | 16,382 | 65,534 | 255.255.0.0
Class C | 24 | 2,097,150 | 254 | 255.255.255.0

[netmask](https://www.computerhope.com/jargon/n/netmask.htm)

## What is the subnet of an IP with Netmask
A standard that defines how to establish and maintain a network conversation through which application programs can exchange data.
## What is the broadcast address of a subnet
An IP broadcast address is the highest number in its class; for example, the broadcast address of a Class C 192.168.16.0 network is 192.168.16.255.
The broadcast address for a subnet must account for the part of the address that is reserved for the subnet
https://www.pcmag.com/encyclopedia/term/broadcast-address
## What are the different ways to represent an ip address with the Netmask

## What are the differences between public and private IPs
## What is a class of IP addresses
## What is TCP
[Transmission Control Protocol](https://searchnetworking.techtarget.com/definition/TCP#:~:text=TCP%20(Transmission%20Control%20Protocol)%20is,of%20data%20to%20each%20other)
## What is UDP
## What are the network layers
## What is the OSI model
## What is a DHCP server and the DHCP protocol
## What is a DNS server and the DNS protocol
## What are the rules to make 2 devices communicate using IP addresses
## How does routing work with IP
## What is a default gateway for routing
## What is a port from an IP point of view and what is it used for when connecting
to another device
### Additional Resources
[IP Subnet Calculator](https://www.calculator.net/ip-subnet-calculator.html)
