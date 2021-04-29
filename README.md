# Deploy-ElasticSearch

A database used for telemetry data ingested by Jaeger and Logstash.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

- elasticsearch · helm/elastic (https://artifacthub.io/packages/helm/elastic/elasticsearch)

Once Helm is set up properly, add the repo as follows:

## Get Repo Info

```console
$ helm repo add elastic https://helm.elastic.co
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `elasticsearch`:

```console
$ helm install elasticsearch --version <version> elastic/elasticsearch -f chart/values.yaml
```

## Uninstalling the Chart

To uninstall/delete the elasticsearch deployment:

```console
$ helm delete elasticsearch
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
