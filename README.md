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
## setting fish
```bash
# fisherman
curl -Lo ~/.config/fish/functions/fisher.fish --create-dirs https://git.io/fisher
# oh my fish
curl -L http://get.oh-my.fish | fish
# ghq
fisher install decors/fish-ghq
# peco
omf install peco
# bob the fish
omf install bobthefish
```