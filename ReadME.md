# Cluster

This repo is to create a container cluster in using the gitOps method.

## Requirement
The major requirement is to have a gitOps method deployment. The config files for the cluster will leave in github and will be published in the cluster using the gitOps


### Local infrastructure
The cluster that will be deployed needs a space to live. That space will be provided by Kind.

### Installation
```brew install kind```


### Docs 
The docs for kinD is located at [DOCS](https://kind.sigs.k8s.io/docs/user/quick-start)

### Getting up and running
The cluster itself can be started by using the ```kind create cluster name``` command and also it can be used with a config file and used as ```kind create cluster --config kind-example-config.yaml```. To make it easier will be using the config options 