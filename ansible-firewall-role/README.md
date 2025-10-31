Role Name
=========

Configure firewall for ufw and firewalld

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

ufw_list_of_enabled_hosts:
  - 192.168.X.X/24 # Example

ufw_list_of_opened_ports:
  - '80' # http
  - '443' # https
  - '22' # ssh


firewall_services_redhat:
    - ssh
    - dhcpv6-client

firewall_ports_redhat:
    - '80'
    - '443'
    - '22'

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ansible-firewall-role

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
