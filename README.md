# Port_Scanner
A port scanner is a computer program that checks network ports for one of three possible statuses – open, closed, or filtered . Port scanners are valuable tools in diagnosing network ,connectivity issues.

Port scanning is one of the most popular forms of reconnaissance ahead of a hack, helping attackers determine which ports are most susceptible.It is very useful in the process of  pentesting a website .

Attackers use port scans to break into vulnerable networks to gain unauthorized access to sensitive information. Port scans are also a useful tool for penetration testers (pen testers), enabling them to identify vulnerabilities in their own network with the goal of strengthening its defenses.



**How port scans work**
Ports are logical connection endpoints in a network. Each port is assigned a number that a client uses to identify a server and the service it offers. The number is included in the header of data packets that travel between client and server using transport layer protocols, such as the Transmission Control Protocol (TCP) and the User Datagram Protocol (UDP). A port scan uses this number to identify potentially vulnerable services on a given host.

It does this by sending a series of client requests to server port addresses -- denoted by their port number -- in order to find an active or open port. Once the host receives a message on a port, it returns one of three general responses: open, closed or blocked -- meaning no reply. Open ports represent vulnerable points in a network.

A variety of tools can be used to perform a port scan. The most commonly used tool is Nmap, which stands for Network Mapper. Nmap is a free, open source tool that offers several network mapping features, including port scanning. Users can enter the command nmap-p into a terminal window or command line to utilize its port scanning feature. Nmap-p followed by a single number will return the status of a single port on a given host. The nmap-p command followed by a range of numbers -- e.g., 80-200 -- will return the status of every port in that range. Many other commands are available to specify scans using Nmap, but nmap-p is the most basic. Other Nmap commands include the following:

nmap-sT, which scans TCP ports;
nmap-sU, which scans UDP ports;
nmap-sV, which probes for the services being used on certain ports;
nmap followed by an Internet Protocol address scans ports on that IP address; and
nmap followed by an IP address with a slash after the last digit (e.g., 192.168.1.0/23) scans a subnet.
Beyond Nmap, there are other tools to perform port scans -- such as Metasploit and NetScanTools Pro -- as well as other types of port scans that retrieve different information.
