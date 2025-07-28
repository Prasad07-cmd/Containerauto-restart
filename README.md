# Containerauto-restart
Get the container IP address only and Attach policy to the running container for auto start .

Conclusion :
Through this task, we successfully demonstrated the practical application of Docker container management using the eclipse/centos image. The two main objectives—capturing the IP address of a running container and ensuring a container restarts automatically after a system reboot—were achieved using core Docker features.

In Task 1, we launched a container named dockerip and efficiently extracted its internal IP address using Docker inspection, storing it in the /tmp/address.txt file. This shows an understanding of Docker networking and inspection tools.

In Task 2, we deployed another container named ccaapp with the --restart unless-stopped policy, ensuring high availability by enabling automatic restarts upon system reboot. This highlights the ability to manage container lifecycle policies for production-like environments. 

🔧 Key Learnings:
How to run containers in detached interactive mode.

How to use docker inspect to extract specific container metadata.

Importance and usage of Docker's restart policies for resilience.

Basic scripting potential with container data for automation.

These tasks reflect essential skills in containerization and system automation 
