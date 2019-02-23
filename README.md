# ansible-playbook-awx

Playbook to install AWX on Amazon AMIs.

## Prerequisites

### Roles
This playbook uses the following roles:

* geerlingguy.ansible
* geerlingguy.nodejs
* geerlingguy.awx

So install those first:

`
ansible-galaxy install geerlingguy.ansible
ansible-galaxy install geerlingguy.nodejs
ansible-galaxy install geerlingguy.awx
`

### EC2 Instance
Minimum of a `t2.medium` is required.
