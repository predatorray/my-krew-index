# my-krew-index

This repository is a self-hosted [custom krew index](https://krew.sigs.k8s.io/docs/developer-guide/custom-indexes/).

## Usage

To add the index,

```sh
kubectl krew index add predatorray https://github.com/predatorray/my-krew-index.git
```

To install a plugin,

```sh
# Replace `$PLUGIN_NAME` with one of the plugin name in the table below
kubectl krew install predatorray/$PLUGIN_NAME
```

## Plugins

Here is the list of the plugins hosted in the index.

Name                                                  | Description                            | Stars
------------------------------------------------------| -------------------------------------- | -----
[alias](https://github.com/predatorray/kubectl-alias) | The missing alias command for kubectl. | ![GitHub stars](https://img.shields.io/github/stars/predatorray/kubectl-alias.svg?label=stars&logo=github)