# okd-cluster

## Clone the official OpenShift playbooks

https://github.com/openshift/openshift-ansible.git -b release-3.11

## Modify the invenotry to suit your needs

Change the IP addresses inside the [master], [etcd] and [nodes] groups.
You can add or remove nodes from the inventory, depending on how big your cluster should be.
The example file installs 1 master, 1 infra-node and 1 compute node

## Run the pre-tasks


