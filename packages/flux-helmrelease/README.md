# flux-helmrelease

## Description
kpt package for provisioning a flux helmrelease CR

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] flux-helmrelease`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree flux-helmrelease`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init flux-helmrelease
kpt live apply flux-helmrelease --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
