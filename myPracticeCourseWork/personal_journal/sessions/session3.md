[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 3

## Topics covered
*What topics were covered in this session*
* DHCP Ansible playbook recap
* DHCP lease table
* install dnsmasq
* local dns
* external dns
* bind9 ansible



## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
I checked both DHCP lease table and made sure both ubuntu machines received and assigned ip addresses 
<img width="817" height="60" alt="DHCP assigned " src="https://github.com/user-attachments/assets/ee60badc-9a58-445f-b15c-281379042f19" />


used systemctl status dnsmasq to verify that the service was active on the ansible controller 
<img width="1143" height="362" alt="dnsmasq status" src="https://github.com/user-attachments/assets/dc891561-249d-442e-9d83-5b3407bb9d02" />

I used nslookup to test dns resolution. both vms were successful 
<img width="914" height="193" alt="nslookup both vms" src="https://github.com/user-attachments/assets/8275dd32-935c-48e6-b044-9ec8de188ba0" />

I used dig to query google.com through the dnsmasq server. the response was successful 
<img width="889" height="342" alt="external dns" src="https://github.com/user-attachments/assets/67e5c1b9-6522-42bb-b079-09aaf34a63ed" />


I also used nslookup to confirm that the bind9 server could resolve local hostnames... and external domains google.com
<img width="815" height="163" alt="bind " src="https://github.com/user-attachments/assets/3fba0965-2f21-45f7-baf2-1332bfb31427" />






## Summary of learning
*What did you learn through these exercises*

```
TASK [Gathering Facts] *************************************************************************************************************************************************************************************
[WARNING]: Host 'ubuntu-2' is using the discovered Python interpreter at '/usr/bin/python3.12', but future installation of another Python interpreter could cause a different interpreter to be discovered. See https://docs.ansible.com/ansible-core/2.21/reference_appendices/interpreter_discovery.html for more information.
ok: [ubuntu-2]
[WARNING]: Host 'ubuntu-1' is using the discovered Python interpreter at '/usr/bin/python3.12', but future installation of another Python interpreter could cause a different interpreter to be discovered. See https://docs.ansible.com/ansible-core/2.21/reference_appendices/interpreter_discovery.html for more information.

```
