# THIRD_PARTY_NOTICES

This repository is based on and includes code derived from third-party open source software.

## Included Third-Party Software

### 1. cert-manager-webhook-loopia
- Upstream project: Identitry/cert-manager-webhook-loopia
- Upstream repository: https://github.com/Identitry/cert-manager-webhook-loopia
- Copyright: Original authors and contributors
- License: Apache License 2.0

This repository is a fork and/or modified derivative of the upstream project.

### 2. loopia-go
- Upstream project: jonlil/loopia-go
- Upstream repository: https://github.com/jonlil/loopia-go
- Copyright: Original authors and contributors
- License: MIT License

Portions of this repository include or are derived from code from `loopia-go`, used to communicate with the Loopia XML-RPC API.

## Local Modifications

Service Well AB has made local modifications to support production use, including fixes related to Loopia DNS record creation behavior.

Known modifications include:
- adjustment to Loopia zone record serialization behavior for `addZoneRecord`
- integration of patched Loopia client code into this repository build process
- deployment and packaging changes for internal use

## License Notices

### Apache License 2.0 Notice
This product includes software developed by third parties and licensed under the Apache License, Version 2.0.

A copy of the Apache License 2.0 should be provided in this repository as `LICENSE` or otherwise made available with the source distribution.

### MIT License Notice
This product includes software developed by third parties and licensed under the MIT License.

The MIT License text for included or vendored components should be preserved in the relevant source directory or included in the repository distribution.

## No Endorsement

The names of the original projects, authors, or contributors must not be used to imply endorsement of this fork or its modifications without prior written permission.

## Internal Ownership

This fork and its modifications are maintained by Service Well AB for internal and production use.