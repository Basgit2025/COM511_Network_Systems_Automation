# configure dnsmasq and pxe boot sources

## dnsmasq example 

primarily taken from ansible by example
see https://www.ansiblebyexample.com/articles/ansible-dnsmasq-dhcp-dns-network-services


## running

```
#you may need to change the known_hosts key
rm ~/.ssh/known_hosts

```

```
cd project-ansible3-1
ansible-playbook -i inventory/dev/hosts.ini  setup-dns-server.yml

```
