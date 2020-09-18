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

# Solution:

Install dependencies:

  VirtualBox:

    Windows ->  https://download.virtualbox.org/virtualbox/6.1.14/VirtualBox-6.1.14-140239-Win.exe
    Mac OS  ->  https://download.virtualbox.org/virtualbox/6.1.14/VirtualBox-6.1.14-140239-OSX.dmg
    Linux   ->  https://www.virtualbox.org/wiki/Linux_Downloads

  Vagrant:

    Windows ->  https://releases.hashicorp.com/vagrant/2.2.10/vagrant_2.2.10_x86_64.msi
    Mac OS  ->  https://releases.hashicorp.com/vagrant/2.2.10/vagrant_2.2.10_x86_64.dmg
    Linux   ->  https://releases.hashicorp.com/vagrant/2.2.10/vagrant_2.2.10_linux_amd64.zip
    
Clone project and run setup:

git clone https://github.com/jamalspringer/devops-projects.git

cd devops-projects

vagrant up


  
  
  


