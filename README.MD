User: ansible

OS: red hat(V 6) family

Python:  2.6 and 2.7

App: Ansible

### Role Variables
haproxyip: IP Address of HA Server
target: nginx server IP

### Dependencies

None

### Example Playbook

 - -- hosts:  "{{ target }}"" 
 
        vars_files:
            - vars/main.yml
            roles:
            - nginx
            - php
            
#### Author Information

- Sanjay Mishra(sanjay.mishra@zycus.com)
