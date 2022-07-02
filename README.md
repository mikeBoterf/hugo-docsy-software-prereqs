# hugo-install

Just simple Ansible scripts to install software required for hugo to function properly.

## Run it

```
ansible-playbook init-hugo-workstation.yml --ask-become-pass
```

# tl;dr

Each playbook handles a task of installing a software application.

## Software Installed

- Install golang
  - Version is hard-coded.. that will change in the future hopefully
  - Version: 18
- Install hugo
  - Version is hard-coded.. that will change in the future hopefully
  - Version: 101 extended
- Install Node
  - In an attempt to keep it simple:
    - The playbook only works on OS's such as Ubuntu and Rocky/Rhel8 systems.
    - Playbook will install version **18** of node on `Ubuntu` like OS's and **16** on `RHEL` like OS's.

### Future Plan

Please feel free to add input. I've been doing this in my spare time. This isn't very robust.
Maybe I'll make all of these roles and pull them in that way. My goal is to keep it simple. 
