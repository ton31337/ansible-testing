# Configuration

## /etc/ansible/hosts
```
[zookeeper]
10.0.0.1 myid=1
10.0.0.2 myid=2
10.0.0.3 myid=3

[kafka]
10.0.0.2 broker_id=1
```

## Install Zookeeper
```
$ ansible-playbook zookeeper/zookeeper.yml
```
