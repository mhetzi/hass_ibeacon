# iBeacon



Adds a whitelist to the iBeacon component. 
The whitelist allows devices without a name to be added.

To add a entry to the Whitelist call the ibeacon.whitelist_add service:

```
service: ibeacon.whitelist_add
data:
  uuid: 407b699a-ba14-4028-83a3-220f910c8fee
```

Whitelist does not get written to disk, because when the entities are created the name is no longer needed.
