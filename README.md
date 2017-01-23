# ansible-docker-nexus
Deployment of dockerised Nexus3 for Centos with ansible.

Edit your /etc/ansible/hosts file to point the machine where you wish to deploy Nexus.

Run the command:
ansible-playbook site.yml

To test the connection run:
curl -u admin:admin123 http://localhost:8081/service/metrics/ping
