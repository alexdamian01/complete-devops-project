# Complete DevOps Project

An end-to-end DevOps project built around a simple Flask application that displays the current time. The goal was to practice automating the build, deployment, and delivery process using common DevOps tools.

## How it works

- GitHub Actions builds a Docker image when changes are pushed to `main`.
- The image is pushed to Docker Hub with a tag based on the commit SHA.
- Terraform is used to manage the Kubernetes environment.
- Helm manages the application deployment, while Argo CD handles continuous delivery and keeps the cluster in sync with the Git repository.

## Tech stack

Python, Flask, Docker, GitHub Actions, Terraform, Kubernetes, Helm, Argo CD, and Minikube.

## What I learned

Building a CI/CD pipeline, containerizing an application, managing Kubernetes resources with Terraform, and using GitOps to automate application deployments.
