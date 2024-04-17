# edge1

## Description


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] edge1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree edge1`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init edge1
kpt live apply edge1 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
