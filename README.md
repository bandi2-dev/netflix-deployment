# Netflix Platform Deployment

## Overview

This repository contains all Kubernetes deployment assets for the Netflix Platform.

Infrastructure is managed separately using Terraform.

Application source code is managed in the netflix-app repository.

This repository is responsible for deploying workloads to Google Kubernetes Engine (GKE).

---

## Components

- Kubernetes Manifests
- Helm Charts
- Gateway API
- Horizontal Pod Autoscaler
- ConfigMaps
- Secrets
- Jenkins Pipeline
- Deployment Scripts

---

## Deployment Flow

GitHub

↓

Jenkins

↓

SonarQube

↓

Docker Build

↓

Artifact Registry

↓

Helm

↓

GKE

↓

Gateway API

↓

Netflix Platform

---

## Repository Structure

helm/

k8s/

scripts/

docs/

Jenkinsfile

README.md

---

## Status

- [ ] Namespaces
- [ ] Gateway API
- [ ] Helm Chart
- [ ] Jenkins Pipeline
- [ ] ConfigMaps
- [ ] Secrets
- [ ] HPA