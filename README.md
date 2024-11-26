# ansible_desktop
Ansible configuration for Kubernetes nodes

Using Vagrant to provision VMs:
- workstation from where we will execute commands to interact with master and worker nodes
- kmaster : kubernetes controlplane node
- node-01, node-02 and node-03 : nodes for our workloads

Using Ansible for:
- configuring VMs (installing packages, updating, patching)
- Installing packages.
- Installing kubernetes on controlplane and nodes.
- creating users
- Configuring k8s access
