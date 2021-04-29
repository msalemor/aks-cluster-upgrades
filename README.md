# AKS Cluster Upgrades

## Upgrading the cluster

- The steps for upgrading a cluster are outlined here:
  - https://docs.microsoft.com/en-us/azure/aks/upgrade-cluster

## What could go wrong during an upgrade

- Possible deprecation of APIs
- Assess what deprecated APIs are being used
- Using custom objects that may break after upgrade

## Recommendations

- Review the deprecation notes
- Don't assume the upgrade will work
- Test the upgrade


