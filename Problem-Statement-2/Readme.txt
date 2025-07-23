#  Problem Statement 2 – Kubernetes Security Scan using Kubescape

##  Objective

Perform a Kubernetes cluster security scan using the open-source tool Kubescape. The goal is to identify misconfigurations and vulnerabilities in the cluster setup.

---

## Environment Setup

- OS Windows 11  
- Platform Docker Desktop with Kubernetes enabled  
- Kubernetes Version v1.32.2  

---

##  Steps Performed

1. Enabled Kubernetes via Docker Desktop.
2. Verified the cluster was up using
   ```bash
   kubectl get nodes
