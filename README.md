# Ansible-cisco-backup (ACB)

Here is a teamplate to backup cisco configs to ansible server and tftp server

## Getting Started

ansible-playbook cisco_backup.yml -i inventory -k -u user

### Prerequisites

add hosts to inventory file

```
[cat]
192.168.x.x
```

chose backup method in group_vars/all
```
use_tftp_server: true
use_local_server: false

```

### 
