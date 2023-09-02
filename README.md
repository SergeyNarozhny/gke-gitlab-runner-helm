# GKE Gitlab Runner

## Setup
См. https://docs.gitlab.com/charts/charts/gitlab/gitlab-runner/

## Install / upgrade helm chart
```
$ helm upgrade --install --namespace gitlab-runner gitlab-runner . --values values.yaml
```

## Add-ons
```
$ kubectl apply -f add-ons/cleanup.yml
$ kubectl apply -f add-ons/trusted-ca.yml
$ kubectl apply -f add-ons/node-custom-setup.yml
```
