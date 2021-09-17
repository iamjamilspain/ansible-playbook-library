# How to run this playbook

This playbook of course requires ansible to be installed on the machine. Once that is there, you can run it with this script

### First Run

The playbook will create a folder called workspace in this **datapower-local** folder. 

Each run will create a subfolder in the workspace directory which will contain the local files and folders mapped each instance. 

```
ansible-playbook dp-limited-setup.yml
```

