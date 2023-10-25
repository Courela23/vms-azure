# vms-azure
<p align="center">
  
![Screen Shot 2023-10-25 at 5 06 00 PM](https://github.com/Courela23/vms-azure/assets/136120929/49928605-b34e-4b09-afe9-0ec252411ef5)
 </p>
<h1>Creating a Virtual Machine (VM) in Microsoft Azure</h1>
This project showcases the procedure for provisioning a virtual machine in the Azure cloud and examining the resulting network structure using Network Watcher.<br />

<h2>Things youw will need</h2>

- Microsoft Azure account
- Computer with a good internet connection



<h2>High-Level Steps</h2>

- Create a resource group.
- Navigate to "Virtual machines" and choose "Create Azure virtual machine."
- Complete the mandatory fields on the "Basics" Tab.
- Proceed to "Review + create."
- If the VM successfully passes validation, proceed to "Create."
- After the VM is created, you can inspect it in Network Watcher.
- To optimize your Azure credit usage, consider removing unnecessary Resource Groups.

<h2>Summary</h2>

<p>
<img src="https://i.imgur.com/zkr3A9P.png" height="70%" width="70%"/>
</p>
<p>
To get started on creating the virtual machine, search for “virtual machine” in the search bar at the top of the Azure homepage and select “Virtual machines.” Click “Create” in the top left corner (the blue “Create” button in the middle of the screen also works) and then select “Azure virtual machine.”
</p>
<br />

<p>
<img src="https://i.imgur.com/bwTogp0.png" height="50%" width="50%"/>
</p>
<p>
<img src="https://i.imgur.com/3h91vqh.png" height="50%" width="50%"/>
</p>
<p>
The first page is the “Basics” page to fill in the required fields. For the Resource group, make a new one by selecting “Create new” and also select an appropriate region based on your location. The location you select can affect your options for the “Size” field, so this may need to be carefully checked. Be sure to check the box under Licensing. Once finished, click “Review + create”.
</p>
<br />

<p>
<img src="https://i.imgur.com/ksIytig.png" height="50%" width="50%"/>
</p>
<p>
Before the VM is created, make sure it passes validation. Once the message at the top confirms a successful set up, click “Create.”
</p>
<br />

<p>
<img src="https://i.imgur.com/3iB9u1P.png" height="70%" width="70%"/>
</p>
<p>
It is likey the VM will take time to get set up by Azure, but once finished, you'll be able to look at the configuration of the VM. It is important to know the location of the public and private IP addresses on this page, since finding this information would be important for future labs.
</p>
<br />

<p>
<img src="https://i.imgur.com/J9BB8fA.png" height="70%" width="70%"/>
</p>
<p>
The Network Watcher feature is helpful because it dsiplays a diagram of various components of the VM in Azure. As you can see, when you create a VM, it’s not just the virtual machine itself that is created. Along with the VM (VM-1), Azure also created a virtual network (VM-Lab-vnet), a subnet (default), a virtual NIC (vm-1960), a Network Security Group a.k.a. firewall (VM-1-nsg), and a public IP address (VM-1-ip).
</p>
<br />

<p>
After successfully creating the VM be sure to delete the machine when not in use to mitigate credit cost for usage.
</p>
<br />
