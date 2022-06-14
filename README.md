# gitops-ps

This repository provides overlays for [the Pipeline Service](https://github.com/openshift-pipelines/pipelines-service)

It also includes the Pipelines as Code flows, which are leveraged for automating the provisioning of changes.

The kustomize approach taken here is to use remote bases. The [upstream gitops directory](https://github.com/openshift-pipelines/pipelines-service/tree/main/gitops) contains the base files.
