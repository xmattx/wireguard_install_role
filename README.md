# Ansible Role for installing wireguard

## Warning

This role is still under development and untested!!!!

## Before Starting

Remember to popolate vars file
```bash
wireguard_install/roles/wireguard_install_role/vars/main.yml
```

Then Popolate inventory file
```bash
wireguard_install/inventory.ini
```

Finally, you can run the playbook
```bash
ansible-playbook -i inventory.ini playbook.yml
```

## Notes

This role is based on an awesome work made by angristan here on GitHub. Check it out!
```
https://github.com/angristan/wireguard-install
```