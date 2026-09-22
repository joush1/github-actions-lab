# github-actions-lab

[![Terraform CI/CD](https://github.com/joush1/github-actions-lab/actions/workflows/terraform.yml/badge.svg)](https://github.com/joush1/github-actions-lab/actions/workflows/terraform.yml)

This repository demonstrates GitHub Actions automation for Terraform deployments.

## Workflow

- **On Pull Request**: Runs format, validate, and plan
- **On Push to Main**: Runs format, validate, plan, and apply

## Resources Created

- S3 Bucket with versioning enabled