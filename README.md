# Types of Malware

**Purpose of Malware = Monetary Goal :money_with_wings: is the #1 reason**<br/>
**Virus:** Attaches itself to a program, usually an executable file, .Exe must be opened or running, no human action means the virus doesn't spread.<br/>
**Trojan Horse:** Most common, software with a desired function, misleads users of its true intent (for example, fake login screens)<br/>
**Ransomware:** Encrypts files, malware makes PC not available until Ransom is paid.<br/>
**Logic Bombs:** Predefined event time/day, script or code results in a lot of problems and disruptions when it's executed<br/>
**Spyware:** Trojan horse like software, records browsing, key strokes, and sends it to the attacker, (sometimes it may come with a bundle software, making the user unaware)<br/>
**Grayware:** Accepted through EULA, behaves like Spyware/Trojan<br/>
**Rootkits:** Backdoor access, software allowing in and out access without being detected<br/>
**Hoaxes:** Message warning the recipient of a non-existent computer virus/threat, false information, news which results in a DoS attack.


# TCP/IP Model: #
![TCP/IP Image](/images/OSI_vs_TCP_IP_model.png)

# More details about each layer:
**Application:** Allows programs to connect to our network<br/>
**Presentation:** Encrypt/Decrypt data for humans to read on screen, translates packages of data into another form, raw data into a certain format<br/>
**Session:** Who’s allowed to talk and when, performs a handshake with another computer, control connections between computers establish, terminate, manage connections, regulate who can send what, and how much, coordinates the conversation, and controls/manages layers 1 through 4<br/>
**Transport:** Sessions into packets, manage and control data packets, transfer of data, transfer of data, TCP = Transmission Control Protocol (receipt), UDP = User Datagram Protocol (no receipt)<br/>
**Network:** IP address to router, packages the data into packets, you can change the IP #, IP used to transfer data to a computer on a different network, NIC = IP and MAC Address<br/>
**Data Link:** Mac address to switch or router, bits into frames, transfer from point to point access from a computer to a device, packages those bits/data into frames, Media Access Control Address<br/>
**Physical:** Cables, turns data into bits, physical/electrical stage, conversion from Data to signals, pinouts, voltages, code, specifications, NIC

 
 
 # MAC vs. IP #
![MAC/IP Image](/images/MAC_and_IP.png)

# Subnetting #
Process of dividing a network into small networks and is a common task on IPv4 networks.
![cidr.PNG](/images/cidr.PNG)

# Network Mask/Host Address Reference #
![netmask.PNG](/images/netmask.PNG)

# PING #
Ping is a networking utility program or a tool to test if a particular host is reachable. When you ping a remote computer you are actually sending a messafe called echo request, the remote computer then replied to your message which is called echo reply. 


# Traceroute:
Traceroute is a utility that records the route (the specific gateway computers at each hop through the internet between your computer and a specified destination computer.) It also calculates and displays the amount of time each hop took.

**Hop:** Journey from one computer to anothero<br/>
**Packets:** Information that travels along the traceroute is knowno<br/>
**ICMP:** Internet Control Message Protocol (ICMP) / relay query messages
