# Helm Chart for NetBox


[NetBox](https://netbox.readthedocs.io/) is an IP address management (IPAM) and data center infrastructure management (DCIM) tool.

**Updated guide to use, test, ref directly on Github**

## Description

This [Helm](https://helm.sh/docs/) chart is used to deploy `netbox` with a stable configuration to Kubernetes clusters.

## Prerequisites

- Kubernetes 1.25.0+ (a [current](https://kubernetes.io/releases/) version)
- Helm 3.10.0+ (a version [compatible](https://helm.sh/docs/topics/version_skew/) with your cluster)
- helm-git ([latest](https://github.com/aslafy-z/helm-git))

## Usage

Add the repository:

```shell
helm repo add netbox git+https://github.com/matroid/netbox-chart@charts/netbox?ref=develop
```

Refer to the detailed documentation [here](./charts/netbox/README.md).

## License

See [LICENSE](./LICENSE).

### Credits

https://github.com/bootc/netbox-chart#license