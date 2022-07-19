# Ansible
Deeper dive into the functionalities of ansible in more robust and complex infrastructure provisioning

Commands:
~ ansible all -m apt -a update_cache=true --become --ask-become-pass - administers sudo privileges to ansible to make updates across host servers
