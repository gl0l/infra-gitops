# joomla-infra

Welcome to the Core GitOps Infrastructure Control Plane.

## Overview
This repository manages our platform topology, environment allocations, and access keys via declarative Infrastructure-as-Code.

### Automated Actions
- **Pull Requests**: Automatically triggers `terraform plan`.
- **Main Branch Merges**: Automatically executes `terraform apply -auto-approve`.
