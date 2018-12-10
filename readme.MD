Install Wordpress + MariaDB + Statistic monitoring
==================================================

pre instalation steps
---------------------

0. Ansible is installed in version ``>=2.7.0``
1. ensure server ips exists within ``servers.ini``
2. ensure private ips are set for DB and Metric  within ``infrastructure.ini``

instalation
-----------

```bash
ansible-playbook -i servers.ini infrastructure.yml
```
