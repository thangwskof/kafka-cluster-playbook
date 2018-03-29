### Prerequisites ###

ansible==2.4.2.0
Jdk1.8.0_161
kafka_2.11-0.10.2.0

### Playbook Structure ###
The playbook only contains one role, basically this roles will install and configure 4 services:
* WGET
* Zookeeper
* Apache Kafka
* Java JDK


### Contribution guidelines ###
* Configure IP server to hosts file
* Configure repo download, link download jdk, apache kafka to the /roles/vars/main.yml

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact


### Execute ###
```ansible-playbook -i hosts site.yaml -v```

### Clean up ###
``` ansible-playbook -i hosts clean_up.yml -v```
