# Fraunhofer IOSB Helm charts snapshot repository

This repository contains snapshot builds, which are generated automatically.
*DO NOT USE THIS FOR PRODUCTION*
The production ready version can be found in [this](https://fraunhoferiosb.github.io/helm-charts/) repository.

## Content
This repository contains the snapshot versions of Helm charts maintained by Fraunhofer IOSB

## How to use it

To add the Fraunhofer IOSB Helm charts snapshot repository execute:

```
$ helm repo add fraunhoferiosbsnapshots https://fraunhoferiosb.github.io/helm-charts-snapshots
```

Then calling:
```
$ helm repo list
```
should display the Fraunhofer IOSB Helm charts repository entry:
```
fraunhoferiosbsnapshots    https://fraunhoferiosb.github.io/helm-charts-snapshots
```
