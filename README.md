# ansible-flocker-aws
Ansible role for automating deployment of a flocker/swarm cluster of docker containers on AWS instances.

We have used the following variables in the default variables file, so take care to describe them in your playbook.

cluster_name: myclustername
control_service_node: mycontrolnode
cluster_node_agents: mynodelist

