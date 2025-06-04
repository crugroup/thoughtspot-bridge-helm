# ThoughtSpot Bridge Helm Chart

## Prerequisites

- [Helm](https://helm.sh/) 3.x installed
- Access to a Kubernetes cluster

## Installation

```sh
helm repo add thoughtspot-bridge <repository-url>
helm repo update
helm install thoughtspot-bridge thoughtspot-bridge/thoughtspot-bridge
```

## Upgrading

```sh
helm upgrade thoughtspot-bridge thoughtspot-bridge/thoughtspot-bridge
```

## Uninstallation

```sh
helm uninstall thoughtspot-bridge
```

## Customization

Override default values using a `values.yaml` file or `--set` flags:

```sh
helm install thoughtspot-bridge thoughtspot-bridge/thoughtspot-bridge -f values.yaml
```

Refer to `values.yaml` for configurable parameters.