# Dynamic Ansible Inventory OpenStack Script

## Description

**WIP**

This script is based on Ansible's upstream [Working With Dynamic Inventory - OpenStack](https://docs.ansible.com/ansible/latest/user_guide/intro_dynamic_inventory.html#inventory-script-example-openstack).

The original script can be found at Ansible's [repo](https://github.com/ansible/ansible/blob/devel/contrib/inventory/openstack_inventory.py).

## Changes

**Last compared 30th of March, 2019**

The modified script containts the following changes:
* Support floating IPs instead of fixed IPs:

  Use `--port-type` to set which type of IP addresses to be fetched, default is `fixed`:
  ```
  --port-type {fixed,floating}
                        Choose type of IP address
  ```

## License

GNU General Public License v3.0

See COPYING to see the full text.