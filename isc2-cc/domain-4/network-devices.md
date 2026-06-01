2026-05-14 16:10
Status: #InProgress

## Notes
### Hubs
- connect multiple devices, more likely home networks, not smart and wired
- operate at layer 1 of the OSI model
### Switch
- "intelligent hubs", wired devices that "know" the addresses of the connected devices, routes the traffic to that port/device rather than retransmitting to all devices
- operate at layer 2 of the OSI model
- better efficiency over a hub, not as smart as a router, can create vlans and separate broadcast domains
### Router
- control network traffic flow, used to connect similar networks, can be wired or wireless, can connect multiple switches
- operate at layer 3 of the OSI model
- smarter than both hubs and switches
### Firewall
- filters traffic, deployed between private network and the internet, but can be deployed between internal networks (segmentation)
- firewalls monitor/filter net traffic based on predefined rules (like ACLs), they don't encrypt traffic, assign IP addresses (that's DHCP) or resolve domain names (DNS)
#### NGFW (Next Generation Firewalls)
- include deep packet inspection, intrusion prevention, application level control, and threat intelligence, they can block threats via signatures and behavioral analysis
### Server
- Computer that provides info, resources, or data to other computers 
- secured differently than typical endpoints
### Endpoint
- the ends of a network comm link, server is at one end, and client is one end
## See also
- [Network Security](net-sec-index.md)
- [Networking](networking.md)
- [Networking Models](net-models.md)