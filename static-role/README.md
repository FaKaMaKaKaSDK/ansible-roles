# ansible-static-ip
Шаблон для выдачи адресов серверу на ОС Linux Ubuntu 20.04
Ansible role to create a static ip address

## Role Variables

- `static_ip_address` (string) - the ip address

- `static_ip_netmask` (string) - the netmask

- `static_ip_gateway` (string) - the gateway

- `static_ip_dns` (string) - space delimited list of dns

- `static_ip_interface_name` (string) - the interface name to assign the static ip too

- `static_ip_dest_config` (string) - netplan destination configuration file
