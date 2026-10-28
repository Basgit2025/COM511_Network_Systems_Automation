[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 5

## Topics covered
*What topics were covered in this session*
- installed docker on desktop, ran a docker container and built a docker container.
- installed docker on ubuntu through vagrant. building and running a container.


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*



## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
- running ubuntu docker container
<img width="568" height="299" alt="Screenshot 2026-10-28 at 11 35 25" src="https://github.com/user-attachments/assets/c202596d-a035-4623-aa75-2574932faabc" />

The screenshot shows the version of ubuntu running on the docker desktop. the "cat" command to verify the operating system. followed by 'ls' to explore the filesystem. 


- testing a custom docker image
<img width="566" height="141" alt="Screenshot 2026-10-28 at 11 58 47" src="https://github.com/user-attachments/assets/50960f5c-b974-4b3c-a5a0-28c8c401139f" />

I demonstrated a successful execution of a custom docker image built from ubuntu with the 'curl' package installed. also ran the 'docker run' command to confirm that the docker file was installed successfully. 



- Docker inside a vagrant VM (building and running container)
<img width="564" height="308" alt="Screenshot 2026-10-28 at 12 13 37" src="https://github.com/user-attachments/assets/9ea70299-b040-48ac-bbba-b26e6fc23249" />
<img width="571" height="81" alt="Screenshot 2026-10-28 at 12 15 08" src="https://github.com/user-attachments/assets/10d05e28-8165-4a14-8471-20bace52f05a" />

The first screenshot on top is showing the docker image being built inside the VM. using the lecturers docker file and executing there correct command and created the wanted image, demonstrating how container images can be built inside the VM. 

The second screenshot shows the use of docker and confirming the apache container was running successfully. the container was used and mapped accordingly so it allows the web server to be accessed externally. 


- Accessing the web server
<img width="816" height="374" alt="Screenshot 2026-10-28 at 12 22 41" src="https://github.com/user-attachments/assets/6f6c4903-a051-4aac-affb-234c72c06d0b" />
the screenshot shows the apache2 ubuntu default page. I accessed the web server using the given address, confirming the container is functioning correctly through the vagrant machine. 





## Summary of learning
*What did you learn through these exercises*
