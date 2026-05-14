2026-05-14 10:02
Status: #InProgress

## Notes
### Authorized vs unauthorized personnel
- authorization is usually done through a security matrix
### 3 Core Elements of Access
#### Subjects 
- defined as any entity that requests access to assets 
	- what ever initiates a request
	- is active
#### Objects
- defined as anything a subject attempts to access
	- what ever responds to the request
	- do not contain their own access control logic, need an external layer of functionality
	- is passive
#### Rules
- Access rules are an instruction to allow/deny access to an object by comparing the validated identity of the subject to an access control list 
	- i.e. ACL
	- (Access control list)
### Defense in Depth (Layered Defense)
- information security strategy that integrates people, tech, operations to establish multiple barriers across multiple layers and missions of an org
	- i.e. MFA
### Privileged Access Management
- key feature of just in time management is role-based subsets of privileges
### Privileged Accounts
- accounts that have elevated privileges 
	- sys admins
	- helpdesk/IT support staff
	- Security analysts
#### Typical measures for moderating the risk for PAs  
- should have more detailed logging than regular users
- more stringent Access control than normal users i.e. MFA
- deeper verification i.e. background checks
- more auditing than regular accounts
### Separation of Duties
#### Two-Person Integrity
- minimum of two people must be in an area together, not allowing one person to be in an area alone

## See also
- [Access Controls](access-control-index.md)
- [Comparisons](comparisons/index.md)