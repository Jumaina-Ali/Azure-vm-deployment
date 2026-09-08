# Azure-vm-deployment
# PROJECT OVERVIEW -
## This project demonstrates the deployment and configuration of an Azure Virtual Machine and hosting a basic web server using Nginx. 
# Azure Resources used-
## Resource Group : RG-AZ104-VM
## Virtual Machine : VM-AZ104
## Operating System : Ubuntu
## Virtual Network : Vnet-UAENorth-1
## Subnet : SNet-UAENorth-1
## Network Security Group : VM-AZ104-nsg
## Public IP Address : Azure Public IP
## Private IP Address : 172.16.0.4
# CONFIGURATION COMPLETED
## 1. Resource Group - Created a dedicated Azure Resource Group to Organize the resources used in this project. 
## 2. Virtual Machine - Created an Ubuntu-based Azure Virtual Machine named VM-AZ104
## 3. Networking -
## Configured the VM with:
## -Virtual Network
## -Subnet
## -Network Interface
## -Public IP address
## - Network Security Group
## 4. Network Security - Configured inbound network access through the network Security Group.
## SSH - TCP 22 - Allowed from my IP address
## HTTP - TCP 80 - Allowed from any source
## Restricting SSH access to my IP address improves security compared with allowing SSH from the entire internet.
## 5. SSH Connection-
## Connected successfully to the Ubuntu VM using SSH and verified access to the server.
## 6. Nginx Web Server - 
## Installed Nginx on the Ubuntu VM using :
## sudo apt update
## sudo apt install nginx - y
## verified thatt the NGinx was running using :
## sudo systemctl status nginx
## Web Server Testing
## Accessed the Nginx default web page through the VM's public IP address
## http://<Azure-public-IP>
## The nginx welcome page was successfully displayed in the browser.
## Network Flow-
## Internet 
##   ↓ 
## Azure Public IP
##   ↓
## Network Interface (NIC)
##   ↓ 
## Network Security Group
##   ↓ 
## Virtual Network 
##    ↓ 
## Subnet 
##    ↓ 
## Ubuntu Virtual Machine 
##    ↓
## Nginx Web Server
##    ↓ 
## HTTP Port 80
## Skills Demonstrated - 
## Azure Resource Groups
## Azure Virtual Machines
## Azure Virtual Networks
## Azure Subnets
## Network Security Groups
## Public and Private IP addresses
## SSH connectivity
## Linux/Ubuntu basics
## Nginx web server deployment
## Basic Azure networking and troubleshoot
## Project Outcome- 
## Successfully deployed an Ubuntu Virtual Machine in Microsoft Azure, configured network security, connected through SSH, installed Nginx, and exposed a working web page through HTTP.
## SCREENSHOTS -
## 1. Resource Group - <img width="1366" height="638" alt="resource group" src="https://github.com/user-attachments/assets/3a5470d9-d74b-4962-8668-334868b533ab" />
## 2. Virtual Machine - <img width="1366" height="632" alt="vm" src="https://github.com/user-attachments/assets/6889151a-f7c0-47c8-b6eb-9d66234b56a2" />
## <img width="1356" height="627" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/4445ae83-b7ac-4c79-bc4a-c32fd9447e37" />
## <img width="1366" height="625" alt="Screenshot (50)" src="https://github.com/user-attachments/assets/ecb19a4d-8608-414c-ab18-6a319fa63a5c" />
## <img width="1364" height="639" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/730cee9e-2f9b-4384-b5c3-0c3e497438ab" /> 
## <img width="1358" height="677" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/08cea114-5f6e-4b6f-97ea-76f7f9352b85" />
## <img width="1366" height="768" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/64996449-470b-437b-adc0-24ec1b1d1715" />
## <img width="1364" height="674" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/3b3f7989-4306-4028-8717-4752a7593d05" />
## <img width="1366" height="685" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/168a8f1c-e040-4225-a5a3-30d404584962" />









      
