2026-05-14 10:02
Status: #InProgress

## Notes
### RBAC(Role-Based Access Control)
- works best in a high turnover environment
- *privilege creep/permissions creep* a role is temporarily expanded in it's access and then is not returned to what it should be so anyone in the future coming into that role now also has the expanded access
### MAC(Mandatory)
- access is determined by a central authority, enforced based on classifications or security labels, data owners/individuals cannot edit these permissions
- main difference from *DAC* is that with DAC it is up to the object owners discretion, where with MAC it is up to sec admins
### DAC
- object owners define permissions, common in operating systems
- not very scalable
## See also
- [Access Controls](index.md)
- [Comparisons](comparisons/index.md)