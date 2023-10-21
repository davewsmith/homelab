# Ansible

All of this requires an acivated virtual environment.

## Health checks

Verify that nodes are, and show free disk space

    ansible -i inventory/homelab -m shell -a "df -h ." NODE

where NODE is either `all` or some node in the inventory.
