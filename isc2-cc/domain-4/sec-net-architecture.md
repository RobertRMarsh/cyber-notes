2026-05-14 19:20
Status: #InProgress

## Notes
### Microsegmentation
- toolset of adversaries are polymorphic in nature
- orgs that avoid infrastructure centric designs paradigms are more efficient at service delivery and preventing *APTs(Advanced Persistent Threats)*
- allows for granular user level access control
- uses logical rules not physical devices
- ultimate defense in depth end point, no single point of access can lead to broad compromise
- crucial in the cloud 
- maxed out least privilege
- used through virtualization/SDN(Software Defined Networking) also in the cloud VPNs or security groups
### Vlans 
- vlan hopping lets you overhear traffic from another vlan
- consolidate traffic across multiple ports
- NAC systems use VLANs to control whether devices connect to the corporate network or a guest network
### IDS(Intrusion Prevention System)
- *intrusion* an attacker thwarts security
- IDSs automate the inspection of logs and real-time system attempts and system failures
- NIDS do not replace firewalls, they work along side them, creating defense in depth
#### Types of IDS
##### HIDS(Host-based IDS)
- monitors single device, examines events more detailed than *NIDS* 
- can pinpoint affected files
- can detect anomalies on host that NIDS can't
- more expensive due to one per system needing to be monitored 
##### NIDS(Network-based IDS)
- centralized sec management
- cheaper than *HIDS* 
- evaluates whole network 
- broader but less in depth
- low performance impact
### SIEM
- Security Information and Event Management
- gathers log info from many sources
### Network Segmentation(DMZ)
- demilitarized zone
- host systems accessible through a firewall == separated by a secure switch/another firewall
- *Application DMZs* or *Semi-trusted networks* are used today
- *WAF(Web Application Firewalls)* monitor all traffic from outside before passing commands to web server
- interfaces directly with outside world and has more controls than rest of the outside work
### Preventing Threats
- keep systems/applications up to date
- use IDS/IPS systems
- Remove/disable unneeded services/protocols (bloat)
- use firewalls
- up-to-date antimalware software
- anti virus is strongly encouraged and required by *PCI DSS*
- Zenmap scans 
### Redundancy
- design systems with duplicate components in case one should fail
- in a scenario need full power redundancy two power supplies connected to diverse sources would be best
 
## See also
- [Network Security](net-sec-index.md)