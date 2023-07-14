# flux-gitrepo

## Description
kpt package for provisioning a flux gitrepo

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] flux-gitrepo`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree flux-gitrepo`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init flux-gitrepo
kpt live apply flux-gitrepo --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
