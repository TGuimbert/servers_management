# servers_management

## Requirements

* This playbook is only tested with Centos8 
* _ansible_ account on managed servers with public key authentication enabled (`ssh-copy-id`) with sudo rights

## How to use

1. Create a _hosts_ file.
2. Run the playbook with `ansible-playbook -i hosts site.yml -K`
