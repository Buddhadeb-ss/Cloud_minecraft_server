# Cloud_minecraft_server
This project involved setting up and deploying a dedicated Minecraft server using Google Cloud Platform (GCP). The goal was to learn about cloud infrastructure (IaaS), Linux server administration, and network security configuration. The server was hosted on a Compute Engine Virtual Machine running ubuntu Linux.
PROJECT TITLE: Google Cloud Minecraft Server Deployment

OVERVIEW
This project involved setting up and deploying a dedicated Minecraft server using Google Cloud Platform (GCP). The goal was to learn about cloud infrastructure (IaaS), Linux server administration, and network security configuration. The server was hosted on a Compute Engine Virtual Machine running Debian Linux.

TECHNICAL ARCHITECTURE
- Cloud Provider: Google Cloud Platform (GCP)
- Service: Compute Engine (Virtual Machine)
- Operating System: Linux (Ubuntu)
- Runtime: Java Development Kit (JDK)
- Networking: Static IP address with custom firewall rules

KEY IMPLEMENTATION STEPS
1. VM Provisioning: Created a Compute Engine instance on GCP suitable for server hosting.
2. Linux Environment Setup: Connected via SSH and updated the system using APT package manager. Installed Java runtime environment.
3. Network Configuration: Configured VPC Firewall rules to allow TCP/UDP traffic on port 25565, enabling external players to connect.
4. Deployment: Downloaded server software and configured server properties.
5. Process Management: Used Linux tools like 'screen' or 'tmux' to run the server process in the background, ensuring 24/7 uptime even after SSH disconnect.

SKILLS DEMONSTRATED
- Cloud Computing basics (VM creation, billing management)
- Linux Command Line Interface (CLI) navigation and file management
- Network security (Firewalls and Ports)
- Remote administration via SSH

CONTENTS OF THIS REPOSITORY
- start.sh: A sample Bash script used to launch the Java process with specific memory allocation.
- server.properties: Configuration file demonstrating server settings.
Results

<img width="714" height="1280" alt="image" src="https://github.com/user-attachments/assets/c3386c4a-2e2e-4c7a-89e2-542d1681a41a" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/c166ae97-ea40-45d1-809e-dab097755dce" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/355aa3c4-a2b2-47ed-adf3-d51390514857" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/55e5d771-e111-4dab-9fab-11dec5debf27" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/ef00ebf6-b06b-4187-a595-94af79f83dbe" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/1d57b0dd-fba1-417b-af64-a193f6d21f0c" />





