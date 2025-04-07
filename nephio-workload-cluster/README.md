# nephio-workload-cluster

## Description
nephio-workload-cluster description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nephio-workload-cluster`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nephio-workload-cluster`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nephio-workload-cluster
kpt live apply nephio-workload-cluster --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
