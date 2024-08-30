<p align="center">
<img src="https://imgur.com/bGOgZG9.png" alt="msAzure logo">
</p>

<h1>Microsoft Azure Virtual Machine</h1>
This tutorial outlines the prerequisites and configuration of virtual machines in Microsoft Azure that can be used like a physical desktop or server machine. <br />


<h2>Environments and Technologies Used</h2>

- Azure portal
- Remote Desktop
  

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Basic understanding of Azure Virtual Machines
- Remote Desktop Client

  

<h2>Create a Windows virtual machine</h2>

<p>
<img src="https://imgur.com/WIDoaQh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the Azure portal, under Azure services, select Create a resource. In the search box, search for Virtual Machines, select create. Walk through the configuration details. Name your Resource Group and your Virtual Machine. Select your region, a "Standard" security type, the Image (Windows 10) and accept default VM architecture (x64)
</p>
<br />

<p>
<img src="https://imgur.com/eDF66VX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You will need to create a username and password that will be used again later when connecting to your virtual machine in remote desktop. Review and create.
</p>
<br />


<h2>Configure the network</h2>
<p>

<img src="https://imgur.com/uZiDwaU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the networking tab, its important to use the existing virtual network so the VM can communicate with the other cloud services. No additional changes are needed. Select Review + create. The system will either validate your options with a pass or fail. 
</p>
<br />

<p>
<img src="https://imgur.com/CH1TDlW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After passing validation, select Create. Azure will show the name of the virtual machine being deployed. Deployment could take up to several minutes. Upon completion, access your VM by selecting, Go to resource. 
<br />
