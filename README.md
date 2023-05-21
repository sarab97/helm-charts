# helm-charts
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/sarab97)](https://artifacthub.io/packages/search?repo=sarab97)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/sarab97/helm-charts/release.yml)
![GitHub](https://img.shields.io/github/license/sarab97/helm-charts)

## Charts
- [ntfy](https://github.com/sarab97/helm-charts/tree/main/charts/ntfy)
- [uptime-kuma](https://github.com/sarab97/helm-charts/tree/main/charts/uptime-kuma)
- [searx-ng](https://github.com/sarab97/helm-charts/tree/main/charts/searx-ng)
- [grocy](https://github.com/sarab97/helm-charts/tree/main/charts/grocy)


## Usage

Helm must be installed and setup to your kubernetes cluster to use the charts. Refer to Helm's [documentation](https://helm.sh/docs) to get started. Once Helm has been set up correctly, add the repo as follows:

```sh
helm repo add sarab97 https://charts.sarabsingh.com
```

If you had already added this repo earlier you might wanna update repo to get latest packages.

```sh
helm repo update
```

You can install a chart release using the following command:

```sh
helm install <release> sarab97/<chart> --values values.yaml
```

To uninstall a chart release use `helm`'s delete command:

```sh
helm uninstall <chart>
```
