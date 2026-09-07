# Azure-vm-deployment
## PROJECT OVERVIEW -
# This project demonstrates the deployment and configuration of an Azure Virtual Machine and hosting 
# a basic web server using Nginx.
## Azure Resources used-
# Resource Group : RG-AZ104-VM
# Virtual Machine : VM-AZ104
# Operating System : Ubuntu
# Virtual Network : Vnet-UAENorth-1
# Subnet : SNet-UAENorth-1
# Network Security Group : VM-AZ104-nsg
# Public IP Address : Azure Public IP
# Private IP Address : 172.16.0.4
## CONFIGURATION COMPLETED
# 1. Resource Group - Created a dedicated Azure Resource Group to Organize the resources used in this project. 
# 2. Virtual Machine - Created an Ubuntu-based Azure Virtual Machine named VM-AZ104
# 3. Networking -
# Configured the VM with:
# -Virtual Network
# -Subnet
# -Network Interface
# -Public IP address
# - Network Security Group
# 4. Network Security - Configured inbound network access through the network Security Group.
# SSH - TCP 22 - Allowed from my IP address
# HTTP - TCP 80 - Allowed from any source
