# GitOps-Config-Portfolio

This repository contains the GitOps configuration files for managing the deployment of applications using Argo CD. It follows a minimalist approach to efficiently run a set of applications in a specific order using Helm charts. The configuration also includes monitoring and logging components.

## Infrastructure
The infra folder in this repository contains all the necessary configuration files for the infrastructure components managed by Argo CD. These files define the desired state of your infrastructure and allow for automatic synchronization and deployment.

## Applications

The `apps_of_app.yaml` file serves as an entry point for managing multiple applications using Argo CD. It defines the order in which the applications should be deployed and provides a consolidated view of the deployment pipeline.

Each application is defined as a Helm chart and is represented as a separate entry within the `apps_of_app.yaml` file. This approach allows for modularity and easy management of individual applications. You can customize each application's deployment parameters and dependencies as needed.
