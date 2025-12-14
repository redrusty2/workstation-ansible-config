```
ansible-playbook -K local.yml
ansible-playbook -K dotfiles.yml
ansible-playbook -K neovim.yml
```

Need to restart for default shell to take effect.

## Old
Create ssh key in `/root/.ssh/`

Then run
```
sudo ansible-pull -U git@github.com:redrusty2/workstation-ansible-config.git
```
