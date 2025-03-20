# Terraform Controller Helm Chart

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square)

## Overview

The Terraform Controller Helm chart deploys the Terraform Controller, enabling GitOps-style management of Terraform resources within a Kubernetes cluster. This controller integrates with tools like Flux to manage infrastructure as code.

## Prerequisites

- Kubernetes 1.16+
- Helm 3.0+
- [Flux](https://fluxcd.io/) installed and configured (optional, for GitOps integration)

## Installation

To install the chart with the release name `terraform-controller`:

```bash
helm repo add my-repo https://my-repo-url/charts
helm install terraform-controller my-repo/terraform-controller
