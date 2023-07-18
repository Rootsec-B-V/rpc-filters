# RPC Filters

RPC Filters to prevent Coercion attacks

- **MS-RPRN.txt**: PrinterBug
- **MS-EFSR.txt**: PetitPotam
- **MS-FSRVP.txt**: ShadowCoerce
- **MS-DFSNM.txt**: DFSCoerce
- **ALL.txt**: MS-RPRN, MS-EFSR, MS-FSRVP, and MS-DFSNM combined

To use the RPC-filters use the netsh utility like so:
```
netsh -f filter.txt
```
