# Pinafore
Install the [Pinafore](https://github.com/nolanlawson/pinafore) web client for Mastodon & Gotosocial in Kubernetes.

## Prerequisites
 - Kubernetes 1.16+
 - Helm 3+

## Get Repo Info
``` shell
helm repo add maxxblow https://maxxblow.de/helm-charts/
helm repo update
```
_See [helm repo](https://helm.sh/docs/helm/helm_repo/) for command documentation._

## Install Chart
```shell
helm install [RELEASE_NAME] maxxblow/pinafore
```
_See [configuration](#configuration) below._
_See [helm install](https://helm.sh/docs/helm/helm_install/) for command documentation._

## Uninstall Chart
```shell
# Helm
helm uninstall [RELEASE_NAME]
```
This removes all the Kubernetes components associated with the chart and deletes the release.

_See [helm uninstall](https://helm.sh/docs/helm/helm_uninstall/) for command documentation._

## Upgrading Chart
```shell
# Helm
$ helm upgrade [RELEASE_NAME] maxxblow/pinafore
```
_See [helm upgrade](https://helm.sh/docs/helm/helm_upgrade/) for command documentation._

## Configuration
See [Customizing the Chart Before Installing](https://helm.sh/docs/intro/using_helm/#customizing-the-chart-before-installing). To see all configurable options:
```
helm show values maxxblow/pinafore
```