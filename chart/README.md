# Elasticsearch Helm Chart

- elasticsearch · helm/elastic (https://artifacthub.io/packages/helm/elastic/elasticsearch)

## Get Repo Info

```console
$ helm repo add elastic https://helm.elastic.co
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `elasticsearch`:

```console
$ helm install elasticsearch --version <version> elastic/elasticsearch -f values.yaml
```

## Uninstalling the Chart

To uninstall/delete the elasticsearch deployment:

```console
$ helm delete elasticsearch
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
