# HashiCorp Sentinel Require Private Module Registry (PMR)

This repo provides 2 relevant files that define a Sentinel Policy that enforces Private Module Registry (PMR) usage.

- [enforce-private-module.sentinel](./enforce-private-module.sentinel) - referenced from [HashiCorp terraform-sentinel-policies repo: cloud-agnostic
/require-all-resources-from-pmr.sentinel](https://github.com/hashicorp/terraform-sentinel-policies/blob/main/cloud-agnostic/require-all-resources-from-pmr.sentinel)
- [sentinel.hcl](./sentinel.hcl) - defines the enforcement level for the policy set. You may change the enforcement level accordingly

Fork this repo and connect Sentinel's policy set to the forked repostory.
