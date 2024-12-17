# HOMELAB 

Welcome to my **HOMELAB**. This project aims to simplify the management and automation of deployment on a **Kubernetes Cluster** hosted in a **Proxmox VE** environnement. 
Application orchestration is achieved using **ArgoCD**, a powerfull **GitOps** tool that anables continuoes deployment form versioned, declarative manifest stored in a Git repository. 

## Architecture 

The following components make up the HOMELAB:
- [Proxmox VE](https://www.proxmox.com/en/): Hypervisor for hosting virtual machines and managing resources.
- [Kairos K3s](https://kairos.io/): Kairos is an open-source project that provides a framework for creating immutable, cloud-native Linux operating systems. It is designed to simplify the deployment and management of lightweight operating systems for Kubernetes clusters, edge devices, and virtualized environments.
- [ArgoCD](https://argo-cd.readthedocs.io/en/stable/): GitOps continuous deployment tool for automating and managing Kubernetes manifests.
- [Terraform](https://registry.terraform.io/providers/bpg/proxmox/latest) Provider=bpg/proxmox : Infrastructure as Code (IaC) for provisioning Proxmox virtual machines.
