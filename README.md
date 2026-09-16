# aws-security-lab-iam-vpc
A hands-on cloud security engineering portfolio documenting foundational AWS security controls, identity hardening (IAM/PoLP), and secure multi-tier network architectures (VPC, NAT Gateways, Bastion Hosts).

# AWS Security Lab: IAM & Network Architecture

A hands-on cloud security engineering portfolio documenting foundational AWS security controls, identity hardening (IAM/PoLP), and secure multi-tier network architectures.

---

## Part 1: Identity and Access Management (IAM)
* **Principle of Least Privilege (PoLP):** Configured strict administrative boundaries and restricted resource access.
* **IAM Policy Simulator:** Validated custom policy permissions and security guardrails.
* **Access Control:** Implemented secure role assumption and read-only policy restrictions.

### IAM Evidence
* ![Admin Group IAM]
* ![IAM Policy Simulator]
* ![Read-Only Role]

---

## Part 2: Custom VPC & Network Security
* **Custom VPC Provisioning:** Deployed a segmented VPC (`HomeLab1-vpc` / `10.0.0.0/16`) to isolate workloads.
* **Subnet Segmentation:** Configured multi-AZ public and private subnets to separate ingress traffic from sensitive backend systems.
* **Gateway Routing:** Integrated Internet Gateways (IGW) and NAT Gateways for secure traffic management.
* **Defense-in-Depth Access:** Deployed a public EC2 Bastion Host for secure entry and isolated a backend EC2 instance in a private subnet with no direct public IP exposure.

### VPC Network Architecture Evidence
* **VPC Resource Map & Topology:**
* **Public Bastion Host (Public Subnet):**
* **Private Backend Instance (Private Subnet):**
