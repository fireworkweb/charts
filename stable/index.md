# fireworkweb charts

## Prerequisites

Add Repository

```bash
$ helm repo add fireworkweb https://fireworkweb.github.io/charts/stable
```

You can update the chart repository by running:

```bash
$ helm repo update
```

## Deploy Laravel

### Deploy with default config

```bash
$ helm upgrade --install app fireworkweb/loki-stack
```
