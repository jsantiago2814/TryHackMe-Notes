# Pre Security Notes

## Offensive Security Intro

* To find hidden URLs, we will use a tool called dirb. This tool uses a brute-force approach, by taking a list of potential page names and testing one by one if they exist in your website. This approach works because people use predictable names a lot of times.

* Command -> dirb [URL]

* Offensive secuuirty = red team

* Offensive security involves breaking into computer systems, exploiting software bugs, and finding loopholds in applications to gain unauthorized access. The goal is ot understand hacker tactics and enhance our secuirty defenses. 

## Defensive Security Intro

* Defensive security = blue team

* Blue Team's two main tasks are preventing intrusions from occuring and detecting intrusions when they do occur and responding properly.

* Some tasks for blue team include cyber security awareness, documenting & managing assets, preventative security, logging & monitoryng, and Frameworks, Policies, & Procedures.

* SOC -> Security Operations Center: isa  team of cyber security professionals that monitors the network and its systems to detect malicious cyber security events. Some main interests are: Trends & Vulnerability Awareness, Policy Violations, Unauthorized & Illegal Activity, and Intrusion & Breach Detection.

* Digital Forensiics is the application of traditional foresic science processes to digital devices. Digital forensics is used to preserve and analyse digital evidence to aide in the investigation of incidents, such as a breach. This may involve looking at information from: File System, System Memory, System Logs, and Network Logs

* Incident response is how organizations manage security events such as breaches, data leaks and cyber attacks. An incident response process is a defined set of stages to minimize damage, contain the threat and recover fast. The proces looks like this: Preparation -> Detection & Analysis -> Containment, Eradication, and Recovery -> Post-Incident Activity
 <img width="1140" height="497" alt="image" src="https://github.com/user-attachments/assets/3360d5f2-0080-4cdb-a957-bbfd05cea3bf" />

* Preparation: Creating the necessary resources and frameworks to handle an incident.

* Detection & Analysis: Using tooling and processes to detect incidents and assess their scope (reach) and severity. Logs can be analyzed for suspicious events.

* Containment, Eradication, and Recovery: Limiting the impact of the incident, such as preventing a virus from spreading and eliminae the cause and restore affected systems.

* Post-Incident Activity: Review the incident overall, how it was handled and could've been prevented. What were the learning points throughout the process?

* SIEM = Security Information and Event Management tool, gathers security-related information and events from various sources and presents them in one dashboard.

## Careers in Cyber

* Security analysts - responsiblities:
    * Work with various stakeholders to analyze the cyber security throughout the company.
    * Compile ongoing reports about the safety of networks, documenting security isssues and measures taken in response.
    * Develop security plans, incorporating research on new attack tools and trends, and measures needed across teams to maintain data security.

* Security Engineer - responsibilities:
    * Testing and screeening security measures across software.
    * Monitor networks and reports to update systems and mitigate vulnerabilities.
    * Identify and implement systems needed for optimal security.

 * Incident Responder - responsiblities:
    * Developing and adopting a thorough, actionable incident response plan.
    * Maintaining strong security best practices and supporting incident response measures.
    * Post-incident reporting and preparting for future attacks, considering learning and adaptations to take from incidents.

* Digital Forensics Examiner - responsiblities:
    * Collect digital evidence while observing legal procedures.
    * Analyze digital evidence to find answers related to the case.
    * Document your findings and report on the case.

 * Malware Analyst - responsibilities:
    * Carry out static analysis of malicious programs, which entails reverse-engineering.
    * Conduct dynamic analysis of malware ssamples by observing their activities in a controlled evironment.
    * Document and report all findings.

* Penetration Tester - responsibilites:
    * Conduct tests on computer systems, networks, and web-based applications.
    * Perform security assessments, audits, and analyze policies.
    * Evaluate and report on insights, recommending actions for attack prevention.

* Red Teamer - responsibilities:
    * Emulate the role of a threat actor to uncover exploitable vulnerabilities, maintain access and avoid detection.
    * Assess organization's security controls, threat intelligence, and incident response procedures.
    * Evaluate and report on insights, with actionable data for companies to avoid real-world instances.

## What is Networking?

* Networks are simply things connected. Can be formed by anywhere from 2 devices to billions.

* The internet is one giant network that consists of many, many small networks within itself.

* The first iteration of the Internet was within the ARPANET project in the late 1960s. This project was funded by the U.S. Defense Deparment and was the first documented network in action. However, it wasn't until 1989 when the Internet as we know it was invented by Tim Berners-Lee by the creation of the World Wide Web (WWW). It wasn't until this point that the Internet started to be used as a repositry for storing and sharing information, just like it is today.

* A network can be one of two type: 1) A private network, 2) a public network

* Devices have two means of identification, with one being permeable. These are: 1) An IP Address and 2) A Media Access Control (MAC) Address - think of this as being similar to a serial number.

* An IP Aaddress (or Internet Protocol) address can be used as a way of identifying a host on a network for a period of time, where that IP address can then be associated with another device without the IP address changing.

<img width="1140" height="487" alt="image" src="https://github.com/user-attachments/assets/cb0913a3-39c2-47dc-8199-c8fc4c1371d5" />

* An IP address is a set of numbers that are divided into four octets. The value of each octet will summarise to be the IP address of the device on the network. This number is calculated through a technique known as IP addressing & subnetting.

* An IP address can change from device to device but cannot be active simultaneously more than once wihtin the same network.

* IP Addresses follow a set of standards known as protocols.

* A public address is used to identify the device on the Internet, whereas a private address is used to identify a device amongst other devices.

* Public IP addresses are given by your Internet Service Provider (ISP) at a montly fee (your bill!).

* IPv4 uses a numbering system of 2^32 IP addresses (4.29 billion)

* IPv6 is a new iteration of the Internet Protocol addressing scheme to help tackle the shortage of addresses for IPv5. IPv6 supports up to 2^128 of IP addresses (340 trillion-puls) and is more efficient due to new methodologies.

<img width="736" height="177" alt="image" src="https://github.com/user-attachments/assets/4f0ef524-c522-4db7-924c-45646c45e2ea" />

* MAC Addresses - Devices on a network will all have a physical network interface, which is a microchip board foudn on the device's motherboard. This network interface is assigned a unique address at the factory it was built at, called a MAC (Media Access Control) address. The MAC address is a twelve-character hexadecimal number (a base sixteen numbering system used in computing to represent numbers) split into two's and separatedby a colon. These colons are considered separators. For example, a4:c3:f0:85:ac:2d. The first six characters represent the company that made the network interface, and the last six is a unique number.

<img width="1140" height="669" alt="image" src="https://github.com/user-attachments/assets/c065dd33-b3b5-4ff8-a563-e9f8de4a6280" />

* Ping (ICMP) - Ping is one of hte most fundamental network tooks available to us. Ping uses ICMP (Internet Control Message Protocol) packets to determine the performance of a connection between devices, for example, if the connection exists or is reliable

* The syntax to do a simple ping is ping IP address or website URL

## Intro to LAN

* Local Area Network (LAN)

* Topology - referring to the design or look of the network at hand.

* Star Topology - Devices are individually connected via a central networking device such as a switch or hub. This topology is most commonly found today becasue of its reliability and scalability - despite the cost. Any informatiion sent to a device in this topology is sent via the central device which it connects. Because more cabling and the purchase of dedicated networking equipment is required for this topology, it is more expensive than any other topologies. However, this topology is much more scalable in nature, which means that it is very easy to add more devices as the demand for the network increases. Unfortunately, the more the network scales, the more maintenance is required to keep the network functional.

<img width="1140" height="669" alt="image" src="https://github.com/user-attachments/assets/85be1a2e-4286-4d57-8efd-d3a47142167a" />

* Bus Topology - This type of connection relies upon a single connection which is known as a backbone cable. this type of topology is similar to the leaf off of a tree in the sense that devices (leaves) stem from where the branches are on this cable. Because all data is destined for each deivce travels along the same cable, it is very quickly prone to becoming slow and bottlenecked if devices within teh topology simultaneously requesting data. This bottleneck also results in very difficult troubleshooting because it quickly becomes difficult to identify which device is experiencing issues with data all travelling along the same route. Bus topologies are one of the easier and more cost-efficient topologies to set up because of their expenses, such as cabling or dedicated networking equipment used to connect these devices. Lastly, another disadvantage fo the bus topology is that there is little redundancy in place in case of failures.

<img width="1140" height="801" alt="image" src="https://github.com/user-attachments/assets/9501d4b1-92c2-4f56-9e9b-d2e51a87d666" />

* Ring Topology - The ring topology (also known as token topology) boasts some similarities. Devices such as computers are connected directly to each other to form a loop, meaning there is little cabling required and less dependence on dedicated hardware such as within a star topology. A ring topology works by sending data across the loop until it reaches the destined device, using other devices along the loop to forward the data. Interestingly, a device will only send received data from another device in this topology if it does not have any to send itself. If the device happnes to have data to send, it will send its own data first before sending data from another device. Becasue there is only one direction for data to travel across this topology, it is fairly eaasy to troubleshoot any faults that arise. However, this is a double-edged sword because it isn't an efficient way of data travelling across a network, as it may have to visit multiple devices before reaching the intended device. Lastly, ring topologies are less prone to bottlenecks, such as within a bus topology, as large amounts of traffic are not travlling across the network at any one time.

<img width="878" height="801" alt="image" src="https://github.com/user-attachments/assets/06d9ecef-6ad2-4a20-921f-c14d28a01aaa" />

* What is a Switch? Switches are dedicated devices within  network that are designed to aggregate multiple other devices such as computers, printers, or any other networking-capable device suing ethernet. These various devices plug into a switch's port. Switches are usually found in larger networks such as busineses, schools, or similar-sized networks, where there are many devices to connect to the network. Swithches can connect a large number of devices by having ports of 4, 8, 16, 24, 32, and 64 for devices to plug into. Switches are much more efficient than their lesser counterprt (hubs/repeaters). Switches keep track of what device is connected to which port. This way, when they receive a packet, instead of repeating that packet to every port like a hub would do, it just sends it to the intended target, thus reducing network traffic.

<img width="1409" height="801" alt="image" src="https://github.com/user-attachments/assets/9efc286b-48c8-4e6a-b589-de174a1a4fed" />

* Both siwtches and routers can be connected to one another.

* What is a Router? It's a routers job to connect networks and pass data between them. It does this by using routing (hence the name router!). Routing is the label given to the process of data travelling across networks. Routing involves creating a patth between networks so that this data can be successfully delivered. Routing is useful when devices are connected by many paths.

<img width="1140" height="390" alt="image" src="https://github.com/user-attachments/assets/cacbf02d-2435-4a6d-b7bb-93beacd0f371" />

* Subnetting is the term given to splitting up a network into smaller, minature networks within itself.

<img width="908" height="801" alt="image" src="https://github.com/user-attachments/assets/b50c8769-b527-45a5-9837-4f4a3843822e" />

* Network administrators use subnetting to categorize and assign specific parts of a network to reflect this. Subnetting is achieved by splitting up the number of hosts that can fit within the network, represented by a number called a subnet mask. As we can recall, an IP address is made up of four sections called octets. The same goes for a subnet mask, which is also represented as a number of four bytes (32 bits), ranging from 0 to 255 (0 - 255). Subnets use IP addresses in three different ways: 1) Identify the network address, 2) Identify the host address, 3) identify the default gateway. Default gateways usually use either the first or last host address in a network (.1 or .254).

* Address Resoultion Protocol (ARP), is the technology tht is responsible for allowing devices to identify themselves on a network. Simply, ARP allows a device to associate its MAC address with an IP address onn the network. Each device on a network will keep a log of the MAC address associated with other devices. When devices wish to communicate with another, they will send a broadcast to the entiere network searching for the specific device. Devices can use ARP to find the MAC address (and therefore the physical identifier) of a device for communication.

* How does ARP work? Each device wihtin a network has a ledger to store information on, which is called a cache. In the context of ARP, this cache stores the identifiers of other devices on the network. In order to map these two identifiers together (IP address and MAC address), ARP sends two type of messages: 1) ARP Request & 2) ARP Reply. When an ARP request is sent, a message is broadcasted on the network to other devices asking, "What is the mac address that owns this IP address?" When the other device receives that message, they will only respond if they own that IP address and will send an ARP reply with its MAC address. The requesting device can now remember this mapping and store it in its ARP cache for future use.

<img width="823" height="864" alt="image" src="https://github.com/user-attachments/assets/fc799cd9-65cc-407e-a4b6-e496c9c6b05b" />

* IP addresses can be assigned either manually, by entering them physically into a device, or automatically and most commonly by using a DHCP (Dynamic Host Configuration Protocol) server. When a device connects to a entwork, if it has not already been manually assigned an IP address, it sends out a request (DHCP Discover) to see if any DHCP servers are on the network. The DHCP server then replies back with an IP address the device could use (DHCP Offer). The device then sends a reply confirming it wants the offered IP Address (DHCP Request), and then lastly, the DHCP server sends a reply acknowledging this has been completed, and the device can start using the IP Address (DHCP ACK).

<img width="636" height="870" alt="image" src="https://github.com/user-attachments/assets/fe591d4a-0603-4ebd-9d12-ca69f1ae090d" />

* OSI (Open Systems Interconnection) Model

* The OSI model is an essential model used in networking. This critical model provides a framework dictating how all networked devices will send, receive, and interpret data. One of the main benefits of the OSI model is that devices can have different functions and designs on a network while communicating with other devices. Data sent across a network that follows the uniformity of the OSI model can be understood by other devies. The OSI model consist of seven layers. Each layer has a different set of responsibilites and is arranges from Layer 7 to Layer 1. At every individual layer that data travels through, specific processes take place, and pieces of information are added to this data.

<img width="1077" height="800" alt="image" src="https://github.com/user-attachments/assets/8ca3ceec-3718-40c0-83bd-90ab95eeee32" />

* Layer 1 - Physical: This layer references  the physical components of the hardware used in networking and is the lowest layer that you will find. Devices use electircal signals to transfer data between each other in a binary numbering system (1's and 0's).

* Layer 2 - Data Link: The data link layer focuses on the physical addressing of the transmission. It receives a packet from the network layer (including the IP address for the remote computer) and adds in the physical MAC (Media Access Control) address of the receiving endpoint. Inside every network-enabled computer is a Network Interface Card (NIC) which comes with a unique MAC address to identify it. MAC addresses are set by the manufacturer and literally burnt into the card; they can't be changed - although they can be spoofed.

* Layer 3 - Network: The third layer of the OSI model (network layer) is where the magic of routing & re-assembly of data takes place (from these small chunks to the larger chunk). Firstly, routing simply determines the most optimal path in which these chunks of data should be sent. Some protocols at this layer determine exactly what is the "optimal" path that data should take to reach a device. OSPF (Open Shortest Path First) and RIP (Routing Information Protocol). At this layer, everythign is dealt with via IP addresses. Devices such as routers capable of delivering packets using IP addresses are known as Layer 3 devices - becaus they are capable of working at the third layer of the OSI model.  

* Layer 4 - Transport: Layer 4 of the OSI model plays a vital part in transmitting data across a network and can be a little bit difficult to grasp. When data is sent between devices, it follows one of two different protocols that are decided upon several factors: TCP or UDP.
    * Transmission Control Protocol (TCP) is designed with reliability and guarantee in mind. This protocol reserves a constant connection between the two devies for the amount of time it takes for the data to be sent and received. Not only this, but TCP incorporates error checking into its design. Error checking is how TCP can guarantee htat data is sent from the small chunks in the session layer (Layer 5) has been received and reassembled in the same order. TCP is used for situations such as file sharing, internet browsing or sending an email. This usage is because services require the data to be accurate and complete.
    * User Datagram Protocol (UDP) is not nearly as advances as the TCP protocol. It doesn't boast the many features offered by TCP, such as error checking and reliability. In fact, any data that gets sent via UDP is sent to the computer whether it gets there or not. There is no synchronization between the two devices or guarantee; just hope for the best, and fingers crossed. UDP is useful in situations where there are small pieces of data being sent. For example, protocols used for discovering devices (ARP & DHCP) or larger files such as video streaming (where it is oky if some part of hte vidwo is pixelated).

 * Layer 5 - Session: Once data has been correctly translated or formatted from the presentation layer (Layer 6), the session layer (Layer 5) will begin to create and maintain the connection to other computer which the data is destined. When a connection is established, a session is created. Whils this conneciton is active, so is the session. Teh session layer is also responsible for closing the connection if it hasn't been used in a while or if it is lost. What is worth of noting is that sessions are unique - meaining that data cannot travel over different sessions, but in fact, only accross each session instead.

 * Layer 6 - Presentation: Layer 6 of the OSI model is the layer in which standardization starts to take place. Because software developers can develop any software such as an email client differently, the data still needs to be handled in the same way - no matter how the software works. This layer acts as a translator for data to and from the application layer (Layer 7). Security features such as data encryption (like HTTPS) occur at this layer.

 * Layer 7 - Application: The application layer of the OSI model is the layer that you will be most familiar with. This familiarity is because the application layer is the layer in which protocols and rules are in place to determine how the user should interact with data sent or received. Everyday applications such as email clients, browsers, or file server browing software such as FileZilla proved a friendly, Graphical User Interface (GUI) for users to interact with data sent or received. Other protocols include DNS (Domain Name System), which is how website addresses are translated into IP addresses.

## Packets & Frames

* A packet is a piece of data from Layer 3 (Network Layer) of the OSI model, containing information such as an IP header and payload.

* A frame, however, is used at Layer 2 (Data Link) of the OSI model, which, encapsulates the packet and adds additional information such as MAC addresses.

* A packet using the Internet Protocol will have a set of headers that contain additional pieces of information to the data that is being sent across a network. Some notable headers include:
   * Time to Live - This field sets an expiry timer for the packet to not clog up your network if it never manages to reach a host or escape!
   * Checksum - This field provides integrity checking for protocols such as TCP/IP. If any data is changed, this value will be different from what was expected and therefore corrupt.
   * Source Address - The IP address of the device that the packet is being sent from so that data knows where to return to.
   * Destination Address - The device's IP address the packet is being sent to so that data knows where to travel next.

 * TCP/IP protocol conists of four layers and is arguably just a summarized version of the OSI model. These layers are: 1) Application, 2) Transport, 3) Internet, and 4) Network Interface.

 * Very similar to how the OSI model works, information is added ot each layer of the TCP model as the piece of data (or packet) traverses it.

 * TCP guarantees that any data sent will be received on the other end. This process is named the three-way handshake.

 * TCP packets contain various sections of information known as headers that are added from encapsulation.
     * Source Port - This value is the port opened by the sender to send the TCP packet from. This value is chosen randomly (out of the ports from 0 - 65535 that aren't already in use at that time).
     * Destination Port - This value is the port nubmer that an application or service is running on the remote host (the one receiving data); for example a webserver running on port 80. Unlike the source port, this value is not chosen at random.
     * Source IP - This is the IP address of the device that is sending the packet.
     * Destination IP - This is the IP address of the device that the packet is destined for.
     * Sequence Number - When a connection occurs, the first piece of data transmitted is given a random number.
     * Acknowledgement Number - After a piece of data has been given a sequence number, the number for the next piece of data will have the sequence number +1.
     * Checksum - This value is what gives TCP integrity. A mathematical calculation is made where the output is remembered. When the receiving device performs the mathematical calculation, the data must be corrupt if the output is different from what was sent.
     * Data - This header is where the data, i.e. bytes of a file that is being transmitted is stored.
     * Flag - This header determines how the packet should be handled by either device during the handshake process. Specific flags will determine specific behaviours.
  
* Thre-way handshake - the term given for the process used to establish a connection between two devices. The Three-way handshake communicates using a few special messages. Below are some of the main ones:
   * 1 - SYN - A SYN message is the initial packet sent by a client during the handshake. This packet is used to initiate a conneciton and synchronize the two devices together.
   * 2 - SYN/ACK - This packet is sent by the receiving device (server) to acknowledge the synchronization attempt from the client.
   * 3 - ACK - The acknowledgement packet can be used by either the client or server to acknowledge that a series of messages/packets have been successfully recieved.
   * 4 - DATA - Once a connection has been established, data (such as bytes of a file) is sent via the "DATA" message.
   * 5 - FIN - This packet is used ot cleanly (properly) close the conneciton after it has been complete.
   * \# - RST - This packet abruptly ends all communication. This is the last resport and indicates there was a problem during the process. For example, if the service or application is not working correctly, or the system has faults such as low resources.
 
<img width="981" height="949" alt="image" src="https://github.com/user-attachments/assets/03011fab-cd5b-41b4-a796-9e803d623793" />

*  Any sent data is given a random number sequence and is reconstructed using this number sequence and incrementing by 1. Both computers must agree on the same number sequence for data to be sent in the correct order. This order is agreed upon during three steps.
   * 1 - SYN - Client: Here's my Initial Sequence Number (ISN) to SYNchronize with (0).
   * 2 - SYN/ACK - Server: Here's my Initial Sequence Number (ISN) to SYNchronize with (5,000), and I ACKnowledge your initial number sequence (0).
   * 3 - ACK - Client: I ACKnowledge your Initial Sequence Number (ISN) of (5,000), here is some data that is in my ISN+1 (0+1).
 
* TCP Closing a Connection - First, TCP will close a connection once a device has determined that the other device has successfullly received all of the data. To initiate the closure of a TCP connection, the device will send a "FIN" packet to the other device. Of course, with TCP, the other device will also have to acknowledge this packet.   

<img width="981" height="949" alt="image" src="https://github.com/user-attachments/assets/ed939f8f-41a5-4f8f-ab27-ccc9ac1ac8c4" />


