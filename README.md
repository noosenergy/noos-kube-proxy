[![CircleCI](https://circleci.com/gh/noosenergy/noos-kube-proxy.svg?style=svg&circle-token=798a263cee229742a5a286732ff613c17d16e175)](https://circleci.com/gh/noosenergy/noos-kube-proxy)

# Noos Kube Proxy
Reverse proxy boilerplate for the Noos platform.

This project regroups quite a few ideas gathered along blogs, threads, repositories and other documentations. To give back to the community, Noos Energy open-sourced the deployment of such a service to help other developpers to jump-start building their cloud-native infrastructure.

## Quickstart

### Kubernetes and Helm installation

On Mac OSX, make sure [Homebrew](https://brew.sh/) has been pre-configured, then install Kubernetes and Helm CLI,

    $ brew install awscli kubectl helm

### Local development

The development workflows of this project can be managed by [noos-invoke](https://github.com/noosenergy/noos-invoke), a ready-made CLI for common CI/CD tasks.

```
$ noosinv
Usage: noosinv [--core-opts] <subcommand> [--subcommand-opts]

...

Subcommands:
  helm.lint          Check compliance of Helm charts / values.
  helm.test          Test local deployment in Minikube.
  local.dotenv       Create local dotenv file.
```
