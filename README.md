# InstallAnsible
Install Ansible on Redhat Linux 9 Workstation

#Find Ansible in Subscription Manager Repository List 
sudo subscription-manager repos --list

#Use the Subscription Manager to Enable Ansible rpm

sudo subscription-manager repos --enable ansible-automation-platform-2.2-for-rhel-9-x86_64-rpms

#Install Ansible 
sudo yum install 

#When Sucessfull use ansible --version 
# ansible --version
ansible [core 2.15.6]
  config file = /etc/ansible/ansible.cfg
  configured module search path = ['/root/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/local/lib/python3.9/site-packages/ansible
  ansible collection location = /root/.ansible/collections:/usr/share/ansible/collections
  executable location = /usr/local/bin/ansible
  python version = 3.9.18 (main, Sep  7 2023, 00:00:00) [GCC 11.4.1 20230605 (Red Hat 11.4.1-2)] (/bin/python)
  jinja version = 3.1.2
  libyaml = True
