# Tech Test Requirements:

Test tasks
Requirement to task implementation:

● Solution must contain a valid Vagrantfile to test solution

● All logic must be implemented via Ansible Playbooks/Roles

● You can use public Ansible roles, Ansible Galaxy is preferred source

● Solution must contain basic README


Redis Cluster
Implement Ansible playbook to deploy Redis cluster in docker containers.
After first playbook run, Redis cluster must be properly initialized. Redis data should be persistent on host.

RabbitMQ cluster
Implement Ansible Playbook to deploy RabbitMQ cluster in docker containers.
After first playbook run, RabbitMQ cluster must be properly initialized. Management interface must be present, admin username and password must be configurable via Ansible variables.

MySQL replication
Implement Ansible Playbook which deploys MySQL master and slave in Docker containers. First playbook run must result in replication process running with now errors. MySQL data directories must be persisted on host’s disk.

# Tech Test Solution:

