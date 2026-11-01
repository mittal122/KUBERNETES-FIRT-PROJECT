# Kubernetes Voting App

My first Kubernetes project: a multi-component voting app deployed with plain pod and service manifests.

## Components

All manifests are in `voting-app/`.

- **Voting app:** pod and service
- **Result app:** pod and service
- **Worker:** pod
- **Redis:** pod and service
- **PostgreSQL:** pod and service

## Deploy

```sh
kubectl apply -f voting-app/
kubectl get pods,svc
```
