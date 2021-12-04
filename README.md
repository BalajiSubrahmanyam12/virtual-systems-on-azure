# virtual-systems-on-azure
creating virtual machine in Microsoft azure  

the process of creating 
Snapshot based backup of Azure VM 
Create Azure Resource Group
Configure VNet/Subnet
Create Azure VM (associate Public IP) and add datadisk and create logical partition in the VM using disk management.
Configure NSG(network security group) and assign it to configured Subnet(point2)
Take Snapshot of VM(OS Disk) Create new VM out of snapshot and point to same resource group(point 1)
Create Vault(Azure Backup)
Configure the backup and schedule the immediate Backup of snapshot VM and give the backup successful results.


is shown in the formate of the image
