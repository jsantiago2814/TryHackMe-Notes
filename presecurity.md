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
