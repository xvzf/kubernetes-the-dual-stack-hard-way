# Kubernetes the hard way - with Ansible
> **AND DUAL STACK NETWORKING**

> **NOTE:** This works on a single node right now but can be scaled out when using a different cni plugin

This repo is just a collection of ansible roles bootstrapping a kubernetes cluster which can do IPv4 and IPv6 networking.
Controlplane is coming up and Pod networking is working fine :-)

## ToDos

- [x] Containerd
- [x] cni plugin
- [x] PKI setup
- [x] ETCd single node cluster
- [x] kube api Server
- [x] kube controller manager
- [x] kube scheduler
- [x] kube proxy (in ipvs mode)
- [ ] DNS clusteraddon (CoreDNS)
- [ ] Traefik 2.x deployment
- [ ] Verifying everything
