# Volcano Community Kubernetes Helm Charts

The code is provided as-is with no warranties.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add volcano-sh https://volcano-sh.github.io/helm-charts
```

You can then run `helm search repo volcano-sh` to see the charts.


**Install Volcano:**
```
helm install volcano volcano-sh/volcano -n volcano-system --create-namespace
```

**Uninstall Volcano:**
```
helm uninstall volcano -n volcano-system
```