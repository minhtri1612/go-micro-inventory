# go-micro-inventory

Split from monorepo go-micro (inventory-service/). Original go-micro folder is left untouched.

## Build

```bash
go test ./...
docker build -t minhtri1612/inventory-service:dev .
```

## CI

Thin Jenkinsfile -> Shared Library go-micro-ci (repo go-micro-pipeline-lib).