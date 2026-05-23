2026-05-22 23:13
Status: #InProgress

## Notes
### Common Security Policies
- all policies should support laws, regulatory compliance, or contractual obligations of an org
#### Data Handling Policy
- data should be required to be handled differently based on who needs access to it, and if it can be made public or if it is classified or sensitive
- should spell out any restrictions or legal definitions around relevant regulations or laws
- data classification helps with ensuring compliance, i.e. classifying credit card data as confidential helps with adhering to *PCI DSS*
#### Password Policy
- defines expectations and commitment to secure access to systems/data
- should outline standards required around password formulation, changeover expectations, secure password storage, and who needs to enforce and validate the policy
#### AUP(Acceptable Use Policy)
- defines accepted use of org's systems and networks
- each employee/anyone accessing org systems and networks should be required to sign a copy
- commonly included: data/system access, data retention, data disclosure, passwords (also covered under a password policy, internet usage, company hardware usage
#### BYOD(Bring Your Own Device) Policy
- org allows employees to pick their own devices/ use personal devices for business use
- hardest from a security standpoint
- as it scales problems compound
#### Privacy Policy
- personnel may be able to access *PII(Personally Identifiable Information)* & *ePHI(electronic Protected Health Information)*
- personnel must follow policies and procedures when handling these to ensure regulatory compliance
- similar to an *AUP* but more narrow in scope 
- should list: what is considered PII/ePHI, proper handling of that information, any punitive measures or actions for a lack of compliance, and laws/regulations the org must follow
- org should have a public document with transparency around how information is used
##### Laws around this area
- *GDPR* from the EU defining Privacy as a human right
- *PIPEDA(Personal Information Protection and Electronic Documents Act)* from Canada
###### Laws Governing Industries
- *HIPPA* in Healthcare 
- *GLBA(Gramm-Leach-Bliley Act)*
#### Change Management Policy
- Discipline of transitioning to a future state from a current state
- defines a process to ensure changes made do not introduce issues or vulnerabilities to a system
 
## See also
[Security Operations](sec-ops-index.md)
[Change Management](change-mgmt.md)