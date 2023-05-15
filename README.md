# GKE Gitlab Runner

## Setup
См. https://docs.gitlab.com/charts/charts/gitlab/gitlab-runner/

## Add-ons
```
kubectl apply -f add-ons/cleanup.yml
kubectl apply -f add-ons/trusted-ca.yml
kubectl apply -f add-ons/node-custom-setup.yml
```
