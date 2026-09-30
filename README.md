# Azure VM: Nextcloud on a Secured Ubuntu Server

A hands-on Microsoft Azure lab: deploying an Ubuntu Server virtual machine inside a secured virtual network, then installing Nextcloud on it.

## What I Built

1. Created a **resource group** to hold all the lab resources
2. Created a **virtual network** and a subnet
3. Protected the subnet with a **network security group (NSG)**
4. Deployed **Azure Bastion** to connect to the VM securely, without exposing SSH to the internet
5. Created an **Ubuntu Server virtual machine**
6. Installed **Nextcloud** by connecting over SSH through Bastion
7. Published a **public IP address**
8. Created a **DNS label** so the site has a friendly address

## Skills Practiced

Azure networking · Network security groups · Azure Bastion · Linux server administration · SSH · DNS

## Screenshot

![Azure VM lab](https://github.com/Archo2/Azure-VM/assets/87620279/7d719212-2dc5-4ea0-a6d1-8dcd33945b3c)

## Author

**Archils Oburu**
- GitHub: [@Archo2](https://github.com/Archo2)
- Email: oburuarchils@gmail.com
