Role Name
=========

Role for add ssh keys

Requirements
------------

need installed ansible.posix collection 

```bash
ansible-galaxy collection install ansible.posix
```

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

list files keys for users:

ssh_public_keyfiles_bee

ssh_public_keyfiles_ansible

Dependencies
------------

[ansible-add-user-role](https://zenden.gitlab.yandexcloud.net/zenden-sysadmins/infra/ansible-roles/ansible-add-user-role)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ansible-ssh-keys-role

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
