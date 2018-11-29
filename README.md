# Requirements

These instructions require the following software:

* Vagrant - https://www.vagrantup.com/downloads.html
* VirtualBox - https://www.virtualbox.org/wiki/Downloads
* Vagrant docker compose plugin 

    ```
    vagrant plugin install vagrant-docker-compose
    ```

# Vagrant Commands

Starts the virtual machine
```
vagrant up
```

SSH into the vagrant vm 
```
vagrant ssh
```

removes the vagrant virtual machine 
```
vagrant destroy
```

Shows all vagrant virtual machine deployments 
```
vagrant global-status
```

# Docker Commands

Show running docker containers 
```
docker ps
```

SSH into docker containers in the vagrant vm 
```
docker exec -it <container name> /bin/bash
```