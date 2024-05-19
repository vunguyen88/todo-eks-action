# todo-eks-action (AWS EKS Deployment)

This repository contains YAML template files for Kubernetes deployments for 4 current services (client-web, auth-server, todo-server, ingress).
The main pipeline in Github Actions used after AWS EKS infra completed it deployment and config.
The pipeline will start first with setup Kube config using AWS access key and secret key, then deploy the Ingress service and other services.
