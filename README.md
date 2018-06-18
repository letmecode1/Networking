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


# OSI and TCP/IP Model: #
![TCP/IP Image](/images/OSI_vs_TCP_IP_model.png)

# More details about each layer:
**Application** Allows programs to connect to our network<br/>
**Presentation** Encrypt/Decrypt data for humans to read on screen, translates packages of data into another form, raw data into a certain format<br/>
**Session** Who’s allowed to talk and when, performs a handshake with another computer, control connections between computers establish, terminate, manage connections, regulate who can send what, and how much, coordinates the conversation, and controls/manages layers 1 through 4<br/>
**Transport** Sessions into packets, manage and control data packets, transfer of data, transfer of data, TCP = Transmission Control Protocol (receipt), UDP = User Datagram Protocol (no receipt)<br/>
**Network** IP address to router, packages the data into packets, you can change the IP #, IP used to transfer data to a computer on a different network, NIC = IP and MAC Address<br/>
**Data Link** Mac address to switch or router, bits into frames, transfer from point to point access from a computer to a device, packages those bits/data into frames, Media Access Control Address<br/>
**Physical** Cables, turns data into bits, physical/electrical stage, conversion from Data to signals, pinouts, voltages, code, specifications, NIC<br/> 

**Link Layer** This layer defines how to access a specific network topology, for example Ethernet, Token Ring, ARP and so on.<br/>
**Internet Layer** Sometimes called the network layer, the internet layer defines defines how to datagrams are formatted and handles the routing of data through the network. Examples, IP Version 4, IP Version 6, and the Internet Control Message Protocol (ICMP), Routing.<br/>
**Transport Layer** This layer provides end-to-end data delivery service. This is the layer that assembles packets and sends them to the Internet layer for processing. Examples, TCP and UDP.<br/>
**Application Layer** This layer consists of application programs and servers as the network interface into user application. ICMP Examples, Ping, Host Unreachable, TCP Examples, HTTP, FTP, POP3, Telnet, DNS (backup), UDP Examples, TFTP, DHCP, SNMP, RPC, DNS (primary)  <br/>

 # MAC vs. IP #
![MAC/IP Image](/images/MAC_and_IP.png)

# Subnetting #
Process of dividing a network into small networks and is a common task on IPv4 networks.
![cidr.PNG](/images/cidr.PNG)

# Network Mask/Host Address Reference #
![netmask.PNG](/images/netmask.PNG)

# PING #
Ping is a networking utility program or a tool to test if a particular host is reachable. When you ping a remote computer you are actually sending a messafe called echo request, the remote computer then replied to your message which is called echo reply. Implements ICMP protocol.


# Traceroute:
Traceroute determines the network path between two hosts("Trace the Route") and it calculates and displays the amount of time each hop took.

**tracert** Windows<br/>
**traceroute** Linux/Windows<br/>
**Hop** Journey from one computer to anothero<br/>
**Packets** Information that travels along the traceroute is knowno<br/>
**ICMP** Internet Control Message Protocol (ICMP) / relay query messages<br/>

# UDP, ICMP, and TCP
**User Datagram Protocol (UDP)** Part of the Internet Protocol suite used by programs running on different computers on a network. Used to send short messages called datagrams but overall, an unreliable, connectionless protocol. Commonly used for streaming audio and video because it offers speed! Faster than TCP because there is no form of flow control or error correction <br/>
**Internet Control Message Protocol (ICMP)** Designed to not carry application data, but rather information about the status of the network itself. Used by network devices, like routers, to send error messages indicating, for example, that a requested service is not available or that a host or router could not be reached. The best-known example of ICMP in practice is the ping utility, that uses ICMP to probe remote hosts for responsiveness and overall round-trip time of the probe messages. When you ping a remote computer, you are actually sending a message called echo request, the remote computer then replies to your message which is called echo reply. <br/>
**Transmission Control Protocol (TCP)** The most commonly used protocol on the Internet, because TCP offers error correction<br/>

# X Area Netowrk:
**Local Area Network (Lan)** Limited geographical area<br/>
**Wide Area Network (WAN)** Large geographical area<br/>
**Metropolitan Area Network (MAN)** Covers a city<br/>
**Campus Area Network (CAN)** Covers building on a campus<br/>
**Personal Area Network (PAN)** Very small network<br/>
**Storage Area Network (SAN)** Robust part of LAN housing storage<br/>
