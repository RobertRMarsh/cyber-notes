2026-05-14 16:22
Status: #InProgress

## Notes
## Networking Models
- they;
	- provide reliable, managed communications between hosts
	- isolate functions into layers
	- use packets as basis of comms
	- routing, addressing, and control are standardized
	- allow layers beyond internetworking for extra functionality
	- vendor agnostic 
### Layers
#### Application/Upper Layer
- manages integrity of connection, manages comms
- transforms data into a format any system can understand1
##### Application
##### Presentation
##### Session
#### Data Transport/Lower Layer
- responsible for receiving physical bits and converting them into frames
##### Transport 
##### Network
##### Data Link
##### Physical 
## TCP/IP
- commonly used by embedded systems when connected to a corporate network
- internet
### TCP/IP VS OSI
<table style="text-align: center;">  
  <thead>
    <tr>  
      <th style="text-align: center;">OSI</th>  
      <th style="text-align: center;">TCP Architecture</th>  
      <th colspan="4" style="text-align: center;">TCP/IP Suite</th>  
    </tr>  
  </thead>
  <tr>  
    <td style="text-align: center;">Application Layer</td>  
    <td rowspan="3" style="text-align: center;">Application Layer</td>  
    <td style="text-align: center;">FTP</td>
    <td style="text-align: center;">Telnet</td>
    <td style="text-align: center;">SNMP</td>
    <td style="text-align: center;">LPD</td>
  </tr>  
  <tr>  
    <td style="text-align: center;">Presentation Layer</td>  
    <td style="text-align: center;">TFTP</td>
    <td style="text-align: center;">SMTP</td> 
    <td style="text-align: center;">NFS</td> 
    <td style="text-align: center;">X Window</td> 
  </tr>  
  <tr>  
    <td style="text-align: center;">Session Layer</td>  
    <td style="text-align: center;">Mexico</td>  
  </tr>  
  <tr>  
    <td style="text-align: center;">Transport Layer</td>  
    <td style="text-align: center;">Transport Layer</td>  
    <td style="text-align: center;">TCP</td>  
  </tr>  
  <tr>  
    <td style="text-align: center;">Network Layer</td>  
    <td style="text-align: center;">Internet Layer</td>  
    <td style="text-align: center;">ICMP</td>  
  </tr>  
  <tr>  
    <td style="text-align: center;">Data Link Layer</td>  
    <td rowspan="2" style="text-align: center;">Network Interface Layer</td>  
    <td rowspan="2" style="text-align: center;">Ethernet</td> 
    <td rowspan="2" style="text-align: center;">Fast Ethernet</td> 
    <td rowspan="2" style="text-align: center;">Token Ring</td> 
    <td rowspan="2" style="text-align: center;">FDDI</td> 
  </tr>  
  <tr>  
     
  </tr>  
</table>

### TCP/IP Protocols
- *UDP* 
	- in the *transport layer*
	- simple connectionless protocol
	- faster
- *TCP*
	- in the *transport layer*
	- full duplex connected protocol
	- slower but more secure
- *ICMP (Internet Control Message Protocol)*
	- in the *internet/network layer*
	- determines network/connection health
	- used by ping, traceroute and other similar commands
		- ping uses ICMP echo packets
## OSI
- theorectical framework
- encapsulation is the adding of header, or trialer/footer to data
- At the physical layer data is transformed to binary and sent across a network
### Examples 
- photos are presentation layer
- logical ports are the session layer
- tcp/udp are transport layer
- routers are network layers
- switches are data link layer
### Encapsulation
- occurs moving down from application layer ==> Physical Layer
- each new layers payload is the result of the encapsulation of the last layer
- data unit increases in size as we move down and further instructions are added
### De-encapsulation
- occurs moving up from the Physical layer ==> application layer
- data decreases in size as it moves up
## IOT(Internet-Of-Things)
- embedded devices connected to each other that accomplish things irl
	- smart appliances
- segment off the network, many have security vulnerabilities/do not have up to date firmware
## Cloud Deployment Models
#### The 4 Models
##### Public
- easy access 
##### Private
- private org's own cloud
- org is responsible for all maintenance
- can rent resources from third party based on *service model*
##### Hybrid
- retain ownership of critical tasks
- have convenient access to public cloud for non critical functions
##### Community
- can be either public or private
- communist cloud
 
## See also
- [Network Security](net-sec-index.md)