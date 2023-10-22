# us-west-π

Configuration/deployment scripts for my rolling disaster of a homelab.

Having been cobbled together from various sources,
this is beyond use-at-your-own-risk-ware.

## Assumptions

  * All nodes have a public key emplaced
  * All nodes nodes are running Tailscale

## One-time Setup

Ansible runs from a virtual environment.

    python3 -m venv venv
    . venv/bin/activate
    pip install --upgrade pip  # just in case
    venv/bin/pip install ansible ansible-lint

## Per-use Setup

Everything in `ansible/` requires an activated virtual environment.

    . venv/bin/activate



