# App of Apps for ArgoCD

Argo CD App to reference to all other apps which has to be deployed, for easy central deployment with Git-Ops

## Installation

You need to have a ArgoCD Cluster up and running, than simple add this one file,
and if you dd new Apps in the folder ```local```they will also get deployed.

    kubectl apply -f apps.yml
