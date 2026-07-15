2026-07-15 13:25
Status: #InProgress 

# Notes
## OWASP Security Principles
- Open Web Application Security Project
### Main Principles
#### Minimize the Attack Surface
- *Attack Surface* is the potential vulnerabilities an attacker could exploit
- *Attack Vectors* are pathways attackers use to penetrate defenses
##### Common Examples of Attack Vectors
- weak passwords
- phishing emails
- to minimize; disable software features, restrict access to certain assets, have more complex password requirements
#### Principle of Least Privilege
- minimize damage of a breach if an account is compromised by limiting the reach of accounts to what is necessary
- also helps to limit insider threats 
#### Defense-in-Depth
- an org should have multiple controls to address threats in different ways
#### Separation of Duties
- no one should be given so many privileges where they can abuse the system
#### Keep Security Simple
- complex security controls are harder to follow so avoid unnecessary complications
#### Fix Security Issues Correctly
- analyze root cause and apply the solution
### Additional Principles
#### Establish Secure Defaults
- it should take work to make an application insecure, secure by default
#### Fail Secure
- when a service fails it should default to most secure option, fail close not fail open
#### Don't Trust Services
- third party vendors have different standards than your org so you should not blindly assume they are secure
#### Avoid Security through Obscurity
- security should not stem from secrecy but though solidity of the methods implemented 

## See also
- [Security Frameworks and Controls](0-security-frameworks-&-controls-index.md)
- [GCPC](../../0-gcpc-index.md)