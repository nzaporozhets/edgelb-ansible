**EdgeLB ansible playbook**


*Ansible playbook to deploy [EdgeLB](https://docs.mesosphere.com/services/edge-lb/)*

---

## Instructions


1. Copy hosts.example file to hosts and add your host to it. Host should have DC/OS CLI installed and connected to your cluster.
2. Start the playbook
3. Grant this permission for each EdgeLB pool you will create: dcos security org users grant edge-lb-principal dcos:adminrouter:service:dcos-edgelb/pools/<POOL-NAME> full
