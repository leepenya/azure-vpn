# azure-vpn
<p align="center">
<img src="https://imgur.com/Vxvq35v.png" height="60%" width="40%" alt="Microsoft Azure Logo"/>
</p>

<h1>Creating a Virtual Private Network in Microsoft Azure</h1>
In this project, I deployed a virtual private network (VPN) on Microsoft's cloud platform, Azure.<br />

<h2>Requirements</h2>

- Computer with internet connection
- Microsoft Azure account
  - Credit card to set up the account

<h2>High-Level Steps</h2>

- Step 1: Deploy a virtual machine ("VM") in Azure.
- Step 2: Install a VPN client on the VM.
- Step 3: Verify that the VPN's IP address is different from the host machine and the VM's IP addresses.

<h2>Specific Steps</h2>

<p>
<img src="https://imgur.com/CJsndCZ.png" height="80%" width="80%" alt="Azure VM Details"/>
</p>
<p>
1. I used the website whatismyipaddress.com (see above) to determine my host machine's public IPv4 address and location. 
</p>
<br />

<p>
<img src= "https://imgur.com/CDMdMgK.png" height="80%" width="80%" alt="VM public IP"/>
</p>
<p>
2. I essentially followed the first five steps of my lab "Creating a Virtual Machine in Microsoft Azure" to create and deploy a VM. In this case, however, I selected a region other than my actual one and then used RDP to connect from my host computer to my VM via its public IP address (shown above). 
</p>
<br />

<p>
<img src="https://imgur.com/hIRiaL7.png" height="80%" width="80%" alt="VM Location"/>
</p>
<p>
3. Using whatismyipaddress.com again, I noted the public IP address and location of the VM I had created.
</p>
<br />

<p>
<img src="https://imgur.com/fUOCoK6.png" height="80%" width="80%" alt="Download VPN Client"/>
</p>
<p>
4. Next, to connect my VM to a VPN, I set up an account at protonvpn.com, downloaded a VPN client, and installed it on my VM.
</p>
<br />

<p>
<img src="https://imgur.com/aNgzrI8.png" height="80%" width="80%" alt="Free Connection"/>
</p>
<p>
5. I then utilized the VPN client to obtain a VPN connection based in the Netherlands.
</p>
<br />

<p>
<img src="https://imgur.com/iq6lKbM.png" height="80%" width="80%" alt="VM Deployed"/>
</p>
<p>
6. Lastly, I used my VM's browser to determine my VM's new IP address and location and verified that they were different not only from my host machine's public IP address and location but also from my VM's original ones.
 </p>
<p>Thanks for checking out my Azure VPN lab!
</p>


</p>
<br />
