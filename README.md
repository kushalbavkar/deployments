# Application deployments

Project containing deployment descriptors (manifest) files for application deployments.

Mostly using **Helm** as package manager to deploy application in local Kubernetes cluster.

## Installation

     $ helm install {release.name} {chart.directory}

## Future implementation 

#### Plan is to use `ArgoCD` to automated deployments to K8s cluster
