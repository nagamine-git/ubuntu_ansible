# Ubuntu Auto Setup By nagaminenot

## How to Use
```bash
# install ansible
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
# run ansible-playbook
ansible-playbook -i localhost site.yml -vv --ask-become-pass
```
