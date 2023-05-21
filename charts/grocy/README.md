# grocy

> A Helm chart for Kubernetes

* <https://github.com/sarab97/helm-charts>
* <https://github.com/grocy/grocy>

## Usage

Helm must be installed and setup to your kubernetes cluster to use the charts. Refer to Helm's [documentation](https://helm.sh/docs) to get started. Once Helm has been set up correctly, add the repo as follows:

```sh
helm repo add sarab97 https://charts.sarabsingh.com
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.

To install this chart simply run the following command:

```sh
helm install grocy sarab97/grocy
```

To uninstall this chart simply run the following command:

```sh
helm delete grocy
```
