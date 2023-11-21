<!--- For help refer to https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.20.md?plain=1 as example --->

- [v1.28.0](#v1280)
  - [Synced with which upstream CA](#synced-with-which-upstream-ca)
  - [Changes made](#changes-made)
    - [During merging](#during-merging)
    - [During vendoring k8s](#during-vendoring-k8s)
    - [Others](#others)


# v1.28.0


## Synced with which upstream CA

[v1.28.0](https://github.com/kubernetes/autoscaler/tree/cluster-autoscaler-1.28.0/cluster-autoscaler)

## Changes made
 - See general release notes of 1.28.0: https://github.com/kubernetes/autoscaler/releases/tag/cluster-autoscaler-1.28.0

### During merging
  - Log message for the `scale up not possible case` was updated and an integration test that depended on it was updated

### During vendoring k8s
- mcm v0.50.0 -> 0.50.1
- mcm-provider-aws v0.17.0 -> v0.19.2
- mcm-provider-azure v0.10.0 -> v0.11.1

### Others
- [Release matrix](../README.md#releases-gardenerautoscaler) of Gardener Autoscaler updated.