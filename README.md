# circle-windows-package-tracker

Track packages installed on CircleCI's Windows executors. Updated every hour.

See [`config.yml`](.circleci/config.yml) to learn how it works.

## Served files

### diff

Diff of installed applications/packages between `stable` and `previous`

* [Managed applications](dist/diff-managed-previous-stable.txt)
* [Chocolatey packages](dist/diff-chocolatey-previous-stable.txt)
* [Uninstallers](dist/diff-uninstallers-previous-stable.txt)

Diff of installed applications/packages between `stable` and `edge`

* [Managed applications](dist/diff-managed-stable-edge.txt)
* [Chocolatey packages](dist/diff-chocolatey-stable-edge.txt)
* [Uninstallers](dist/diff-uninstallers-stable-edge.txt)

### Managed

Applications intentionally installed by CircleCI

* [`stable`](dist/managed-stable.md)
* [`previous`](dist/managed-previous.md)
* [`edge`](dist/managed-edge.md)

### Chocolatey

Packages installed with Chocolatey

* [`stable`](dist/chocolatey-stable.txt)
* [`previous`](dist/chocolatey-previous.txt)
* [`edge`](dist/chocolatey-edge.txt)

### Uninstallers

Applications having an uninstaller recognized by Windows

* [`stable`](dist/uninstallers-stable.txt)
* [`previous`](dist/uninstallers-previous.txt)
* [`edge`](dist/uninstallers-edge.txt)
