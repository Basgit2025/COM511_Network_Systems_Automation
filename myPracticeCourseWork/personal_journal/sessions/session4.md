[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 4

## Topics covered
*What topics were covered in this session*
Vagrant PXE server/ client enviroment 


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
- PXE network installation
<img width="436" height="328" alt="Screenshot 2026-10-21 at 13 00 03" src="https://github.com/user-attachments/assets/f3b62e3d-d3b6-4139-aae1-71ea53d35b50" />
this screenshot shows the pxe boot menu displayed on the client vm. I have chosen to download the nfs option to install ubuntu over the network using the PXE server.


- ubuntu installation process
<img width="507" height="413" alt="Screenshot 2026-10-21 at 13 18 57" src="https://github.com/user-attachments/assets/686a5f46-6dc9-4d9d-9344-4662690e7f21" />
this is the automated installation of the ubuntu on the PXE client. once completed, the client is supposed to automatically shut down.

- successful ubuntu installation
<img width="505" height="424" alt="Screenshot 2026-10-21 at 13 29 55" src="https://github.com/user-attachments/assets/c4faca2d-f076-423a-b220-7c62b17062d6" />
after ubuntu has been successfully installed on the client vm, after selecting the local boot. I then chose to log in using the ansible account provided.


- ansible connectivity test
<img width="839" height="143" alt="Screenshot 2026-10-21 at 14 02 09" src="https://github.com/user-attachments/assets/e1d9131f-2e59-49b3-a67a-6812e927dccf" />
this shows the ansible version which proves the successful installation. this allows the PXE server to act as an ansible control for managing the client.

- successful ansible connectivity test
<img width="661" height="109" alt="Screenshot 2026-10-21 at 14 03 37" src="https://github.com/user-attachments/assets/f0a38101-7465-4461-a830-b060f818f516" />
this show communication between the PXE server and the client with the shown ip address. after configuration and creating a ansible inventory file I executed an ansible ping to communicate with the client vm.


- Apache installation
<img width="840" height="203" alt="Screenshot 2026-10-21 at 14 03 58" src="https://github.com/user-attachments/assets/0372ebe2-1176-473e-84d6-91b2d03d1ae1" />
this is my attempt to install apache on ubuntu client using the playbook. the playbook managed to connect to the client, but I had an error related to the apt package. although there are errors made the test confirmed communication with the client. 




## Summary of learning
*What did you learn through these exercises*
