---
page_title: "cloudflare_web3_hostname Resource - Cloudflare"
subcategory: ""
description: |-
  Manages Web3 hostnames for IPFS and Ethereum gateways.
---

# cloudflare_web3_hostname (Resource)

Manages Web3 hostnames for IPFS and Ethereum gateways.


<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String) The hostname that will point to the target gateway via CNAME.
- `target` (String) Target gateway of the hostname.
- `zone_id` (String) The zone identifier to target for the resource.

### Optional

- `description` (String) An optional description of the hostname.
- `dnslink` (String) DNSLink value used if the target is ipfs.

### Read-Only

- `created_on` (String) Creation time.
- `id` (String) The ID of this resource.
- `modified_on` (String) Last modification time.
- `status` (String) Status of the hostname's activation.

