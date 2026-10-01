# hde-pipelines
HDE Tekton pipeline definitions
# hde-pipelines

Tekton pipeline definitions for the Hybrid Development Environment (HDE) Phase 3.
Pipelines build and test on approved compute, run Trivy scans and secrets gates,
and produce immutable artifacts and evidence for Argo CD to deploy.

## Scope
Binary Bit Ops/Nexus remains the live PHP/MySQL application on Truehost cPanel.
This repository does not authorise a Kubernetes migration of that application.

## Rules
- Changes are made by pull request only.
- No secrets, tokens or credentials are committed here.
- Credentials are supplied at runtime by the managed secrets service.
