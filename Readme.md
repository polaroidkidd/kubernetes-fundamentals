# Accompanying exercises for the Kubernetes Fundamentals course

[![Gitpod open-workspace](https://img.shields.io/badge/Gitpod-ready--to--code-908a85?logo=gitpod)](https://gitpod.io/#https://github.com/MMerzinger/kubernetes-fundamentals)

This repository contains the accompanying practice tasks for the Kubernetes Fundamentals course. 

To follow along the practice tasks, please make sure to setup `kubectl` as explained in the initial mail using one of those two options:
1. Install `kubectl` locally using the [docs](https://kubernetes.io/docs/tasks/tools/)
2. Register and start [Gitpod](https://gitpod.io/#https://github.com/MMerzinger/kubernetes-fundamentals)

## A note about PowerShell

Commands found in this repo were tested with PowerShell Core. You may have PowerShell Version 5 installed locally, which you can check with `$PSVersionTable`. In this case some commands, especially `curl`/`Invoke-WebRequest` behave quite different than `bash` or PowerShell Core. You may need to use wrapper such as `(Invoke-WebRequest <URL>).Content`.

## Structure

The following output of `tree -L 2` shows the folder structure of this repo:

```bash
.
├── Cheatsheet.md
├── LICENSE
├── Readme.md
├── demos
│   ├── apps
│   ├── helm
│   └── ingress
├── examples
│   ├── cicd
│   ├── config
│   ├── daemonsets
│   ├── deployments
│   ├── docker
│   ├── hpa
│   ├── kustomize
│   ├── namespaces
│   ├── network
│   ├── networkpolicies
│   ├── pods
│   ├── psp
│   ├── rbac
│   ├── scc
│   ├── serviceaccounts
│   ├── statefulsets
│   ├── storageclasses
│   └── vpa
└── practice
    ├── 01-pods
    ├── 02-pods2
    ├── 03-replicasets
    ├── 04-deployments
    ├── 05-hpa
    ├── 06-configuration
    ├── 07-storage
    ├── 08-serviceaccounts
    ├── 09-network
    ├── 10-networkpolicies
    ├── 11-scheduling
    ├── 12-ingress
    ├── 12-namespaces
    ├── challenges
    └── k8s-kustomize

```

## License

MIT: https://marcm.mit-license.org
