2026-05-16 00:00
Status: #InProgress

## Notes
### Logs
- impose a computational cost but are invaluable for determining accountability
- proper design of logging environments + frequent log reviews are best practice
#### Relevant info in logs (not limited to these)
- User IDs
- System Activity
- Dates/Times
- Device and location ID
- Successful Logs and resource access attempts
- System config changes and system protection deactivation and activation events
#### Logging Practices
- Controls should be implemented to prevent logs from being altered 
	- maintains confidentiality and integrity of log data
- standards, regulations, policies and procedures govern how long logs should be kept as they could be evidence in an event
##### Event Logging Best Practices
- different tools will be used if it is an attack leaving the infrastructure or coming in
###### Ingress Monitoring
- Surveillance and assessment of all inbound comms traffic and access attempts
- tools for this include;
	- firewalls
	- gateways
	- Remote auth servers
	- IDS/IPS
	- SIEM Solutions
	- Anti-Malware Solutions
###### Egress Monitoring
- Used to regulate data leaving the org's IT environment
- *DLP(Data Loss Prevention)* is helping to ensure confidentiality and should inspect all data leaving org such as;
	- Email (contents/attachments)
	- Copies to Portable media (USB)
	- FTP(File Transfer Protocol)
	- Posting to Web Pages
	- API's(Application Programming Interface)
 
## See also
- [Security Operations](sec-ops-index.md)