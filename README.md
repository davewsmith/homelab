# Homelab Stuff

Configuration stuff for my homelab.

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
    venv/bin/pip install ansible

## Setup

Everything in [ansible/README.md](Ansible) requires an activated virtual environment.

    . venv/bin/activate

