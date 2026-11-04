[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 6

## Topics covered
*What topics were covered in this session*



## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
- building and running apache containers
<img width="707" height="161" alt="Screenshot 2026-11-04 at 11 49 09" src="https://github.com/user-attachments/assets/4b791ab9-7101-4027-9cc1-02e3885063a1" />

this figure shows the use docker compose to build a customer apache image, and ran two containers from it. the terminal shows that both containers are running successfully. 
<img width="795" height="614" alt="Screenshot 2026-11-04 at 11 51 10" src="https://github.com/user-attachments/assets/2eb41a02-9afd-4564-a195-1669c00e96cf" />
<img width="799" height="593" alt="Screenshot 2026-11-04 at 11 51 20" src="https://github.com/user-attachments/assets/d52493b6-fa2c-4aef-a897-fb6f94faf9f3" />

I accessed both containers through my browser using the local host for each of the sites. this confirms the containers was running correctly. 


- pre build images and bind mounts
<img width="711" height="120" alt="Screenshot 2026-11-04 at 11 53 39" src="https://github.com/user-attachments/assets/c23b6af6-a284-4366-a91d-68a168adf49a" />
I ran two containers using a pre built apache image

<img width="693" height="443" alt="Screenshot 2026-11-04 at 11 54 11" src="https://github.com/user-attachments/assets/c1c9d7f5-d099-443b-b587-02b90354e62a" />
<img width="819" height="502" alt="Screenshot 2026-11-04 at 11 54 01" src="https://github.com/user-attachments/assets/b1042abb-9199-43a6-b98c-9d47bb5bd11a" />
 both these screenshots are confirmation that our containers are both working

 <img width="706" height="135" alt="Screenshot 2026-11-04 at 12 27 51" src="https://github.com/user-attachments/assets/4bd46f12-27ee-4d67-bc2a-d9009181cce7" />
 I then deployed Wordpress and mariadb  using docker compose 

 <img width="1408" height="560" alt="Screenshot 2026-11-04 at 12 27 21" src="https://github.com/user-attachments/assets/329a8e53-184d-46fc-aecd-6ba71788e5b5" />
<img width="1432" height="715" alt="Screenshot 2026-11-04 at 12 27 14" src="https://github.com/user-attachments/assets/fb0eda99-abf9-4de7-ac1b-2d951ec38487" />
<img width="839" height="547" alt="Screenshot 2026-11-04 at 12 27 03" src="https://github.com/user-attachments/assets/4eb4670e-d163-4256-8251-baa9994fa7b9" />
I accessed the Wordpress admin page by entering the sign in credentials and these are confirmations that our Wordpress websites loaded successfully 

<img width="716" height="211" alt="Screenshot 2026-11-04 at 12 29 12" src="https://github.com/user-attachments/assets/130886ef-25e1-446b-998b-eaa1585dc7a8" />
I started 6 containers, including three word press and NGINX 
<img width="1436" height="111" alt="Screenshot 2026-11-04 at 12 46 09" src="https://github.com/user-attachments/assets/759ea3ee-73f3-460c-b649-ffe743eae030" />
After accessing the https I used the terminal to monitor the NGINX and word press logs to observe incoming logs 



## Summary of learning
*What did you learn through these exercises*
I learned how docker compose simplifies management of multiple containers with yaml. practiced building images, and using pre made images. also word press made it easier to understand how web servers work. gained understanding through troubleshooting docker containers and checking logs to ensure that services were operating correctly. 
