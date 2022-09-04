# Kubernetes declarative approach

## Creating deployments:

`kubectl apply -f=deployment.yaml`

## Creating services:

`kubectl apply -f=service.yaml`

## Creating service and deployments using single file (master-deployment.yaml):

`kubectl apply -f=master-deployment.yaml`

## Deleting service and deployments:

`kubectl delete -f=deployment.yaml -f=service.yaml`
