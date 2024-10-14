# Network Programming Exam Notes

## 1. Network Structures and Protocols

### IP Addresses and C Structures

- **struct addrinfo**: Prepares socket address structures for subsequent use
- **struct sockaddr**: Holds socket address information for many types of sockets
- **struct sockaddr_in**: Makes it easy to reference elements of the socket address (IPv4)
- **struct in_addr**: IPv4 only, for historical compatibility
- **struct sockaddr_in6**: For IPv6 socket addresses
- **struct sockaddr_storage**: Flexible structure that holds both IPv4 and IPv6 structures

### Function inet_pton

- "Presentation to network"
- Converts an IP address in numbers-and-dots notation into either a struct in_addr or a struct in6_addr

### Internet Protocol Stack

1. Application Layer: Supports network applications (HTTP, IMAP, SMTP, DNS)
2. Transport Layer: Process-to-process data transfer (TCP, UDP)
3. Network Layer: Routing of datagrams from source to destination (IP, routing protocols)
4. Link Layer: Data transfer between neighboring network elements (Ethernet, 802.11 WiFi, PPP)
5. Physical Layer: Bits "on the wire"

### Encapsulation

- Each layer adds its own header to the data from the layer above
- Message -> Segment -> Datagram -> Frame
- Analogous to Matryoshka dolls (stacking dolls)

## 2. C Structures and Programming

### C Structure Basics

- Collection of one or more variables (possibly of different types) grouped under a single name
- Similar to a Java class without methods
- Syntax:
  ```c
  struct student {
      char name[50];
      int id;
      double GPA;
  };
  ```

### Accessing Structure Fields

- Use the dot operator (.)
- Example: `var.name`, `var.id`, `var.GPA`

### typedef with Structures

- Creates an alias for the structure type
- Makes declaration shorter
- Example:
  ```c
  typedef struct {
      char name[50];
      int id;
      double GPA;
  } Student;
  
  Student var; // No need for 'struct' keyword
  ```

### Nested Structures

- Structures can contain other structures
- Example:
  ```c
  typedef struct {
      char first[21];
      char middle;
      char last[21];
  } Name;

  typedef struct {
      int day;
      int month;
      int year;
  } Date;

  typedef struct {
      Name name;
      int id;
      double GPA;
      Date dateOfBirth;
  } Student;
  ```

### Pointers to Structures

- Create pointers to structures using the & operator
- Dereference using the -> operator
- Example:
  ```c
  Student* pStudent = &student1;
  pStudent->id = 12345;
  ```

## 3. Network System Calls

- getaddrinfo()
- socket()
- bind()
- connect()
- listen()
- accept()
- send() and recv()
- sendto() and recvfrom()
- close() and shutdown()
- getpeername() and gethostname()

## 4. UDP (User Datagram Protocol)

### sendto() Function

- Used for sending UDP datagrams
- Syntax: `sendto(sockfd, buf, len, flags, *to, tolen)`
- `to` is a pointer to a struct sockaddr
- Returns the number of bytes sent or -1 on error

### recvfrom() Function

- Used for receiving UDP datagrams
- Syntax: `recvfrom(sockfd, buf, len, flags, *from, *fromlen)`
- `from` is a pointer to a local struct sockaddr_storage
- Returns the number of bytes received or -1 on error

## 5. Networking Concepts

### What is the Internet?

- "Network of networks"
- Interconnected ISPs
- Billions of connected computing devices (hosts/end systems)
- Packet switches (routers, switches) forward data
- Communication links (fiber, copper, radio, satellite) with varying bandwidths

### Protocols

- Define format, order of messages sent and received
- Define actions taken on message transmission and receipt
- Examples: HTTP, TCP/IP, WiFi, 4G/5G, Ethernet

### Internet Standards

- RFC: Request for Comments
- IETF: Internet Engineering Task Force

### Network Analysis Tools

- Wireshark: Packet analyzer that captures and analyzes network traffic

Remember to review specific code examples and practice implementing these concepts in C programs. Good luck with your exam preparation!

