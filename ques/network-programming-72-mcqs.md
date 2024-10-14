# 100 Network Programming Multiple Choice Questions

1. Which structure is used to prepare socket address structures for subsequent use?
   a) struct sockaddr
   b) struct addrinfo
   c) struct in_addr
   d) struct sockaddr_storage

2. What does the function inet_pton do?
   a) Converts a network address to a printable string
   b) Converts an IP address in numbers-and-dots notation to a struct in_addr or struct in6_addr
   c) Creates a new network connection
   d) Resolves a hostname to an IP address

3. Which layer in the Internet protocol stack is responsible for routing datagrams from source to destination?
   a) Application layer
   b) Transport layer
   c) Network layer
   d) Link layer

4. In C, how do you typically access a field of a structure?
   a) Using the arrow operator (->)
   b) Using the dot operator (.)
   c) Using square brackets ([])
   d) Using parentheses ()

5. What is the purpose of typedef when used with structures in C?
   a) To create a new data type
   b) To allocate memory for the structure
   c) To initialize the structure
   d) To define a function prototype

6. Which operator is commonly used to access fields of a structure through a pointer in C?
   a) Dot operator (.)
   b) Arrow operator (->)
   c) Asterisk operator (*)
   d) Ampersand operator (&)

7. What is the primary difference between send() and sendto() functions?
   a) send() is for TCP, sendto() is for UDP
   b) send() is faster than sendto()
   c) sendto() can send larger amounts of data
   d) send() is deprecated in modern systems

8. Which of the following is NOT a common network system call?
   a) socket()
   b) bind()
   c) execute()
   d) listen()

9. What does UDP stand for?
   a) Unified Data Protocol
   b) User Datagram Protocol
   c) Universal Delivery Process
   d) Uninterrupted Data Packet

10. Which tool is commonly used for capturing and analyzing network traffic?
    a) gcc
    b) gdb
    c) Wireshark
    d) Valgrind

11. In the context of network programming, what does ISP stand for?
    a) Internet Service Provider
    b) Internal System Protocol
    c) Integrated Service Platform
    d) International Standard Practice

12. Which of the following is NOT a layer in the Internet protocol stack?
    a) Application layer
    b) Presentation layer
    c) Network layer
    d) Link layer

13. What is encapsulation in the context of network protocols?
    a) The process of securing data transmission
    b) The addition of headers by each layer to data from the layer above
    c) The compression of data before transmission
    d) The division of large data into smaller packets

14. Which structure is flexible enough to hold both IPv4 and IPv6 structures?
    a) struct sockaddr
    b) struct in_addr
    c) struct sockaddr_storage
    d) struct addrinfo

15. What is the purpose of the recvfrom() function?
    a) To establish a new network connection
    b) To send data over a network
    c) To receive UDP datagrams
    d) To close a network connection

16. Which protocol operates at the transport layer?
    a) HTTP
    b) IP
    c) TCP
    d) Ethernet

17. What does RFC stand for in the context of Internet standards?
    a) Request for Comments
    b) Ready for Compilation
    c) Remote Function Call
    d) Reliable Frame Check

18. What is the main purpose of the struct sockaddr_in?
    a) To store IPv6 addresses
    b) To make it easy to reference elements of the IPv4 socket address
    c) To prepare socket address structures
    d) To hold both IPv4 and IPv6 structures

19. Which function is used to convert a human-readable IP address to network byte order?
    a) htons()
    b) ntohl()
    c) inet_pton()
    d) gethostbyname()

20. What is the purpose of the bind() system call?
    a) To connect to a remote server
    b) To assign a local address to a socket
    c) To start listening for incoming connections
    d) To send data over a network

21. In C, what does the keyword struct do?
    a) Defines a new variable
    b) Creates a function
    c) Declares a new data type
    d) Allocates memory

22. Which of the following is a characteristic of UDP?
    a) Connection-oriented
    b) Guaranteed delivery
    c) Connectionless
    d) In-order packet delivery

23. What is the purpose of the listen() system call?
    a) To accept incoming connections
    b) To mark a socket as passive, ready to accept incoming connections
    c) To connect to a remote server
    d) To send data over a network

24. Which layer of the OSI model is not present in the TCP/IP model?
    a) Physical layer
    b) Network layer
    c) Session layer
    d) Application layer

25. What is the main difference between struct sockaddr and struct sockaddr_in?
    a) struct sockaddr is for IPv6, struct sockaddr_in is for IPv4
    b) struct sockaddr is a generic structure, struct sockaddr_in is specific to IPv4
    c) struct sockaddr is for TCP, struct sockaddr_in is for UDP
    d) There is no difference, they are interchangeable

26. What does IETF stand for?
    a) Internet Engineering Task Force
    b) International Electronic Transfer Framework
    c) Integrated Ethernet Technology Forum
    d) Internet Encryption and Transmission Facility

27. Which of the following is NOT a valid C data type?
    a) int
    b) float
    c) string
    d) char

28. What is the purpose of the accept() system call?
    a) To initiate a connection to a remote server
    b) To bind a socket to a local address
    c) To accept an incoming connection and create a new socket for it
    d) To close a network connection

29. Which protocol provides reliable, in-order delivery of data?
    a) UDP
    b) IP
    c) TCP
    d) ICMP

30. What is the main purpose of the getaddrinfo() function?
    a) To convert IP addresses to hostnames
    b) To retrieve address information for a hostname or service
    c) To set up a new network connection
    d) To bind a socket to a local address

31. In C, how do you declare a pointer to a structure?
    a) struct name *ptr;
    b) *struct name ptr;
    c) struct *name ptr;
    d) struct name ptr*;

32. Which layer of the TCP/IP model is responsible for end-to-end communication?
    a) Application layer
    b) Transport layer
    c) Internet layer
    d) Link layer

33. What is the purpose of the shutdown() system call?
    a) To immediately terminate a network connection
    b) To partially close a network connection
    c) To restart a network service
    d) To initialize a new socket

34. Which of the following is NOT a valid socket type?
    a) SOCK_STREAM
    b) SOCK_DGRAM
    c) SOCK_HTTP
    d) SOCK_RAW

35. What does the htons() function do?
    a) Converts a short integer from host byte order to network byte order
    b) Converts a long integer from host byte order to network byte order
    c) Converts a string from host format to network format
    d) Converts an IP address from host format to network format

36. Which structure is used to store IPv6 addresses?
    a) struct in_addr
    b) struct sockaddr_in
    c) struct sockaddr_in6
    d) struct addrinfo

37. What is the purpose of the select() system call?
    a) To choose between multiple network interfaces
    b) To select a specific protocol for communication
    c) To monitor multiple file descriptors for I/O events
    d) To select a specific IP address for binding

38. In C, what does the sizeof operator return?
    a) The number of elements in an array
    b) The memory address of a variable
    c) The size in bytes of a data type or variable
    d) The length of a string

39. Which protocol is used for domain name resolution?
    a) HTTP
    b) FTP
    c) DNS
    d) SMTP

40. What is the purpose of the setsockopt() function?
    a) To set various options for a socket
    b) To establish a new network connection
    c) To configure network interfaces
    d) To set up routing tables

41. Which of the following is a characteristic of TCP?
    a) Connectionless
    b) Unreliable delivery
    c) Flow control
    d) Fast transmission of small amounts of data

42. What is the main purpose of the gethostbyname() function?
    a) To retrieve the local hostname
    b) To convert a hostname to an IP address
    c) To set up a new network connection
    d) To retrieve information about the local host

43. In C, how do you allocate memory dynamically?
    a) Using the new keyword
    b) Using the malloc() function
    c) Using the alloc() function
    d) Using the create() function

44. Which layer of the OSI model deals with routing?
    a) Data Link layer
    b) Network layer
    c) Transport layer
    d) Session layer

45. What is the purpose of the connect() system call?
    a) To accept incoming connections
    b) To bind a socket to a local address
    c) To establish a connection to a remote server
    d) To start listening for incoming connections

46. Which of the following is NOT a valid IP address?
    a) 192.168.0.1
    b) 10.0.0.1
    c) 172.16.0.1
    d) 256.0.0.1

47. What is the main difference between TCP and UDP?
    a) TCP is connectionless, UDP is connection-oriented
    b) TCP provides reliable delivery, UDP does not
    c) TCP is faster than UDP
    d) UDP provides flow control, TCP does not

48. Which function is used to convert a network address to a printable string?
    a) inet_pton()
    b) inet_ntop()
    c) ntohl()
    d) htonl()

49. What is the purpose of the fork() system call in network programming?
    a) To create a copy of the current process
    b) To split a network connection into multiple streams
    c) To divide a large file for faster transmission
    d) To create a new network interface

50. In C, what is a union?
    a) A data type that can hold different types of data at different times
    b) A combination of multiple structures
    c) A type of network connection
    d) A special kind of array

51. Which protocol is used for secure communication over a computer network?
    a) HTTP
    b) FTP
    c) HTTPS
    d) SMTP

52. What is the purpose of the getpeername() function?
    a) To get the name of the local host
    b) To get the name of the remote peer connected to a socket
    c) To get the IP address of a hostname
    d) To get the port number of a service

53. In C, what does the volatile keyword do?
    a) Makes a variable unchangeable
    b) Tells the compiler that the variable can change unexpectedly
    c) Increases the performance of the program
    d) Allocates the variable in read-only memory

54. Which of the following is NOT a valid socket option?
    a) SO_REUSEADDR
    b) SO_KEEPALIVE
    c) SO_BROADCAST
    d) SO_CONNECT

55. What is the purpose of the poll() system call?
    a) To survey network users
    b) To check the status of network interfaces
    c) To monitor multiple file descriptors for I/O events
    d) To measure network latency

56. Which protocol is used for sending email?
    a) SMTP
    b) POP3
    c) IMAP
    d) HTTP

57. What is the main purpose of the struct in_addr?
    a) To store IPv6 addresses
    b) To store IPv4 addresses
    c) To store both IPv4 and IPv6 addresses
    d) To store MAC addresses

58. In C, what is the purpose of the static keyword when used inside a function?
    a) To make the variable global
    b) To make the variable retain its value between function calls
    c) To allocate the variable on the heap
    d) To make the variable read-only

59. Which system call is used to change the mode of a socket to non-blocking?
    a) setsockopt()
    b) fcntl()
    c) ioctl()
    d) mode()

60. What is the purpose of the gethostname() function?
    a) To get the IP address of the local host
    b) To get the name of the local host
    c) To get the name of a remote host
    d) To get the domain name of the local network

61. Which of the following is NOT a valid errno value?
    a) ECONNREFUSED
    b) ETIMEDOUT
    c) EWOULDBLOCK
    d) ENOTCONNECTED

62. What is the purpose of the ntohl() function?
    a) To convert a long integer from network byte order to host byte order
    b) To convert a short integer from network byte order to host byte order
    c) To convert an IP address from network format to host format
    d) To convert a hostname to an IP address

63. In C, what does the restrict keyword do?
    a) Limits access to a variable
    b) Tells the compiler that a pointer does not alias
    c) Makes a variable read-only
    d) Allocates the variable in a special memory region

64. Which protocol is used for secure shell access?
    a) HTTP
    b) FTP
    c) SSH
    d) Telnet

65. What is the purpose of the recv() function?
    a) To send data over a connected socket
    b) To receive data from a connected socket
    c) To check if data is available on a socket
    d) To close a network connection

66. In the context of sockets, what does the backlog parameter in the listen() function represent?
    a) The maximum number of pending connections in the queue
    b) The timeout for accepting new connections
    c) The maximum number of simultaneous connections
    d) The size of the receive buffer

67. Which of the following is NOT a valid IP address family?
    a) AF_INET
    b) AF_INET6
    c) AF_UNIX
    d) AF_BLUETOOTH

68. What is the purpose of the setsockopt() function with the SO_REUSEADDR option?
    a) To allow multiple sockets to bind to the same port
    b) To increase the size of the socket buffer
    c) To enable broadcasting on the socket
    d) To set the socket to non-blocking mode

69. In C, what is a function pointer?
    a) A pointer to a memory location where a function is stored
    b) A special type of integer pointer
    c) A pointer to the return value of a function
    d) A pointer to the first parameter of a function

70. Which layer of the OSI model is responsible for data encryption?
    a) Physical layer
    b) Data Link layer
    c) Presentation layer
    d) Application layer

71. What is the purpose of the getaddrinfo() function?
    a) To convert an IP address to a hostname
    b) To retrieve address information for a hostname or service
    c) To get the local IP address
    d) To set up a new network connection

72. In C, what does the const keyword do when applied to a pointer?
    a) Makes the pointer itself constant
    b) Makes the data pointed to constant
    c) Both a and b
    d) Neither a nor b

73. Which of the following is NOT a valid socket type?
    a) SOCK_STREAM
    b) SOCK