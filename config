#!/bin/sh
if ! [ -x "$(command -v ansible-playbook)" ]; then
  sudo dnf install ansible
fi
ansible-playbook playbook.yml
