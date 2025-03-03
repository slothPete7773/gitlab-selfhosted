# gitlab-selfhosted

## Test ping to all hosts
ansible all -m ping -i inventory.ini

## run playbook example
ansible-playbook playbook.yaml -i inventory.ini