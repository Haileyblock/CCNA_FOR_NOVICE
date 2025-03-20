**What is networking?**
- Real life: 2 friends exchange information, share the picture, talk... 
- Computer world: 2 computers exchange information, share the resources

**How does it work?**
- Move data from one device to another device
- Follow the strict rules of : NETWORKING MODEL (INVISIBLE PROTOCOL/ PHYSICAL REQUIREMENTS) 

**A. PHYSICAL REQUIREMENTS**

**Networking Devices**

I. End devices (Computers, Printers...) 

II. Intermediary devices
1. Network Interface Cards (NICs aka card mạng)
   
2. Repeater (bộ mở rộng Wifi): receive signal -> clean unwanted noise -> transmit the signal again (higher level)
   
3. Bridges (cầu nối): connect many LANs
   
4. Hubs: receive data -> broadcast (copy) -> send it to other devices in the same LAN (no routing -> network collision)
   
5. Switches (bộ chuyển mạch): just like hub, but it doesn't copy, it check the address and send the data to the correct place in a LAN
    
6. Routers (bộ định tuyến aka bộ phát wifi): a connection between LAN and WAN, routing the data,
   
7. Modem (Modulator and Demodulator aka bộ điều giải): analog <-> digital data (0 and 1) 

**Interfaces (giao diện)**
- Interaction between hardware and software components, between human and electronic devices (Software, Hardware, User (CLI, GUI)

**Links**
1. Cables (connect devices to an Internet source)
- Coaxial Cables (đồng trục)
- Shielded Twisted Pair Cables (STP) (cáp xoắn đôi có vỏ bọc)
- Unshielded Twisted Pair Cables (UTP) (Cáp xoắn đôi không vỏ bọc)
- Fibre Optic Cables (cáp quang)

2. Ports
- Serial
- USE (Universial Serial Bus)
- PS/2
- VGA (Video Graphic Array)
- Sockets (speakers, microphones)
- Ethernet
...

**INVISIBLE PROTOCOL**
  
![image](https://github.com/user-attachments/assets/47406505-a305-4b33-a293-b1c7f766aba7)

I. TCP/IP model (Transmission Control Protocol/ Internet Protocol)

- Department of Defense (DoD aka Bộ Phòng Thủ) - 1960s
- How data transmitted over networks using TCP/IP model: divide data into packet (4 layer)

4 layers (Lowest -> highest)

1. Physical and Data link aka Network Access (Ethernet, 802.11): Tầng vật lý
- Lowest layer
- Transmit the information from one system to others (Ethernet cable, port)
2. Internet aka Network (IP, ICMP): Tầng mạng
- Data is sent correctly and accurately
- IP: Internet Protocol (deliver packet from the source host -> destination host)
3. Transport (TCP, UDP): Tầng giao vận
- Provide a reliable connection between 2 communicating devices
- UDP (User Datagram Protocol) + TCP 
4. Application (HTTP, POP3, SMTP): Tầng ứng dụng
- Provide the interface between software and network
- Provide the devices the access network + applications: emails, cloud storage...
- HTTP + TELNET

II. OSI model (Open System Interconnection)

- 7 layers (Lowest -> Highest)

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

Packet Tracer - Investigate the TCP/IP and OSI models in action

**Overview**
- data broken down into smaller pieces (for identification purpose) -> put back together when they arrive (encapsulation process)
- each piece has specific name and belong to different layer

I. Part 1: Examine HTTP Web Traffic 














