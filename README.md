<img width="652" alt="Screen Shot 2023-07-13 at 1 55 23 PM" src="https://github.com/SiclaitGitHub/qualys-scanner/assets/139138443/5801bb62-8742-40e3-96a3-7b26cc8bc1cc">
<h1>Qualys Cloud Platform- Vulnerability Managment Software
 
  This tutorial outlines the installation of the Qualys Cloud Platform  on a Virtual Machine in Azure<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Learn Qualys Vulnerability Management (Home Lab)](https://www.youtube.com/watch?v=l5At5WDj7v0&t=157s)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Microsoft Remote Desktop
- Qulays Cloud Platform (Community Version)
- FireFox (Version 1.0.4)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Installation Steps</h2>

<img width="908" alt="Screen Shot 2023-07-10 at 1 30 29 PM" src="https://github.com/SiclaitGitHub/osticket-prereqs/assets/139138443/4f97a83e-1c37-4210-9dc1-8530cb7f91bf">


1. Set up your Azure Virtual Machine

Azure is a cloud computing platform and service offered by Microsoft. It provides a wide range of cloud services that enable organizations to build, deploy, and manage applications and services through Microsoft-managed data centers.

A virtual machine (VM) on Microsoft Azure is a computing resource that uses software instead of a physical computer to run programs and deploy apps. Each VM instance can run its own operating system (OS), which means multiple VMs can run different operating systems on the same physical machine.

Create a new Azure resource group, virtual network, subnet and virtual machine running Windows 10. Choose a VM size according to your needs. Once the VM is set up, you will need to connect to it using Remote Desktop. For this, you'll need the public IP address of the VM and the credentials you provided during the VM setup.
</p>


<img width="1424" alt="Screen Shot 2023-07-13 at 2 27 34 PM" src="https://github.com/SiclaitGitHub/qualys-scanner/assets/139138443/53ab2396-d9be-455f-8265-3aaba48b876b">

2. Install Mozilla FireFox (Version 104.0)

Mozilla Firefox, commonly known as Firefox, is a free and open-source web browser developed by the Mozilla Foundation. It is available for various operating systems, including Windows, macOS, Linux, and mobile platforms such as Android and iOS.Firefox is known for its speed, security, and flexibility, and it has gained popularity as an alternative to other web browsers. 

 - Download Mozilla FireFox (Version 104.0) Of of the FireFOx website


<p>
<img width="1412" alt="Screen Shot 2023-07-14 at 4 58 11 PM" src="https://github.com/SiclaitGitHub/qualys-scanner/assets/139138443/6ca98397-a853-4178-893d-8896aa32d168">

</p>
<p>
 
3. Install Qualys Cloud Platform

 Qualys Cloud Platform, is a cloud-based vulnerability management and security compliance solution developed by Qualys Inc., a leading provider of cloud-based security and compliance solutions. QualysGuard helps organizations identify and mitigate security vulnerabilities, track compliance with various industry standards, and improve their overall security posture.

- The "Community Edition" version od Qualys is sufficient for this excersice.
- create and account using a busines or student email to request login instruction
- Follow the instruction in the email you recieve from Quallys
- Log into you Qualys account on VM1 to continue thw excersise.


<img width="1413" alt="Screen Shot 2023-07-14 at 5 37 17 PM" src="https://github.com/SiclaitGitHub/qualys-scanner/assets/139138443/ae674a8f-6d5e-4d9e-af9d-1f8dd4416b47">


4. Set VM1's Private IP Address to Static in Azure

- On the Virtual Machine window "VM1"
- Click 'Networking"
- Click on the Network Interface hyperlink
- Click on "IP Confirguration"
- Click on the "ipconfig" hyperminl as the bottom of teh window
- Select "Static" for the Allocation options
- Click "Save"
</p>
<br />

<p>
<img width="1097" alt="Screen Shot 2023-07-14 at 5 21 58 PM" src="https://github.com/SiclaitGitHub/qualys-scanner/assets/139138443/892d2fb1-95c7-44be-8621-51a312e69c08">

</p>
<p>
4. Configure Qulays Cloud Platform

- Under the "Configure Scanner Appliances" on the Qualys Cloud Platform dashboard click on "Download Virtual Scanner"
- Click on "Start Wizard"
- Name your scanner and select you Virtualization Platform
- Click "Next: to add a new Virtual Scanner
- Copy and store the "personalization Code" provided
- Click "Check Activity" to begin scanner activation
- 



</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
