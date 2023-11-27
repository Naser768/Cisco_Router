# Cisco_Router
Build the following network in packet tracer with all necessary connection and testing required.
Instruction:


Make a report file where all necessary command and descriptions are listed.

Screenshots of the DNS & HTTP services working in the mentioned departments.
If you were not able to complete any specification, mention your limitations and discuss.
***No need to make the report unnecessarily big. Just do the necessary points and discussions mentioned above briefly, write to the point only.***
………………………………………………………………………………………………………………………………………………………………

I.	Introduction (A brief about your project):
       In today's world, networking has become a crucial part of our daily life. It has become a core foundation for different aspects of life. Computer networking refers to the connection of multiple computers or other digital devices to share data. It includes involvement of  both hardware and software technologies whether the connection used is wired or wireless. A computer network enables communication between computers and access to the internet, as well as the sharing of resources like printers, files, and data storage. Additionally, networking facilitates group and individual collaboration as well as the exchange of data and information between several platforms and gadgets.
              Networking topology refers to the arrangement of the components of a network. It has a direct relationship with the functionality of a network. It describes the logical and physical structure of the network. A well thought-out network layout improves user experience and aids administrators in maximizing performance while meeting operational requirements. It is simpler to find defects, debug and resolve issues, and share resources across networks when the appropriate topology is adopted for a business's requirements. (A Brief of your project)
                         This project aims to create a computer network for an education institution        consisting of 6 rooms (Internet lab, Computer Department, IT Department, Server room, Principal room and Principal room). To connect all the devices 6 switches were used. For routing purpose 3 routers were used. Our goal is to create such a network where data can be transferred from any device of one room to any device of another room. 
II.	Methodology:
Components:
           1. Switches:  In our project we used 6 switches in total to connect all the devices. Switch PT was used to connect all the devices in each room. Switch PT is a type of switch which contains 4 ports by default. We can use up to 4 ports in this switch.
 
1. Router (1941):   Router (1941) is a popular model that belongs to Cisco's Integrated Services Router (ISR) series. It offers a range of features and capabilities, including high-performance routing, security, and connectivity options, making it suitable for various network environments.    
  	            
2. PC: 21 PCs were used in this project. Each has their own IP addresses and are connected to the switch of each room.
 
        	           3. Laptop: Only 1 Laptop was used in this project, which is available in the Principal’s room.
 
        	           4. Printer: In total 6 printers were used in this project. Each printer has its own IP address and a default gateway.
 
                          5. Server: Three types of servers were used: FTP, DNS and WEB. FTP server is a type of server used to transfer small files. A DNS server is a computer server that keeps a database of hostnames and public IP addresses that it uses to resolve, or convert, hostnames to IP addresses as necessary.
 
        	           6. Cable: Copper Straight-Through and Serial DTE cables were used to connect all the devices. A Copper Straight-Through cable is a kind of twisted pair cable that is used to link a computer to a network hub such as a router.  Any device that serves as a source or a destination for binary digital data is a serial DTE.

  
Fig. Serial DTE cable                                                           Fig. Copper Straight-Through

III. Addressing: (Naser)
1.	Ip address
2.	Ethernet
3.	Gateway
4.	Router
5.	 Switch


III.	Modules and Routing Protocols. (If you have used additional modules write about them. Discuss in brief which routing protocol you used and why is it best suited):
     
Results and Discussion (Screenshots of at least one PC from from every network being able to communicate with other networks. Send simple PDU for this purpose. Make sure that the PDU List Window is clearly visible.):









Computer Department:

PC or Printer	IP Address
PC 0	192.168.2.2
PC 1	192.168.2.3
PC 2	192.168.2.4
PC 3	192.168.2.5
PC 4	192.168.2.6
Printer 0	192.168.2.7

Principle Room:

PC or Printer	IP Address
Laptop0	192.168.4.3
PC5	192.168.4.2


Internet Lab :

IP ADDRESSES OF ALL THE COMPONENTS
PC0	128.168.0.2
PC1	128.168.0.3
PC2	128.168.0.4
PC3	128.168.0.5
Printer	128.168.0.6
Default Gateway	128.168.0.1


IT Department 

IP ADDRESSES OF ALL THE COMPONENTS
PC0	192.168.1.2
PC1	192.168.1.3
PC2	192.168.1.4
PC3	192.168.1.5
PC4	192.168.1.6
Printer	192.168.1.7
Default Gateway	192.168.1.1







Others
Here we use 4 PCs and 3 Printers.

❖	IP ADDRESSES OF ALL THE COMPONENTS
Office	192.168.3.2
Exam	192.168.3.3
PO	192.168.3.5
Enjy	192.168.3.4
Printer2	192.168.3.8
          Printer3	          192.168.3.7
          Printer4	          192.168.3.6
          Default Gateway	          192.168.3.1

Server Room

FTP Server:


IP Address	1.0.0.4
Subnet Mask	255.0.0.0
Default Gateway	1.0.0.1
DNS Server	1.0.0.2


WEB Server:


IP Address	1.0.0.3
Subnet Mask	255.0.0.0
Default Gateway	1.0.0.1
DNS Server	1.0.0.2


DNS Server:


IP Address	1.0.0.2
Subnet Mask	255.0.0.0
Default Gateway	1.0.0.1
DNS Server	1.0.0.2

