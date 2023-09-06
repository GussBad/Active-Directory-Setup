# Active-Directory-Setup
In my recent project, I successfully built a home lab Active Directory environment, mirroring the structure of an enterprise-level network. This project aimed to simulate various essential components of an organization's IT infrastructure, ensuring smooth operations and efficient management


![Server Configuration](https://github.com/GussBad/Active-Directory-Setup/assets/98527927/f43c7b70-c75b-4609-9fbc-342ed047f5a9)



## Key Components Implemented

1. DNS (Domain Name System): I configured DNS services to provide name resolution within the network. DNS is crucial for translating human-readable domain names into IP addresses, facilitating seamless communication between devices.

2. DHCP (Dynamic Host Configuration Protocol): DHCP was set up to automate IP address assignment to network devices. This dynamic allocation simplifies network management, ensuring that devices always receive appropriate IP configurations.

3. Active Directory Domain Services (AD DS): AD DS formed the backbone of the project, providing centralized user and resource management. I created a domain controller to establish a domain for user authentication and authorization, enhancing security and user access control.

4. Remote Access: Remote access capabilities were configured to enable secure connectivity to the network from external locations. This functionality is crucial for remote employees or administrators to manage network resources.

5. User Management Script: To simulate a large-scale organization, I utilized PowerShell to create and manage user accounts. A custom script generated and added a thousand user accounts to the Active Directory, streamlining the user provisioning process.

6. Client Configuration: I configured a Windows-based client machine to connect to the network. This client was integrated into the domain, allowing seamless authentication and access to network resources.

![Seutp Users](https://github.com/GussBad/Active-Directory-Setup/assets/98527927/1df6868e-9cce-4d79-9c70-7c5e51e9b13c) 






## How It Works

This environment is designed to facilitate the seamless registration of new employees or clients into the system, promoting efficient access and robust connectivity across networked computers. To emulate a large-scale enterprise, a PowerShell script was employed to generate a thousand users. Following meticulous configuration, the system exhibited flawless performance, enabling effortless user registration and consistently smooth operations.
![Setup Client](https://github.com/GussBad/Active-Directory-Setup/assets/98527927/1dbddf51-61c7-4be4-9610-a54c489dea04)


## Project Outcome
The implemented infrastructure successfully mimics an enterprise environment, demonstrating proficiency in network design and management. It showcases the essential components of a functional Active Directory setup, emphasizing security, automation, and scalability.
Overall, this project serves as a valuable learning experience and a practical demonstration of building and managing an enterprise-level network within a controlled environment.


