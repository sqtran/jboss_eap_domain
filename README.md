# jboss_eap_domain
An Ansible Playbook used for customizing EAP in Domain mode.

## Disclaimer
- This playbook assumes that EAP is already installed in the default locations, which also assumes that it was installed on RHEL/Centos via YUM.
- This playbook is a working example, not meant to be "production" already

## Usage
First customize the sample_inventory file with whatever fits your use-case.

Then run the following command on your terminal
```bash
ansible-playbook -i sample_inventory playbook.yml
```

### TODO
- Convert this into a Ansible Role
- Remove hardcoded values for default passwords
