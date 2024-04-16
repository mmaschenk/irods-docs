---
title: using icommands
nav_order: 3
layout: default
---
## Connecting to iRODS through icommands

### Creating your iRODS environment file

```json
{
"irods_client_server_negotiation": "request_server_negotiation",
"irods_encryption_algorithm": "AES-256-CBC",
"irods_encryption_key_size": 32,
"irods_encryption_num_hash_rounds": 16,
"irods_encryption_salt_size": 8,
"irods_port": 1247,
"irods_host": "irods.tudelft.nl",
"irods_zone_name": "tud"
}
```

### Running iinit 