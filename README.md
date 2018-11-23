# Collection of [Helm](https://helm.sh/) charts for [KubeVirt](http://kubevirt.io/).

This repository contains following charts:
* Single vm - Deploys single virtual machine instance together with service exposing ssh port

# Usage

To run charts from this repo you can clone this repo and run helm:

```
git clone https://github.com/pkliczewski/charts
cd charts
helm install single-vm/
```

or use:

TODO: verify this when repo created

```
helm repo add kubevirt-charts https://github.com/pkliczewski/charts
helm install single-vm --repo kubevirt-charts
```