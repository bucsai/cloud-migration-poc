# Cloud Migration PoC

This repository is a Proof-of-Concept demonstrating the use of Ansible to automate end-to-end migrations between on-premises infrastructure and different cloud providers.

## Target Architecture

The PoC environment mimics a hybrid migration scenario involving:
- **On-Premises Infrastructure:** Local VMs representing the source environment, running:
  - **Windows Server** instances hosting services like enterprise web applications.
  - **Linux** instances hosting databases and backend services.
- **Cloud Infrastructure:** Target environments where matching resources are dynamically provisioned. Currently, testing is conducted on **Microsoft Azure**, but support for other providers such as **AWS**, **GCP**, **Hetzner**, and **OVH** is planned.
