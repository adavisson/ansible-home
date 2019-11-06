readme.md
# About
This repository hosts ansible playbooks and taskst to help automate updating control of home systems.

# To run playbook:
`ansible-playbook -i hosts.yml <PLAYBOOK NAME> --ask-become-pass`

# Notes:
 - If connection to webservers fail, check inbound rules for aws security group
 - All servers are Ubuntu 18.04 LTS
 - For Plex update:
  - Download latest package to '~/Downloads/plex/', make sure it is the only file in folder and then run playbook
