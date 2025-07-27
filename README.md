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
<img src="https://github.com/Justin-Colon/wire-shark/blob/aee6ad7bda87b819db4c94c538b1d5e60d61d09b/ICMP/2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
What is shown in the highlighted portion is the public IP addess of my windows 10 vm. I then copy this IP address so that I can enter it onto RDP.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/wire-shark/blob/59cd00e7f50dc05ee6ecc1cfd09b7517242cd5d0/ICMP/3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On RDP is where I plugged in the public IP address of vm1 so that I can connect to it. 
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/wire-shark/blob/e7c9bfc8fddb62adbac51b682de6ad2a07db73d2/ICMP/4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once on windows 10 I opened powershell which is a command line tool that allows me to talk with my computer. 
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/wire-shark/blob/dadf604de21451ee50cecd569ac968f59fea1d9d/ICMP/5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now I downloaded windows x64 installer on wireshark which is network protocol analyzer, a tool that lets you see exactly what’s happening on a network in real time. 
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/wire-shark/blob/59ae5e458210be07b6aa2fffe293ae0866514570/ICMP/6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once wireshark is downloaded on vm1, you can see where I highlighted, right next to ethernet, there's a scribble of some sort. That is actually wireshark indicating that there is network activity. Now to open up this ethernet apllication, I left it highlighted and clicked on the shark fin on the top left corner of the wireshark program.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/wire-shark/blob/3a97db6814770b9a0a0352098ffe815929940c2d/ICMP/8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here is what is happening on the backend of my computer. A bunch of data be sent over the internet but I am going to filter it so that only ICMP traffic is being shown.
</p>
<br />

