2026-05-14 10:02
Status: #InProgress

## Notes
### RBAC(Role-Based)
- works best in a high turnover environment
- *privilege creep/permissions creep* a role is temporarily expanded in it's access and then is not returned to what it should be so anyone in the future coming into that role now also has the expanded access
### Rule-Based 
- conditions and rules govern access
- applied universally not based on roles like RBAC
### MAC(Mandatory)
- access is determined by a central authority, enforced based on classifications or security labels, data owners/individuals cannot edit these permissions
- most restrictive
### DAC(Discretionary)
- object owners define permissions, common in operating systems
- not very scalable

## See also
- [Access Controls](access-control-index.md)
- [Comparisons](comparisons/index.md)