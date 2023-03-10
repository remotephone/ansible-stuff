# ansible-stuff

Random ansible playbooks for things

## docker-prune.ymk

Prune the docker systems, cleans em up real quick.

## fix-journal-usage.yml

The journal files were filling up my swarm hosts. This fixes that.

## update_and_reboot.yml

update... and reboot.

`ansible-playbook update_and_reboot.yml -i inventory.yml --ask-become-pass`
