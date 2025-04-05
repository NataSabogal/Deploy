# Automated Deployment with GitHub

This repository contains the necessary files to automate the deployment of a backend on a remote server using GitHub Actions and SSH.

## Content
- `saludo.txt`: Welcome file.
- `deploy.yml`: YAML script to automate deployment.

## Basic Instructions
1. **Set Up SSH Access**:
   - Make sure to configure the public and private keys for passwordless access.
   - Add the private keys to the Secrets of the GitHub repository.
2. **Automate Deployment**:
   - The `deploy.yml` file sets up the workflow to automatically deploy the project.
   - Each time you push changes to the `main` branch, deployment will be executed.
