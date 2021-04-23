This is a basic framework of Ansible.

- inventory file : ansible.cfg 
- global varaibles : group_vars/all.yaml
- hosts : hosts information

```shell
.
├── README.md
├── ansible.cfg
├── group_vars
│   └── all.yaml
├── hosts
├── roles
│   └── test
│       ├── files
│       │   └── template.html
│       ├── handlers
│       │   └── main.yaml
│       ├── tasks
│       │   └── main.yaml
│       └── templates
│           └── main.j2
└── test_ansible.yaml
```

For testing purpose, it produces `./roles/files/template.html` 
