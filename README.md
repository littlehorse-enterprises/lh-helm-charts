# LH Helm Charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```
helm repo add littlehorse https://littlehorse-enterprises.github.io/lh-helm-charts/
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
littlehorse` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> littlehorse/<chart-name>

To uninstall the chart:

    helm delete my-<chart-name>