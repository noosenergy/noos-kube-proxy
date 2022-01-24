[![CircleCI](https://circleci.com/gh/noosenergy/neptune-kube-proxy.svg?style=svg&circle-token=798a263cee229742a5a286732ff613c17d16e175)](https://circleci.com/gh/noosenergy/neptune-kube-proxy)

# Neptune Kube Proxy
Neptune reverse proxy boilerplate.

## Quickstart

### Kubernetes and Helm installation

On Mac OSX, make sure [Homebrew](https://brew.sh/) has been pre-configured, then install Kubernetes and Helm CLI,

    $ brew install awscli kubectl helm

### Local development

The development workflows of this project can be managed by [noos-invoke](https://github.com/noosenergy/noos-invoke), a ready-made CLI for common CI/CD tasks.

```
$ noosinv
Usage: noosinv [--core-opts] <subcommand> [--subcommand-opts] ...
```
