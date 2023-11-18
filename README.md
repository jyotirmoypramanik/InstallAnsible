# InstallAnsible
<b>Install Ansible on Redhat Linux 9 Workstation</b>
<br>
#Find Ansible in Subscription Manager Repository List 
<br><font face='Courier New'>$sudo subscription-manager repos --list</font>

#Use the Subscription Manager to Enable Ansible rpm

<br><font face='Courier New'>sudo subscription-manager repos --enable ansible-automation-platform-2.2-for-rhel-9-x86_64-rpms</font>

#Install Ansible 
<br><font face='Courier New'>$sudo yum install </font>

#When Sucessfull use ansible --version 
<br>$ansible --version
<br>$ansible [core 2.15.6]
<br>  config file = /etc/ansible/ansible.cfg
<br>  configured module search path = ['/root/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
<br>  ansible python module location = /usr/local/lib/python3.9/site-packages/ansible
<br>  ansible collection location = /root/.ansible/collections:/usr/share/ansible/collections
<br>  executable location = /usr/local/bin/ansible
<br>  python version = 3.9.18 (main, Sep  7 2023, 00:00:00) [GCC 11.4.1 20230605 (Red Hat 11.4.1-2)] (/bin/python)
<br>  jinja version = 3.1.2
<br>  libyaml = True
