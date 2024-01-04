# RASPI HOME DEPLOY
This project aims to deploy raspi home to a target.  
This software use ansible to deploy.

## Deploy
To deploy use
```
$ ansible-playbook deploy.yml -i <hosts_file>
```
Use tags to specify particular operation
```
$ ansible-playbook deploy.yml -i <hosts_file> --tags <tag>
```
## Update
To update used docker images:
```
$ ansible-playbook update.yml -i <host_file>
```
Use tags to specify particular operation
```
$ ansible-playbook update.yml -i <host_file> --tags <tag>
```
