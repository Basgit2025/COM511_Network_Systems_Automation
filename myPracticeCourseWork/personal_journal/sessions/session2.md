[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 2

## Topics covered
*What topics were covered in this session*
in session 2, I have learned how to use ansible along side vagrant and virtual box to automate the Instruction from this module. I managed to activate three virtual machines through an ansible controller. 


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
exercise 2.2 - starting the virtual machines 
I used the "vagrant up" to start up the three virtual machines using vagrant for the ansible exercise. 
<img width="711" height="60" alt="starting ansible controller" src="https://github.com/user-attachments/assets/741dbd35-dac3-4efe-9dbc-b27b639e78e5" />



Rocky linux provisioning, configured rocky linux and used ssh keys to access the machines and for it be used by ansible. 
<img width="1440" height="900" alt="provisioning and confirming all three vms" src="https://github.com/user-attachments/assets/80cc6830-1c13-4ff3-84eb-ffd074646666" />



After starting the machines and using ssh keys for ansible, I used the "vagrant status" command to check that they are running properly. 
<img width="881" height="238" alt="vagrant confirmation" src="https://github.com/user-attachments/assets/9d8a2dd1-eb0c-4f0f-a70b-783173c690ac" />



I accessed the ansible controller and pinged all three machines to make sure there is communication between them. 
<img width="1436" height="453" alt="ansible ping to all addresses" src="https://github.com/user-attachments/assets/731c7dfb-c665-4be3-9199-eddffc059217" />



I ran the Rocky linux apache playbook like it was instructed from the examples. after running all the commands from the playbook and ran successfully without failed tasks. 
<img width="1440" height="382" alt="apache installation" src="https://github.com/user-attachments/assets/86191cb3-6087-4392-a26c-fc85c53e58cf" />



## Summary of learning
*What did you learn through these exercises*

I learned how I can use vagrant and use ansible to perform all the automation tasks. also being able to fire and manage multiple machines. 
how ssh key allow access for ansible to automate exercises. 
how ansible allows automation make system admin more efficient and consistent. 
