[![CircleCI](https://circleci.com/gh/0hlov3/helm-charts/tree/main.svg?style=svg)](https://circleci.com/gh/0hlov3/helm-charts/tree/main)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/maxxblow)](https://artifacthub.io/packages/search?repo=maxxblow)
[![Release Charts](https://github.com/Maxxblow/charts/actions/workflows/release.yml/badge.svg)](https://github.com/Maxxblow/charts/actions/workflows/release.yml)
[![pages-build-deployment](https://github.com/Maxxblow/charts/actions/workflows/pages/pages-build-deployment/badge.svg?branch=main)](https://github.com/Maxxblow/charts/actions/workflows/pages/pages-build-deployment)
# Helm Charts
Find your favorite application and launch it. :)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```shell
  helm repo add maxxblow https://maxxblow.de/charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
maxxblow` to see the charts.

To install the <chart-name> chart:

```shell
  helm install my-<chart-name> <alias>/<chart-name>
```

To uninstall the chart:
```shell
  helm delete my-<chart-name>
```

## Need Help?
 - [#charts:matrix.fedi.tech @ Synapse](https://matrix.to/#/#charts:matrix.fedi.tech)

## Want to Contribute?
 - [#charts-development:matrix.fedi.tech](https://matrix.to/#/#charts-development:matrix.fedi.tech)