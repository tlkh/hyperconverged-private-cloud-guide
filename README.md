# Hyper-converged Private Cloud Guide
A guide to building a hyper-converged private cloud on commodity hardware

## Index

* (What is hyper-convergence?)[#hyper-convergent-infrastructure]
* Hypervisor: Proxmox
* Storage: Ceph
* Networking: Linux Bridge

## Hyper-convergent infrastructure

TLDR; All datacenter components are in one chassis.

### Advantages

* Lower complexity
* Lower footprint (especially for smaller-scale deployments)
* Easy to gradually scale horizontally over time by adding new nodes

### This takes the form of

* Software defined compute (KVM / LXC)
* Software defined storage (Ceph)
* Software defined network (Open vSwitch / Linux Bridge)

