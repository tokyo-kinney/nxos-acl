# nxos-acl
Manage ACL on Cisco NXos 9000 switches

To check proper parsing by the module ranges were added as ACL definition.

```
  40 permit tcp 1.2.3.10/32 range 7937 9936 1.2.3.0/24 established
  50 permit tcp 1.2.3.20/32 range 7937 9936 1.2.4.0/26
```

Please always start by editing the nxos-cisco-9k-template file to use your own ACLs.
