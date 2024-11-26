# ansible_desktop
Ansible configuration for Kubernetes nodes

Using Vagrant to provision VMs:
- workstation from where we will execute commands to interact with master and worker nodes
- kmaster : kubernetes controlplane node
- node-01, node-02 and node-03 : nodes for our workloads

Using Ansible to:
- confige VMs (installing packages, updating, patching)
- Install packages.
- Install kubernetes on controlplane and nodes.
- create users
- Confige k8s access
