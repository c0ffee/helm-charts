# Deployment example using Helm

### Prerequisites

Makre sure the Helm repository is installed as follows:

```console
helm repo add c0ffee https://c0ffee.github.io/helm-charts
helm repo update
```

### Deployment

In order to deploy the manifest for this example, issue the
following command:

```console
helm install vaultwarden c0ffee/app-template --namespace default --values values.yaml
```

This will apply the rendered manifest(s) to your cluster.
