# Multi-tenancy Kubernetes OnPremises

In this repository I will follow you to deploy a multi-tenancy kubernetes using the RKE2 (Rancher Kubernetes Engine 2) distribution. As you can imagine I have used a VMware environment, but you can reuse the configuration on all type of infrastructure, for example bare metal or other type of virtualization.

Before proceeding read the following design choices:

- Cilium for Network Plugin
- CoreDNS
- Cilium LoadBalancer IPAM + Nginx Ingress Controller to access to the services
- VMware Cloud Native Storage for CSI storage (this is the only VMware lock-in point) 

Click on the following section:

- [Control Plane Configuration](https://github.com/emilianopepe/kubernetes-onprem/blob/main/docs/control-plane-configuration.md)
- [Worker Node Configuration](https://github.com/emilianopepe/kubernetes-onprem/blob/main/docs/worker-node-configuration.md)
- [Services Exposure](https://github.com/emilianopepe/kubernetes-onprem/blob/main/docs/services-exposure.md)
