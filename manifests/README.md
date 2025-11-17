# ArgoCD Demo Application

This repository acts as the **source of truth** for a demo application deployed through **ArgoCD** on **GKE**.

## Structure
- manifests/
  - deployment.yaml
  - service.yaml
  - kustomization.yaml

ArgoCD continuously syncs the cluster state from this repository.
