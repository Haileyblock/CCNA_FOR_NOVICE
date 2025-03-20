**PERSPECTIVE ON NETWORKING**

User perspective: House -> modem (Wifi) -> Internet

But now, as a future networking engineer, we need to broaden our mind, and learn deeply about network.

Bigger network: enterprise network

Smaller network: SOHO (Small office/ home office)

**REMEMBER: NETWORKING IS JUST MOVING DATA FROM THIS PLACE TO ANOTHER PLACE**

**TCP/IP NETWORKING MODEL**

Networking model = networking architecture = networking blueprint (mô hình mạng) = set of documents describe one function for a network

Networking model = protocol + physical requirements 

**HISTORY**
- Start build 1970s - Open Systems Interconnection (OSI) was created by The International Organization for Standardization (ISO)

  Before: Each computer has their own languages
  
  Now: Allow all computer communicate with each other 

- US Departments of Defense (DoD): Researchers at many universities developed TCP/IP (Volunteered)

**OVERVIEW**

- RFC (Request For Comments): a system of technical and organizational information about the Internet.

  Avoid repeated work
- TCP/IP model: a set of rules (physical, the OS, card...) which allows computer connect with each other.

  Has 5 layers, different functions, many protocols related (bottom -> top): Physical, Data Link, Network, Transport, Application

**APPLICATION LAYER**
- Provide an interface between software running on a computer and the network itself
- Example: HTTP, POP3, SMTP...
  - HTTP Mechanisms (Hypertext Transfer Protocol)
  - Tim Berners-Lee created - 1990s
  - Step 1: Send a message with HTTP header to the server (Request to get a file: Get.htm) 
  - Step 2: Response from server page (with http header + data home.htm)
  - Step 3: more home.htm data (without HTTP header)

**TRANSPORT LAYER**
- Provide services to the application layer protocols 
- Smaller number of protocols
- Example (most common): TCP (Transmission Control Protocol) and UDP (User Datagram Protocol)
  - TCP Error Recovery Basics (Phục hồi lỗi)
  - Step 1: When the request + response had been lost through the network (TCP (SEQ =1) + HTTP + Data) 
  - Step 2: TCP feature: Error Recovery: Realized the error and send a TCP back , asking Larry to send message 2 again

  -> Adjacent-layer interaction function on the same computer (tương tác lớp liền kề) (the concepts of how adjacent layers in a networking model work together)
  - Example: HTTP needs error fix -> TCP provide
  -> Same-layer interaction on a different computer (tương tác 2 lớp giống nhau)
  - Example: TCP layer work with TCP layer.

**NETWORK LAYER**
- Many protocol, but one major protocol: IP (Internet Protocol)
- Example: IP Basics: identify the name of end devices + group devices
- Dotted-Decimal notation (DDN)
- IP Routing (Tìm địa chỉ của IP và định ra tuyến đường)
  - Step 1: Larry server send packet to nearby router on the same LAN, it recognizes the IP address and send it to the target
  - Step 2: Repeat the process

**DATA-LINK AND PHYSICAL LAYERS**
- Many protocols and standards
- Ethernet frame examples
- The physcial transmission of data
  - Step 1: Encapsulate IP Packet between Ethernet header and Ethernet Trailer (Ethernet frame)
  - Step 2: Physically transmit it through the Ethernet cabling
  - Step 3: Receive the electrical signal
  - Step 4: De-encapsulate by removing the Ethernet header and trailer

**ENCAPSULATION PROCESS**
- /encapsulated/ 
HEADER/IP HEADER/TCP HEADER/HTTP HEADER/The content of the page/TRAILER
- SEGMENT: transport layer
- PACKET: network layer
- FRAME: link layer

**OSI MODEL AND TERMINOLOGY**
- OSI commonly used by networking vendors, companies
- TERMINOLOGY: PROTOCOL DATA UNIT (PDU)
- L7PDU APPLICATION
- L6PDU PRESENTATION
- L5PDU SESSION
- L4PDU TRANSPORT
- L3PDU NETWORK
- L2PDU DATA LINK

  
 
