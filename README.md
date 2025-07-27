<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:800/0*R0z2QhK2HnM0aU5Z.jpg"alt="osTicket logo"/>
</p>

<h1>Wireshark</h1>
This tutorial outlines how to observe ICMP traffic using wire shark between two vm's on your personal operating system.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Windows 10 server 
- Ubuntu Server 22.04 LTS-x64 Gen 2
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Ubuntu Server 22.04 LTS-x64 Gen 2

<h2>List of Prerequisites</h2>

- Azure Account 
- Region Selection
- Resource Group
- Virtual Network
- VM Image
- VM Size
- Authentication Method
- Storage Type
- Public IP Address(Optinal)
- Inbound Port Rules


<p>
<img src="https://github.com/Justin-Colon/wire-shark/blob/fcb8dcdbbf01f33b9494884457df3e3ff8d38060/ICMP/1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First thing I did was make sure I created and configured two VM's. Operating system for vm1 is windows 10 and vm2 is using linux. 
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/9cc93bada740c7d6b72a3077a48616211f52cef5/vpn/vpn3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here is where we search https://whatismyipaddress.com/ just to get the IP address of our personal computer.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/5bd98f4418a52f75fce756bec083167f16cf5d49/vpn/vpn4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I did the samething in our VM this time and as you can see our IP address and region is different from our actual computer. We have established a tunnel between our computer and the vm using a non vpn connection. 
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/74e8d6a079e848329393848d0471de1999570fa2/vpn/vpn5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now I have gone ahead and downloaded proton vpn onto my vm only.
</p>
<br />
