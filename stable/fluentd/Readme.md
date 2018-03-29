# Fluentd Helm Chart

This directory contains a Kubernetes chart to deploy a [Fluentd](https://www.fluentd.org/) Open-Source Log Collector


## TL;DR;

```console
$ helm install incubator/fluentd
```

## Introduction

This chart bootstraps a [Fluentd](https://www.fluentd.org/) on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

## Prerequisites

- Kubernetes 1.4+ with Beta APIs enabled

## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm install --name my-release incubator/fluentd
```

The command deploys Fluentd on the Kubernetes cluster in the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration
...

Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`. For example,

```console
$ helm install --name my-release \
    incubator/fluentd
```

Alternatively, a YAML file that specifies the values for the above parameters can be provided while installing the chart. For example,

```console
$ helm install --name my-release -f values.yaml incubator/fluentd
```
