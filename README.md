# Kubernetes in Docker in Karrybit

## Clusters

### Create

```sh
task cluster-create-dev
task cluster-create-stg
task cluster-create-prod
```

| env | port |
| ---- | ---- |
| dev | 32080, 32443 |
| stg | 32081, 32444 |
| prod | 32082, 32445 |

Open `localhost:32080/echo` in chrome.

### Delete

```sh
task cluster-delete-dev
task cluster-delete-stg
task cluster-delete-prod
```

## Context

### Use

```sh
task use-context-dev
task use-context-stg
task use-context-prod
```

### Show

```sh
task context
```
