2026-05-03 17:01
Status: #InProgress

## Notes
### CIA Triad
#### Confidentiality 
- is ensuring only authorized and authenticated users have access to information, while protecting it from improper disclosure
##### PII(Personally Identifiable Information)
- any data about an individual that can be used to identify them
##### PHI(Protected Health Information)
- info regarding ones health, classified or sensitive information
##### Sensitivity
- measure of importance assigned to info by the owner
#### Integrity
- is ensuring data/systems consistency, accuracy and completeness for a stated purpose
##### Data Integrity
- assurance data has not been altered unauthorized 
##### System Integrity
- maintenance of known good config
- ensuring requires awareness of the *State*
	- current condition of the system
- *baseline* is the State at a certain point in time 
#### Accessibility 
- is ensuring the access to data/systems when users need them 
- associated with *Criticality*
##### Criticality 
- importance an org assigns to data 
### Authentication
- Process of verifying or proving a user's identity
- needed to ensure confidentiality so you know someone is who they say they are
- also ensures *non-repudiation* is possible because if there is proof someone is who they are, they cannot claim that they did not do something
##### Common methods of Authentication
- *Something you know*, passwords or passcodes
- *Something you have*, access cards or badges
- *Something you are*, biometrics like; retina, finger, and palm scanners
###### Types of Authentication
- *SFA(single-factor authentication)*, one method of authentication
- *MFA(multi-factor authentication)*, multiple methods of authentication
##### Common examples of Authentication
- ATMS require;
	- Your Card, *Something you have*
	- Your PIN, *Something you know
- Synchronous tokens: one-time passwords that change periodically (30-60 seconds) RSA SecurID and authenticator apps
### Non-repudiation
- inability to deny taking an action
- ensure responsibility for one's decisions
- rely on the authentication of one's identity

## See also
- [Security Principles](sec-principles-index.md)
- [Comparisons](comparisons/index.md)