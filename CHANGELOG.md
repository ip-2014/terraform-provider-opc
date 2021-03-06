## 0.1.3 (Unreleased)

FEATURES: 

* **New Resource:** `opc_storage_object` [GH-55]

BUG FIXES: 

* r/ip_network: Allow changing the name of an IP Network [GH-73]
* r/opc_compute_image_list_entry: Fix resource imports [GH-66]
* r/storage_container: Fixed `allowed_origins` [GH-62]
* r/storage_volume: Allow errors to surface from Create [GH-69]
* r/vnic_set: Make `virtual_nics` Computed [#52](https://github.com/terraform-providers/terraform-provider-opc/issues/52)

NOTES: 

* Various doc fixes/updates

## 0.1.2 (August 02, 2017)

FEATURES:

 * **New Datasource:** `opc_compute_image_list_entry` ([#50](https://github.com/terraform-providers/terraform-provider-opc/issues/50))
 * **New Datasource:** `opc_compute_storage_volume_snapshot` ([#46](https://github.com/terraform-providers/terraform-provider-opc/issues/46))
 * **New Resource:** `opc_compute_storage_container` ([#23](https://github.com/terraform-providers/terraform-provider-opc/issues/23))
 * Add timeout configuration: ([#41](https://github.com/terraform-providers/terraform-provider-opc/issues/41))
  
BUG FIXES:
 * `opc_storage_volume_snapshot`: Fix crash on import ([#10](https://github.com/terraform-providers/terraform-provider-opc/issues/10))
 * `opc_compute_storage_volume`: bootable volumes can be added without an image list/image list entry ([#19](https://github.com/terraform-providers/terraform-provider-opc/issues/19))
 * r/security_list: Suppress case diffs for security_list ([#27](https://github.com/terraform-providers/terraform-provider-opc/issues/27))

## 0.1.1 (June 21, 2017)

NOTES:

* Bumping the provider version to get around provider caching issues - still same functionality 

## 0.1.0 (June 20, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
