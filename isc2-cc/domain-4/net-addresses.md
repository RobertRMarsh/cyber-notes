2026-05-14 16:16
Status: #InProgress

## Notes
### MAC(Media Access Control) Address
- every network device is designated one
- i.e. 00-13-02-1F-58-F5 
	- first 3 bytes denote vendor/manufacturer of the physical interface, no two devices have the same MAC address on the same local network
- assigned in the firmware of the interface
### IP(Internet Protocol) Address
- associate with unique logical interface
- represents network interface, useful when a physical device is swapped with new hardware
#### IPv4 VS IPv6
##### IPv4
- 32-bit address
- was projected to exhaust by late 1980s
- expressed as four *octets* and contains a *network number* and a *host* 
	- *octets* contain any number between 0 and 255
		- 0 is the network itself
		- 255 is for broadcast
		- the first octet 127 is reserved for loopback address
			- 127.0.0.1
			- used to self diagnosis network interface
	- *Network Number* represents an orgs network
		- assigned by external org, like *ICANN(Internet Corporation for Assigned Names and Numbers)* 
	- *Host* is the network interface
	- *Subnets* ease network administration
		- *Subnet Masks* are used to define the part of the address used for the subnet
			- usually converted to decimal, i.e. 255.255.255.0
- was subdivided into public and private IPs 
	- *private* address can be shared by anyone
	- IP address groups mean SOHO and other situations can use 192.168.2.xxx for their networks safely
	- usable Private IPs
		- 10.0.0.0 to 10.225.225.224
		- 172.16.0.0 to 172.31.255.254
		- 192.168.0.0 to 192.168.255.254
#### IPv6
- 128-bit address
- modernization of IPv4
- *IPSEC* is optional for IPv4 but mandated for IPv6
- formatting:
	- shown as 8 groups of 4 digits
	- uses hexadecimal 0000-ffff
	- separated by colons not periods
- example:
	- 2001:0db8:0000:0000:0000:ffff:0000:0001.
	- can be shorted by 
		- 2001:db8::ffff:0:1
	- ::1 is the loopback address
	- 2001:db8:: to 2001:db8:ffff:ffff:ffff:ffff:ffff:ffff
		- reserved for documentation use
	- fc00:: to fdff:ffff:ffff:ffff:ffff:ffff:ffff:ffff
		- reserved for internal addresses, not routable on the internet
 
## See also
- [Network Security](net-sec-index.md)