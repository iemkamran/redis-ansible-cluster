# Redis High Availability Setup
Multiple node redis cluster ansible yaml. now we can easily deploy 3-node, 4-node or n-nodes cluster of redis with simple ansilbe configuration.

Role Name
A brief description of the role goes here.

Requirements
Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Dependencies
A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

---
 - hosts: Server
   user: xyz
   become: true
   become_user: root
   roles:
    - redis_7000
    - cluster    
    - pidfix:
    
    
    
    
    
    
