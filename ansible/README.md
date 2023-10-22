# Ansible scripts

These require an activated virtual environment.

**Reminder:** deprecation warnings are disabled.

## Health checks

Verify which nodes are up, and show free disk space

    ansible -i inventory/homelab -m shell -a "df -h ." NODE

where NODE is either `all` or some node in the `homelab` inventory.

## Update/upgrade Pinot

    ansible-playbook -i inventory/pinot playbooks/upgrade.yml --ask-become-pass
