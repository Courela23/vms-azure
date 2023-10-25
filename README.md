# vms-azure
<p align="center">
  
![Screen Shot 2023-10-25 at 5 06 00 PM](https://github.com/Courela23/vms-azure/assets/136120929/49928605-b34e-4b09-afe9-0ec252411ef5)
 </p>
<h1>Creating a Virtual Machine (VM) in Microsoft Azure/ Remotely connecting to the VM</h1>
This project showcases the procedure for provisioning a virtual machine in the Azure cloud and using remote desktop to connect to it.<br />

<h2>Things you will need</h2>

- Microsoft Azure account.
- Computer with a good internet connection.
- Microsoft Remote Desktop (If you are using a Macbook).



<h2>High-Level Steps</h2>

- Create a resource group.
- Create VM
- Connect to VM using Remote Desktop

<h2>Summary</h2>
<p>
<h2>Creating a Resource Group
</p>
<p> 
  
![Screen Shot 2023-10-25 at 5 55 18 PM](https://github.com/Courela23/vms-azure/assets/136120929/1d5ca85f-5626-45db-86e3-eb8e8a84e201) </h2>To create a resource group in Azure, start by logging into the Azure Portal. Once logged in, navigate to the "Resource groups" section and click on the "Add" button. You'll be prompted to provide a name for your resource group, choose a subscription, and select a region. After configuring these details, click "Review + create" for validation, and then "Create" to finalize the creation of your resource group. This group serves as a logical container for your Azure resources, making it easier to manage and organize your cloud.</p>

<p>
<h2>Creating the VM </h2>

To create a virtual machine (VM) in Azure, first, sign in to the Azure Portal, then use the search bar to find "Virtual Machines." In the search results, click on "Virtual Machines," and select "+ Add" to begin the VM creation process. Fill in the necessary information, including the VM's name, operating system, authentication method, and size. Configure additional settings if required, review your choices, and click "Create" to initiate the VM deployment.

<p>
<h2>Connecting to VM</h2>

To remotely connect to an Azure Virtual Machine (VM), use Remote Desktop Protocol (RDP) for Windows VMs or SSH for Linux VMs. For Windows, open the Remote Desktop client and enter the VM's public IP address with your provided username and password. For Linux, open your terminal or SSH client and use the "ssh" command with the VM's username and public IP. Ensure that the necessary network security group rules are configured to allow RDP or SSH traffic, and follow best practices for secure remote access.

<p>
To optimize your Azure credit usage, consider removing unnecessary Resource Groups.
</p>
<br />
